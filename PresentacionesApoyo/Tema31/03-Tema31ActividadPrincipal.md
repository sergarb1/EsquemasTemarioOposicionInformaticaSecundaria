---
marp: true
title: Actividad Principal – Programación en C
theme: default
paginate: true
backgroundColor: #ffffff
_class: lead
---

# 💻 Actividad Principal  
## “Gestor de canciones en C”

---

## 🎯 Enunciado de la Actividad

Desarrolla una aplicación en lenguaje **C** que permita gestionar una **colección de canciones** de forma **modular**.

El programa debe implementar las siguientes funcionalidades:

- **Alta de canción**: añadir nuevas canciones con al menos los siguientes campos:
  - Título (cadena)
  - Artista (cadena)
  - Duración (minutos y segundos)
- **Listado**: mostrar todas las canciones almacenadas.
- **Búsqueda**: por título o por artista.
- **Eliminación**: de una canción por su título o posición.

---

## 🔧 Requisitos técnicos

- Uso de **struct** para representar cada canción.
- Almacenamiento dinámico mediante punteros y **memoria dinámica** (`malloc`, `free`).
- Implementación modular con:
  - Múltiples funciones reutilizables.
  - Separación de archivos: `main.c`, `canciones.c`, `canciones.h`.
- Entrada/salida a través de **consola**.

---

## ✅ Entregables

- Código completo funcional (.c y .h).
- Compilable con `gcc` (sin errores).
- Comentarios explicativos mínimos en el código.
- Documento o presentación breve con:
  - Estructura del programa
  - Diagrama de flujo o pseudocódigo
  - Justificación de decisiones técnicas

---

## 🧪 Evaluación

Tu proyecto será evaluado en base a:

- Corrección técnica y modularidad
- Uso correcto de punteros y memoria
- Limpieza y documentación del código
- Comprobación con varios casos de prueba
- Defensa oral breve con demo funcional

---

## 🚀 Extensiones opcionales

Si terminas antes y quieres mejorar tu nota:

- Ordenar las canciones alfabéticamente.
- Añadir opción de guardar o cargar canciones desde archivo (.txt).
- Implementar un menú interactivo en consola.
- Usar listas enlazadas para permitir crecimiento ilimitado.

---

## 💡 Consejo final

> Cuida la modularidad y prueba cada función por separado.  
> ¡Tu código debe compilar, funcionar y poder explicarse!
