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
+ [El papel de los flujos de trabajo en la reproducibilidad de la ciencia.](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2023_2024/biblio/how_to_flow.pdf) 
+ Descripción de [Kepler](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2023_2024/biblio/kepler.pdf), un sistema de flujo de trabajo científico muy útil (y algo complejo).
+ [Ejemplos de flujos de trabajo.](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2023_2024/biblio/workflow_reusable.pdf) 



## Hilo argumental

En este acto docente intentaremos reproducir de manera explícita el proceso que se sigue habitualmente cuando se prepara y ejecuta un proyecto de investigación científica. La idea es que los estudiantes sean capaces de abstraer el conocimiento adquirido para aplicarlo a otras situaciones.

+ La pregunta que nos hemos propuesto abordar es de las denominadas "[no investigables](https://www.quora.com/What-is-a-non-researchable-question/answer/Lawrence-Ness-4)". Se trata de una pregunta compleja que *a priori* no sabemos contestar. Sabemos a dónde queremos llegar: construir un flujograma que muestre los pasos a dar para responder a nuestra pregunta. Pero no sabemos cómo se hace eso. 
+ Cuando nos enfrentamos a algo que no sabemos hacer, es útil hacer dos cosas en paralelo:
  + Evocar el poco o mucho conocimiento que tengamos sobre el asunto en cuestión. Esto implica, en nuestro caso, tratar de extraer información de lo aprendido sobre pinares de repoblación tanto en esta asignatura como en cualquier otra. 
  + A continuación, es buena idea preguntar a quién sepa sobre este asunto. En nuestra situación no tenemos a mano a expertos humanos que puedan ayudar. Pero en los últimos meses disponemos de expertos no humanos que pueden ser de utilidad: las herramientas de inteligencia artificial que permiten entablar conversaciones. En nuestro caso usaremos [ChatGPT](https://chat.openai.com/) y [Perplexity](https://www.perplexity.ai/). 


Tras poner en práctica estas dos ideas, obtuvimos el siguiente esquema. No es un flujo de trabajo, 	pero sí recoge algunas ideas útiles para su construcción en los siguientes pasos. También puedes descargarlo [aquí](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2023_2024/presentacion/como_hacer_flujograma.zip):


<iframe frameborder="0" style="width:100%;height:703px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=como_hacer_flujograma.drawio#R5Vpbc5s4FP41zLQPzRgwvjzGjtNMt9vtbma2lzcZTo1akIgQjp1fvzpCYG7xeNvE2M2LjY4ESJ%2FO%2Bc5FWO483rwVJAn%2F5AFEljMINpZ7ZTmOPRoP1R9Ktrlk4hnBStDADNoJbukDGOHASDMaQFobKDmPJE3qQp8zBr6syYgQ%2FL4%2B7BuP6m9NyApaglufRG3pJxrIsFhXsQzsuAG6CotX26Np3hOTYrRZShqSgN9XRO7CcueCc5lfxZs5RIheAUx%2B3%2FUjveXMBDB5yA0%2FksH6n6%2FuNH239Pyvfwzvp8PJG7OMNYkys2IzWbktIIBAIWKaXMiQrzgj0WInnQmesQDwNQPV2o15z3mihLYSfgcpt2Z7SSa5EoUyjkxveylmdSnPhA975l%2FoBBErkHvGufk4XEvlBQaot8BjkGKrBgiIiKTr%2Bu4To0SrctwOZnVhkP4fqNtt1OeONbteMCW9y6y5a11OERHKFCYp2g%2FoySV8GRGf4oCZy7R8CTEvR1AmQayBUWE5o0gBMlvi1UpqkEckVvsxY8sU%2FxTcROvphsb0gahxg4jot6yAgWi8puhdq15Z62NEZoKo9V%2B3VEfCRtZ3mkR0xdS1DzhTJViDkFTZ26XpiGkQ5EoFqZrVUj8K1SrhanF6I7yZ5V3hs5QepblK4aNTKfgPmPOIq%2BdeMc7wKd9oFDVEjyobTgU2e9XD9HpDY9OG1WzXtO93HOEWsrBCD8V9T65RkzO3Y%2FdAOx6flh0PXgjs05OC3W2h%2FlGRVsYkEhSNE8UKyBstBnzFOIJCCsqsMG1IfBCvW5t3H1IJtwnRIN6rEOdA4A%2BnktHQq1FJSREVKrGdDioZPReVjFvoXiYQIXIIL140cb3L0D2kBZgNDEXI42WmZjl7fjSH4zoxD%2B02mpMOMCfPBeb0MVUt8LzLKKAXTSEhvUI3aUI3OB50n8Y0vfv7Zvj5bpO9ow8fbv5iX96cLpV2TvfQSLQ3D7Zv1hX9%2FAC%2BirwkySkSyRIjw8DEezoQhFRqW7eZJoR0F6letMlhkQenPoakc52%2BBTx%2FRv6nf5RiUxLFGBRie5NE%2BgVXPsVRRydlx63bgttBI52kXAaCT75Roz6sQSEotp%2Fx%2FguvaH6p9l1tzMPz1ta0ft6KTj4O3DfrKsvzQOQqbAxJBxjqP2PI%2Br7KvXyVAKkMp51m5ekcTaVKeIg2rjzrU%2BlLmehpe7topnR9mMq0bireMeOXzs3w%2BrWUqp1UzObJLWXYtpR9unkiltKuN%2F1LBMU0P1ftBFhA0Q1ov4BPY3Xh0RXcdk9NwScvwxWMz9IVtLMnU1RLk0zFPKRIo%2FAn2WWtUuk36HQAcu20dE0b1xVpsCKSQEH%2BjPqhdhIItQ6YmK%2F8QaqVVPsG3oelOI2q2MjrsJTRMVOIImz73U1lepam0s6N%2BXeeJwkh2ZbGILEarZUcbSKD3GAire7rivNIuQqRAI1Gx1Mx9Ukv%2FqIREI3HffsLe9irFdjWkSIi%2B9AUvLdqZve0e%2FHnTwtz98DTohu7Xet4X6RaCYiUV07aUohplFPMK8JoTBTFvNbgIAlhiVlIUkSppZdOBPch5VZ5XNc6SDs%2BGw0aTrmzvux10NH02eio3wTteHTknCcdtSv4v2X%2B3LU9Z0FjTpvGdEmJxwlIzAR0asExZGKZFGU2jVOMsgdcSVojsYLDapVc69FvDnrgsFGjHNt%2FYtFLOfYXlP3Jq0Dm1o%2F4VcZuq6ZefaeGzQ8ecmszdzU2oZzGL5wZvZCEz%2B6ok58FebUr5bdcny0nPBDmWJ74MiNlxtdkpYrQnDvrengGAdGNlSaqSz1KJ4qw7YWzJg1L6D8NbJemFnhdO4HArXj0cAJfoeQKlj4O5Wx30HADo74hdZyXQTfOeWbWTjvj06fRcbZtBkAqBwSt6rZmnhh8lfalOR%2BZDyVBG4sokr2VIEGZ6uWfvmz0aXXxsWRJZfWTuxWkstdgquGivUmHFXV96PETCaFq7r5vzn387jNxd%2FEf"></iframe>

+ Con las ideas anteriores en mente, procedemos a elaborar el flujograma que guiará el desarrollo de la asignatura. Para construir dicho esquema, tenemos en cuenta los siguientes elementos o pasos:
  1. Identificación de variables implicadas en el proceso ecológico a analizar. Este primer paso implica un nuevo proceso de desagregación, puesto que trataremos de evaluar en qué medida el proceso en cuestión depende de distintas variables biofísicas. Nos preguntaremos: ¿qué variables ambientales pueden condicionar la regeneración de la encina bajo el pinar? Para ello, y con objeto de suplir nuestros aún limitados conocimientos sobre este proceso, podremos consultar el esquema final que hay en [esta](https://github.com/aprendiendo-cosas/T_contexto_pinares_ecoinformatica_ugr/raw/2023_2024/presentacion/generalidades_pinares_reboblacion.ppt) presentación.
  2. ¿Son todas las variables del mismo tipo? Es de esperar que algunas variables tengan carácter biofísico (precipitación, profundidad del suelo, etc.) y otras socioeconómico (distancia a vías de comunicación, tasa de desempleo por municipio, etc.). Esta distinción será importante cuando las integremos todas para dar una respuesta final.
  3. Fuentes de datos: Una vez identificadas las variables que consideramos relevantes, procederemos a evalular la disponibilidad de datos para su uso en el análisis. En ese proceso quizás tengamos que usar variables subrogadas de las originales. [Aquí](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/1365-2664.13366) tienes una definición de lo que significa variable suborgada (lee solo el Abstract del artículo para una idea general) y [aquí](https://ebooks.publish.csiro.au/content/indicators-and-surrogates-biodiversity-and-environmental-change) un libro completo que trata sobre el asunto. La identificación de las fuentes de datos de partida también nos permitirá caracterizar preliminarmente el procesamiento que será necesario aplicar a los datos originales para satisfacer nuestras necesidades. Esta última frase, que pasa desapercibida, es muy importante porque ese procesamiento ocupará el grueso de la asignatura. En cada uno de los procesos aprenderemos técnicas diferentes (bases de datos, teledetección, cartografía de la vegetación, etc.)
  4. Hipótesis previas sobre cómo creemos que podría participar cada variable en el proceso general. Es decir, analizaremos en qué medida contribuye cada variable seleccionada a explicar la regeneración de la encina bajo el pinar. Por ejemplo, ¿Cómo afecta la densidad del pinar a la regeneración de la encina? En este caso está claro porque tenemos evidencias al respecto: a densidades bajas hay poca regeneración y a densidades altas también. Este paso será útil para hacernos una idea de cómo pueden interactuar las distintas variables que hemos seleccionado.
  5. Integración de todas las variables para obtener un resultado único. Se trata de la fase más crítica porque implica construir un modelo conceptual en el que todas las variables seleccionadas se integren y nos permitan responder a la pregunta (¿de qué variables depende la regeneración?, ¿Cuál es el peso relativo de cada variable?). El resultado de este paso deberá de ser un mapa que muestre cuantitativamente la "intensidad" del proceso de regeneración en cada punto del territorio. Esta intensidad se podrá medir en probabilidad, idoneidad o en número de encinas que se regeneran dependiendo del tipo de metodología utilizada para la integraión. Este paso lo abordaremos en una sesión específica al final de la asignatura
  
  A continuación se muestra el flujograma tal y como quedó tras el trabajo de la clase. Se puede descargar [aquí](https://github.com/aprendiendo-cosas/T_flujo_trabajo_ecoinf_ugr/raw/2023_2024/presentacion/20240111_workflow_pinares_1.zip) en formato Draw.io.


<iframe frameborder="0" style="width:100%;height:2768px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=20240111_workflow_pinares_1.drawio#R7V1Zc9s4Ev41qpp92BRvSY8%2BkkyqkplsZXeSzBtEwhISklBAUrbz6wcACZEEWhLXsXjYfklEELKI7v4afaE5c6%2BSu7cMbTcfaITjmWNFdzP3euY4djD3%2BH9i5L4cWfjVwJqRqJpUD3wiP3E1aFWjBYlw1pqYUxrnZNseDGma4jBvjSHG6G172g2N27%2B6RWtsDHwKUWyOfiZRvilHHdcN6hu%2FY7LeqJ8O1AITpGZXS8k2KKK3jSH39cy9YpTm5afk7grHgnqKMOX33hy4u38yhtO8yxdu%2F%2FP56uLy8%2B%2Ff338pogv88Tv5EP%2B7etgdiotqxdXD5veKBDjiFKkuKcs3dE1TFL%2BuRy8ZLdIIi5%2Bx%2BFU95z2lWz5o88FvOM%2FvK%2FaiIqd8aJMncXXXXEq1uowWLMRHnl%2FJBGJrnB%2BZ55bzxFoaP1AR6i2mCc7ZPZ%2FAcIxysmtzH1VCtN7Pq8nMP1SU%2Fj%2BobhtUf1PwpWMBFPkPymk2cwKUcPpdpqtsuydSgzFcoLbiY3gfE05%2F5vJJtxuS409bJIl2yzHZJvSq5NT71X4Ahd%2FXkn9%2FFjn%2FM7gaz0pW2f4x7uwwy%2FHdUXreKcBUIKjUgO1V17c1qIJqaNOA08I6EwccgwPXJMsZWRUhmV25s0s3VczYIUbQKhYfLw7ygFMHxTGO6ZqhhNNsixnhT4qZfu9jfeMUs27IHVYq8ShKuvPBDzQ%2BBCYfbAdgRHAuRrgGIz4yGuIMJYQvk%2FJbXwyisw1NVkV2moKPQDF3eVpyF31Krj%2BEgub0Y%2FdfxPdfWcFCDXyVA643VwPXd9VPlFf3zauG4MvBh%2Bt8t6POd0al8wNT0HEakVLtT1yraBhx50NrlcW0rJh5R4kORiXRc0OiL4Tdi1Nhu1jbWrqtRGypF3YmH22NU8xQY5vVOMWFLm8TFsVknQpDR%2Fw5IeJCNAk30i%2BqGwmJopKHmBsucrMuubilJM3luv3LmX8t%2FhZnW1ZLP9%2Fz6Xd8RWMqMJVSYQBxiMSxNvQYO8m8jRJnaaJkbyc1UeKeCyXKyZoKTJaThMnSgMlrYVvGSMDhJyed%2BD8p7puYyUqXdscvBH5SbgcFsUDFivFPa%2FHpR0E4IfjNEltsRWP5NbEvVF%2FhC0QhX6CcFotRzLjwPzvgOW3geT4APB8Annc24JkOILd6bziwSIQik9dbmuM0JEjGVmSEJSv4zj95u0HTiAFgW%2FdrN9juwNa137KtT9jVD9ekttNRlSpJHYkuVc%2BtK1OlRrnOVODI2nbHtsSXHN6g%2BxejpNKNdhuC%2FsKEoOv1apQM4uD%2BApS8iULJDP1%2BwN8oU7ZDyKmIE4mXtoWhb074CAC3NKRt8D0XXGkBzzngEjvQ1nY%2Bm8O0QycGtK5esr0YFdAUnV8I3zfhzdjyC%2BF7IfzAMep2fHpvUj%2B%2BFd2VP443Kv7YZuROZu6BKENE1iSv%2FE5g64%2FxjhvNfNc0d%2Fap%2BaJajGBwV9QZJDg3AIgWHUE0rqieeuwGhrYH8zl9Jiz3FqRKxgAp3l4Tlk4wrV3XmahD55gOXVh6bnFYxA03rIwxWl2DikMKb%2BAOLbzmVnmN06wioawPqTxdkvKFZ2qQ4S1dxc2AkmUblJ3YFunpRTwWlOed97lJusNuknZfm6TTdZNU8joWnWTukjK4lFeJrYxTgkRlqioqQiKiTzJRFZ0AWRVYEtMoEJPKUbKfsf%2F2jwKrn07bP5HgiCBDkp5qbCqY6zgGMtEuVI53tuCUO%2FU6VLdzIeq4KlHd5aAKtDcvozt%2FxqVA1XM3gPEu3fHlI0akUruhXNVwD%2F2IBz6B%2BmC9yNKyBq4Pdp9JCMt1pqm3PNOa7oM%2FdyT%2F0vjc4A6%2FqpkjLlrFryPl6bh0nWf6WhMzAroS3htXLEs9dzMejLZIWc87zFdzpDZiYm6sFum1HWCv6fkMxCARsgEUU%2BfK%2FXEpJtdMJP4lI2vXCIzrDBkxs62h473eM0lcuF2zf%2B64srOuuc02pNnccnuVZkM5D33cyjUjWA8NAJukndjOaZyFc4BK6n4DwJ5pulyirGZDdZJWQkskqkFHeZSBvhua5kpnAme9fxlaSyDoZ0PQOlulp2duq02zc8voHUnggvjfIpLlSGSv1OwQReLzttRkdzKfVRYjcmBKEZCJLuC%2BSIJVhzDqiuAQsxCl9F%2BTh6yuUD3o1NGyV8gOcjivf%2FtAOXmnvcGRhVbMk6oorRLJJCMZhM8BTQY9meEBFez92r9moW1Tre01l9RJUnMxJvQDmnwNlaf5Is5chVGbysYGmDE%2FFzN80z4YQvs8XIso%2FX1Si%2FjjqkZRz90gfNJAwdMRel%2BX%2BcErB31%2F6jLfNVnnj6uuVj13swKLptJ1YKWy1%2B1YLv9Cbgd1uS1DaQ%2Fd4WRiBYN%2B14JBZRmMRVyBgkEkagXlefGmnTKgeOoHFEcgnmb87H0ZAdr7lhj2JpXFV3qcZbAokz5oPVfXECjCYYHKc6vqaH%2BBRRBBSBxDK%2FTNLNkcZUDjMXSVOlmijH0XMPZBaThb5ZI%2FsDf7yneDtkdrWfsZ%2FfRj8rsGwkfm6Pqmo1YCOSM50c%2BPaxBu2q86ZHVIWy8Ybip03d5YBICTCB05PxuGlSU%2BGIY9q9334dVysewZw1176wxnw3z%2Bsfv77%2F9R8unr1deN9%2BNNHv9JoUMPozUewQUArg680MF057HHPhDjQitOz32QS4W9uAOf0dLq%2BU2oTz5F6L0r8dAUR%2BLW5OPtS%2F2MxNI2tZsNNRt6DHsVZNV4vSlY0DsCYlx4MMOMso1pRPZtTKuNH2dcHAnfyn%2FWXbmiQ61ny8xyCzpDumJaHy17AZ3%2Fgcp07ceI74J0nw%2B7c58hl3RM2E%2BCYrAY8LGnfhgo6j1knGgIRogGoKUPFdGcfXVPLtpc8f8L6aGUO3ZI05ykBXT4Hx9mxjE2PFXXRc9v2QsgFrWPpz626wJy3Az1v1sXstIhrVxZtsMmw4%2FsPAeEoDx0t4r37R5exGDvwVqAjXe2hpKgGDy9U1zgMoFTsMessZFsg2YF4UUe157RDSpSJH2inQCRcIdQekNWMgR1JWFbxpKub0T71sMu0gTOeekKdO4AeyakQO3HqEKDTSYzUf1f7priluUhS8sYjYqwaaNvuacpXg5xkCMTcVrnukJz%2BmzgDnNl8nGdroEde1yOLNCa%2BD1KowzlfFCY7PLIfirqJ6erhha6vANnJs513BSmullzNzFx7%2Byh%2BuMSd9NHjXAW8lXUno4oIX8l7GbRTl0P0fxx%2Fdc7g1W91m%2FoCXJImM%2BVIIdpOkhQ5hdk1%2B8qu9a4ZNd0%2Fq64URFyM4L7TmYwEUntzYjsgoKTLWXSUbw%2FJNp5bQYNKN%2Beni90PCCiDuULbftsEg6Y9LN2yjfOUZuETXVhJVWn5TL%2Bpbvc%2BpvfULzCXCGJL%2BQM5dWrsfTuDyfeFvdUvXH95UN1dqWPfDLsfj4Td9zpuuk7g52APPrchzvlGZX6AypA215qVU9QTrHXHR5o65VARxxmZbHMsSDhxFxlW3%2BLE2cG4Cv3muBVPYKe0EtL4HUCRyGmoG5cM8LUfFFaEy0NC4JEfItUrTrLNFltB%2Bh7vdH%2F7rCZ8EzMAtt45ewCAOrZakVhQXAMQXhL6ToWOvM14hAU%2F6drEfaYBJse%2B4iy7eim3HJh6tZzvY0GZtmEztLAC%2Bhqo7mDnaU5%2BtxNrFy%2Be3PQfphA1FF%2F%2FyPUY77XqCPQCWRiwg2cvIEnDtZw6%2Bhzt5qKAFFHgxuDHgyD5LVXt0M1K52uvAItAeCJI7NgzfREhLcFM2OGw4utG4xNbF96VZ4W9JOIUEwcCyLMCEijiLEJCxle16NL4u%2BXNR1pREKs0PNpg9KUmh0W%2B8SPrxvhw%2BNnQu%2FxOiq7p4XcGZWQe2bgYh%2FmOyXB1aXIm%2F6Bd7I507Qjf4Gxr0DNz3otkvHG%2B6rUo%2BJ9Ggfj8kWBJnMoI%2BtUZuTK06Bl8zFSDsliWz5ZpvgkDprBPPnyiZsiNWynrJiZsfOEX2zKYkHOpYiyxmtWy7rBiK%2Bf1Q0JOT4S%2FhwA4PrcRRZ6iY0LtZuD%2Bo7Z59tHTK%2BLpDf8s1Hq1yIpLquls4PMKJmHExLLWSfysBNTe0b26ax6j18ySvPGvbd8kRv5dkI%2B%2BA8%3D"></iframe>













