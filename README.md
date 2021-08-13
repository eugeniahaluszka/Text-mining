# Trabajo de presentación para curso de posgrado: "Text mining"

Actualmente, la mayoría de la información que una persona produce y consume es en formato texto, sumado a esto, el crecimiento explosivo de la información de texto en línea ha creado una fuerte demanda de herramientas de software inteligentes que proporcionen servicios para ayudar a las personas a gestionar y a la utilización de estos datos que en general son de gran tamaño (ChengXiang, 2016).


## Tema: Tópicos ocultos en torno a la temática de obesidad

### Introducción

En la actualidad se está haciendo uso de las plataformas de redes sociales como fuente de información en diversas investigaciones en salud. Las mismas han producido resultados que de alguna forma revolucionaron los procesos de vigilancia y gestión en salud, entre otros, generando un cambio paradigmático en esta área y favoreciendo la medicina preventiva y la promoción de la salud (Organización Panamericana de la Salud [OPS], 2016). La información contenida en redes sociales ha demostrado ser de utilidad para predecir y explicar las características y estados de brotes de enfermedades (Ginsberg J, 2009). Si bien al comienzo estos estudios se orientaron al análisis de enfermedades transmisibles (Boon-Itt S, 2020; Ginsberg J, 2009), actualmente se aplica a las enfermedades crónicas de naturaleza multicausal (Tsuya A, 2014; Lui CW, 2021). La plataforma de Twitter es una de las redes sociales más utilizadas para extraer información a partir de minería de datos de texto. Esto se debe a que les permite a los investigadores obtener un gran caudal de información generado por los usuarios y, además, contiene una API propia que facilita y controla el proceso (Tweepy, 2009). Desde la minería de datos de texto se trabaja con el procesamiento del lenguaje natural (PLN) (Cortéz Vasquez A, 2009), el cual abarca parte de la ciencia de datos, el aprendizaje automático (Machine Learning) y la lingüística. El PLN permite que las computadoras interactúen con el lenguaje humano, dándole significado para que pueda ser usado de manera práctica en el desarrollo de asistentes conversacionales, traducciones, análisis de sentimientos, modelado de tópicos, entre otros (Cortéz Vasquez A, 2009).
En el presente proyecto, disciplinas de la ciencia de datos como son el PLN basado en el aprendizaje automático serán utilizadas para la recopilación, análisis y síntesis de un gran caudal de datos (Big Data), que permitirán identificar tópicos de discusión en torno a la temática de la obesidad. Se estaría de este modo considerando las concepciones y representaciones de las personas en torno a esta patología, lo cual desde una perspectiva holística se considera de importancia para comprender las prácticas o resultados de salud de las poblaciones y los factores sociales que la condicionan. 
	
### Motivación: 

Específicamente, asumimos que existen tópicos sobre obesidad predominantemente discutidos en las plataformas sociales virtuales, cuyo conocimiento y análisis aportaría a la comprensión de los determinantes sociales de esa patología. Además, se espera que a partir de este proyecto se implementen herramientas de análisis como lo son el PLN y el aprendizaje automático para el estudio de los condicionantes sociales de la salud de las poblaciones, en este caso en relación a obesidad, pero potencialmente aplicable a otras enfermedades de naturaleza multicausal.

### Planteamiento del problema: 

Ante la primera etapa del proyecto surge el primer problema a resolver: ¿Cuáles serán las palabras clave utilizadas para recolectar tweets relacionados en este caso a la temática de la obesidad que abarque y visibilice todos los discursos en torno a esta temática? 

### Meta: 

Generar una base de tweets que sea completa y relevante en torno a una temática particular de las Ciencias de la Salud, a partir de una palabra clave y sus derivadas. La selección de las mismas debería ser sistemática y metodológica, para permitir su reproducibilidad. Además, debería garantizar la representatividad de la base de datos a obtener, en función de abordar todos los discursos sociales considerando palabras características de los mismos con el fin de poder visibilizarlos.

### Organización: 

Este repositorio se organizó en 2 carpetas. En la carpeta 1 denominada “Metodología aplicada a la selección de palabras clave”, se encuentran las técnicas que fueron aplicadas, con una breve explicación, junto con las notebooks y sus respectivas salidas. Para cada técnica se mencionan y describen los procedimientos realizados, además de sus principales características. En las notebooks se encontrará el procedimiento llevado a cabo de manera detallada, su análisis, explicación, resultados visibles y conclusiones. En la carpeta 2 “Conclusiones” se podrá encontrar las principales conclusiones de todo el trabajo elaborado y los problemas futuros a tratar.

Trabajo inspirado en Han van der Veen, 2015 "Composing a more complete and relevant Twitter dataset" y Joaquin Amat Rodrigo, 2020 "Análisis de texto con python" disponible en: https://www.cienciadedatos.net/documentos/py25-text-mining-python.html


### Referencias bibliográficas

Boon-Itt S, Skunkan Y. Public Perception of the COVID-19 Pandemic on Twitter: Sentiment Analysis and Topic Modeling Study. JMIR Public Health Surveill 2020;6(4):e21978
ChengXiang Z, Sean M 2016. Text d Data Management and Analysis: A Practical Introduction to Information Retrieval and Text Mining. ‎ Association for Computing Machinery and Morgan & Claypool Publishers New York.
Cortez Vásquez A, Vega huerta H, Pariona Quispe J, Huayn, AM. Procesamiento de lenguaje natural. RISI. 2009;6(2), 45–54
Ginsberg J, Mohebbi MH, Patel RS, Brammer L, Smolinski MS, Brilliant L. Detecting influenza epidemics using search
engine query data. Nature 2009 Mar 19;457(7232):1012-1014.
Lui CW, Wang Z, Wang N, Milinovich G, Ding H, Mengersen K, Bambrick H, Hu W. A call for better understanding of social media in surveillance and management of noncommunicable diseases. Health Res Policy Syst. 2021 Feb 10;19(1):18.
Organización Panamericana de la Salud. La eSalud en la Región de las Américas: derribando las barreras a la implementación [Internet]. 2016 [citado el 7 de julio de 2018]. Disponible en: http://iris.paho.org/xmlui/handle/123456789/31287 
Tsuya A, Sugawara Y, Tanaka A, Narimatsu H. Do Cancer Patients Tweet? Examining the Twitter Use of Cancer Patients in Japan. J Med Internet Res 2014;16(5):e137
Tweepy. Stream reference and documentation [Internet]. 2009-2021 [Citado 23 de julio de 2021]. Disponible en: https://docs.tweepy.org/en/latest/stream.html 
