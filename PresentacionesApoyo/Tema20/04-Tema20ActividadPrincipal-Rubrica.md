---
marp: true
title: Rúbrica – Actividad Salt Master/Minion
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# ✅ Rúbrica de Evaluación  
## Actividad: Automatización con Salt  
### Módulo: Servicios de Red – 2.º SMR

🧪 Evaluación del despliegue de Salt master-minion y ejecución remota de tareas.

---

## 📋 Criterios generales

| Criterio                                          | Peso (%) |
|---------------------------------------------------|----------|
| Configuración funcional del sistema master/minion | 25%      |
| Ejecución remota de comandos básicos              | 20%      |
| Aplicación correcta del archivo `.sls`            | 25%      |
| Claridad del código y organización                | 10%      |
| Documentación o explicación final                 | 10%      |
| Ampliaciones o mejoras opcionales                 | 10%      |

---

## 🧠 1. Configuración master/minion

| Nivel     | Descripción                                              |
|-----------|----------------------------------------------------------|
| 🟥 Bajo    | No se establece conexión o configuración incorrecta     |
| 🟧 Medio   | Conexión parcial o requiere intervención externa         |
| 🟩 Alto    | Master y minions conectados correctamente y de forma autónoma |

---

## 🔧 2. Comandos remotos

| Nivel     | Descripción                                              |
|-----------|----------------------------------------------------------|
| 🟥 Bajo    | No se ejecutan comandos o fallan sistemáticamente        |
| 🟧 Medio   | Se ejecutan con errores menores o sin comprenderlos      |
| 🟩 Alto    | Se ejecutan correctamente (`cmd.run`, `service.status`) y se interpretan los resultados |

---

## 📦 3. Archivo .sls funcional

| Nivel     | Descripción                                                     |
|-----------|-----------------------------------------------------------------|
| 🟥 Bajo    | El archivo `.sls` falla o no realiza ninguna acción             |
| 🟧 Medio   | Instala el servicio pero no asegura su ejecución o arranque    |
| 🟩 Alto    | Instala y garantiza que el servicio está activo y habilitado   |

---

## 📁 4. Organización y limpieza

| Nivel     | Descripción                                            |
|-----------|--------------------------------------------------------|
| 🟥 Bajo    | Archivos desordenados, sin comentarios ni estructura  |
| 🟧 Medio   | Código funcional pero poco organizado                 |
| 🟩 Alto    | Código modular, limpio, con comentarios clave         |

---

## 📝 5. Documentación o defensa

| Nivel     | Descripción                                                  |
|-----------|--------------------------------------------------------------|
| 🟥 Bajo    | Sin documentación ni explicación                             |
| 🟧 Medio   | Explicación incompleta o poco clara                          |
| 🟩 Alto    | Explicación clara del proceso, dificultades y soluciones    |

---

## 🌟 6. Ampliaciones opcionales

| Nivel     | Descripción                                                   |
|-----------|---------------------------------------------------------------|
| 🟥 Bajo    | Se entrega solo lo requerido                                 |
| 🟧 Medio   | Añade pequeños extras (más comandos, logs, colores…)         |
| 🟩 Alto    | Despliegue de múltiples servicios, estadísticas, scripts     |

---

## ✅ Evaluación final

✔ Se valorará que el alumnado:

- Domine los conceptos básicos de **SaltStack**  
- Automatice tareas de forma funcional  
- Sea capaz de **explicar y defender** su trabajo  
- Aplique **buenas prácticas de configuración y organización**

🎯 ¡Una actividad que une redes, administración y automatización real!
