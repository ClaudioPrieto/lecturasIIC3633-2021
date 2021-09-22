# Lectura 5: Combining Predictions for Accurate Recomender Systems

En el paper se analiza la aplicacion sistemas recomendadores ensamblados en el dataset de _Netflix Prize_. En este se utilizan una serie de algoritmos de filtrado colablorativo implementadas previamente, los cuales se combinan de manera lineal, finalmente incrementando el accuracy obtenido por estos algoritmos implementados de forma separada. 

Se dice que en el caso del entrenamiento de redes neuronales se utiliza _gradient descent_, sin embargo, no se justifica porque se utiliza este metodo y si este es la mejor opcion para este caso. Se podria evaluar y comparar otro metodo de entrenamiento para la red neuronal.

En los algoritmos de filtrado colaborativo se muestra que se uso los clasificadores KNN-1, KNN-2, KNN-3 y KNN-4, siendo este ultimo el con mejor RMSE. No se entiende porque no se utiliza KNN con mayor cantidad de vecinos, si este podria tener mejor resultados que los on 1 0 2 vecinos.

Es interesante el concepto de mezclar los resultados de diferentes filtrados colaborativos, ya que los diferentes algoritmos tienen fortalezas y debilidad que pueden complementarse mediante este metodo. Seria interesante un estudio que muestre las diferentes combinaciones de algoritmos, y no solo la evaluacionn de los 18 algoritmos en los vectores.

Uno de los metodos para evaluar el modelo es el _Bagged Gradient Boosted Decision Tree_, el cual es una implementacion de arboles de decision con algunos cambios como lo es el _bagging_, serian interesante evaluar la implentacion de esto mismo en otros algoritmos para mejorar los resultados y obtener un mejor RMSE.
 
