# Detección de Frescura en Frutas y Verduras 🍎🥒

Este proyecto implementa modelos de Aprendizaje Computacional (Machine Learning) para clasificar frutas y verduras según su estado de conservación (fresco o podrido). El objetivo final es desplegar una aplicación interactiva que permita al usuario utilizar la cámara de su dispositivo para identificar el producto y su estado en tiempo real.

## 🚀 Fase Actual: Fase 1 - Gestión de Datos
Se ha completado la descarga, el Análisis Exploratorio de Datos (EDA), la limpieza de imágenes corruptas y la estandarización de las clases para evitar duplicidades conceptuales. Se consolidaron más de 200,000 imágenes en un único archivo procesado.

## 📁 Estructura del Repositorio

├── data/
│   ├── raw/          # Referencia al dataset original (Kaggle)
│   └── processed/    # Referencia al dataset limpio y unificado
├── .gitignore        # Ignora archivos temporales y entornos virtuales
├── LICENSE           # Licencia del proyecto
├── README.md         # Este archivo
├── requirements.txt  # Dependencias iniciales del entorno
└── proyecto_frescura_fase1.ipynb # Notebook con descarga, EDA y limpieza

*Nota: Por el tamaño masivo de las imágenes, los datos físicos se gestionan mediante Google Drive y Colab, no se suben directamente a GitHub.*

## 🛠️ Cómo ejecutar este proyecto

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)
