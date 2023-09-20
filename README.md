# TecnicasDeAprendizajeAutomatico
Repositorio publico, en donde el objetivo es juntar las diferentes herramientas de Machine Learining a usarse en la Ciberseguridad

# 1.- Detección de anomalías:

El Isolation Forest (Bosque de Aislamiento) es un algoritmo de detección de anomalías utilizado en machine learning y ciberseguridad para identificar patrones inusuales en un conjunto de datos. Fue propuesto por Fei Tony Liu, Kai Ming Ting y Zhi-Hua Zhou en 2008. La idea principal detrás del Isolation Forest es que las anomalías son raras y, por lo tanto, más fáciles de aislar en comparación con las instancias normales en un conjunto de datos.

El funcionamiento del Isolation Forest se puede resumir en los siguientes pasos:

Selección aleatoria de características: En cada paso del algoritmo, se elige una característica aleatoria del conjunto de datos. Esta selección aleatoria de características ayuda a acelerar el proceso de aislamiento de anomalías y reduce la necesidad de calcular la importancia de todas las características.

Selección aleatoria de valores umbral: Para cada característica seleccionada, se elige aleatoriamente un valor de umbral dentro del rango de valores observados para esa característica.

División de datos: El conjunto de datos se divide en dos subconjuntos utilizando el valor de umbral seleccionado. Los puntos de datos que tienen un valor menor o igual al umbral se colocan en un subconjunto y los puntos de datos con un valor mayor se colocan en el otro subconjunto. Esto simula la división de un conjunto de datos en ramas en un árbol de decisión.

Recursión: Los pasos anteriores se repiten recursivamente en los subconjuntos resultantes hasta que se aíslen todas las anomalías o se alcance una altura máxima predefinida en el árbol. Cada vez que se divide un subconjunto, se reduce su tamaño a la mitad aproximadamente.

Construcción de árboles múltiples: El proceso anterior se repite para construir múltiples árboles de aislamiento. Cuantos más árboles se construyan, mejor será la capacidad del algoritmo para identificar anomalías.

Puntuación de anomalías: Para puntuar un punto de datos, se calcula la profundidad promedio en la que se encuentra ese punto en todos los árboles. Los puntos que se aíslan rápidamente en varios árboles se consideran más propensos a ser anomalías.

Umbral de decisión: Para determinar si un punto de datos es una anomalía, se compara su puntuación con un umbral de decisión. Los puntos con una puntuación superior al umbral se consideran anomalías.

El Isolation Forest tiene la ventaja de ser eficiente y escalable, lo que lo hace adecuado para detectar anomalías en conjuntos de datos grandes. Además, no requiere normalización de datos y puede manejar características categóricas. Es especialmente útil en la detección de intrusiones, la identificación de malware y la identificación de comportamientos anómalos en el tráfico de red.

# 2.- Detección de intrusiones:



3.- Clasificación de malware:



4.- Análisis de tráfico de red:


5.- Predicción de amenazas:


6.- Seguridad de aplicaciones web:



7.- Autenticación y acceso seguro:


8.- Visualización de datos de seguridad:


9.- Aprendizaje federado en ciberseguridad:


10.- Recopilación de conjuntos de datos:
