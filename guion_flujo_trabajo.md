# Construcción de un flujo de trabajo para responder a la pregunta planteada


> + **_Versión_**: 2022-2023
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
+ [El papel de los flujos de trabajo en la reproducibilidad de la ciencia.](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2021-2022/biblio/how_to_flow.pdf) 
+ Descripción de [Kepler](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2021-2022/biblio/kepler.pdf), un sistema de flujo de trabajo científico muy útil (y algo complejo).
+ [Ejemplos de flujos de trabajo.](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2021-2022/biblio/workflow_reusable.pdf) 



## Hilo argumental

En este acto docente intentaremos reproducir de manera explícita el proceso que se sigue habitualmente cuando se prepara y ejecuta un proyecto de investigación científica. La idea es que los estudiantes sean capaces de abstraer el conocimiento adquirido para aplicarlo a otras situaciones.

El hilo argumental descrito a continuación es la propuesta del profesor para el desarrollo de la sesión. Pero, dado que será un trabajo colaborativo, puede que la conversación discurra por otros caminos. Si fuera así, este texto se complementará con los temas abordados en realidad.

+ La pregunta que nos hemos propuesto abordar es de las denominadas "[no investigables](https://www.quora.com/What-is-a-non-researchable-question/answer/Lawrence-Ness-4)". Se trata de una pregunta compleja que requiere ser "diseccionada" para ser respondida. La dividiremos en dos preguntas más fácilmente abordables.
+ En primer lugar observamos que en la pregunta hay dos partes diferentes. Esto es muy común cuando trabajamos en un contexto de gestión y conservación de recursos naturales:
  + ¿En qué pinares debemos de intervenir...?: Es una pregunta de gestión que implica la intervención sobre el territorio. Para responder a esta parte de la pregunta necesitamos conocimiento científico que sería generado por la siguiente parte de la pregunta.
  + ¿... para optimizar el proceso de naturalización?: Esta segunda parte contiene otra pregunta que pone el foco en un proceso ecológico concreto, la regeneración de la encina bajo el dosel de pinos. Desde un punto de vista ecológico este proceso es equivalente al de sucesión. 
