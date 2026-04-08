# Optimización de parámetros de láseres ultrarrápidos con técnicas de machine learning

[![Estado de Compilación](https://github.com/jusrojasrod/tesis-maestria/actions/workflows/compilar_tesis.yml/badge.svg)](https://github.com/jusrojasrod/tesis-maestria/actions)
[![Descargar PDF](https://img.shields.io/badge/Descargar-Borrador_Actual-darkred.svg)](https://github.com/jusrojasrod/tesis-maestria/releases/download/latest/main.pdf)

Repositorio oficial con el código fuente en LaTeX de mi tesis de maestría en Física.

## 📥 Descarga del Documento

El PDF de la tesis se compila automáticamente en la nube cada vez que se registra un nuevo cambio en la rama principal. No es necesario compilar el código para leer el documento.

👉 **[Descargar la versión más reciente del PDF aquí](https://github.com/jusrojasrod/tesis-maestria/releases/download/latest/main.pdf)**

## 🎯 Resumen del Proyecto

Este trabajo de investigación se enfoca en la intersección entre la óptica no lineal y la inteligencia artificial. El objetivo principal es explorar y aplicar técnicas de *Machine Learning* para modelar, predecir y optimizar el comportamiento y los parámetros fundamentales de los láseres ultrarrápidos.

## ⚙️ Compilación Local

Si deseas clonar este repositorio y compilar el documento en tu propia máquina, necesitarás una distribución completa de TeX Live o MiKTeX.

El proyecto está configurado para compilarse preferiblemente con `latexmk`, ya que maneja automáticamente las pasadas de la bibliografía:

```bash
latexmk -pdf main.tex