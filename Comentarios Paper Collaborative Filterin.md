## Comentarios Paper Collaborative Filtering Recommender Systems

El paper trata de explicar el proceso de filtrar o evaluar los llamados items usando la opinión de las otras personas.
Este proceso se aborda desde dos puntos de vista distintos. El primero es un sistema de recomendación no probabilístico. Acá nuevamente hay dos grandes subconjuntos que fueron abordados en el tema. El primero es un sistema de recomendación basado en el usuario. Esto quiere decir que se basa en las opiniones de otras personas sobre un item en especifico y se saca un promedio de sus ratings de ese producto para luego asignarselo a la persona que se le está recomendando el producto. Por otro lado, también se abordó el sistema de recomendación basado en el item. La diferencia es que ahora con el item que se quiere predecir su rating, se compara con otros productos buscando ver cuales son los que más se parecen en ratings para poder así ver con cuáles productos que sí existe información se puede predecir el rating del producto en cuestión.

Por otro lado, se comentan también sobre los sistema de recomendación probabilísticos. Como lo dice su nombre, estos se basan en probabilidades y algo que se explicaba y logré rescatar es el hecho de que uno tiene una ventaja con estos sistemas, ya que como nos estamos basando en modelos de probabilidad es que podemos saber qué tan confiables son las predicciones que estamos haciendo mediante intervalos de confianza y técnicas que ayudan a ver que tan confiable es lo que estamos prediciendo.

Ambos modelos se abordan de la parte teórica y práctica, desarrollando sus cualidades, ventajas y desventajas.
Una de las cosas que más me tenía en duda y pude solucionarlo, aunque parcialmente, es entender bien qué hacer dependiendo del caso que uno tenga. Sé que con la práctica uno podra divisar esa diferencia de manera más simple, pero a pesar de que nombraron cualidades y pusieron ciertos ejemplos, creo que igual faltaron algunos más conn distintos casos para así que quedara de manera más clara las diferencias y cómo se puede ir "jugando" dependiendo del problema al cual uno se esta enfrentando.
Otra cosa que encontré interesante es el hecho de los distintos ratings que existen, los explícitos e implícitos. Rescato la separación y la demostración de cómo en en la vida real generalmente hay mucha incertidumbre, pero es lógico que el ser humano repite ciertos patrones debido a ciertos gustos. Un ejemplo que rescato es el hecho de escuchar música. Hoy en día Spotify, la cual es una de las aplicaciones más usadas en el día de hoy, ocupa este rating implícito donde si una persona escucha más de una cantidad específica de segundos, eso da a parecer de que a la persona le gusto la canción, o el estilo o el género.
La última interrogante que el paper también me ayudo para solucionar es sobre qué pasa cuando uno quiere incluir un sistema de recomendación nuevo en un software. En el paper se habla con el nombre de "cold start issues". Acá se barajan ciertas posibilidades para poder disminuir la probabilidad de error del sistema al no tener infomración en un principio. Entre esas, y la cual encontré sorprendente es el hecho de poder generar información ficticia. Lo que me hubiera gustado saber un poco más de esta solución es qué tan adecuada es y cuándo se puede ocupar.