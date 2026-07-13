# 📊 Predicción de Fuga de Clientes (Churn) integrando NPS y Datos Transaccionales

Este proyecto desarrolla un modelo de Machine Learning (Random Forest) diseñado para predecir la probabilidad de fuga de clientes en el sector financiero, combinando comportamiento transaccional con métricas cualitativas de Customer Experience (Net Promoter Score).

## 🎯 Objetivo del Negocio
Identificar proactivamente a los clientes con alto riesgo de abandono para focalizar estrategias de retención. El análisis demuestra cómo la experiencia del cliente (ser "Detractor") combinada con indicadores de riesgo (Morosidad) acelera drásticamente la tasa de fuga.

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python
* **Modelado & ML:** Scikit-Learn (RandomForestClassifier)
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn

## 📂 Estructura del Proyecto
```text
├── data/
│   ├── raw/                 # Datos transaccionales y de encuestas sintéticos
│   └── processed/           # Datos transformados listos para ML
├── notebooks/
│   ├── 01_exploracion_nps.ipynb   # Análisis Exploratorio de Datos (EDA)
│   └── 02_modelo_churn_nps.ipynb  # Entrenamiento y evaluación del modelo
├── src/                     # Scripts modulares de Python
├── requirements.txt         # Dependencias del entorno
└── README.md
