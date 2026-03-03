# Telecom X – Parte 2: Predicción de Cancelación (Churn)

## Descripción

Proyecto de Machine Learning para predecir qué clientes de Telecom X tienen mayor probabilidad de cancelar sus servicios (churn). Se construye un pipeline completo de modelado predictivo: preprocesamiento, selección de variables, entrenamiento, evaluación e interpretación de resultados.

## Estructura del Proyecto

```
challenger2-data-science-LATAM-parte2/
│
├── data/
│   └── raw/
│       └── telecomx.csv          # Dataset original
│
├── notebooks/
│   ├── 01_churn_prediction.ipynb # Notebook principal
│   └── modelo_churn_campeon.pkl  # Modelo final seleccionado (Random Forest)
│
├── pyproject.toml                # Configuración del proyecto (uv)
├── .gitignore
└── README.md
```

## Tecnologías

- **Python 3.12** — gestionado con [uv](https://docs.astral.sh/uv/)
- **pandas** — manipulación de datos
- **scikit-learn** — modelado predictivo
- **jupyter** — entorno de análisis

## Configuración del entorno

```bash
# Instalar dependencias
uv sync

# Abrir JupyterLab
uv run jupyter lab
```

## Objetivos

1. Preparar los datos para el modelado (tratamiento, codificación, normalización)
2. Análisis de correlación y selección de variables
3. Entrenamiento de modelos de clasificación
4. Evaluación del rendimiento con métricas
5. Interpretación de resultados e importancia de variables
6. Conclusión estratégica sobre los factores de cancelación
