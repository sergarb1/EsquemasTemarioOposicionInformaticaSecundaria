---
marp: true
title: Actividad Principal – SQL
description: Ingeniería de consultas: optimiza y asegura tu base de datos
theme: default
_class: lead
paginate: true
backgroundColor: #fefefe
---

# 🧪 Actividad Principal  
## “Ingeniería de consultas: optimiza y asegura tu base de datos”

---

## 📝 Enunciado de la actividad

Desarrollarás una actividad práctica centrada en la mejora de una base de datos existente. El objetivo es **identificar ineficiencias, corregir errores y aplicar buenas prácticas** en SQL.

---

## 📂 Material de partida

Se proporciona:

- Una base de datos relacional ya creada (SQLite o PostgreSQL)
- Consultas mal optimizadas o incorrectas
- Definiciones incompletas o poco seguras (falta de restricciones, permisos…)

---

## 🔧 Tareas a realizar

1. **Analiza** la base de datos: tablas, relaciones, tipos de datos.
2. **Detecta problemas**:
   - Consultas innecesariamente complejas
   - Ausencia de índices
   - Subconsultas mal estructuradas
   - Faltan restricciones o claves
3. **Corrige y reescribe**:
   - Simplifica y optimiza consultas
   - Aplica restricciones o índices
   - Refactoriza para claridad y eficiencia

---

## 🔐 Mejora la seguridad

- Aplica roles y permisos con `GRANT`, `REVOKE`
- (Opcional) Implementa Row Level Security (RLS)
- Añade `CHECK`, `NOT NULL`, `DEFAULT`, etc.

---

## 📊 Prueba y documenta

- Ejecuta cada mejora
- Compara antes/después en:
  - Claridad del código
  - Tiempos de ejecución
  - Seguridad
- Elabora una breve **documentación técnica** del proceso

---

## 🚀 Opcional: nivel avanzado

- Aplica funciones de ventana (`OVER`, `PARTITION BY`)
- Añade triggers simples (`AFTER INSERT`, `BEFORE UPDATE`)
- Usa Common Table Expressions (CTE)
- Exporta resultados a CSV para su análisis posterior

---

## 📦 Entregables

✔ Script SQL con mejoras aplicadas  
✔ Documento de análisis (PDF o Markdown)  
✔ Capturas o resultados medidos (si aplica)  
✔ (Opcional) vídeo o presentación técnica
