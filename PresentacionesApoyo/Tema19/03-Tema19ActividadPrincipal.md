---
marp: true
title: Enunciado – Gestor de Música con Ficheros
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 🎧 Actividad Principal  
## Gestor de música con persistencia en ficheros  
### Módulo: Programación – 1.º DAM

🎯 Diseña una aplicación de consola que permita gestionar una colección de canciones y guardar los datos en un fichero para conservarlos entre ejecuciones.

---

## 🧠 ¿Qué debe hacer tu programa?

Tu aplicación debe permitir:

- ➕ Añadir canciones con los siguientes campos:
  - Título  
  - Artista  
  - Duración (en segundos o mm:ss)  
  - Género

- 🔍 Buscar canciones por título o artista  
- ❌ Eliminar canciones existentes  
- 📋 Listar todas las canciones registradas

---

## 💾 Persistencia de datos

- Los datos deben guardarse en un **fichero de texto o binario**  
- Al iniciar el programa, debe cargarse la colección guardada  
- Al salir o realizar cambios, debe actualizarse el fichero

📁 Ejemplo:  
`canciones.txt` con una canción por línea  
o  
`canciones.dat` serializado

---

## 📑 Requisitos mínimos

✔ Menú claro con opciones numeradas  
✔ Al menos 4 funciones diferentes implementadas  
✔ Persistencia funcional (leer y escribir fichero)  
✔ Control de errores: fichero inexistente, entrada inválida, etc.  
✔ Estructura modular (funciones, clases si se desea)

---

## 🌟 Opcional (Ampliación)

- Exportar la lista en `.csv` o `.json`  
- Ordenar canciones por duración o artista  
- Filtrar por género  
- Crear una interfaz gráfica sencilla  
- Mostrar estadísticas (número total, duración media, etc.)

---

## 📝 Entrega esperada

- Código funcional con persistencia  
- Fichero de datos generado por el programa  
- Capturas o explicación escrita  
- Opcional: demostración oral o vídeo corto

🎯 ¡Construye tu primer gestor de datos reales con ficheros y estructuras útiles!
