---
marp: true
title: Tema 18 – Gestión de Entradas/Salidas (E/S)
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 🧠 Tema 18  
## Sistemas Operativos: Gestión de E/S

🎯 Control de la interacción entre la CPU y los periféricos.  
📦 Clave para el rendimiento, la eficiencia y la comunicación hardware/software.

---

## 1. Introducción

La gestión de E/S permite:

- Interacción eficiente entre CPU y dispositivos  
- Intercambio de datos **seguro**, **coordinado** y **transparente**  
- Aislar los detalles del hardware para facilitar el desarrollo

---

## 2. Objetivos del subsistema de E/S

🔹 **Abstracción del hardware**  
➡ Oculta complejidad técnica, facilita la portabilidad

🔹 **Asignación y liberación de dispositivos**  
➡ Compartición eficiente de recursos

🔹 **Planificación de acceso**  
➡ Ordena peticiones y mejora el uso del hardware

🔹 **Protección y sincronización**  
➡ Previene conflictos o accesos simultáneos

---

## 3. Componentes del sistema de E/S

- 🎛️ **Drivers**: traducen órdenes del SO al lenguaje del dispositivo  
- 🧠 **Subsistema E/S (kernel)**: gestiona colas y acceso  
- 🧪 **Buffering**: desacopla velocidades CPU ↔ dispositivo  
- ⚡ **Caching**: acelera accesos frecuentes, reduce latencia

---

## 4. Técnicas de gestión de E/S

---

### 🌀 E/S Programada (Polling)

- La CPU interroga continuamente al dispositivo  
- ❌ Ineficiente → la CPU se bloquea esperando

---

### ⚡ E/S con Interrupciones

- El dispositivo **interrumpe** a la CPU cuando está listo  
- ✅ Más eficiente → permite multitarea

---

### 🚀 DMA (Direct Memory Access)

- El dispositivo accede directamente a la memoria sin usar CPU  
- Ideal para: discos, red, vídeo  
- ✅ Reduce carga del procesador

---

## 5. Clasificación de dispositivos y modos de acceso

---

### 5.1 Por función

- Entrada: teclado, ratón  
- Salida: pantalla, impresora  
- Entrada/Salida: disco, red, USB

---

### 5.2 Por tipo de acceso

- 📜 **Carácter**: flujo secuencial (teclado)  
- 📦 **Bloque**: acceso por bloques fijos (discos)

---

### 5.3 Por sincronización

- 🔁 **Sincrónico**: el proceso espera a que termine  
- ⏩ **Asincrónico**: el proceso continúa y es notificado luego

---

## 6. Planificación de E/S (en discos)

---

### Algoritmos comunes:

- **FCFS**: por orden de llegada  
- **SSTF**: menor distancia al cabezal  
- **SCAN / C-SCAN**: "ascensor", barrido en ambas direcciones  
- **LOOK / C-LOOK**: barrido solo donde hay peticiones

---

## 7. Monitorización y rendimiento

---

### 7.1 Herramientas útiles

- iostat, iotop, dstat, htop, Task Manager  
- Prometheus + Grafana (visualización en red)

---

### 7.2 Indicadores clave

- ⏱️ **Latencia**: retardo en la respuesta  
- 📊 **Throughput**: datos procesados por segundo  
- 🧱 **Cuellos de botella**: procesos que ralentizan el sistema

---

### 7.3 Aplicación práctica

- Comparar técnicas de E/S en laboratorio  
- Analizar comportamiento real de disco y CPU  
- Evaluar impacto en el rendimiento

---

## 8. Conclusión

✅ La E/S es esencial en cualquier sistema operativo moderno.

- Conecta el mundo físico con el lógico  
- Su eficiencia mejora el rendimiento global  
- Evolución:  
  - De **polling** 🛑  
  - A **interrupciones** ⚡  
  - Hasta **DMA** y sistemas inteligentes 🚀

🎯 Sin buena gestión de E/S, no hay rendimiento real
