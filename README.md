# PortafolioAnalisisIA
**Portafolio para la clase Inteligencia Artificial Avanzada para la Ciencia de Datos, Grupo 101**

Dentro del portafolio se encuentran tres archivos importantes: [Módulo 1 Técnicas de procesamiento de datos para el análisis estadístico y para la construcción de modelos](LimpiezaDatos.ipynb), [Módulo 2 Análisis y Reporte sobre el desempeño del modelo](ReporteDesempeño.ipynb) y [Análisis del contexto y la normatividad](Análisis_del_Contexto_y_la_Normatividad_-2.pdf). Estos folders contienen los archivos de los entregables que corresponde a cada uno de los módulos en donde se pide una evidencia de portafolio. 


## Módulo 1 Técnicas de procesamiento de datos para el análisis estadístico y para la construcción de modelos
Para la evidencia del módulo 1, se creó el archivo [LimpiezaDatos.ipynb](LimpiezaDatos.ipynb) en donde se descargó la [base de datos](precios_autos-2.csv) y se hizo un análisis exploratorio para una compañía automovilista china para que puedan entender el mercado automovilista americano y puedan establecer una fábrica de unidades en dicho país al predecir el valor de los precios en base a las variables de los carros. En este, se crearon diferentes gráficos de histogramas y de boxplot para encontrar valores atípicos y ver cómo tratarlos. Igualmente se hicieron análisis de colinealidad y de distribuciones para observar qué variables son las que puedan predecir el precio de un automovil en base a diferentes factores que afectan al consumidor americano. Finalmente se eligieron seis variables que se consideraron importantes para la predicción de los precios de los autos.



## Análisis del contexto y la normatividad
Dentro del [archivo](Análisis_del_Contexto_y_la_Normatividad_-2.pdf), se encuentra el Análisis del Contexto y la Normatividad, la cual explica sobre las leyes y la normatividad que involucran el uso de la base de datos de [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) y cómo es que el uso de esta no está rompiendo ninguna ley. Igualmente en esta se hace un análisis de los escenarios en que se puede utilizar de manera no-ética la base de datos.



## Módulo 2 Análisis y Reporte sobre el desempeño del modelo
Para el [ReporteDesempeño.ipynb](ReporteDesempeño.ipynb), se utilizó nuevamente la base de datos [CO2 Emissions.csv](https://www.kaggle.com/datasets/bhuviranga/co2-emissions?select=CO2+Emissions.csv) con la cual se separaron los datos en train (60%), validation (20%) y test (20%) para entrenar, validar y probar el modelo. Para este se entrenó el modelo como Regresión Lineal y se verificó antes de hacer las pruebas con el test. Una vez que se validó el modelo y observando que los resultados son buenos gracias a los errores encontrados, se implementó con el batch de test y se propuso el modelo que nos ayudará a predecir los datos. Enseguida, se hizo una prueba de normalidad en los residuos para ver si hay sesgo en los datos, con la cual no se encontró sesgo. Finalmente, se buscó mejorar el desempeño del modelo al cambiar los hiperparámetros utilizando la función Ridge() de sklearn. Dentro de este, se logró mejorar el modelo ya que logramos encontrar que los errores son menores y cuidando que no haya un overfitting en el modelo. Finalmente se volvió a predecir algunos datos y se compararon con el modelo anterior para después encontrar que evidentemente el nuevo modelo es mejor.
