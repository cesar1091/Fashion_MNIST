# Fashion_MNIST :smile:
En el siguiente repositorio tome la base de datos de Fashion MNIST de Kaggle, en primer lugar al ser una base de datos de imagenes colocadas pixel por pixel para graficar 
lo reescale a su dimensión original y lo grafique gracias a la paqueteria de matplotlib.pyplot, luego de leer en la base de datos su clasificación al ser demasiadas variables 
para el estudio realize un pipeline en la cual haremos un análisis de los componentes principales de los pixeles más relevantes para cada clasificación. Luego, al pipeline se le 
agrego un support vector classifier con un meshgrid con el cual podremos conocer a los mejores parametros para nuestro modelo haciendo una validación cruzada. Finalmente se escoge
los mejores parámetros y se observa la certeza del modelo.

Cabe aclarar que se toma un subconjunto de toda la base de datos ya que era demasiado costo computacional el correr con toda la base de datos. A mayor precisión mayor coste computacional, 
Por ello al terminar el script pude realizar un cuadro de la matriz de confusión para verificar en donde falla más las predicciones.

Lo recomendable cuando se trabaja con base de datos muy grandes es sacar una muestra aleatoria que este uniformemente distribuida para cada clase.
