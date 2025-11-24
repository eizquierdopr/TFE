# TFE – Análisis de Sentimiento con MLflow

Repositorio para el proyecto de TFE del **grupo 1**.  
El objetivo es entrenar, versionar y desplegar un modelo de **análisis de sentimiento** a partir de textos, utilizando **Python**, **MLflow** y modelos de *machine learning*.

Actualmente el repositorio contiene:

- Conjuntos de datos procesados (años 2018–2019 y 2020).
- Artefactos de modelo entrenado (pipeline de sentimiento y función de preprocesado).
- Trazas de experimentos y modelo registrado con **MLflow**.

---

## 🧱 Estructura del repositorio

```bash
TFE/
├── dataset/
│   ├── dataset_final_v2_2018_2019.csv
│   └── dataset_final_2020.csv
├── modelos/
│   ├── preprocess_text_function.joblib
│   └── sentiment_analysis_pipeline.joblib
└── mlflow/
    ├── ... (experimentos, métricas, parámetros, etc.)
    └── models/
        └── sentiment_analysis_pipeline/
            └── version-1/
                ├── meta.yaml
                └── ... (artefactos del modelo)
