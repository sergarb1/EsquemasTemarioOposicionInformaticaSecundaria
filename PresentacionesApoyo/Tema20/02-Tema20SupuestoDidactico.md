---
marp: true
title: Parte Didáctica – Servicios de Red (2.º SMR)
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 🌐 Parte Didáctica  
## Módulo: Servicios de Red – 2.º SMR  
### Gestión remota y automatización con Salt

---

## 🧩 2.1 ¿Qué supuesto queremos trabajar?

Implementar un sistema básico de **gestión remota de sistemas** mediante **SaltStack**, donde el alumnado:

- Crea una arquitectura master-minion con máquinas virtuales
- Automatiza tareas como instalación de servicios
- Ejecuta y supervisa comandos a distancia

---

## 👥 2.2 Contextualización del alumnado

- Ciclo: **Sistemas Microinformáticos y Redes (2.º curso)**  
- Módulo: Servicios de Red  
- Alumnado con experiencia básica en entornos Linux  
- Conocimientos previos en redes, servicios y máquinas virtuales

---

## 📚 2.3 Conocimientos previos requeridos

- Uso de **Ubuntu Server**  
- Manejo básico de la terminal  
- Instalación de paquetes (`apt`)  
- Edición de archivos de configuración (`nano`, `vim`)  
- Uso de máquinas virtuales (VirtualBox, Proxmox…)

---

## 🎯 2.4 Objetivos de aprendizaje

- Comprender la arquitectura **master-minion** en Salt  
- Instalar y configurar un sistema de automatización remota  
- Ejecutar tareas administrativas desde una consola centralizada  
- Crear archivos `.sls` para configurar servicios de red  
- Fomentar la eficiencia, escalabilidad y buenas prácticas

---

## 🧠 2.5 Metodología

- Aprendizaje práctico y por proyectos  
- Actividad guiada con fases escalonadas  
- Trabajo individual o en parejas  
- Evaluación continua por observación y entregables funcionales  
- Resolución de incidencias técnicas reales

---

## 📦 2.6 Material didáctico (DUA)

- Instrucciones paso a paso (guía PDF y videotutorial)  
- Máquina virtual base preconfigurada  
- Plantilla `.sls` y comandos de ejemplo  
- Accesos alternativos: consola local o terminal SSH  
- Recursos en texto, imagen y vídeo para distintos estilos de aprendizaje

---

## 🧑‍💻 2.7 Secuencia de acciones formativas

1. Introducción a la administración remota  
2. Creación de VMs Ubuntu (una master, una o más minion)  
3. Instalación y configuración de Salt  
4. Verificación de conexión (`test.ping`)  
5. Ejecución de comandos simples (`cmd.run`, `service.status`)  
6. Creación de archivo `.sls` para desplegar un servicio (nginx)  
7. Comprobación y puesta en común de resultados  
8. Documentación del proceso

---

## ⚙️ 2.8 Actividad principal  
### Automatización con Salt: arquitectura master-minion

🧪 El alumnado deberá:

- Crear una **VM master** y una o más **VMs minion** con Ubuntu Server  
- Instalar y configurar **Salt** en ambos extremos  
- Verificar la conexión con `test.ping`  
- Ejecutar comandos remotos (`cmd.run`, `service.status`)  
- Crear un archivo `.sls` que:  
  - Instale un servicio (ej. `nginx`)  
  - Asegure que esté activo

🎯 Se valorará la funcionalidad, automatización y documentación del proceso

---

## 📊 2.9 Evaluación: instrumentos y criterios

### 📋 Criterios

- Correcta instalación y conexión Salt master-minion  
- Ejecución funcional de comandos remotos  
- Creación y aplicación de un `.sls` válido  
- Resolución autónoma de errores comunes  
- Documentación clara del proceso

### 🧪 Instrumentos

- Revisión directa de las VMs  
- Comprobación funcional (ping, servicio activo)  
- Documento entregable o exposición breve  
- Lista de control o rúbrica funcional

---

## ♿ 2.10 Inclusión y atención a la diversidad

- Entorno simplificado con VM base ya configurada  
- Comandos preparados en plantilla para quienes lo requieran  
- Acompañamiento técnico durante el despliegue  
- Explicaciones por escrito, vídeo y oral  
- Adaptación de ritmo y complejidad

---

## 🚀 2.11 Actividades de ampliación

🌟 Para alumnado avanzado:

- Desplegar múltiples servicios con un `.sls` más complejo  
- Integrar gestión de usuarios, firewall o backups  
- Automatizar configuración de red  
- Usar Salt para monitorización básica  
- Documentar todo en una wiki o presentación final

---

## ✅ Conclusión

✔ Se fomenta:

- Uso realista de herramientas profesionales  
- Automatización y eficiencia en administración  
- Pensamiento sistemático y buenas prácticas DevOps

🎯 ¡Salt no solo automatiza… también enseña cómo pensar en grande desde el primer nodo!