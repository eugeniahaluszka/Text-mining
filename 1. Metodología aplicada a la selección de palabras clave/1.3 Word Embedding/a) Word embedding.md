## Word embedding

Los métodos de embedding de palabras aprenden una representación vectorial de valor real para un vocabulario predefinido de tamaño fijo a partir de un corpus de texto. El proceso de aprendizaje está unido con el modelo de red neuronal en alguna tarea, como la clasificación de documentos, o es un proceso no supervisado que utiliza estadísticas de documentos.

Los Word Embeddings son funciones que nos permiten mapear palabras a un vector n-dimensional, partiendo del supuesto de que palabras que se encuentran en un espacio semejante deben tener algún tipo de relación. 
Así, un embedding de palabras es una representación aprendida de un texto, donde las palabras que tienen el mismo significado tienen una representación similar. La representación distribuida se aprende a partir del uso de las palabras, permitiendo que palabras que son usadas de maneras similares resulten en representaciones similares, considerando su significado.

Existe una gran variedad de métodos para generar word embeddings y éstos métodos pueden aplicarse a distintos tipos de textos e idiomas. Así, cada conjunto de word embeddings puede contener un conocimiento distinto a otros word embeddings.
Es común que los investigadores pongan a su disposición de forma gratuita word embedding o incrustaciones de palabras previamente formadas, a menudo bajo una licencia de acceso abierto, para que pueda utilizarlas en sus propios proyectos académicos o comerciales. Estos pueden ser utilizados en los proyectos en lugar de entrenar sus propias incrustaciones desde cero. 
Entonces existen dos opciones principales cuando se trata de usar embeddings pre-entrenados:
    Utilizarlos de manera estática, en donde el WE se mantiene y utiliza como componente de su modelo, siempre y cuando el WE se adapta al problema y da buenos resultados y la otra forma es usarlo actualizado, donde el embedding pre-entrenado se utiliza para sembrar el modelo, pero el embedding se actualiza conjuntamente durante el entrenamiento del modelo. 

## Aplicaciones


Sistemas de traducción: Generalmente estos sistemas están formados por una red neuronal que actúa como codificador y una red neuronal que actúa como decodificador. Tanto la entrada como la salida de estas redes neuronales son secuencias de palabras, estas palabras se representan mediante word embeddings. 
Análisis de opinión en textos: Con el crecimiento de popularidad de las redes sociales, resulta muy interesante el desarrollo de un sistema capaz de analizar si las opiniones de sobre un producto son positivas o negativas. 
Generación de textos: Mediante el uso de redes neuronales recurrentes es posible generar texto de forma automática. Combinando estos modelos con redes convolucionales es incluso posible crear sistemas que anoten o describan imágenes.
Chatbot, o sistemas que respondan preguntas de usuarios. 
