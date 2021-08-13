### Conclusión general

A partir del problema planteado se distingue la necesidad de elegir una técnica que optimice y resuelva al mismo. En general los procedimientos llevados a cabo permitieron seleccionar, a nuestro criterio, la técnica que dio mejores resultados y resolvió el problema planteado. Sin embargo, es importante destacar que la aplicación de cada una de las mismas fue un proceso indispensable que permitió aclarar nuestro objetivo y reconocer sus ventajas y desventajas para futuras intervenciones.
Las técnicas que se aplicaron fueron:
  - Term Frequency, si bien no fue el método elegido, la misma puede ayudar a distinguir variaciones semánticas sutiles, por lo que generalmente debemos considerarla en un principio como análisis exploratorio del documento a trabajar.
  - Probability of words, que presentó resultados interesantes y mostró cuales eran las palabras más notables del dataset. Su implementación se adecuó de mejor manera a la demanda, optimizando los resultados obtenidos en relación a la aplicación de TF.  
  - Word embedding, cuya implementación fue la que dió respuesta al objetivo planteado. Para verificar que las _keywords_ seleccionadas sean las adecuadas en función del contexto abordado se comenzó la recolección de tweets con las mismas y se observó que lograban mantener la diversidad de discursos sociales en el dataset que se iba almancenando.

### A tener en cuenta

Errar es humano! y es aquí donde se hacen notorios nuestros errores. 
  - En primer lugar para que todas las técnicas funcionen de manera adecuada es importante un preprocesamiento del texto. Para ello es importante saber que tipo de corpus es sobre el que se está trabajando, así se pueden encontrar más rápidamente las características particulares de los textos. Por ejemplo en twitter se maneja un tipo de escritura que no sigue las reglas gramaticales usualmente. 
  - Otro aspecto importante es realizar la lematización, que es algo que no se llevó a cabo durante el procedimiento. Esto podría haber resultado en un mejor desenlace para las técnicas de TF y PW.  
  - Durante la recolección de los datasets usados para los análisis no se incorporó la columna 'retweet', de esta forma no se contaba con una sistematización adecuada para eliminar aquellos que eran retweets. Esto influyó de manera negativa en los resultados de TF, donde casi todas las palabras que resultaron frecuentes para obeso corresponden al mismo tweet que tuvo muchos retweets. Este tweet se puede ver de manera ilustrativa en la sección 'algunas curiosidades de los resultados' más abajo.
  - Por último algo que hubiese sido interesante realizar es una evaluación de cada una de las técnicas con el uso de métricas. Esto podría haberse realizado utilizando el _accuracy_ = count related _t_ / count _t_ * 100 . Nuestra forma de evaluar si las palabras eran las adecuadas o no fue a través de nuestro criterio a priori como expertas en el área. Sin embargo, es importa recalcar que existen varios métodos de evaluación y pueden ser más objetivos para cuando se trabaja sobre un tópico que no se tiene tanto conocimiento. 

También podríamos haber utilizado otras técnicas para resolver este problema. Una de ellas podría haber sido Latent Dirichlet Allocation (LDA) la cual permite que conjuntos de observaciones puedan ser explicados por grupos no observados que explican porqué algunas partes de los datos son similares. Hubiera sido interesante aplicarla pero se tendrá en cuenta como técnica a implementar más adelante en el análisis para el modelado de tópicos. Otra técnica que se podría haber usado es la combinación de dos métodos. Quizás mezclando TF con PW y viceversa hubiera sido interesante ver como podrían, o no, haber cambiado esos resultados.

### Problemas futuros a resolver

Una vez que se finalice la primer etapa del proceso de recolección de tweets con las nuevas _keywords_ se procederá a sistematizar el filtrado de las localizaciones de los usuarios. Se tiene interés en dejar sólo aquellos tweets que pertenecen a usuarios de Argentina, y posteriormente generar una nueva base pero con los tweets provenientes sólo de Córdoba Capital. Como el filtrado por coordenadas no puede ser usado si se están recolectando los tweets con _keywords_ este proceso deberá ser llevado a cabo manualmente. Por el momento se ha pensado en ordenar las locaciones por frecuencia de aparición y utilizar los términos de aquellas que presentan alta frecuencia.

### Algunas curiosidades de los resultados 

Tweet polémico para TF: https://twitter.com/agustinbjs_/status/1394061977358635009?s=20 y los resultados del top 10 de TF, _OBESO: obesos, decirle, hermoso, river, quieras, penales, pusiste, picame, cardona, perdono._ Coincidencias ? 

En PW aparecieron las palabras Seagal y CSIC las cuales llamaron nuestra atención. Hicimos una búsqueda y este fue el resultado:
En mayo el actor Steven Seagal fue acusado de acoso sexual y muchxs usuarixs de twitter hicieron mención del mismo como "el obeso Seagal" 
https://as.com/tikitakas/2021/05/20/portada/1621488340_684040.html    

El CSIC es el consejo superior de investigaciones científicas de España. Si bien algunos tweets de España fueron eliminados, se buscó en la base y encontró que algunas de las noticias también habían sido compartidas por usuarios con locación en Argentina. La noticia compartida estaba relacionada a probióticos y sobrepeso.
https://www.csic.es/ 
