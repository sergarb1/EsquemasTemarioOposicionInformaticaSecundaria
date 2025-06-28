Aquí tienes una presentación **completa en formato Marp** para el **Tema 2: Elementos funcionales de un ordenador digital**, enfocada en los **conceptos científicos** que sustentan cada parte. Está organizada por secciones, con redacción clara y didáctica, y enriquecida para que ninguna diapositiva quede vacía.

---

### ✅ Presentación MARP – Conceptos científicos

```markdown
---
marp: true
title: Tema 2 – Elementos funcionales de un ordenador digital
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 💻 Tema 2  
## Elementos funcionales de un ordenador digital

📘 Fundamentos físicos, lógicos y científicos del tratamiento de la información en sistemas digitales.

---

## 🔹 1. Introducción

Los elementos funcionales de un ordenador digital constituyen la base para el procesamiento automático de la información.

- Se organizan en **subsistemas especializados**:
  - Procesamiento (CPU)
  - Memoria
  - Entrada/Salida
  - Interconexión (buses)

📡 Todos trabajan de forma coordinada y sincronizada.

---

## 🧠 2.1 Unidad Central de Proceso (CPU)

La CPU es el cerebro del sistema. Ejecuta instrucciones según el flujo del programa.

**Componentes clave:**

- **Registros internos**:
  - PC: contador de programa
  - IR: registro de instrucción
  - MAR/MDR: dirección y datos
  - FLAGS: indicadores de estado (overflow, zero...)

- **ALU / FPU**:
  - ALU: operaciones lógicas y aritméticas
  - FPU: operaciones en coma flotante

---

## ⚙️ Unidad de Control

Gestiona el orden de ejecución de instrucciones.

### Tipos:

- **Cableada**: lógica fija (combinacional). Alta velocidad.
- **Microprogramada**: más flexible. Puede modificarse por firmware.

🔁 Coordina todos los elementos de la CPU de forma secuencial o paralela.

---

## 🧮 2.2 Memoria Principal

Memoria de trabajo donde se almacenan **datos e instrucciones** en ejecución.

### Tipos:

- **DRAM** (dinámica): barata, pero necesita refresco. Común en RAM.
- **SRAM** (estática): rápida y cara. Usada en cachés L1/L2.

📌 Ambas son **volátiles**, pierden su contenido al apagar el sistema.

---

## 🗂️ Jerarquía de memoria

Del más rápido al más lento:

```

Registros > Caché (L1–L3) > RAM > SSD > HDD

```

📉 Cada nivel reduce velocidad pero aumenta capacidad y reduce coste.

🔁 La jerarquía mejora rendimiento gracias al **principio de localidad**.

---

## 🔌 2.3 Subsistema de Entrada/Salida

Permite la comunicación del procesador con el **entorno físico**.

### Dispositivos comunes:

- Teclado, ratón, monitor, discos, red, sensores...

### Modos de funcionamiento:

- **Polling**: la CPU consulta repetidamente el periférico
- **Interrupciones**: el periférico avisa a la CPU
- **DMA**: transfiere datos sin intervención directa de la CPU

---

## 🔗 2.4 Sistema de Buses

Conjunto de líneas que transportan **señales y datos** entre componentes del sistema.

### Tipos de buses:

- **Datos**: información binaria
- **Direcciones**: ubica posición en memoria
- **Control**: gestiona lectura, escritura e interrupciones

---

### Temporización

| Tipo       | Características                           |
|------------|--------------------------------------------|
| Síncrona   | Controlada por reloj común (más predecible) |
| Asíncrona  | Se basa en señales de control (más flexible) |

📡 El bus es esencial para la comunicación interna del sistema.

---

## 🏛️ 3. Modelos de Arquitectura

### 3.1 Von Neumann

- Memoria única para instrucciones y datos
- Problema: **cuello de botella** al acceder

🧠 Simplicidad estructural, pero limitado en velocidad

---

### 3.2 Harvard

- Memorias separadas para instrucciones y datos
- Acceso paralelo → mejor rendimiento

🔧 Usado en sistemas embebidos, DSPs y microcontroladores

---

## 🧩 4. Taxonomía de Flynn

Clasifica arquitecturas según **flujos de instrucciones y datos**

| Tipo  | Significado                            |
|-------|-----------------------------------------|
| SISD | Un núcleo, una instrucción, un dato      |
| SIMD | Una instrucción, múltiples datos (GPU)   |
| MISD | Raro, uso académico                      |
| MIMD | Múltiples instrucciones y datos (CPU multinúcleo) |

🔁 La clasificación refleja distintos grados de **paralelismo**.

---

## 💾 5. Memorias: Tipos y evolución

| Tipo           | Descripción                                |
|----------------|---------------------------------------------|
| ROM/EEPROM     | No volátiles, para configuración del sistema |
| Flash          | Reprogramable, usada en almacenamiento      |
| HBM            | Alta velocidad, cercana a la CPU            |
| GDDR6          | Memoria para GPU (gráficos)                 |
| Optane         | Rápida y persistente, tecnología híbrida    |
| SoC            | CPU + RAM + GPU integradas (móviles)        |

📌 Las nuevas tecnologías buscan **velocidad, densidad y eficiencia energética**

---

## 🔄 6. Ciclo de instrucción

Cada instrucción pasa por estas **etapas**:

```

Fetch → Decode → Execute → Memory → Write-back

```

- **Fetch**: buscar instrucción en memoria
- **Decode**: interpretarla
- **Execute**: realizar la operación
- **Memory**: acceder a datos si es necesario
- **Write-back**: almacenar resultado

---

### Optimización del ciclo

🔧 Técnicas para acelerar la CPU:

- **Pipeline**: ejecución solapada por etapas
- **Superescalaridad**: múltiples instrucciones por ciclo
- **Out-of-Order Execution**: reordenamiento dinámico
- **SMT**: varios hilos por núcleo (hyperthreading)
- **Multicore**: varios núcleos físicos

---

### 🔮 Predicción de saltos

Evita ciclos perdidos en bifurcaciones de código

- **2-bit predictor**: 4 estados para mayor estabilidad
- **Perceptrón predictor**: usa aprendizaje histórico
- **TAGE**: combinación de predictores
- **ML avanzado**: nuevas investigaciones con redes neuronales

📈 Mejora el rendimiento global del procesador

---

## 🚀 7. Tendencias Futuras

| Tecnología         | Aplicación y potencial                         |
|--------------------|------------------------------------------------|
| Computación cuántica | Qubits, superposición, paralelismo masivo     |
| Neuromórfica        | Modela el comportamiento del cerebro humano   |
| Aceleradores IA     | TPU, NPU, FPGA dedicados a tareas de IA       |
| Sistemas heterogéneos| Integración de CPU, GPU y NPU                |

🔬 Innovaciones orientadas a rendimiento, eficiencia e inteligencia artificial.

---

## ✅ Conclusión

Los elementos funcionales del ordenador digital permiten:

✔ Ejecutar instrucciones de forma precisa y rápida  
✔ Comunicar con periféricos y almacenar información  
✔ Optimizar el rendimiento mediante jerarquías y paralelismo  
✔ Adaptarse a nuevas demandas tecnológicas (IA, big data, computación cuántica)

🎯 ¡Entender su estructura es esencial para cualquier informático!
