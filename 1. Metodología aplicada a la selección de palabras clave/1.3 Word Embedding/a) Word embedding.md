## Word embedding

El método de Word Embedding (WE) consiste en representar palabrasen un espacio vectorial n-dimensional. Cada vector guarda información semántica, lo que permite que pueda ser asociado o disociado a otros vectores (palabras) según los distintos contextos gramaticales. De esta forma se tiene en cuenta tanto la semántica como las relaciones entre las palabras. 
Los métodos de WE aprenden una representación vectorial de valor real a partir de un corpus de texto. Este corpus es de gran importancia ya que le va a nutrir al WE con respecto a contextos gramaticales y usos de las palabras.

Existe una gran variedad de métodos para generar WE y éstos métodos pueden aplicarse a distintos tipos de textos e idiomas. Así, cada conjunto de WE puede contener un conocimiento distinto a otros WE.



Es común que los investigadores pongan a su disposición de forma gratuita word embedding o incrustaciones de palabras previamente formadas, a menudo bajo una licencia de acceso abierto, para que pueda utilizarlas en sus propios proyectos académicos o comerciales. Estos pueden ser utilizados en los proyectos en lugar de entrenar sus propias incrustaciones desde cero. 
Entonces existen dos opciones principales cuando se trata de usar embeddings pre-entrenados:
    Utilizarlos de manera estática, en donde el WE se mantiene y utiliza como componente de su modelo, siempre y cuando el WE se adapta al problema y da buenos resultados y la otra forma es usarlo actualizado, donde el embedding pre-entrenado se utiliza para sembrar el modelo, pero el embedding se actualiza conjuntamente durante el entrenamiento del modelo. 

## Aplicaciones


Sistemas de traducción: Generalmente estos sistemas están formados por una red neuronal que actúa como codificador y una red neuronal que actúa como decodificador. Tanto la entrada como la salida de estas redes neuronales son secuencias de palabras, estas palabras se representan mediante word embeddings. 
Análisis de opinión en textos: Con el crecimiento de popularidad de las redes sociales, resulta muy interesante el desarrollo de un sistema capaz de analizar si las opiniones de sobre un producto son positivas o negativas. 
Generación de textos: Mediante el uso de redes neuronales recurrentes es posible generar texto de forma automática. Combinando estos modelos con redes convolucionales es incluso posible crear sistemas que anoten o describan imágenes.
Chatbot, o sistemas que respondan preguntas de usuarios. 


## Procedimiento realizado
