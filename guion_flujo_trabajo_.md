# Construcción de un flujo de trabajo para responder a la pregunta planteada


> + **_Versión_**: 2023-2024
> + **_Asignatura (titulación)_**: Ciclo de gestión del dato: ecoinformática (máster conservación, gestión y restauración de la biodiversidad. UGR). 
> + **_Autor_**:  Curro Bonet-García (fjbonet@uco.es)
> + **_Duración_**: Unas seis horas (tres sesiones de dos horas)



## Objetivos del acto docente

Esta sesión tiene la siguiente finalidad:

> Construir un flujo de trabajo que nos permita encontrar respuestas a la siguiente pregunta: "¿En qué pinares debemos de intervenir para optimizar el proceso de naturalización?"
> 

También tiene los siguientes objetivos específicos:

+ Disciplinares: objetivos relacionados con la ecología:
  + Mejorar el conocimiento sobre la estructura y funcionamiento de los pinares de repoblación en el sudeste de la Península Ibérica.
  + Afianzar el conocimiento ya existente sobre la formulación de preguntas científicas y de preguntas sobre manejo de recursos naturales.
  + Contribuir a generar conocimiento útil para abordar un problema ambiental complejo.
+ Instrumentales: Objetivos relacionados con la adquisición de competencias en el manejo de herramientas. 
  + Aprender a reformular preguntas no investigables para que sí lo sean.
  + Aprender a construir flujos de trabajo para abordar preguntas científicas.
  + Extraer una lista de variables importantes para resolver un problema concreto.
  + Distinguir el concepto de variable del de criterio de toma de decisión.



## Flujos de trabajo

Un flujo de trabajo es una secuencia de acciones ordenadas cuya ejecución tiene un objetivo determinado. Esta definición tan genérica se puede particularizar más en nuestro ámbito de trabajo: secuencia de acciones que realizamos sobre un conjunto de datos para satisfacer un objetivo dado. En nuestro caso, el objetivo es responder a la pregunta descrita en la sección anterior.

Es importante que aprendamos a crear flujos de trabajo porque nos ayudan en el proceso de creación y análisis de la información ambiental. En esta sesión construiremos un flujo de trabajo que nos guiará durante el resto de la asignatura.

En los siguientes enlaces tienes información sobre flujos de trabajo. Recomendamos su lectura:
+ [El papel de los flujos de trabajo en la reproducibilidad de la ciencia.](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2022-2023/biblio/how_to_flow.pdf) 
+ Descripción de [Kepler](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2022-2023/biblio/kepler.pdf), un sistema de flujo de trabajo científico muy útil (y algo complejo).
+ [Ejemplos de flujos de trabajo.](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2022-2023/biblio/workflow_reusable.pdf) 



## Hilo argumental

En este acto docente intentaremos reproducir de manera explícita el proceso que se sigue habitualmente cuando se prepara y ejecuta un proyecto de investigación científica. La idea es que los estudiantes sean capaces de abstraer el conocimiento adquirido para aplicarlo a otras situaciones.

