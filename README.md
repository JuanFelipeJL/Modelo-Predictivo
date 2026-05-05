# Modelo-Predictivo
# Proyecto Minería de Datos — Predicción de Churn

Proyecto de minería de datos aplicado sobre un dataset de clientes de telecomunicaciones.
El objetivo es predecir si un cliente abandonará el servicio (Churn) usando técnicas
de calidad de datos y modelos de clasificación supervisada.

---

## Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `Calidad_de_datos.ipynb` | Perfilado, diagnóstico de las 6 dimensiones de calidad y pipeline de limpieza | Entrenamiento de modelos, hiperparametrización y despliegue web |
| `telco_customer_data_v2.csv` | Dataset original (70,000 clientes, 21 variables) |
| `modelo_churn_mlp.pkl` | Modelo MLP entrenado y serializado |

---

## ¿Qué encontrarás?

**Calidad de datos**
- Perfilado automático con ydata-profiling
- Diagnóstico de completitud, unicidad, validez, consistencia, integridad y actualidad
- Pipeline de limpieza completo (imputación, corrección de tipos, outliers)

**Minería de datos**
- Comparación de 5 modelos: Árbol de Decisión, KNN, Red Neuronal, SVM y Random Forest
- Hiperparametrización con GridSearchCV sobre el mejor modelo (MLP, F1=0.7686)
- Despliegue web interactivo con Gradio

---

## Tecnologías

Python · scikit-learn · pandas · Gradio · Jupyter Notebook

---

## Autores
 Curso de Minería de Datos · Colombia
**Juan Felipe Joaqui Lopera** 
**Sara Maria Chavez Herrera**
**Maria Jose Gomez Villegas**