+ Para abordar la pregunta que se centra en el proceso ecológico daremos los siguientes pasos:
  1. Identificación de variables implicadas en el proceso ecológico a analizar. Este primer paso implica un nuevo proceso de desagregación, puesto que trataremos de evaluar en qué medida el proceso en cuestión depende de distintas variables biofísicas. Nos preguntaremos: ¿qué variables ambientales pueden condicionar la regeneración de la encina bajo el pinar? Para ello, y con objeto de suplir nuestros aún limitados conocimientos sobre este proceso, podremos consultar el esquema final que hay en [esta](https://github.com/aprendiendo-cosas/T_contexto_pinares_ecoinformatica_ugr/raw/2021-2022/presentacion/generalidades_pinares_reboblacion.ppt) presentación.
  2. ¿Son todas las variables del mismo tipo? Es de esperar que algunas variables tengan carácter biofísico (precipitación, profundidad del suelo, etc.) y otras socioeconómico (distancia a vías de comunicación, tasa de desempleo por municipio, etc.). Esta distinción será importante cuando las integremos todas para dar una respuesta final.
  3. Fuentes de datos: Una vez identificadas las variables que consideramos relevantes, procederemos a evalular la disponibilidad de datos para su uso en el análisis. En ese proceso quizás tengamos que usar variables subrogadas de las originales. [Aquí](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/1365-2664.13366) tienes una definición de lo que significa variable suborgada (lee solo el Abstract del artículo para una idea general) y [aquí](https://ebooks.publish.csiro.au/content/indicators-and-surrogates-biodiversity-and-environmental-change) un libro completo que trata sobre el asunto. La identificación de las fuentes de datos de partida también nos permitirá caracterizar preliminarmente el procesamiento que será necesario aplicar a los datos originales para satisfacer nuestras necesidades. Esta última frase, que pasa desapercibida, es muy importante porque ese procesamiento ocupará el grueso de la asignatura. En cada uno de los procesos aprenderemos técnicas diferentes (bases de datos, teledetección, cartografía de la vegetación, etc.)
  4. Hipótesis previas sobre cómo creemos que podría participar cada variable en el proceso general. Es decir, analizaremos en qué medida contribuye cada variable seleccionada a explicar la regeneración de la encina bajo el pinar. Por ejemplo, ¿Cómo afecta la densidad del pinar a la regeneración de la encina? En este caso está claro porque tenemos evidencias al respecto: a densidades bajas hay poca regeneración y a densidades altas también. Este paso será útil para hacernos una idea de cómo pueden interactuar las distintas variables que hemos seleccionado.
  5. Integración de todas las variables para obtener un resultado único. Se trata de la fase más crítica porque implica construir un modelo conceptual en el que todas las variables seleccionadas se integren y nos permitan responder a la pregunta (¿de qué variables depende la regeneración?, ¿Cuál es el peso relativo de cada variable?). El resultado de este paso deberá de ser un mapa que muestre cuantitativamente la "intensidad" del proceso de regeneración en cada punto del territorio. Esta intensidad se podrá medir en probabilidad, idoneidad o en número de encinas que se regeneran dependiendo del tipo de metodología utilizada para la integraión. En este paso exploraremos tres alternativas diferentes:
     + Métodos estadísticos: se trata de encontrar una función matemática que explique correctamente cómo cambia la variable dependiente (regeneración de encina bajo el pinar) en función de las múltiples variables independientes. Esta aproximación es la tradicional. Implica contar con una serie de lugares del territorio para los que haya datos de las variables independientes y de la dependiente (regeneración). Para encontrar la función matemática en cuestión necesitamos proponer un test estadístico cuya naturaleza dependerá de cómo sean los datos de partida. Esta aproximación es muy potente y es la más común en la ciencia ecológica. En nuestro caso no podemos llevarla a la práctica porque no disponemos de los datos necesarios. Además, la función matemática sería muy compleja porque usamos muchas variables independientes de entrada.
       
     + Álgebra de mapas: Se trata de un conjunto de técnicas que permiten combinar mapas procedentes de formatos diversos para resolver un problema de ubicación en el espacio de una actividad dada (en nuestro caso ubicación de las zonas con más regeneración). La idea es usar la capacidad que tienen los SIG y nuestro conocimiento del sistema ecológico en cuestión para construir un modelo espacial. Según el criterio experto podemos decir algo así: "la regeneración será mayor en lugares con suelos profundos Y con mucha vegetación natural en el sotobosque". Esa afirmación es fácilmente implementable en un SIG. Usaremos técnicas parecidas a la esbozada anteriormente para integrar los datos. Detallaremos este método en las sesiones finales de la asignatura.
     + Métodos basados en procesos: Consisten en simular el funcionamiento íntimo de los procesos elementales implicados en la pregunta en cuestión. Es el conjunto de métodos más complejo. Su aplicación requiere disponer de un conocimiento profundo de todos los procesos fisiológicos y ecológicos implicados en la regeneración de la encina bajo el pinar. Sería algo parecido a los modelos que nos ayudan a predecir el clima: se basan en el conocimiento de las leyes físicas que rigen el intercambio de materia y energía entre los distintos elementos del sistema climático. Definitivamente no tenemos capacidad de generar modelos de ese tipo para el problema ambiental. Sin embargo, seguramente tendremos una charla sobre una persona con gran conocimiento en este tipo de modelos.
+ El abordaje de la parte de "gestión" de la pregunta inicial se realizará usando la técnica de [Evaluación Multicriterio](http://wiki.gis.com/wiki/index.php/Multi_Criteria_Evaluation). Se trata de una aproximación que permite identificar lugares del territorio que reúnen unas características determinadas. Es muy utilizado para seleccionar lugares en los que realizar una actividad concreta. En nuestro caso esta técnica nos permitirá combinar el mapa obtenido como respuesta a la pregunta científica con las variables socioeconómicas que identificamos en los pasos anteriores. Analizaremos con detalle esta técnica en las sesiones finales de la asignatura.

La siguiente figura muestra resumidamente el hilo argumental que seguiremos:



![image](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2021-2022/presentacion/metodologia.png)



## Resultados

Iremos trabajando en los pasos anteriores durante dos sesiones de dos horas. Será un trabajo colaborativo en el que los alumnos propondrán ideas y el profesor irá plasmándolas en un esquema de flujo usando una aplicación llamada [Diagrams](https://app.diagrams.net/). 



+ En la primera sesión (15/11/2022) identificamos algunas variables potencialmente interesantes para resolver las dos preguntas descritas anteriormente. El flujo de trabajo resultante se puede descargar [aquí](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/main/presentacion/20221115_workflow_pinares_1.drawio.zip) y ver a continuación.



<iframe frameborder="0" style="width:100%;height:1537px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=20221115_workflow_pinares_1.drawio#R7Vtbc9o4FP41PDbjO%2BYxQNKdnWaaSXZn20dhK7aysuWV5QL59SsZCdsSBNKBOLjNA7GOZBl939G5yYzcWbb6TEGR3pEY4pFjxauROx85ju1aNv8nJGspsSxnI0koiqWsETyiF6gGSmmFYlh2BjJCMENFVxiRPIcR68gApWTZHfZEcPepBUigIXiMADal%2F6CYpRup47pB0%2FEHREmqHh343qYnA2q0XEqZgpgsWyL3ZuTOKCFsc5WtZhAL%2BBQwm%2Ftu9%2FRuvxmFOTvmhuf5Ha3Y95fkU%2F6A%2FMfbP5fT4pOc5QfAlVzxHJUFydECoxjEgjoooEwqwP%2FBXHyIScsKYiLXxdYKLb7EQlzyLwUw5iMSCrKROy0gRRlkkOp9903HdJkiBh8LEIkZllyfuCxlGeYtm18%2BoRVUCiLa5vLVWiBlcNUSSTg%2BQ8IfRdd8iOz1PUmN1E5HtZcN1baiL22xHEgZkNqVbKdu8OcXkoI30OEYdFxHfAO81DwMB3e3i7sb9I772ADeABnG3DLIJqEsJQnJAb5ppFNKqjyG4jkWbzVjvhBSSPSeIWNriSaoGOlivRfbklQ0gq8swJW2EdAEstcWKu2WWMyrVFGIAUM%2Fumbw5Li7Bux3oADK6oycAPPFTBeUXyXi6ppbflbFF78BNMPjTfreAJ5BxF8w4%2BgBVlFw8XBr9iZw%2BobbN%2BC%2BpzBCBWIgQqOZO5q6%2BcWj7nRRH%2FfuXQNTyUkhkHoSkF%2FPB6fo4bhvyI%2Fxq3l8LSJ13spJDrsgdV3qXogOurMWAP6O9SvZ0V5PPuGeIP5N9qr8ZKzhuvHj8q52rK5NFIw1Ij1too2jNyaqOdou%2B%2BdpC38t2mwNbf9EtE3embaJQVs7nCo4ZYhTwPPpC7dz4YeLn5QGtaB%2FADFqe3MexGNAxUS5yOk4D5dOg75vbCfsnQezoPGVCqUfUFylo267vaNu1i0G7S8sXe8d68pq%2FTk%2F6T58bV5r8uq8Z%2FYmtpmdD5nVrRPZ7ivrPKza%2FbJqpvpfRIjA9FTIyokghwcLVpWD%2Bg6KwIIz78yEEqC6vxKeLSL5c5UzoiINNdIMNLiNY10lKRkl%2F8IZwYQ2SvSEMNZEAKMk581IeE5heYXFRBHA17IjQ3Fcl%2BF2meQjVfF4KxwEWsy4y%2FVZO7TVPZsRNosKWNBGDP%2FXYZZ%2FLKq6sF9WC0oSEG9prG9Pqwyqk4BtBfqKX%2FxdgoyUahjdE%2B0Mlv%2Bxvqs9v28FMOsbDyQi5eYgZ2BBj2f3HvSYtY12thUjrtloUbX3RN0BywJGqN59dTtDESULRNjFl5%2B8UCMpsHonyaxk3KJnYJASAbogG7PYPeMUlu6rkPxXIYwWFJGDt1w6jYFWRbT9%2FhMMs7LxwPcRohqTw%2BFAdy%2F9n1moh7U4mIGctV8TyBGjgNVBwdD2hO5%2FxiqO7o8Ps9RhoPyG9IxjQ9ff2o3vonHlq%2BZ81e6crw%2FFUgfPrJUDPXhorYz4B0kUAz39D0KN4zfUi6%2FGthWMQ9sOA98LtXn1UPHMqaFSoF9Aoya%2FNepdNOqdSkin0wxlwn9rxpk1wyxDzWFeonapoUD5jhLChUUOtvXx3jIMzU34kV9uUy%2BtHdy8x1r193m5zTHrMY%2BYFOaxH01JtqjKw%2Bp5AnUca4Gst6NuGe5QRt3snA4lM7U7i4v4IAbdD3YW%2F5u04iRnDnum2Sb0YZ8nEK6ZSA6acW9yNWn9aY7Xf%2F006ESMB%2F0ybqaqd6Q%2BH1CHTeJEiTtwUU2rS2opEATFspgQq98k1FVT4dzrIRF36ZzmkpnlhcGcM4R6MW5nIehE5wy82fweZUN%2B87se9%2BZ%2F"></iframe>

En esta primera sesión comentamos, entre otras cosas, lo siguiente:
+ Importancia del concepto de variable subrogada.
+ Variables continuas y discretas. Vemos como ejemplo los mapas de series de vegetación (discretos) o de pisos bioclimáticos (discretos) frente a los mapas de precipitación.
+ Procesos de interpolación y de regresión para obtener mapas continuos a partir de fuentes de datos puntuales.
+ Relación entre la altitud, la pendiente y la orientación. 
+ Los modelos de insolación.
+ La imposibilidad de obtener mapas de variables que aunque son muy importantes no tienen fuentes de datos válidas (ej. el impacto de la microbiota del suelo en la regeneración de la vegetación).



