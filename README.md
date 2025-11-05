# Laboratorio de Comunicaciones Digitales - TV Digital

Este repositorio contiene los archivos de simulación y los resultados correspondientes al desarrollo de la **"Guía de Conceptos Básicos de Comunicaciones Digitales"** del programa de Ingeniería en Telecomunicaciones de la Universidad Militar Nueva Granada.

El objetivo de la práctica fue analizar y comparar el rendimiento de diferentes esquemas de modulación digital (BPSK y 16-QAM) con y sin el uso de técnicas de codificación de canal (Códigos de Hamming y Códigos Convolucionales).

---

## 📂 Contenido del Repositorio

A continuación se describe el propósito de cada archivo en este repositorio:

### 📄 Documento de Resultados

-   **`SNRFI.pdf`**: **Archivo principal.** Este documento PDF contiene todas las tablas de resultados y las gráficas comparativas de **BER vs. SNR (dB)** generadas durante la práctica. Es el resumen visual de todos los hallazgos.

### 💻 Archivos de Simulación Simulink

-   **`CD.slx`**: Modelo de Simulink para el **Ejercicio 1**. Contiene la simulación comparativa de la modulación **BPSK** con y sin codificación de canal usando un **Código de Hamming**.

-   **`CD2.slx`**: Modelo de Simulink para el **Ejercicio 3**. Contiene la simulación comparativa de la modulación **16-QAM** con y sin codificación de canal usando un **Código Convolucional** y un decodificador Viterbi.

### 📊 Archivos de la Herramienta BERTool

-   **`Bertool.ber`** y **`bertool2.ber`**: Archivos de sesión de la herramienta **BERTool** de MATLAB. Estos archivos guardan las configuraciones y los resultados de las simulaciones teóricas y analíticas utilizadas para validar los modelos de Simulink.

---

## 🛠️ Herramientas Utilizadas

-   **MATLAB R2008a (o superior)**
-   **Simulink**
-   **Communications Toolbox**

---

## 🚀 Cómo Utilizar

1.  **Para ver los resultados finales:** Descargue y abra el archivo `SNRFI.pdf`.
2.  **Para explorar las simulaciones:**
    -   Clone o descargue este repositorio.
    -   Abra los archivos `.slx` (`CD.slx` y `CD2.slx`) utilizando MATLAB y Simulink para ver la arquitectura de los sistemas de comunicación.
3.  **Para analizar las curvas teóricas:**
    -   Abra MATLAB.
    -   En la línea de comandos, escriba `bertool`.
    -   Dentro de la herramienta, vaya a `File > Open Session` y cargue los archivos `.ber`.

---

## 👥 Autores

-   **Realizadores:**
    -   Miguel Andrey Peña Cárdenas
-   **Director del Proyecto:**
    -   Ing. José de Jesús Rugeles

### Institución

-   **Universidad Militar Nueva Granada**
-   Programa de Ingeniería en Telecomunicaciones
