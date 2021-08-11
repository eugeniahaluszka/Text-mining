## Probability of words

Este método consiste en identificar la probabilidad de que un término ocurra en un documento 'x', teniendo en cuenta a su vez la probabilidad que ese término ocurra en otro documento 'y'. Aquí no sólo se tiene en cuenta la frecuencia del término en un documento, sino la probabilidad que ocurra en ese documento en particular. Se estaría considerando de alguna forma la relevancia de un término para x documento, asegurandose de que el mismo responderá a la temática apuntada.

Para su procedimiento se debe tener un documento que responda a la temática de interés y otro documento (llamado a partir de ahora _no-documento_) que trata de temas en general. Se deberán calcular las probabilidades de ocurrencia de los términos en ambos documentos y luego serán comparadas. Es decir, la probabilidad que el término_1 ocurra en el documento es comparada contra la probabilidad de que el término_1 ocurra en el _no-documento_. Se obtendrán los términos más notables de cada documento y las mismas estarán relacionadas con el conjunto de datos, dando lugar a posibles _keywords_ adicionales a la temática.

## Aplicaciones

Si bien aquí proponemos este método para encontrar términos definidos como palabras, muchas veces se utilizan N-grams. Los N-grams son conjuntos de palabras que coocurren simultaneamente y pueden estar compuestos por dos palabras (bigrams) como "cómo estás", tres palabras (trigrams), etc. Usualmente el texto predictivo del celular utiliza está técnica para ir proponiendo la siguiente palabra en la oración. Es muy útil también para extraer una idea de un texto o capítulo de libro, o incluso de un discruso presidencial!

Ahora vamos a ponerlo en marcha en la notebook, ítem b).
