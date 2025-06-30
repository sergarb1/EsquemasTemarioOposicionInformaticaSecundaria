---
marp: true
title: Enunciado – Simulación de Gestión de Memoria
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 💻 Actividad Principal  
## Simulación de gestión de memoria  
### Módulo: Programación – 1.º DAM

🎯 Simula cómo un sistema operativo asigna y libera bloques de memoria a procesos de forma dinámica y controlada.

---

## 🧠 ¿Qué vas a desarrollar?

El alumnado implementará un programa que:

- Representa la memoria como una estructura con **N bloques numerados**
- Simula llamadas desde un programa ficticio que:
  - Solicita bloques de memoria
  - Libera bloques previamente asignados
  - Consulta el estado actual del sistema

---

## 📊 Visualización del sistema

- Cada operación se representa **visualmente** en una **tabla** o **cuadrícula**
- El estado de cada bloque debe actualizarse tras cada operación
- Se observarán **huecos contiguos** y **fragmentación externa**

---

## ⚠️ Casos que deben gestionarse

- Reserva de bloques consecutivos
- Liberación de memoria previamente ocupada
- Fallo al reservar por falta de hueco suficiente (aunque haya espacio fragmentado)
- Consulta en tiempo real del estado de la memoria

---

## 🔗 Relación con el contenido teórico

- Reproduce las **operaciones reales** de un sistema operativo
- Aplica la lógica de **memoria contigua**
- Introduce visualmente los conceptos previos a:
  - **Paginación**
  - **Segmentación**
- Relaciona programación estructurada con gestión de recursos del sistema

---

## 🌟 Posibles extensiones (opcional)

Para quienes completen la funcionalidad básica:

- Implementar **algoritmos de asignación**:  
  - Primer ajuste  
  - Mejor ajuste

- Añadir **compactación manual** tras liberaciones
- Generar múltiples solicitudes automatizadas como si fueran procesos
- Mostrar estadísticas de uso de memoria (bloques libres/ocupados)

---

## ✅ Entregables esperados

- Código funcional del simulador
- Visualización del estado de memoria tras cada operación
- Pruebas con distintos patrones de uso
- (Opcional) Explicación escrita o en vídeo del funcionamiento

📌 ¡El objetivo es que entiendas y simules cómo se organiza la memoria de verdad!
