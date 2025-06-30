---
marp: true
title: Tema 47 - Instalación y Explotación de Aplicaciones
description: Instalación, explotación, compartición de datos y automatización
theme: default
_class: lead
paginate: true
backgroundColor: #f9f9f9
---

# 🖥️ Tema 47  
## Instalación y explotación de aplicaciones informáticas  
### y compartición de datos

---

## 1️⃣ Introducción

La instalación y explotación de aplicaciones son fases críticas del ciclo de vida del software.  
Su correcta ejecución garantiza:

- Disponibilidad
- Rendimiento
- Seguridad

La **compartición de datos** permite colaboración eficiente.  
Debe seguir buenas prácticas, marcos normativos y automatización.

---

## 2️⃣ Instalación de aplicaciones

### Fases:
- Revisión de requisitos
- Elección del tipo:  
  → local, cliente-servidor, virtualizado
- Configuración inicial: idioma, puertos, licencias
- Verificación post-instalación: logs, funcionalidad

### Métodos:
- **Asistida (GUI):** Entornos manuales
- **Desatendida:** Scripts, `.msi`, `.deb`, `.rpm`
- **En red:** GPO (Group Policy Objects), SaltProject
- **Contenedores/VM:** Docker, VMware, Proxmox

---

## 3️⃣ Explotación de aplicaciones

### Objetivos:
- Rendimiento
- Disponibilidad
- Mantenimiento
- Seguridad

### Acciones clave:
- Actualizaciones y parches
- Gestión de usuarios/roles (LDAP, AD)
- Monitorización: Zabbix, Grafana, Prometheus
- Backups: rsync, Veeam
- Soporte técnico: GLPI, Jira, Hesk

---

## 4️⃣ Compartición de datos

### Métodos:
- **Archivos compartidos:** SMB (Windows), NFS (Linux)
- **Transferencias seguras:** FTP/SFTP, SCP, rsync
- **Sincronización:** OwnCloud, Google Drive, Nextcloud
- **Bases de datos:** MySQL, PostgreSQL
- **Suites colaborativas:** Microsoft 365, Google Workspace

---

## 🔐 Seguridad en compartición de datos

- Control de acceso:  
  ➤ ACL (Access Control Lists), RBAC  
- Cifrado:  
  ➤ En tránsito (TLS), en reposo (LUKS, BitLocker)  
- Trazabilidad:  
  ➤ Logs, versiones, alertas

---

## 5️⃣ Escenarios profesionales

### Entorno educativo:
- Clonado de aulas
- Imágenes maestras
- Mantenimiento centralizado

### Entorno empresarial:
- GPO y Active Directory
- Helpdesk / asistencia

### Nube y teletrabajo:
- IaaS: Azure, AWS
- SaaS: Google Workspace, Office365
- VPN para acceso seguro

---

## 6️⃣ Automatización y DevOps

### Herramientas:

- **Gestión de configuración:**  
  ➤ Ansible, Puppet, SaltProject  
- **Contenedores y orquestación:**  
  ➤ Docker, Docker Compose, Kubernetes  
- **Integración y despliegue continuo (CI/CD):**  
  ➤ Jenkins, GitHub Actions, GitLab CI  
- **Infraestructura como código:**  
  ➤ Terraform

---

## 7️⃣ Buenas prácticas y marco legal

- Instalación **documentada y reproducible** (Git)
- Registro de **incidencias y cambios**
- **RGPD / LOPDGDD**: protección de datos y logs
- Licencias:  
  ➤ GPL, MIT, Apache, EULA
- **Documentación viva** y versionada

---

## 8️⃣ Indicadores de calidad

- **SLA (Service Level Agreement):** Disponibilidad del sistema
- **MTTR (Mean Time To Repair):** Rapidez para resolver fallos
- **Satisfacción del usuario**
- **Alertas proactivas** con monitorización activa

---

## ✅ Conclusión

Instalar, mantener y compartir aplicaciones de forma segura y eficiente  
es clave para la productividad y continuidad del servicio.  
👉 Automatizar + Documentar = Profesionalidad

