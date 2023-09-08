# PortafolioAnalisisIA
**Portafolio para la clase Inteligencia Artificial Avanzada para la Ciencia de Datos, Grupo 101**

Dentro del portafolio se encuentran tres archivos importantes: [Módulo 1 Técnicas de procesamiento de datos para el análisis estadístico y para la construcción de modelos](LimpiezaDatos.ipynb), [Módulo 2 Análisis y Reporte sobre el desempeño del modelo. (Portafolio Análisis)](ReporteDesempeño.ipynb) y [Análisis del contexto y la normatividad](Análisis_del_Contexto_y_la_Normatividad_-2.pdf). Estos folders contienen los archivos de los entregables que corresponde a cada uno de los módulos en donde se pide una evidencia de portafolio. 


## Modulo1
Dentro del [Modulo1](Modulo1) encontramos distintos archivos que pertenecen al módulo de Estadística. Este se desgloza de la siguiente manera:

### [LimpiezaDatos.ipynb](Modulo1/LimpiezaDatos.ipynb)


### [ConstruccionModelo.ipynb](Modulo1/ConstruccionModelo.ipynb)





## Modulo2
Dentro del [Modulo2](Modulo2) encontramos distintos archivos que pertenecen al módulo de Machine Learning. Este se desgloza de la siguiente manera:

### Implementación de una técnica de aprendizaje máquina sin el uso de un framework
En el archivo de [RegresionLineal.ipynb](Modulo2/Portafolio1/RegresionLineal.ipynb) se utilizó la base de datos llamada [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) con la cual se trabajó con la intención de implementar una técnica de aprendizaje máquina sin el uso de un framework. Para este, se creó un modelo de Regresión Lineal con la intención de predecir cuánto contaminan los vehículos en base a los parámetros que se tienen en la base de datos. Dentro del archivo se hizo la lectura y descripción de los datos, donde encontramos los valores estadísticos de estos y la cantidad de valores nulos en el dataframe. Después se hizo una matriz de correlación para encontrar qué variables tienen relación lineal con la variable de CO2 Emissions para ver cuales causan la contaminación vehicular. Finalmente se crearon gráficos para visualizar los datos y, en base a esto, se eligió la variable Engine Size (L) para usar en el modelo. 


### Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución
Para este [archivo](Modulo2/Portafolio1/RegresionLinealFramework.ipynb), se utilizó la base de datos [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) con la que se trabajó para crear un modelo de Regresión Lineal utilizando un framework. Para este, se entrenó utilizando LinearRegression() de la librería sklearn. En el archivo se hizo lectura y descripción de los datos para encontrar los valores estadísticos de las variables al igual que verificar que no haya valores nulos. Después se hizo una matriz de correlación con la cual se optó por utilizar todas las variables cuantitativas del dataframe para el modelo. Enseguida, se crearon los daots de entrenamiento y de prueba para entrenar el modelo y verificarlo. Finalmente se encontró una función que predice los valores del dataframe junto con los valores de los errores que la regresión obtuvo.


### Análisis del contexto y la normatividad

Dentro del [archivo](Modulo2/Portafolio1/Análisis_del_Contexto_y_la_Normatividad_-2.pdf), se encuentra el Análisis del Contexto y la Normatividad, la cual explica sobre las leyes y la normatividad que involucran el uso de la base de datos de [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) y cómo es que el uso de esta no está rompiendo ninguna ley. Igualmente en esta se hace un análisis de los escenarios en que se puede utilizar de manera no-ética la base de datos.


### Análisis y Reporte sobre el desempeño del modelo
Para el [ReporteDesempeño.ipynb](Modulo2/Portafolio1/ReporteDesempeño.ipynb), se utilizó nuevamente la base de datos [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) con la cual se separaron los datos en train (60%), validation (20%) y test (20%) para entrenar, validar y probar el modelo. Para este se entrenó el modelo como Regresión Lineal y se verificó antes de hacer las pruebas con el test. Una vez que se validó el modelo y observando que los resultados son buenos gracias a los errores encontrados, se implementó con el batch de test y se propuso el modelo que nos ayudará a predecir los datos. Enseguida, se hizo una prueba de normalidad en los residuos para ver si hay sesgo en los datos, con la cual no se encontró sesgo. Finalmente, se buscó mejorar el desempeño del modelo al cambiar los hiperparámetros utilizando la función Ridge() de sklearn. Dentro de este, se logró mejorar el modelo ya que logramos encontrar que los errores son menores y cuidando que no haya un overfitting en el modelo. Finalmente se volvió a predecir algunos datos y se compararon con el modelo anterior para después encontrar que evidentemente el nuevo modelo es mejor.
