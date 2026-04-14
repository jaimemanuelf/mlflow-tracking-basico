# MLflow Tracking Básico

Este proyecto demuestra el uso básico de **MLflow** para el seguimiento de experimentos de machine learning. Utiliza el dataset de calidad de vino tinto (*Wine Quality*) para entrenar y comparar modelos de regresión, registrando parámetros, métricas y artefactos en MLflow.

## Características

- Entrenamiento de modelos de regresión con **scikit-learn**:
  - **KNN** (K-Nearest Neighbors)
  - **ElasticNet**
- Registro automático en MLflow de:
  - Parámetros del experimento (tipo de modelo, tamaño del conjunto de prueba, etc.)
  - Métricas de entrenamiento y prueba (MSE, MAE, R²)
  - Modelo entrenado como artefacto
- Script para realizar predicciones cargando un modelo registrado en MLflow

---

# Configuración en MacOS y Linux

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
source .venv/bin/activate
source setup.sh
```

# Configuración en Windows

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
.venv\Scripts\activate
setup
```

# Ejecución de pruebas

Ejecute el siguiente comando en el terminal:

```bash
pytest
```