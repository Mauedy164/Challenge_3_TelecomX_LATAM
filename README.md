
# 📊 Challenge 3 - TelecomX LATAM

Este proyecto forma parte del tercer desafío del curso de ciencia de datos de Alura LATAM. El objetivo principal es analizar y predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones llamada **TelecomX**.

## 🧠 Objetivo

Desarrollar un modelo predictivo que identifique los factores que influyen en la cancelación de clientes, utilizando técnicas de preprocesamiento, balanceo de clases, normalización, análisis de correlación y modelado con distintos algoritmos de machine learning.

## 📁 Estructura del Proyecto

El archivo `challenge_3_telecomx_latam.py` incluye las siguientes etapas:

- Carga y exploración de datos
- Preprocesamiento y codificación
- Balanceo de clases (SMOTE y undersampling)
- Normalización
- Análisis de correlación
- Modelado con regresión logística, Random Forest, KNN y SVM
- Evaluación de modelos
- Interpretación de resultados
- Propuestas de estrategias de retención

## 🛠️ Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
```

2. Crea un entorno virtual (opcional pero recomendado):
```bash
python -m venv env
source env/bin/activate  # En Linux/macOS
env\Scripts ctivate    # En Windows
```

3. Instala las dependencias necesarias:
```bash
pip install -r requirements.txt
```

## 🚀 Ejecución del Script

1. Asegúrate de tener el archivo de datos limpio `Data_limpia_TelecomX.json` en la ruta correcta, o ajusta la ruta en el script.

2. Ejecuta el script:
```bash
python challenge_3_telecomx_latam.py
```

3. El script generará:
- Métricas de evaluación de modelos
- Gráficos de correlación y matrices de confusión
- Archivos CSV con los datos divididos (`telecomx_train.csv`, `telecomx_test.csv`)
- Imágenes como `confusion_matrices.png` y `variable_importance_models.png`

## 📊 Principales hallazgos

- Clientes con menor antigüedad (`tenure`) tienen mayor probabilidad de cancelar.
- Altos cargos mensuales y totales aumentan el riesgo de churn.
- La baja interacción con el servicio también influye.
- Facturación electrónica y características demográficas tienen impacto.

## 🧠 Estrategias de Retención

- Descuentos para nuevos clientes
- Planes personalizados para clientes en riesgo
- Mejora de la experiencia digital
- Incentivos para clientes con baja interacción
- Atención especial a adultos mayores

## 🧪 Tecnologías utilizadas

- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib, Seaborn

---

