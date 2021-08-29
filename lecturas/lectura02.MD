#Lectura 02: Matrix factorization techniques for Recommender Systems

El _paper_ trata sobre el uso de modelos de factorizacion matriciales en Sistemas Recomendadores y como son superiores a los algoritmos KNN utilizados en esta area. Una de las ventajas que tiene este metodo es que se puede incorporar informacion implicita en el caso de que no se tenga datos explicitos ingresados por el usuario. En el texto se explica una implementacion basica del modelo de factorizacion matricial, en donde se representan todos los items y usuarios en sus respectivos vectores, en donde el producto punto entre el vector del item i y el vector del usuario u, representa la interaccion entre u e i. Ademas se explica la implementacion de _biases_ tanto para usuarios como para items, de tal forma que se reconozca que usuarios tienden a catalogar cosas mas altas o bajas y que items tienden a recibir calificaciones mas altas o bajas, de esta forma disminuir el error de las recomendaciones que se realizan a partir de esta informacion.

Se muestra como utilizar la factorizacion matricial para contrarrestar el problema de _cold start_ mediante la recoleccion de datos implicitos ingresados por el usuario y tamnbien se mustra como utilziar datos temporales, tales como las variaciones en los _biases_ de los usuarios. Finalmente se hable de como implementaron este tipo de algoritmos en la _netflix Prize Competition_ obteniendo resultados muy buenos.

Uno de los conceptos mas interesantes en el texto fue cuando se le agrego a la prediccion la variable del tiempo, es algo que deberia ser importante en algoritmos de recomendacion, ya que todos los usuarios desarrollan sus gustos a medida que pasa el tiempo siendo los ultimos ratings ingresados por el este los que mas peso deberian tener en un sistema recomendador.

Otro aspecto interesante es como incorporan los atributos basicos del usuario en la misma ecuacion general del modelo de factorizacion matricial, esto podria resultar muy util en casos de _cold start_ extremos en los cuales todavia no se cuenta con ningun otro dato implicito del usuario como historail de busqueda o compras realizadas.  



