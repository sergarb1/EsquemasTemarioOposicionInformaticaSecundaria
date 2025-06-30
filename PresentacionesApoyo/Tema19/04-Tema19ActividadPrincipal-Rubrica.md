---
marp: true
title: Rúbrica – Simulación técnicas de E/S
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# ✅ Rúbrica de Evaluación  
## Actividad: Simulación comparativa de técnicas de E/S  
### Módulo: Programación – 1.º DAM

📊 Evaluación del simulador que compara polling, interrupciones y DMA desde el punto de vista de uso de CPU y eficiencia.

---

## 📋 Criterios generales

| Criterio                                       | Peso (%) |
|------------------------------------------------|----------|
| Simulación correcta de las 3 técnicas          | 30%      |
| Medición y representación de tiempos/uso CPU   | 25%      |
| Claridad y modularidad del código              | 15%      |
| Análisis y reflexión de los resultados         | 15%      |
| Presentación / visualización de resultados     | 10%      |
| Mejoras opcionales implementadas               | 5%       |

---

## 🔁 Simulación de técnicas de E/S

| Nivel     | Descripción                                                          |
|-----------|----------------------------------------------------------------------|
| 🟥 Bajo    | Solo se simula una técnica o hay errores graves                     |
| 🟧 Medio   | Se simulan 2 o más técnicas con resultados poco diferenciados       |
| 🟩 Alto    | Se simulan correctamente polling, interrupciones y DMA              |

---

## ⏱️ Medición de tiempos y uso de CPU

| Nivel     | Descripción                                                          |
|-----------|----------------------------------------------------------------------|
| 🟥 Bajo    | No se mide ni se representa el tiempo real o uso de CPU             |
| 🟧 Medio   | Se mide de forma básica, sin análisis claro                         |
| 🟩 Alto    | Se mide y compara correctamente el tiempo bloqueado/activo en cada técnica |

---

## 🧱 Claridad y estructura del código

| Nivel     | Descripción                                                    |
|-----------|----------------------------------------------------------------|
| 🟥 Bajo    | Código desorganizado o sin comentarios                        |
| 🟧 Medio   | Código funcional con funciones básicas                         |
| 🟩 Alto    | Código modular, limpio, bien documentado                      |

---

## 📊 Análisis y reflexión

| Nivel     | Descripción                                                       |
|-----------|-------------------------------------------------------------------|
| 🟥 Bajo    | No se explica el impacto o las diferencias entre técnicas        |
| 🟧 Medio   | Análisis simple o centrado en el resultado numérico              |
| 🟩 Alto    | Reflexión clara sobre eficiencia, multitarea, comportamiento real |

---

## 🧩 Visualización y presentación

| Nivel     | Descripción                                                   |
|-----------|---------------------------------------------------------------|
| 🟥 Bajo    | No hay gráficos o son poco comprensibles                     |
| 🟧 Medio   | Presentación textual o con esquemas básicos                  |
| 🟩 Alto    | Visualización clara, gráfica, comparativa entre técnicas     |

---

## 🌟 Ampliaciones opcionales

| Nivel     | Descripción                                                       |
|-----------|-------------------------------------------------------------------|
| 🟥 Bajo    | Solo la funcionalidad mínima                                     |
| 🟧 Medio   | Añade peticiones aleatorias o variantes de planificación         |
| 🟩 Alto    | Usa herramientas reales, implementa SCAN vs FCFS o representación temporal avanzada |

---

## ✅ Evaluación final

✔ Se valorará que el alumnado:

- Comprenda y distinga claramente las **tres técnicas de E/S**  
- Sepa **medir su impacto en CPU y rendimiento**  
- Sea capaz de **explicarlo con argumentos y representación visual**

🎯 ¡Una actividad que simula cómo piensa y decide un sistema operativo real!
---
marp: true
title: Rúbrica – Gestor de Música con Ficheros
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# ✅ Rúbrica de Evaluación  
## Actividad: Gestor de música con ficheros  
### Módulo: Programación – 1.º DAM

📁 Evaluación de un programa funcional que gestiona una colección de canciones con persistencia de datos.

---

## 📋 Criterios generales

| Criterio                                  | Peso (%) |
|-------------------------------------------|----------|
| Funcionalidad básica del gestor           | 30%      |
| Uso correcto de persistencia con ficheros | 25%      |
| Organización y estructura del código      | 15%      |
| Interfaz clara e interacción por consola  | 10%      |
| Control de errores y validaciones         | 10%      |
| Mejoras opcionales (ordenar, exportar...) | 10%      |

---

## 🎵 Funcionalidad del gestor

| Nivel     | Descripción                                                   |
|-----------|---------------------------------------------------------------|
| 🟥 Bajo    | Añade canciones pero no permite eliminar ni buscar           |
| 🟧 Medio   | Permite añadir, eliminar y listar, pero con errores menores  |
| 🟩 Alto    | Permite todas las funciones principales de forma robusta     |

---

## 💾 Persistencia en ficheros

| Nivel     | Descripción                                                       |
|-----------|-------------------------------------------------------------------|
| 🟥 Bajo    | No guarda o no carga la información                              |
| 🟧 Medio   | Guarda correctamente pero falla la lectura o viceversa           |
| 🟩 Alto    | Guarda y carga correctamente los datos en cada ejecución         |

---

## 🧱 Organización del código

| Nivel     | Descripción                                                 |
|-----------|-------------------------------------------------------------|
| 🟥 Bajo    | Código en un solo bloque, sin funciones                     |
| 🟧 Medio   | Código modular con funciones pero poca claridad             |
| 🟩 Alto    | Funciones bien definidas, código limpio y comentado         |

---

## 🖥️ Interfaz por consola

| Nivel     | Descripción                                                 |
|-----------|-------------------------------------------------------------|
| 🟥 Bajo    | Interfaz confusa o poco amigable                            |
| 🟧 Medio   | Menú funcional pero sin validaciones claras                 |
| 🟩 Alto    | Menú estructurado, con instrucciones claras y navegación fluida |

---

## ⚠️ Validación de entradas y errores

| Nivel     | Descripción                                                    |
|-----------|----------------------------------------------------------------|
| 🟥 Bajo    | No hay control de errores ni validaciones                     |
| 🟧 Medio   | Se valida lo esencial (números, vacíos)                       |
| 🟩 Alto    | Validación completa: duplicados, datos inválidos, ficheros    |

---

## 🌟 Ampliaciones opcionales

| Nivel     | Descripción                                                    |
|-----------|----------------------------------------------------------------|
| 🟥 Bajo    | No incluye ninguna mejora adicional                           |
| 🟧 Medio   | Añade al menos una funcionalidad extra (ordenar, exportar...) |
| 🟩 Alto    | Implementa varias ampliaciones útiles y bien integradas       |

---

## ✅ Evaluación final

✔ Se valorará que el programa:

- Use ficheros de forma correcta y persistente  
- Permita gestionar canciones con fluidez  
- Esté bien estructurado y sea legible  
- Muestre interés en extender o mejorar la funcionalidad

🎯 ¡Primer paso hacia programas que guardan y recuperan datos como lo hacen las aplicaciones reales!
