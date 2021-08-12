## Conclusión

A partir de la aplicación de probability of words (PW) se determinó que esta técnica tampoco sería la adecuada para resolver nuestro objetivo. Sin embargo, cabe destacar que los resultados obtenidos son interesantes de analizar. El PW permitió diferenciar las palabras que identificaban el dataset con temática de obesidad y esto es de gran importancia para extraer ideas principales o incluso se podrían haber extraído n-grams y conocer un poco más sobre lo que twittean los usuarios en ese dataset. 
Entre las principales observaciones podemos mencionar lo siguiente:
  - Para esta técnica no es necesario eliminar las stopwords, dado que las mismas presentarán la misma probabilidad de aparición tanto en el _dataset_ como en el _no-dataset_. De todas formas se llevó a cabo en este proyecto y se eliminaron las palabras semilla que fueron usadas para recolectar los tweets del dataset de obesidad.
  - La principal desventaja de este método es que una palabra 'extraña' que aparece en uno de los datasets puede presentar una probabilidad alta de ocurrencia en el mismo sin estar significativamente relacionada con la temática. 
  - Otra desventaja de esta aplicación es la necesidad de otro documento para la comparación de las probabilidades de ocurrencia. 

Esta técnica podría ser implementada más adelante para conocer los n-grams de conjuntos de tweets, siendo parte de un análisis exploratorio. 
Realizar este procedimiento nos ayudó a aclarar y definir correctamente nuestro objetivo. Necesitamos palabras clave para la recolección de tweets pero las mismas deben de alguna forma reemplazar esa palabra semilla, es decir actuar como sinónimos. Dado esto es que planteamos la aplicación de otro método acorde a la resolución del problema: Word Embedding.