+ La pregunta que nos hemos propuesto abordar es de las denominadas "[no investigables](https://www.quora.com/What-is-a-non-researchable-question/answer/Lawrence-Ness-4)". Se trata de una pregunta compleja que *a priori* no sabemos contestar. Sabemos a dónde queremos llegar: construir un flujograma que muestre los pasos a dar para responder a nuestra pregunta. Pero no sabemos cómo se hace eso. 
+ Cuando nos enfrentamos a algo que no sabemos hacer, es útil hacer dos cosas en paralelo:
  + Evocar el poco o mucho conocimiento que tengamos sobre el asunto en cuestión. Esto implica, en nuestro caso, tratar de extraer información de lo aprendido sobre pinares de repoblación tanto en esta asignatura como en cualquier otra. 
  + A continuación, es buena idea preguntar a quién sepa sobre este asunto. En nuestra situación no tenemos a mano a expertos humanos que puedan ayudar. Pero en los últimos meses disponemos de expertos no humanos que pueden ser de utilidad: las herramientas de inteligencia artificial que permiten entablar conversaciones. En nuestro caso usaremos [ChatGPT](https://chat.openai.com/) y [Perplexity](https://www.perplexity.ai/). 


















+ En primer lugar observamos que en la pregunta hay dos partes diferentes. Esto es muy común cuando trabajamos en un contexto de gestión y conservación de recursos naturales:
  + ¿En qué pinares debemos de intervenir...?: Es una pregunta de gestión que implica la intervención sobre el territorio. Para responder a esta parte de la pregunta necesitamos conocimiento científico que sería generado por la siguiente parte de la pregunta.
  + ¿... para optimizar el proceso de naturalización?: Esta segunda parte contiene otra pregunta que pone el foco en un proceso ecológico concreto, la regeneración de la encina bajo el dosel de pinos. Desde un punto de vista ecológico este proceso es equivalente al de sucesión. 
+ Para abordar la pregunta que se centra en el proceso ecológico daremos los siguientes pasos:
  1. Identificación de variables implicadas en el proceso ecológico a analizar. Este primer paso implica un nuevo proceso de desagregación, puesto que trataremos de evaluar en qué medida el proceso en cuestión depende de distintas variables biofísicas. Nos preguntaremos: ¿qué variables ambientales pueden condicionar la regeneración de la encina bajo el pinar? Para ello, y con objeto de suplir nuestros aún limitados conocimientos sobre este proceso, podremos consultar el esquema final que hay en [esta](https://github.com/aprendiendo-cosas/T_contexto_pinares_ecoinformatica_ugr/raw/2022-2023/presentacion/generalidades_pinares_reboblacion.ppt) presentación.
  2. ¿Son todas las variables del mismo tipo? Es de esperar que algunas variables tengan carácter biofísico (precipitación, profundidad del suelo, etc.) y otras socioeconómico (distancia a vías de comunicación, tasa de desempleo por municipio, etc.). Esta distinción será importante cuando las integremos todas para dar una respuesta final.
  3. Fuentes de datos: Una vez identificadas las variables que consideramos relevantes, procederemos a evalular la disponibilidad de datos para su uso en el análisis. En ese proceso quizás tengamos que usar variables subrogadas de las originales. [Aquí](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/1365-2664.13366) tienes una definición de lo que significa variable suborgada (lee solo el Abstract del artículo para una idea general) y [aquí](https://ebooks.publish.csiro.au/content/indicators-and-surrogates-biodiversity-and-environmental-change) un libro completo que trata sobre el asunto. La identificación de las fuentes de datos de partida también nos permitirá caracterizar preliminarmente el procesamiento que será necesario aplicar a los datos originales para satisfacer nuestras necesidades. Esta última frase, que pasa desapercibida, es muy importante porque ese procesamiento ocupará el grueso de la asignatura. En cada uno de los procesos aprenderemos técnicas diferentes (bases de datos, teledetección, cartografía de la vegetación, etc.)
  4. Hipótesis previas sobre cómo creemos que podría participar cada variable en el proceso general. Es decir, analizaremos en qué medida contribuye cada variable seleccionada a explicar la regeneración de la encina bajo el pinar. Por ejemplo, ¿Cómo afecta la densidad del pinar a la regeneración de la encina? En este caso está claro porque tenemos evidencias al respecto: a densidades bajas hay poca regeneración y a densidades altas también. Este paso será útil para hacernos una idea de cómo pueden interactuar las distintas variables que hemos seleccionado.
  5. Integración de todas las variables para obtener un resultado único. Se trata de la fase más crítica porque implica construir un modelo conceptual en el que todas las variables seleccionadas se integren y nos permitan responder a la pregunta (¿de qué variables depende la regeneración?, ¿Cuál es el peso relativo de cada variable?). El resultado de este paso deberá de ser un mapa que muestre cuantitativamente la "intensidad" del proceso de regeneración en cada punto del territorio. Esta intensidad se podrá medir en probabilidad, idoneidad o en número de encinas que se regeneran dependiendo del tipo de metodología utilizada para la integraión. En este paso exploraremos tres alternativas diferentes:
     + Métodos estadísticos: se trata de encontrar una función matemática que explique correctamente cómo cambia la variable dependiente (regeneración de encina bajo el pinar) en función de las múltiples variables independientes. Esta aproximación es la tradicional. Implica contar con una serie de lugares del territorio para los que haya datos de las variables independientes y de la dependiente (regeneración). Para encontrar la función matemática en cuestión necesitamos proponer un test estadístico cuya naturaleza dependerá de cómo sean los datos de partida. Esta aproximación es muy potente y es la más común en la ciencia ecológica. En nuestro caso no podemos llevarla a la práctica porque no disponemos de los datos necesarios. Además, la función matemática sería muy compleja porque usamos muchas variables independientes de entrada.
       
     + Álgebra de mapas: Se trata de un conjunto de técnicas que permiten combinar mapas procedentes de formatos diversos para resolver un problema de ubicación en el espacio de una actividad dada (en nuestro caso ubicación de las zonas con más regeneración). La idea es usar la capacidad que tienen los SIG y nuestro conocimiento del sistema ecológico en cuestión para construir un modelo espacial. Según el criterio experto podemos decir algo así: "la regeneración será mayor en lugares con suelos profundos Y con mucha vegetación natural en el sotobosque". Esa afirmación es fácilmente implementable en un SIG. Usaremos técnicas parecidas a la esbozada anteriormente para integrar los datos. Detallaremos este método en las sesiones finales de la asignatura.
     + Métodos basados en procesos: Consisten en simular el funcionamiento íntimo de los procesos elementales implicados en la pregunta en cuestión. Es el conjunto de métodos más complejo. Su aplicación requiere disponer de un conocimiento profundo de todos los procesos fisiológicos y ecológicos implicados en la regeneración de la encina bajo el pinar. Sería algo parecido a los modelos que nos ayudan a predecir el clima: se basan en el conocimiento de las leyes físicas que rigen el intercambio de materia y energía entre los distintos elementos del sistema climático. Definitivamente no tenemos capacidad de generar modelos de ese tipo para el problema ambiental. Sin embargo, seguramente tendremos una charla sobre una persona con gran conocimiento en este tipo de modelos.
+ El abordaje de la parte de "gestión" de la pregunta inicial se realizará usando la técnica de [Evaluación Multicriterio](http://wiki.gis.com/wiki/index.php/Multi_Criteria_Evaluation). Se trata de una aproximación que permite identificar lugares del territorio que reúnen unas características determinadas. Es muy utilizado para seleccionar lugares en los que realizar una actividad concreta. En nuestro caso esta técnica nos permitirá combinar el mapa obtenido como respuesta a la pregunta científica con las variables socioeconómicas que identificamos en los pasos anteriores. Analizaremos con detalle esta técnica en las sesiones finales de la asignatura.

La siguiente figura muestra resumidamente el hilo argumental que seguiremos:



![image](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2022-2023/presentacion/metodologia.png)



## Nueva propuesta de hilo argumental

- Planteamos la pregunta.
- Describimos a dónde queremos llegar: flujograma. Conjunto de pasos ordenados cuya aplicación resuelve la pregunta inicial.
- Constatamos que no sabemos cómo resolverla. Ante este tipo de preguntas tenemos dos formas de abordaje:
- Apelar a lo que sabemos sobre el asunto:
  - lluvia de ideas sobre qué hacer. Es importante que anotemos todas las ideas que surgen.
  - Recurrimos a la presentación del día anterior.
- Preguntamos al que sepa:
  - Google...
  - ChatGPT
- Recopilamos lo que hemos aprendido y empezamos a construir el flujograma.







+ Cuestiones que deben de salir a relucir en el proceso:
  + ok Necesidad de identificar las variables socioecológicas implicadas en el proceso estudiado.
  + ok Grado de investigabilidad de la pregunta en cuestión. 
  + ok El papel que podría jugar en nuestro problema la aproximación correlacional.
  + ok Existencia de otras formas de generar conocimiento y de responder a la pregunta:
    + Modelado ecológico.
    + Experimentos controlados.
    + Conocimientos locales y expertos.
  + ok Concepto de variable ecológica como descriptora del sistema que estamos estudiando.
  + ok Concepto de variable subrogada.
  + ok Existencia de distintas formas de representar una variable ecológica relevante.
  + ok Idea de fuente de datos.
  + ok Procesamientos para transformar datos primarios en variables utilizables para nuestro objetivo.
  + ok Grado de espacialización de una variable.
  + Concepto de serie temporal
  + Hipótesis previas sobre cómo creemos que condicionan las variables consideradas al proceso en cuestión.
  + ok Concepto de iteración: repetimos el proceso hasta que estemos contentos
  + 





+ Modus operandi:
  + Diagrama de draw.io con dos flujos de trabajo paralelos.
  + Uno indicando cómo procedemos para hacer el flujo de trabajo
  + hablemos de variables y de cómo se espacializan.
    + forma de subrogar procesos ecológicos (y sociales)
    + fuentes de datos
    +  
  + otro con el flujo en sí







## Resultados

Iremos trabajando en los pasos anteriores durante dos sesiones de dos horas. Será un trabajo colaborativo en el que los alumnos propondrán ideas y el profesor irá plasmándolas en un esquema de flujo usando una aplicación llamada [Diagrams](https://app.diagrams.net/). 



+ En la primera sesión (15/11/2022) identificamos algunas variables potencialmente interesantes para resolver las dos preguntas descritas anteriormente. El flujo de trabajo resultante se puede descargar [aquí](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2022-2023/presentacion/20221115_workflow_pinares_1.drawio.zip) y ver a continuación. En esta primera sesión comentamos, entre otras cosas, lo siguiente:
  + Importancia del concepto de variable subrogada.
  + Variables continuas y discretas. Vemos como ejemplo los mapas de series de vegetación (discretos) o de pisos bioclimáticos (discretos) frente a los mapas de precipitación.
  + Procesos de interpolación y de regresión para obtener mapas continuos a partir de fuentes de datos puntuales.
  + Relación entre la altitud, la pendiente y la orientación. 
  + Los modelos de insolación.
  + La imposibilidad de obtener mapas de variables que aunque son muy importantes no tienen fuentes de datos válidas (ej. el impacto de la microbiota del suelo en la regeneración de la vegetación).



<iframe frameborder="0" style="width:100%;height:1037px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=20221115_workflow_pinares_1.drawio#R7Vtbc9o4FP41PDbjO%2BYxQNKdnWaaSXZn20dhK7aysuWV5QL59SsZCdsSBNKBOLjNA7GOZBl939G5yYzcWbb6TEGR3pEY4pFjxauROx85ju1aNv8nJGspsSxnI0koiqWsETyiF6gGSmmFYlh2BjJCMENFVxiRPIcR68gApWTZHfZEcPepBUigIXiMADal%2F6CYpRup47pB0%2FEHREmqHh343qYnA2q0XEqZgpgsWyL3ZuTOKCFsc5WtZhAL%2BBQwm%2Ftu9%2FRuvxmFOTvmhuf5Ha3Y95fkU%2F6A%2FMfbP5fT4pOc5QfAlVzxHJUFydECoxjEgjoooEwqwP%2FBXHyIScsKYiLXxdYKLb7EQlzyLwUw5iMSCrKROy0gRRlkkOp9903HdJkiBh8LEIkZllyfuCxlGeYtm18%2BoRVUCiLa5vLVWiBlcNUSSTg%2BQ8IfRdd8iOz1PUmN1E5HtZcN1baiL22xHEgZkNqVbKdu8OcXkoI30OEYdFxHfAO81DwMB3e3i7sb9I772ADeABnG3DLIJqEsJQnJAb5ppFNKqjyG4jkWbzVjvhBSSPSeIWNriSaoGOlivRfbklQ0gq8swJW2EdAEstcWKu2WWMyrVFGIAUM%2Fumbw5Li7Bux3oADK6oycAPPFTBeUXyXi6ppbflbFF78BNMPjTfreAJ5BxF8w4%2BgBVlFw8XBr9iZw%2BobbN%2BC%2BpzBCBWIgQqOZO5q6%2BcWj7nRRH%2FfuXQNTyUkhkHoSkF%2FPB6fo4bhvyI%2Fxq3l8LSJ13spJDrsgdV3qXogOurMWAP6O9SvZ0V5PPuGeIP5N9qr8ZKzhuvHj8q52rK5NFIw1Ij1too2jNyaqOdou%2B%2BdpC38t2mwNbf9EtE3embaJQVs7nCo4ZYhTwPPpC7dz4YeLn5QGtaB%2FADFqe3MexGNAxUS5yOk4D5dOg75vbCfsnQezoPGVCqUfUFylo267vaNu1i0G7S8sXe8d68pq%2FTk%2F6T58bV5r8uq8Z%2FYmtpmdD5nVrRPZ7ivrPKza%2FbJqpvpfRIjA9FTIyokghwcLVpWD%2Bg6KwIIz78yEEqC6vxKeLSL5c5UzoiINNdIMNLiNY10lKRkl%2F8IZwYQ2SvSEMNZEAKMk581IeE5heYXFRBHA17IjQ3Fcl%2BF2meQjVfF4KxwEWsy4y%2FVZO7TVPZsRNosKWNBGDP%2FXYZZ%2FLKq6sF9WC0oSEG9prG9Pqwyqk4BtBfqKX%2FxdgoyUahjdE%2B0Mlv%2Bxvqs9v28FMOsbDyQi5eYgZ2BBj2f3HvSYtY12thUjrtloUbX3RN0BywJGqN59dTtDESULRNjFl5%2B8UCMpsHonyaxk3KJnYJASAbogG7PYPeMUlu6rkPxXIYwWFJGDt1w6jYFWRbT9%2FhMMs7LxwPcRohqTw%2BFAdy%2F9n1moh7U4mIGctV8TyBGjgNVBwdD2hO5%2FxiqO7o8Ps9RhoPyG9IxjQ9ff2o3vonHlq%2BZ81e6crw%2FFUgfPrJUDPXhorYz4B0kUAz39D0KN4zfUi6%2FGthWMQ9sOA98LtXn1UPHMqaFSoF9Aoya%2FNepdNOqdSkin0wxlwn9rxpk1wyxDzWFeonapoUD5jhLChUUOtvXx3jIMzU34kV9uUy%2BtHdy8x1r193m5zTHrMY%2BYFOaxH01JtqjKw%2Bp5AnUca4Gst6NuGe5QRt3snA4lM7U7i4v4IAbdD3YW%2F5u04iRnDnum2Sb0YZ8nEK6ZSA6acW9yNWn9aY7Xf%2F006ESMB%2F0ybqaqd6Q%2BH1CHTeJEiTtwUU2rS2opEATFspgQq98k1FVT4dzrIRF36ZzmkpnlhcGcM4R6MW5nIehE5wy82fweZUN%2B87se9%2BZ%2F"></iframe>

+ En la segunda sesión (17/11/2022) seguimos avanzando en la construcción del flujo de trabajo. Comentamos los aspectos que se ven a continuación. Abajo puedes ver la versión del flujo de trabajo y [aquí](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2022-2023/presentacion/20221117_workflow_pinares_2.drawio.zip) descagarlo.
  + Concepto de criterio y su comparación con la variable. Función de transformación de la variable en criterio.
  + Idea de transformación de conjunto de datos para generar la variable que necesitamos a partir de información primaria. 
  + La importancia del relieve en la distribución y dinámica de los ecosistemas terrestres.


<iframe frameborder="0" style="width:100%;height:1314px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=20221117_workflow_pinares_2.drawio#R7Vzbdps4FP0ar5U%2BuIurL492nGTaadq0ybTTRxkUWy0gKkQc5%2BtHAmFAUhy3tQ14%2BtAUhLho73OOzkVyzz4PH68IiJfX2IdBzzL8x54961mWaYwN9h9vWectljV08pYFQb7oVTbcoidY3CpaU%2BTDpNaRYhxQFNcbPRxF0KO1NkAIXtW73eOg%2FtYYLKDScOuBQG39gny6FMOw7UF54S%2BIFsvi1QNXDDAERW8xlGQJfLyqNNkXPfucYEzzo%2FDxHAYcvgKY%2FL7LZ65uvozAiO5yw7fZNUnp16dFP%2FqE3NvLt6tp3BdPeQBBKkZ8gxPkod653ZvaEbtEYAAoegCcRcj%2BBCDJRhd5y%2BzIxxEbF8mPeYcEhijIexGYxIwVzMnY3OojEGUHZzGK2Ncnr3rWIGBDmM4JO1rwI4EYXRc8MPBifsiGC4IABnhBQMg6xpCgEFJI5Gs35YXpaokovI2Bx5%2BwYpLK2pY0DNiZyQ7v0SMsRM%2FcvLwKbIESJBQ%2BVpoE0FcQs1eRNesirrquIF3Ifd8aiYZVKUVm0WlZEaBCY4AQ3MXm2SW17ECw%2BxNMWwrTE4%2Fp1lNGG787SRl0nQfedmvAW1rgLQ3wg4MBP1SQV1CGPrM64hQTusQLplXBRdk6JTiNfMjfY7Czss87jGMB3zdI6VrACVKmdTWwnwU3wSnx4JYB2MLuArKAdNtAhU3kg9nKlTApdRO7d9xtBfZrEG%2FMmGpzJmxWoanfeQ2w6howMJtWAEch4g6GDD1AUwK6D3fd0g%2BdpuF21SmdQA%2FFiILKvN5x1M066iPXbRj18VZrE8PIR2y4zJXtOPKj1pmX4gMq0H8CzMmsOrEJDgDhD4q4z8N46DoN7rBOgz1unIaBSgP2WDDhg%2B7PqY7kVRrDpuG21Fl1BiOBtvDos%2Fjq1LA3nUHj2I8UUFvtwBeO%2BYsevJjEWuLAW6pFuQ1wrNpussThPE1eFs89iONgLM1%2FhiqNI40wjvYgjLMfd%2BH7j%2BEk7n9J315eXp%2F%2FveprMjgzlFDAJrosycJdkPtUuB7bkjUdtxJywsU8pl%2BiJUZNuFQMNP90n%2FFE0DytOip5ig1nzEUoBEFOG0oY7gkm3fcf3ZFElKMLmA6VGdNrUCPmnEFI1v%2BK%2B7OTr%2FzktVuczh6rF2drcbbTNKAdpyaPo8dj2NQ0sO2zK3p0RZgRK5TlnoBFyLAAz6iRSDJ3Xm%2Bkeac%2FcjQh71H1RuOBFjOPmHiijJGJF8CMipTMQYS7T4XskQ510cBRqVBzPjPN5MLHAObMbhUcZWqyhGTO%2B0xmD5icADtyBaBpblQvVlaThxz%2B0ivzcJhGyDuhfJ1EijlunBbT%2FX%2FM%2BsNdZ327VbO%2BWjS7gwz6quGKCfZTr2rgYibjgGQ9ID%2FPsiBM5gmimKDOFzdNqdZg6pJ%2Bx1UiNffahFb9unaMdtSOxjIj2766gvoUYZ%2B9ltQTgKcj%2BnK%2Bu%2B827nOZHRP18a4TgdkqWVcLa5dppMR6lIAoucckrPpM6qqiwY%2BUL7ea8hkizLwuM8%2BvVFSn0g5isSSguE9h%2FJipx5Gc43J19r%2Fwa6o6YFrD1%2B6h1EBNQE4K2DRmyEjgIo8KOXfzutnqto0yjYFM0DFLFXp2Bt0yUubOSSqnVVbKVLNUezJTtOL2VkxTjBMklmWeVZvrPvGrnnX%2BokkbgJArRzRP4qZNnO1sDFXh4%2BpUyNGo0KZx%2F9yqia7dLVyVviwmCcALoUu3jeDGLyv4O%2BbCV30dxlAwPclA39w50m9XMGOqof7%2BPTxdlaBTllFx%2Fka6AOjIhlH1zXc3jM%2FUbU5m3YopZ2taULGxVF89BHEl78y4YqBpigBs0LQOGQjQImLHHl9bwCHm0CAPBBNxIUS%2Bn9tSmKAnMM8exU1cjFFEs6G50547489i5jMp0U8owd%2FhOQ4w5zTCEcwoCgKpaS8sFZ5bwdJYt3DA1LBkHYwlaztLD9xPmAeamuapsjSQFp32teUDXWB1OJJUh191MyJ%2FwveglVhUmKl7GM%2BC9OIkXUFAZ0uKtp3ncvGGG05%2Fxa0zpKqaLRup3D8Rt5XgKk8ayk%2Fa7PUrnpQ7MMqTMpo2A%2F8N5lR3%2FpSZc8aGhLfl%2Fipz0pNs1z0uc2qZO6%2BcRj7yYGEel2kIs2yS7L2d1D43eUWyecwVyfp1OqYC6knGWbrVtHpAjB0NwZHWUTl%2F%2BKkD0q6Ktz38w08dkMb2k2797mrVFSSbaccHFG9c9CzJN7m4vrh7dqLx1gFi1BH75fljnpP8br5pAN73RUb9h5Syx2xccjHHuHvKOUib7DQrdQeaGeZgS91tjaPWnIYMD7hS11BVZNtez5ZoSPHZ1S1gcMEDyzLDw6UV8CfdsH9ZH%2BP%2BTGy9fqXQe8wMmyVV77Q7G21dgs0%2BmMA3skbtN%2BR2158KaJncqrH8G54uiXFQy07ChMkfyqT37M3sS8%2Be8CdHvH6dzQD5sk5%2BuMrEo2F5lioxI13O5Mjy3N6Nc1s9kOPLc3brhBCwrnQQKblnQ31rVA8Kx2PpF4Hk1IBk8X62%2F0i8rxSJ%2FIv3GvTbqtsV8t%2BZ4gWF%2Bzz8T5DHz36k2Y42FKYB6G0KrS%2F%2B9MFRdVLeOmDoytu6bJB5sLjdaSRu%2Fw2l3HUhm9Oy%2BFutlr2ffX7DR4JpNqmUa5ZPogImWSPTbnxLptOqAOJw8YOza%2FxgtWsVlaMGECBY4FYV4q2x%2FHsErirWh9oBnvaDj963Dw%2BfPn8mj9EF%2FfDPla%2FZAZ5v%2BO7VMxMSZqdaK7ScupOiL%2BgaGoJ%2BoVbITssfcMw9nvKHMO2L%2FwA%3D"></iframe>

+ En la tercera y definitiva sesión completamos algunas variables y obtenemos [esta](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2022-2023/presentacion/20221121workflow_pinares_3.drawio.zip) versión del flujograma. 


<iframe frameborder="0" style="width:100%;height:1763px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=20221121workflow_pinares_3.drawio#R7R3Zdpu69mu8VvrgLEbbeXTipKe9TU%2Fb9La3jzIotnIAUQGZvv5KTAZJxjSxETjnoSnIDGJP2rNG5oX%2F%2BJ6AcH2NXeiNDM19HJmLkWGYlmnR%2F9jIUzZiGNNJNrIiyM3G9M3ADXqG%2BaCWjybIhVHtwhhjL0ZhfdDBQQCduDYGCMEP9ctusVd%2FawhWUBi4cYAnjv5EbrzOP8M0J5sf%2FoJotS5ePbHzT%2FZBcXX%2BKdEauPihMmRejswLgnGcHfmPF9Bj4CsAk913teXXcmYEBnGbG%2B4W1ySJfz2vxsE3ZN9cfXw4D8f5U%2B6Bl%2BRf%2FAVHyEGjC3N0bgb0JwI9EKN7wLAI6R8PROnXBc46PXJxQL%2BLZMfsggj6yMuuIjAKKVYwQ0Z5q4tAkB6chCigs4%2FejYyJRz%2FhfEno0Yod5RCLnwo8UOCF7JB%2BLvA86OEVAT69MIQE%2BTCGhP%2Fty%2BaH84c1iuFNCBz2hAdKqXRsHfsePdPp4S16hAXp6eXLq4AtoARJDB8rQzmg30NMX0We6CX5r7adIz2n%2B7Gp66eGnY09bAhJL65bV2joLB8DOe2uysdvsEsPcgT%2FAbINAdlzh7LXc4o5dneUUOgNHvamXYO9Ycw0EfCGBPCTgwF%2BKkBegDJ0qeDJTzGJ13hFGcu73IyeE5wELmTv0ejZ5ppPGIc5%2BO5gHD%2Fl4AQJZbwasLcCN8IJcWDDB5i56AVkBeOmD83FIvuYRlzlUqUuZfcOd1MA%2BzUIS0kmip05XVjixB08Bxh1DpjoqhnAEhDxHfoUeiBOCBg6uCdWHdxTWzW4bXFVJ9BBIYpBZWkfONT1%2BhI7m6qG%2BlmjtAlh4CL6uVSbHTjkZ70TL8UEKqD%2FBqieWdVjI%2BwBwh4UMJ2H4mHoaLCndTSYZ8rRMBHRgB1qT7hg%2BGsqJ%2BQNrUt58wl55rPvf3S0Hwl5uPwcOH%2BhkuqHokQauRZQ1SKlH5YL0p4okYaovCxgkBN1bjilluzgSXxaX1F1a6JaohizgZH4RCTxJl2hLyQuCu4bD4fiEknW2F8m0W7y3AM5Ts44NUMTqXEmIcbZoeStJZqTvaXOxe%2Fv%2Fuev%2Fjwc%2F0w%2BXl1dX%2FznYVw4%2B3bKX8tQRZ1N067KXxTFgOpxqRuRadi3Sa5ZN7kjBy6deZei3qXaLaUTc2D0b7Skf1PvFf0bTfoHm4ZL2YGgZVI1dzJfPU4ZJEA%2B8DLuQBEl7wiT4Vuh9oTjB8uQ8MOh%2FOtyQaVEW6EgJE%2F%2Fy%2B9PT36xk1O7OF08Vn9cPOVnL%2BcjiTdYDo9pr%2FhIXL7fE7pWFMxyS8DKp7AAW9goj1YNnm84tWo8szqMS0kRIzGwigU%2BX9%2BDFCNzx4MpKhKyBAEePio4n4I%2BlfkUOkWF6DleSBYX9g1gSeVWgaOUTdaQLNk188U9JkeAHbO%2BwMjca53iRjTSeDa5z8C%2FUX4d7CcBco7H688Hd%2FUz9au%2B%2FTZW%2FWnbVd%2Fs1aovht6%2FQwr6quAKCXYTpyrgQkrjgKRXQHaeOvkozRMUY4IGnyJRmoklFylnIjGCo4KrXs4ds5bcoczx1zTrCtTPEXbpa0ndv308pM9Hzca2cp1LHxipn7VdCPrlRhHD81dJINh6MQFBdIuJX9WZxPTEye%2BE5W2esxXCT7UuPfOvVFinMg7CPLGouE%2FAeJee9RnvSrRl8r%2FQa6o8oBvTU%2FtQbCD6eecF2CRiSIvgKrMKGe6WdbE1bBmla7xvy%2B4yEifHzmRYQkpv7aSyeiWldNFLtScxFVfU3opoCnGE8vzuk%2BpwXSd%2BNzIudoq0CfAZcwTLKFQt4kyrFFSFjitjIUvCQuXg%2FnErOrraS7gq%2BlKbxAM7TJdhC0EhG0GWxd2pnlYWchy5oa%2B3tvT7Zczooqm%2Ffw1PFiUYlGQUlD9p4mzHglHUzdsLxi1xm6NJy9J5b00PIjaGqKv7IKz4nSmuKNAkQQD60XEdZMBDq4AeOyyFg4GYgQY5wJvnP%2FjIdTNZCiP0DJbpo5iICzEK4vTT7PORvWDPouIz2kA%2Fign%2BB15gDzOcBjiAKYo8jxvaC5YsDktnsvwMXYIl42BYMpqxdM%2F0hKUniWkeK5YmXOr6WBo%2BkBlWh0NSm6yywJ2zYtYNLCqYqWsYW4G0c5GuQEAmS4qx1mt5%2FoYvDP0VtU7j8qhNXkhl%2Bkl%2B2wa4wpOm%2FJPKouHiSZkCIzwpRVP54a%2FAnKjOHzPmrDONg7dhvxRz3JNM2%2B4Wc2KYO4ucBi5yYCEe14kPU28Sr70dVbUsX9egd1nXIM%2FT0QWgHqWdJUsWlwNEaykIOsqjsv7FTx0g%2FYp4m9N%2F8VMHiLKq9MZ5V6OuICqXHRfEuFTRUyff%2FPL68vvWhcZ58hBFHTF3rx%2FLDMmfluUAcP5Zpaj%2FO4npY0qVPF9j7P0sMpwrb2aK9utEssLso5JDThASRa1LDjnVJjOOS8zZDj5Jzyq6wmtzeDWReZpqyXvCO8W0qyWmcMVMzo3vh9ExYE%2F6Qv%2Bl12i3J3lrh3cC4rv0vRlcXE9aOW3KXG%2FmwVhBSfbaK%2Bi2bSuSntGtaOV%2FYI6UEHs1vyWMKP2hlHpPPix%2Bjsw5e3LAItvp2pAlfLLDh5Q8FNMzL9hl3pSO6fk4ajC6J%2B%2F01jkh4KlyQe672%2B4T4ARa6QXdZvrzN5xpGofybApb7ta2vG6XC2JfjgNTVN181vSOBSVuMxdChBx29jtJiw%2BRn3hgVAZrdzZh6ZR7%2BfIDTRYil3mU9IPZ%2FpYS2%2F8Vy1HbZDirZza8GHH7vPjxgX0JjtPlZ5P3fBRRtBlH62aX1bNyilBshHRlplttLQ2jX5lYlmhqAG%2BFexXMN854spZkyRyqSUIy9r46d3%2Fff%2FvxgzwGl%2FHf%2F33vSor1s9r8Ud27wcHsWOONXMhkrGsysaNJELSPeKO8uP3opI68OZIodKTXGapkjnQ2SpJs%2B4scZTZ806xrJvw9SzzKkpJuWVeFTHe6QcEtlSH3wN2ehjkAty1XAKvbksaWh%2FLbyhvTvA32MJQpTC9yAphcUo1u853I%2BRyQGU9YRoMX4AW2exNUK%2ByLmj1wKvU63lyRsV6nza%2BUxBRfzkKHcY%2FtpmSLz2baXyZL03dWidoPk3gAFD1V3c5NUvsKIlhGXoswLKMQBzGybZUn2da4aG%2FfyHDTMnPsT0rOWqz1ZxL07MORL9e2lLhHXi5xJI5A%2BXcpq4ptmnaFC5wEBGlXJC9rkFC2Gkt5w4cBJeOcR%2BZZ7UN6IYErGEBSkzwgSRPzT%2BnhJdWNYP1581HWSea86REBm4kD%2FCVKH%2FOLoQJtnRx42kzufMfkluCO%2FbQGVGln74BETObrtDCDZ0FL1kdeFk07mIjcUZIbpXDOfMRJEJedtO5RBtJNBot7lA1zN94cJR1z5Sg7vm408u%2BU5AHIL1TmVW6c95ZdAu6poDqiTRr4mpiZbA%2BkTvnDEM3AYekZetsu6q3LBzoifLFa4vIxJgCyBTvvsIi9LIZOYZkO5EF0CIJiyZDo4N2GzHmClqQydmrFSPZcyOTJsAUHb49sLG11K6tYXixL23UwI9b8rXk%2FPvZoP8yJ20HxoL3COucWNmRKT6duYV005UOCHegin%2B24k24%2FSIVzBv44y88plVUfBPAOjxrDk12KGL7a15hICnI6FTHGGwkZynLvmhoJ92RhldRiXwDPSbLtjqKESvhb5CBK3Vf0MGMC9uaS5p00TFVffZWyAJ%2FmN55turnsipvr2h76U8nhPDAXeOvtdtRt2ihPUHgjQfDW%2BDH7FQaXlD2%2FP%2F9wNWSVhovijCeqA9093vdIPt%2BO4m18wcHY5hPAt8Tb%2FjSmzdsf46Ib%2BLaYtjiz%2Bg0HimmL8T%2F%2FeL1JY9767rQtohwBZ29ksWpbazvr11olekecrFEXU5AzDZg9RNL94WYNggCXXcPkSnJ%2B%2B5%2FwXLf1WXyzY%2BkeobJGr3wvlf2pd2Ja9c3XTwKYjieyzvdbm1jtlIuDRdaPsH9D4zZeuxXsfhn0pmjQ77%2BPobh9S21vsB43r%2BaVAMucnU4l3oED9q9upKIXNTGsA%2F%2BoNi7UNV41tjTVUUBT9BirkImvkG12W9mmbA%2B2xnlLo4AhpX5YbOuZ5ZZQrnBQfetCUG%2BO8kwhTv87AYRC0QXMlc%2FSfhJqbDkgOwbEZZyUnRAMXcZmaivn%2BSAKlWISnjhY6bw8u17UzAbGFJLGxfILlTUubpx3LTX9lgptMuJSp%2BQrBfBWScoEqTaglK5NnadrScFbt7s297eivJE2d1raRr9oWEwkvU0iljfNiDjL76g1n22ka4UUbAmSWTkFv5GUvqIgfvf%2B5P1K6Svm%2FRJ7TeMMNJglPrmVjR37a4lNOO9SqcMr45TXbLDhcptp%2BvRkDY56T3lds2YcCpVvKm%2BLFsKwFnBL4iqXf2nPxJh8f1n5xvIpL2SdHY6QKzgNwFDPFAPLPbHaWmJ2v3JPLNES284D6UodJT5yYbrdtXaSpyi%2FOzaO4Go3x122CJfjSfTfLTh7IhNRrRZx7eQzcNZpyRv7E7I4kpE1wIqSTHNbgjsseowGhkabD0Wpl2tiqGNggq5t2WcB%2Br4IOtFcbwxiayf30GFqM%2FAGzwZjQ%2BADUzkjKKH77m38AvK7bfy9KwYvygMb896gYnuMbXlgOu8A5W44TB6Y%2FUZS9NuTT7%2FCXsW8K%2BIWsrCXI2iVQg1cmFa0g1QHVV2bMuYjubokl6VTj48trmPDUiDstlngdr8y62zR1fZtHrFN%2F54lhf1Kk94M1W7JQms4eunc2vPVM1oWPV99peUO27vKSXlg0dSC0nbvZdwvihT9G5WavjJSEaVuiqyxTpipDY%2FQ23hkNw5asOWKivtKIZlbGr9b%2ByE1C3pKMAufbTRw%2BlHra9bInw7%2BHw%3D%3D"></iframe>

kk
