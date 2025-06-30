---
marp: true
title: Enunciado – Actividad SaltStack
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# ⚙️ Actividad Principal  
## Automatización con Salt: arquitectura master-minion  
### Módulo: Servicios de Red – 2.º SMR

🎯 Objetivo:  
Simular un sistema de administración remota basado en Salt, desplegando servicios automáticamente sobre máquinas virtuales.

---

## 🖥️ ¿Qué debes hacer?

1. **Crear una VM master** (Ubuntu Server)  
2. **Crear una o más VMs minion** (Ubuntu Server)  
3. Instalar y configurar **Salt** en ambas:

   - `salt-master` en la master  
   - `salt-minion` en cada minion  
   - Configurar nombres y claves

---

## 🔄 Verificaciones y pruebas

- Verifica la conexión desde la master:  
  `salt '*' test.ping`

- Ejecuta comandos remotos como:  
  - `cmd.run` (por ejemplo: `uptime`)  
  - `service.status` (estado de un servicio)

---

## 📦 Archivo .sls

Crea un archivo **`.sls`** que:

- Instale un servicio, por ejemplo: `nginx`  
- Asegure que esté **activo** y **habilitado**

📁 Ejemplo básico:

nginx:
  pkg.installed
  service.running:
    - enable: True

---

## ✅ Entregables mínimos

* Máquinas virtuales configuradas
* Pruebas funcionales de conexión y ejecución remota
* Archivo `.sls` aplicado correctamente
* Breve documento (o presentación) explicando el proceso

🎯 ¡Convierte tu servidor master en un orquestador profesional de tareas!

