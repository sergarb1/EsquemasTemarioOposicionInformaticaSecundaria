---
marp: true
title: Tema 1 - Representación y Comunicación de la Información
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
---

# 🧠 Tema 1  
## Representación y Comunicación de la Información

📚 Fundamentos esenciales que permiten procesar, transmitir y proteger la información digital.

---

## 🔹 1.1 Introducción

- La **representación de la información** consiste en transformar fenómenos reales en estructuras digitales binarias.
- Es la base de todo sistema informático:
  - Hardware
  - Software
  - Redes
  - Datos

---

## 🔢 1.2 Sistemas de Numeración

- Conceptos clave: base, dígitos, sistema posicional
- Sistemas usados en informática:
  - Binario (base 2)
  - Octal (base 8)
  - Decimal (base 10)
  - Hexadecimal (base 16)

---

### 🔄 Conversión entre sistemas

| De | A        | Método                          |
|----|----------|---------------------------------|
| Binario | Decimal | Potencias de 2              |
| Decimal | Binario | División sucesiva por 2     |
| Binario | Hex     | Agrupación en bloques de 4   |
| Hex     | Binario | Expansión directa por dígitos|

🧪 Útil para debugging, direccionamiento y arquitectura de sistemas.

---

## 🧱 1.3 Representación de Datos

### ✅ Datos lógicos

- Representados como `0` y `1`
- Manipulación con puertas lógicas: AND, OR, NOT, XOR...

---

### ➕ Representación de enteros

- **Signo y magnitud** (obsoleto)
- **Complemento a 1 (CA1)**
- **Complemento a 2 (CA2)** → más simple para hardware

---

### 🔬 Punto flotante (IEEE 754)

| Precisión | Bits totales | Signo | Exponente | Mantisa |
|-----------|--------------|-------|-----------|---------|
| Simple    | 32           | 1     | 8         | 23      |
| Doble     | 64           | 1     | 11        | 52      |

- Normalización: forma `1.xxxxx`
- Permite alta precisión y representación única

---

### 🔤 Representación de texto

| Sistema | Características                        |
|---------|-----------------------------------------|
| ASCII   | 7 bits, limitado a caracteres básicos   |
| Extendido | 8 bits, añade acentos y símbolos      |
| Unicode | UTF-8/16/32, soporta todos los idiomas + emojis |

---

### 🖼️ Representación de imágenes

- Matriz de píxeles (RGB + canal alfa)
- Formatos:
  - **BMP**: sin compresión
  - **PNG**: sin pérdida
  - **JPEG**: compresión con pérdida

---

### 🎞️ Representación de vídeo

- Secuencia de imágenes + audio
- Compresión:
  - Intraframe: dentro de cada imagen
  - Interframe: entre imágenes

**Códecs**:  
- H.264, H.265 (HEVC), AV1 (mejor compresión)

---

### 🔊 Representación de audio

- Muestreo:
  - 44.1 kHz (CD)
  - 48 kHz (vídeo)
- Cuantificación:
  - 16 o 24 bits

| Formato | Tipo        |
|---------|-------------|
| WAV, FLAC | Sin pérdida |
| MP3, AAC | Con pérdida  |

---

## 🔧 1.4 Detección y Corrección de Errores

| Técnica           | Capacidad                             |
|-------------------|----------------------------------------|
| Bit de paridad    | Detección simple (1 bit)              |
| CRC               | Comprobación cíclica de redundancia   |
| Código de Hamming | Corrige 1 bit                         |
| Memorias ECC      | Detecta y corrige errores simples     |
| Reed–Solomon      | Corrige múltiples errores (CDs, QR...)|

---

## ☁️ 1.5 Representación en Big Data y Nube

### Formatos de datos

| Formato | Uso                                    |
|---------|-----------------------------------------|
| JSON    | Datos estructurados (web, APIs)         |
| BSON    | Binario (MongoDB)                       |
| Avro    | Apache Kafka, necesita esquema JSON     |
| ORC     | Columnar optimizado (Hadoop, Hive)      |

➡️ Usados en **pipelines**, **cloud computing** y **análisis masivo** (Spark, Hadoop)

---

## 📡 1.6 Comunicación Digital

### Modelo de Shannon–Weaver

| Elemento      | Función                                |
|---------------|-----------------------------------------|
| Emisor        | Genera el mensaje                      |
| Codificador   | Traduce a señales                       |
| Canal         | Medio físico, puede tener ruido         |
| Decodificador | Reconstruye la señal original           |
| Receptor      | Recibe el mensaje                      |

➕ Posprocesos: **compresión** y **cifrado**

---

## 🔐 1.7 Seguridad

### 🔑 Hashing

- MD5, SHA‑256
- Verifica **integridad** del mensaje

### 🔒 Cifrado

| Tipo        | Ejemplos          | Clave         |
|-------------|-------------------|---------------|
| Simétrico   | AES               | Misma clave   |
| Asimétrico  | RSA               | Clave pública/privada |
| Combinado   | SSL/TLS           | Mixto         |

🛡️ Aplicaciones: HTTPS, VPN, BitLocker, certificados digitales

---

## 🗜️ 1.8 Compresión de datos

### Sin pérdida

| Formato | Algoritmo     |
|---------|---------------|
| ZIP     | Deflate       |
| 7ZIP    | LZWA          |
| FLAC/WAV| Audio sin pérdida |

### Con pérdida

| Formato | Aplicación     |
|---------|----------------|
| JPEG    | Imágenes       |
| MP3     | Audio          |
| H.264   | Vídeo          |

---

## ✅ 1.9 Conclusión

- La **representación y comunicación** de la información es la base de la informática
- Desde circuitos y lógica hasta servicios en la nube
- Esencial para el diseño eficiente, seguro y escalable de sistemas

🎯 Todo lo digital **empieza con unos y ceros**.
