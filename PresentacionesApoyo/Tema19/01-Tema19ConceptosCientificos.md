---
marp: true
title: Tema 19 – Gestión de Archivos y Dispositivos
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 💾 Tema 19  
## Sistemas Operativos  
### Gestión de Archivos y Dispositivos

📁 Organización, acceso, seguridad y rendimiento del almacenamiento y periféricos.

---

## 1. Introducción

El sistema operativo:

- Organiza y gestiona los **archivos y dispositivos**
- Abstrae el hardware para usuarios y programas

🧠 Ejemplo: abrir un documento implica:

- Buscar en sistema de archivos
- Verificar permisos
- Acceder al disco
- Usar el controlador del dispositivo

---

## 2. Objetivos de la gestión

✔ Proporcionar estructura lógica para los datos  
✔ Asegurar integridad y disponibilidad de archivos  
✔ Administrar controladores de dispositivos  
✔ Compartir recursos entre procesos  
✔ Optimizar rendimiento del almacenamiento

---

## 3. Estructura del sistema de archivos

- **Archivo**: unidad lógica de datos (texto, binario…)  
- **Directorio**: agrupación de archivos  
- **Ruta**:
  - Absoluta: `/home/user/doc.txt`
  - Relativa: `../doc.txt`  
- **Descriptor de archivo**: ID interno usado por el sistema para operar sobre archivos abiertos

---

## 4. Tipos y características de sistemas de archivos

| Sistema | Plataforma | Características         | Limitaciones             |
|---------|------------|--------------------------|--------------------------|
| FAT32   | Windows    | Compatible, simple       | 4 GB por archivo         |
| NTFS    | Windows    | Permisos, cifrado, journaling | No nativo en Linux    |
| EXT4    | Linux      | Estable, rápido, journaling | -                    |
| Btrfs   | Linux      | Snapshots, copy-on-write | Complejo de administrar |
| ZFS     | Unix/Linux | Compresión, integridad    | Alto uso de RAM, licencia |

---

## 5. Operaciones y permisos sobre archivos

### 🔧 Operaciones básicas

- Crear, abrir, leer, escribir, cerrar, eliminar

### 🛡️ Permisos en Linux

- `rwx` para usuario, grupo, otros  
- Ejemplo: `-rwxr-xr--`  
- Comandos: `chmod`, `chown`, `umask`

### 🎯 ACLs (Access Control Lists)

- Permisos granulares por usuario o grupo

📄 **Metadatos**: nombre, tamaño, tipo, propietario, fecha  
🔒 Archivos ocultos: empiezan por `.` (ej. `.bashrc`)

📂 Flujo típico: crear → abrir → leer/escribir → cerrar

---

## 6. Gestión de dispositivos

---

### 6.1 Tipos de dispositivos

- 📥 De carácter: flujo (teclado, ratón, serie)  
- 📦 De bloque: acceso por bloques (disco, USB, SSD)

---

### 6.2 Acceso a dispositivos

🔗 Mediante **archivos especiales**:

- Linux: `/dev/sda1`, `/dev/tty`, `/dev/null`  
- Windows: `COM1`, `LPT1`, `C:\`

---

### 6.3 Controladores (drivers)

- Traducen instrucciones del SO al lenguaje del hardware  
- Se cargan automáticamente o manualmente

---

## 7. Montaje y administración de dispositivos

📌 **Montaje**: integrar el dispositivo en el sistema de archivos

📁 **Punto de montaje**: carpeta donde se accede al dispositivo

---

### En Linux:

- Ver dispositivos: `lsblk`, `blkid`  
- Montar: `mount /dev/sdb1 /mnt/usb`  
- Automontaje: `/etc/fstab`

---

### En Windows:

- Letras de unidad (`D:\`, `E:\`)  
- Administración: herramienta "Administración de discos"

---

## 8. Seguridad, fiabilidad y backups

---

### 🧠 Fiabilidad

- **Journaling**: evita corrupción de datos (EXT4, NTFS, ZFS)  
- **Snapshots**: estados inmutables (Btrfs, ZFS)

---

### 🔐 Cifrado

- Windows: **BitLocker**  
- Linux: **LUKS**, ZFS

---

### 📦 Copias de seguridad

- Manuales: `rsync`, `tar`, 7-Zip  
- Automáticas: `cron`, Timeshift, Historial de archivos  
- Regla 3-2-1:  
  - 3 copias  
  - 2 soportes distintos  
  - 1 en otra ubicación

---

## 9. Sistemas de archivos en RAM y virtuales

---

### 9.1 RAM-based: `tmpfs`

- Montado en memoria RAM  
- Carpeta típica: `/tmp`, `/dev/shm`  
- Ventajas: velocidad altísima  
- Desventajas: datos volátiles, limitada por RAM

📌 Ejemplo:  
`mount -t tmpfs tmpfs /mnt/ramdisk`

---

### 9.2 Sistemas de archivos virtuales

- Simulan archivos para exponer info del sistema

📂 Linux:

- `/proc`: info de procesos y hardware  
- `/sys`: parámetros del kernel  
- `/dev`: dispositivos representados como archivos

📂 Windows:

- `NUL`, `CON`, `PRN`, **WMI** (Windows Management Instrumentation)

📊 Aplicación:  
leer `/proc/cpuinfo` o `/proc/meminfo` para analizar el sistema

---

## ✅ Conclusión

✔ La gestión de archivos y dispositivos:

- Abstrae la complejidad del hardware  
- Proporciona seguridad y estructura  
- Optimiza el uso del sistema de almacenamiento

🎯 Desde abrir un archivo hasta montar una unidad, todo pasa por el sistema operativo
