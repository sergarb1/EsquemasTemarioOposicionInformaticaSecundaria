---
marp: true
title: Actividad 2.8 – Procesando datos binarios con bucles
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 🧠 Actividad 2.8  
## Procesando datos binarios con bucles (Java)

🎯 Actividad integradora centrada en la lógica binaria, estructuras de control y manipulación de datos.

---

## 🎯 Objetivo general

Diseñar un programa modular en Java que:

- Realice conversiones numéricas manuales entre sistemas
- Codifique texto carácter a carácter en binario
- Calcule el bit de paridad de cadenas binarias
- Verifique la integridad de datos mediante XOR

---

## 🧩 Parte 1: Conversión de sistemas numéricos

Implementa la conversión de un número decimal a:

- Binario
- Octal
- Hexadecimal

✅ Las conversiones deben realizarse **manualmente con bucles**, sin utilizar funciones automáticas de conversión.

---

## 🧩 Parte 2: Codificación de texto en binario (ASCII)

Convierte un texto introducido por el usuario en su representación binaria, carácter a carácter.

- Usa el código ASCII estándar
- Representa cada carácter como una secuencia binaria de 8 bits

---

## 🧩 Parte 3: Cálculo del bit de paridad

Dada una cadena binaria:

- Cuenta el número de unos
- Determina si hay paridad par (`0`) o impar (`1`)

📌 Esta técnica permite detectar errores simples en transmisiones de datos.

---

## 🧩 Parte 4: Verificación con hash XOR simplificado

Aplica un algoritmo de hash binario muy básico:

- Se recorren los bits de la cadena binaria
- Se aplica una operación XOR secuencial sobre todos ellos
- El resultado sirve como **verificador de integridad**

📌 Si un bit cambia, el valor final cambia → se detecta error.

---

## 📥 Entrada esperada

- Número decimal para convertir a otras bases
- Texto a codificar en binario
- Cadena binaria para análisis de paridad y hash

---

## 📤 Salidas esperadas

- Representación binaria, octal y hexadecimal del número
- Cadena binaria por carácter del texto introducido
- Bit de paridad correspondiente
- Valor hash XOR resultante

---

## ✅ Requisitos técnicos

- Uso adecuado de bucles (`for`, `while`, etc.)
- Estructura clara y modular (funciones separadas)
- Sin uso de métodos automáticos de conversión
- Salidas claras y explicativas en consola
- Código comentado, funcional y bien organizado

---

## 🧪 Ampliaciones opcionales

🔧 Si deseas ir más allá:

- Permitir la codificación y verificación de múltiples mensajes
- Simular errores aleatorios en las cadenas binarias
- Añadir menús o interacción mejorada por consola

---

## 🧠 Criterios de valoración (resumen)

- Corrección funcional de cada parte
- Uso correcto de bucles y lógica binaria
- Claridad, legibilidad y organización del código
- Creatividad o ampliaciones voluntarias

---

# 🚀 ¡Desafío activado!

💡 Esta actividad te permite aplicar programación estructurada  
🧩 Y comprender cómo trabajan los sistemas reales con datos binarios.

👨‍💻 ¡Adelante, descompón, prueba, corrige y mejora!

