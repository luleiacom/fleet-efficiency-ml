# Fleet Efficiency Prediction Pipeline

Este proyecto implementa un flujo completo (End-to-End) de Machine Learning para optimizar el consumo de combustible en empresas de logística, identificando patrones de conducción ineficientes mediante datos de telemetría.

## Objetivos Técnicos (DS Senior)
* **Ingeniería de Datos:** Procesamiento de datasets de entrenamiento para identificar alertas de ralentí y consumos anómalos.
* **Modelado Predictivo:** Entrenamiento de un clasificador **Random Forest** orientado a la toma de decisiones operativa.
* **MLOps & Deployment:** Serialización del modelo en formato `.pkl` (Pickle) para garantizar la portabilidad y el despliegue en entornos productivos (AWS SageMaker).

## Stack Tecnológico
* **Lenguaje:** Python 3.12 (Pandas, Scikit-Learn, Joblib).
* **Gestión de Datos:** SQL para la ingesta y pre-procesamiento del Data Lake.
* **Entorno:** Google Colab para experimentación y GitHub para versionado.

## Contenido del Repositorio
* `modelo_eficiencia.pkl`: El artefacto del modelo listo para ser productizado.
* `entrenamiento.ipynb`: El cuaderno con el pipeline de limpieza, feature engineering y validación.
