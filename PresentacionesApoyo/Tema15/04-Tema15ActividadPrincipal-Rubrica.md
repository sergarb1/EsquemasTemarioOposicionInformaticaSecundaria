---
marp: true
title: Rúbrica – Monitor y gestor de procesos multiplataforma
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# ✅ Rúbrica de Evaluación  
## Actividad: Monitor y gestor de procesos  
### 2.º DAM – Programación de Servicios y Procesos

📌 Evaluación del desarrollo de una herramienta para monitorizar procesos y enviar señales al sistema operativo.

---

## 📋 Criterios generales

| Criterio                                      | Peso orientativo |
|-----------------------------------------------|------------------|
| Funcionalidad básica                          | 30%              |
| Registro de acciones (log)                    | 15%              |
| Modularidad y estructura del código           | 15%              |
| Uso de herramientas del sistema               | 15%              |
| Estilo, claridad y documentación              | 10%              |
| Opcionales y ampliaciones                     | 15%              |

---

## 🔧 Funcionalidad básica

| Nivel     | Descripción                                                      |
|-----------|------------------------------------------------------------------|
| 🟥 Bajo    | Solo muestra información parcial o incorrecta de procesos       |
| 🟧 Medio   | Muestra procesos activos con algunos errores menores            |
| 🟩 Alto    | Muestra PID, CPU, memoria y usuario correctamente y en tiempo real |

---

## 🗂️ Registro en fichero de log

| Nivel     | Descripción                                                     |
|-----------|-----------------------------------------------------------------|
| 🟥 Bajo    | No se registra ninguna acción                                  |
| 🟧 Medio   | Log incompleto o sin formato estándar                          |
| 🟩 Alto    | Registro ordenado, con marcas de tiempo y detalle de cada acción |

---

## 🧱 Estructura y modularidad del código

| Nivel     | Descripción                                                  |
|-----------|--------------------------------------------------------------|
| 🟥 Bajo    | Código desordenado, todo en un único archivo                 |
| 🟧 Medio   | Uso básico de funciones, sin reutilización clara            |
| 🟩 Alto    | Código modular, organizado por funciones o clases reutilizables |

---

## 🔌 Interacción con el sistema operativo

| Nivel     | Descripción                                                 |
|-----------|-------------------------------------------------------------|
| 🟥 Bajo    | No se utilizan herramientas del sistema (psutil, ProcessHandle…) |
| 🟧 Medio   | Uso básico pero limitado o poco robusto                    |
| 🟩 Alto    | Control total: señales (kill, suspend), lectura real de procesos |

---

## ✍️ Estilo y documentación

| Nivel     | Descripción                                                  |
|-----------|--------------------------------------------------------------|
| 🟥 Bajo    | Código sin comentarios ni coherencia                        |
| 🟧 Medio   | Comentarios parciales o confusos                            |
| 🟩 Alto    | Código limpio, comentado, con buena nomenclatura            |

---

## 🌟 Ampliaciones (opcionales)

| Nivel     | Descripción                                                  |
|-----------|--------------------------------------------------------------|
| 🟥 Bajo    | Solo funcionalidad mínima                                   |
| 🟧 Medio   | Exportación a CSV o interfaz básica                         |
| 🟩 Alto    | GUI avanzada, API REST, monitor de red o disco, alertas     |

---

## ✅ Evaluación final

✔ Se valorará:

- Precisión de los datos mostrados  
- Corrección en el uso de señales  
- Claridad del código y modularidad  
- Uso adecuado de herramientas del sistema operativo  
- Creatividad en las mejoras opcionales

🎯 ¡Tu aplicación debe parecer una herramienta real de monitorización!
