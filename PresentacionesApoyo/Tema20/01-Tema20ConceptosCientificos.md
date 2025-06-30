---
marp: true
title: Tema 20 – Explotación y Administración de Sistemas Operativos
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 🖥️ Tema 20  
## Explotación y Administración de Sistemas Operativos  
### Monousuario y Multiusuario

---

## 1. Introducción

📌 El sistema operativo:

- Intermedia entre usuario y hardware  
- Administra procesos, memoria, dispositivos y seguridad  
- Se adapta a entornos domésticos y empresariales

---

## 2. Clasificación de sistemas operativos

### 🔹 Por número de usuarios:

- **Monousuario**: 1 usuario activo  
  - Ej: Windows 10, macOS  
- **Multiusuario**: sesiones simultáneas  
  - Ej: Linux, Windows Server

---

### 🔹 Por tareas:

- **Multitarea**: ejecuta múltiples procesos  
  - Por turnos (cooperativa) o en paralelo (preemptiva)

---

### 🔹 Por uso y entorno:

- **Doméstico**: sencillo, uso personal  
- **Servidor/empresarial**: escalabilidad y control de usuarios

---

## 3. Explotación de sistemas monousuario

- Instalación del SO, drivers y software esencial  
- Configuración de cuentas locales  
- Backups automáticos (Time Machine, Historial de archivos)  
- Medidas básicas de seguridad:  
  - 🔐 Antivirus, actualizaciones  
  - 🔐 Cifrado de disco (BitLocker, FileVault)

---

## 4. Administración de sistemas multiusuario

---

### 4.1 Procesos y planificación

- Ejecución en **modo usuario**  
- Algoritmos: **FIFO**, **RR**, **prioridades**  
- Comunicación: **pipes**, **sockets**, **memoria compartida**

---

### 4.2 Gestión de memoria

- Técnicas: paginación, segmentación, swapping  
- Separación: modo usuario / modo kernel

---

### 4.3 Servicios y demonios

- Linux: `systemd`, `cron`  
- Windows: Task Scheduler, servicios en segundo plano

---

### 4.4 Almacenamiento

- Sistemas de archivos:  
  - NTFS, EXT4, Btrfs, ZFS  
- Volúmenes lógicos:  
  - LVM (Linux), Storage Spaces (Windows)

---

### 4.5 Gestión avanzada

- Linux:  
  - `sudo`, `ACLs`, `journalctl`, `cgroups`  
- Windows Server:  
  - Active Directory, GPOs

---

### 4.6 Copias de seguridad

- Tipos: Completa, Incremental, Diferencial  
- Regla **3-2-1**:  
  - 3 copias  
  - 2 soportes  
  - 1 externa

🛠️ Herramientas: `rsync`, `tar`, `Deja Dup`, `borgbackup`, `cron`

---

## 5. Virtualización y contenedores

---

### 5.1 Máquinas virtuales (VMs)

- Emulan hardware completo  
- Ej.: VirtualBox, VMware  
- Cada VM tiene su propio SO

---

### 5.2 Contenedores

- Aíslan aplicaciones  
- Comparten el **kernel del host**  
- Tecnologías: Docker, LXC  
- Seguridad: AppArmor, SELinux

---

### 5.3 Orquestación

- **Kubernetes**: despliegue, escalado, balanceo  
- **Helm**: gestor de paquetes para Kubernetes

---

## 6. Seguridad y monitorización

---

### 6.1 Seguridad

- 🔐 Modelos de control de acceso:  
  - DAC, MAC, RBAC  
- 🔐 Autenticación multifactor (2FA)  
- 🔐 Cifrado: BitLocker, LUKS, ZFS  
- 🔥 Firewalls: iptables, nftables, Windows Defender Firewall

---

### 6.2 Monitorización

#### Linux:

- `htop`, `journalctl`, Prometheus + Grafana

#### Windows:

- Sysinternals, Event Viewer

---

## 7. Automatización de tareas administrativas

---

### 7.1 Scripts

- Linux: Bash + `cron` o temporizadores `systemd`  
- Windows: PowerShell, `.bat`, Task Scheduler

---

### 7.2 Tareas comunes

- Backups  
- Limpieza de archivos temporales  
- Reinicios automáticos  
- Generación de informes

---

### 7.3 Herramientas avanzadas

- **Ansible**, **SaltStack**, **Puppet**  
➡️ Automatización masiva desde un único punto de control

---

## ✅ Conclusión

✔ La administración de sistemas requiere:

- Conocimiento del entorno  
- Gestión eficiente de recursos  
- Seguridad y automatización  
- Soporte a múltiples usuarios y procesos

🎯 ¡Fundamental para administradores de sistemas y desarrolladores DevOps!
