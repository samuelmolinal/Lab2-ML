# Laboratorio 2 - Complejidad y búsqueda de hiperparámetros

**Curso:** ISIS2611 - Aprendizaje de Máquina
**Caso:** AlpesPlanck

## Integrantes
- Daniel Esteban Pardo Pardo
- Samuel Andrés Molina Luna

## Descripción

Continuación del Laboratorio 1. Se evalúan enfoques de regresión polinomial y regularizada
(Ridge, Lasso) para estimar la temperatura máxima del día siguiente en la estación de Jena,
analizando el efecto de la complejidad sobre la generalización, realizando búsqueda sistemática
de hiperparámetros, y cuantificando la incertidumbre del modelo mediante intervalos de
confianza (bootstrapping).

## Estructura del repositorio

```
├── data/
│   ├── Datos Lab 1.csv              # Dataset de entrenamiento (mismo del Lab 1)
│   ├── Datos Test Lab 1.csv         # Dataset de prueba sin etiqueta
│   └── Diccionario de datos.xlsx    # Descripción de las variables
├── Laboratorio 2 - Complejidad y búsqueda de hiperparámetros.ipynb
└── README.md
```

## Cómo ejecutar

1. Crear y activar un entorno virtual:
   ```
   python3 -m venv .venv
   source .venv/bin/activate      # En Windows: .venv\Scripts\activate
   ```
2. Instalar las dependencias:
   ```
   pip install ipykernel pandas matplotlib seaborn openpyxl scikit-learn scipy statsmodels
   ```
3. Abrir el notebook en VS Code o Jupyter y seleccionar el kernel del entorno virtual creado.

## Entregables

- Notebook (`.ipynb` y `.html`)
- Video explicativo (máx. 3 min)

**Fecha límite de entrega:** 14 de septiembre, 8:00 PM
