---
marp: true
title: Rúbrica – 3 en raya multijugador
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# ✅ Rúbrica de Evaluación  
## Actividad: “3 en raya multijugador”  
### 2.º DAM – Programación de Servicios y Procesos

📌 Evaluación de un servidor concurrente con comunicación mediante sockets y procesos/hilos.

---

## 📋 Criterios generales

| Criterio                                      | Peso (%) |
|-----------------------------------------------|----------|
| Funcionalidad básica de servidor              | 30%      |
| Gestión de procesos/hilos                     | 20%      |
| Comunicación y sincronización                 | 20%      |
| Estructura, modularidad y estilo del código   | 10%      |
| Documentación y presentación del trabajo      | 10%      |
| Mejoras opcionales (GUI, BBDD, logs, etc.)    | 10%      |

---

## 🔧 Funcionalidad del servidor

| Nivel     | Descripción                                                       |
|-----------|-------------------------------------------------------------------|
| 🟥 Bajo    | El servidor se ejecuta pero no gestiona correctamente partidas   |
| 🟧 Medio   | Gestiona una única partida o tiene errores en emparejamientos    |
| 🟩 Alto    | Gestiona correctamente múltiples partidas con emparejamiento dinámico |

---

## 🔄 Gestión de procesos / hilos

| Nivel     | Descripción                                                        |
|-----------|--------------------------------------------------------------------|
| 🟥 Bajo    | No usa hilos ni procesos; todo en un único flujo                   |
| 🟧 Medio   | Usa hilos/procesos pero con errores de aislamiento o rendimiento  |
| 🟩 Alto    | Cada partida se gestiona de forma independiente y eficiente       |

---

## 🔗 Comunicación y sincronización

| Nivel     | Descripción                                                       |
|-----------|-------------------------------------------------------------------|
| 🟥 Bajo    | Comunicación limitada o bloqueante sin control de turnos         |
| 🟧 Medio   | Comunicación básica con lógica funcional mínima de turnos        |
| 🟩 Alto    | Flujo robusto entre clientes y servidor; turnos sincronizados    |

---

## 📦 Modularidad y estilo del código

| Nivel     | Descripción                                                      |
|-----------|------------------------------------------------------------------|
| 🟥 Bajo    | Código desorganizado, sin reutilización ni comentarios          |
| 🟧 Medio   | Estructura básica con algunas clases/métodos reutilizables       |
| 🟩 Alto    | Código limpio, modular, con buena organización y comentado      |

---

## 📄 Documentación y presentación

| Nivel     | Descripción                                                   |
|-----------|---------------------------------------------------------------|
| 🟥 Bajo    | No hay explicaciones ni pruebas visibles                     |
| 🟧 Medio   | Presenta capturas y explicación básica del funcionamiento     |
| 🟩 Alto    | Incluye diagrama, capturas, explicación técnica y ampliaciones |

---

## 🌟 Mejoras opcionales

| Nivel     | Descripción                                                       |
|-----------|-------------------------------------------------------------------|
| 🟥 Bajo    | Solo funcionalidades mínimas                                     |
| 🟧 Medio   | Añade logs o estadísticas básicas                                |
| 🟩 Alto    | Añade GUI, persistencia, gestión de salas, o mejora la experiencia de usuario |

---

## ✅ Evaluación final

✔ Se valorará que el alumnado:

- Implemente un servidor concurrente funcional  
- Sepa manejar **procesos e hilos** para múltiples partidas  
- Gestione correctamente la **comunicación cliente-servidor**  
- Presente el trabajo con profesionalidad y claridad

🎮 ¡Construye una red de juego segura, funcional y escalable!
