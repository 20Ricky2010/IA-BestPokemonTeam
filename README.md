# Predicción de Combates Pokémon usando Machine Learning

Este proyecto fue desarrollado como parte del curso **SI404 - Inteligencia Artificial** en la Universidad Peruana de Ciencias Aplicadas (UPC). El objetivo fue aplicar técnicas de aprendizaje automático para predecir el resultado de combates entre equipos Pokémon y proponer equipos óptimos.

## Contenido del repositorio

- `pokemon.csv`: Datos de 800 Pokémon, incluyendo estadísticas base y tipos.
- `pokemon_id_each_team.csv`: Composición de 100 equipos Pokémon.
- `team_combat.csv`: Resultados de 10,000 combates entre los equipos.
- `pokemon_ai_model.ipynb`: Cuaderno Jupyter con el análisis, procesamiento de datos y entrenamiento del modelo.

## Descripción del proyecto

Se entrenó un modelo de clasificación (Random Forest) para predecir el equipo ganador en un combate Pokémon, basándose en las estadísticas individuales de los Pokémon y la composición del equipo.

Entre los pasos destacados del proceso se incluyen:

- Limpieza y transformación de datos
- Creación de características estadísticas por equipo
- Entrenamiento de un modelo de Random Forest
- Evaluación del modelo y predicción de resultados de combate
- Recomendación de mejoras en los equipos

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Resultado

El modelo logró una buena precisión al predecir combates, y se diseñó un sistema interactivo para probar equipos, ver resultados y explorar composiciones.

## Créditos

Integrantes del equipo:
- Diaz Aguirre Salvador
- Arévalo Alcántara Joaquin
- Salinas Casaico Diego
- Rivas Carrillo Ricardo

## Fuentes de datos

- [Pokemon Challenge Dataset](https://www.kaggle.com/datasets/terminus7/pokemon-challenge)
- [Pokemon Dataset with Team Combat](https://www.kaggle.com/datasets/tuannguyenvananh/pokemon-dataset-with-team-combat)

---

Proyecto desarrollado en 2024 para fines educativos.
