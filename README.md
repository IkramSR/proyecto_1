# Clasificación de gliomas de acuerdo con características clínicas y de mutación

## Descripción
En esta tarea de clasificación se hizo un comparativo del desempeño de dos modelos, un DecisionTree y un RandomForest, para clasificar tumores cerebrales primarios (gliomas) como LGG (glioma de grado inferior) o GBM (glioblastoma multiforme), optimizando hiperparámetros en ambos modelos de tal manera que se logre la mejor precisión sin caer en el sobreajuste. 

## Conclusiones
- Es fácil sobreajustar un árbol de decisión, se deben restringen ciertos parámetros y evaluar con validación cruzada.
- El remuestreo aleatorio en el que se basan los bosques de decisión hace que sea más dificil caer en el sobreajuste pero es importante elegir hiperparámetros adecuados para lograr una mejor precisión.
- Aunque tanto la precisión global como individual (para cada clase) es practicamente la misma para ambos modelos (DecisionTree y RandomForest) la importancia de variables no es igual, por lo tanto el modelo a usar se deberá seleccionar tomando en cuenta el grupo de variables más significativas que representen un menor costo de obtención; por ejemplo, sería mejor usar el modelo que da mayor importancia a la raza que al resultado de un estudio génetico específico, siendo que ambos modelos tienen la misma precisión.



## Datos proporcionados por
Tasci,Erdal, Camphausen,Kevin, Krauze,Andra Valentina, and Zhuge,Ying. (2022). Glioma Grading Clinical and Mutation Features. UCI Machine Learning Repository. https://doi.org/10.24432/C5R62J.

