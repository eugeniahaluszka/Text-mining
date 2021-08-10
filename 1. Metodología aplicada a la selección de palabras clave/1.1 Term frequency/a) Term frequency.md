## Term frequency

En una primera instancia se optó por realizar la selección de keywords basándose en Term frequency (TF). Se trata de una técnica que mide con qué frecuencia ocurre un término en un documento determinado. En NLP (procesamiento del lenguaje natural) un término puede ser entendido como una palabra, frase o incluso un token, sólo dependerá de como sea definido, así como también un documento puede ser una oración, un capítulo de un libro, un tweet, entre otros. A su vez, los documentos pueden presentar distintas longitudes, lo cual puede dar lugar a que un término ocurra con más frecuencia en documentos largos que en documentos cortos. Esto podría generar que se piense que un término es de mayor importancia para un documento largo que uno de menor longitud. Debido a eso es que la frecuencia de los términos a menudo se divide por el número total de términos en el documento como una forma de normalización. Existen otras técnicas de normalización a usar como la frecuencia máxima de los términos como la frecuencia promedio de los términos. De todas formas, no serán profundizas en este trabajo.
Para que los resultados obtenidos con esta técnica sean exitosos es necesario realizar un adecuado pre-procesamiento del texto a análizar. Es importante eliminar las stopwords, las cuales son frecuentemente utilizadas en los textos y no presentan en este caso un significado analítico.
Muchas veces esta técnica suele complementarse con las frecuencias de documento inverso (IDF). La IDF es una ponderación que indica la frecuencia con la que se usa una palabra. Cuanto más frecuente sea su uso en documentos, menor será su puntuación. Estas técnicas se juntan formando TF-IDF, la cual consiste en multiplicar la TF con la IDF y así amortiguar la frecuencia de las palabras muy frecuentes y mejorar la identificación de las palabras importantes del tema.  




### Aplicaciones

Usualmente esta técnica es utilizada para caracterizar un documento, resumir un texto o capítulo de un libro..


Referencias: Gerard Salton and Michael J. McGill. 1986. Introduction to Modern Information Retrieval. McGraw-Hill, Inc., New York, NY, USA.
