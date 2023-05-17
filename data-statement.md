## Data statements para datasets
**Introducción** 

Sabemos que los datos juegan un papel fundamental en el aprendizaje automático. Cada modelo de aprendizaje automático se entrena y evalúa utilizando datos. Las características de estos conjuntos de datos (en inglés, datasets) cambiarán completamente el comportamiento de un modelo. Es poco probable que un modelo funcione bien si su contexto de uso no coincide con sus datasets de entrenamiento o evaluación, o si estos datasets reflejan sesgos no deseados. 

Los data statements para datasets son una metodología que permiten caracterizar los datos y hacer explícitos posibles riesgos de su uso. Tienen el potencial de aumentar la transparencia y la responsabilidad de los productos basados en esos datos. 
Si tenemos un data statement nos podemos preguntar si un sistema entrenado en ese dataset es o no apropiado para cómo se planea utilizar el sistema. Un data statement ayuda también  a mejorar la reproducibilidad de un modelo al documentar cómo difieren distintas versiones del mismo dataset.

Están destinados a abordar las necesidades de dos grupos de partes interesadas clave: creadores de datasets y consumidores de datasets. Para los creadores de datasets, el objetivo principal es fomentar una reflexión cuidadosa sobre el proceso de creación, distribución y mantenimiento de un conjunto de datos, incluidas las suposiciones subyacentes, los riesgos o daños potenciales y las implicaciones del uso. Para los consumidores de datasets, el objetivo principal es garantizar que tengan la información que necesitan para tomar decisiones informadas sobre el uso de un conjunto de datos. 

La forma de elaborar un data statement consiste en entrevistar al creador o responsable del dataset y realizar la serie de preguntas que se enumeran en este documento. En la siguiente sección se detallan los pasos a seguir. 

## 1. Motivación para la creación del dataset

Las preguntas de esta sección están destinadas principalmente a alentar a los creadores de datasets a articular claramente sus razones para crear el conjunto de datos y promover la transparencia sobre los intereses de financiación. 

1.1 ¿Con qué propósito se creó el conjunto de datos? ¿Se tenía una tarea específica en mente? ¿Conoce otros datasets parecidos, y, en ese caso, cuáles son las diferencias? Proporcione una descripción. 
COMPLETAR

1.2 ¿Quién creó el conjunto de datos (por ejemplo, qué equipo, grupo de investigación) y en nombre de qué entidad (por ejemplo, empresa, institución, organización)?
COMPLETAR

1.3  ¿Quién financió la creación del conjunto de datos? 
COMPLETAR

## 2. Composición del dataset 
Estas preguntas están destinadas a proporcionar a los consumidores del conjunto de datos la información que necesitan para tomar decisiones informadas sobre el uso del conjunto de datos para tareas específicas. 

2.1 ¿Qué representan las instancias que componen el conjunto de datos (por ejemplo, documentos, fotos, personas, países)? ¿Hay varios tipos de instancias (por ejemplo, películas, usuarios y calificaciones; personas e interacciones entre ellas; nodos y conexiones)? Proporcione una descripción.
COMPLETAR
 
2.2 ¿Cuántas instancias hay en total (y de cada tipo, si corresponde)?  
COMPLETAR

2.3 ¿De qué datos consta cada instancia? ¿Datos "sin procesar" (por ejemplo, texto o imágenes sin procesar) o características? En cualquier caso, proporcione una descripción y algunos ejemplos.
COMPLETAR
 
2.4 ¿Hay una etiqueta o anotación de supervisión asociada con cada instancia? Si es así, proporcione una descripción. 
COMPLETAR

2.5 ¿Cree que hay algún aspecto de los datos que no ha sido representado y que podría llegar a resultar relevante para alguna aplicación o por sus efectos en algún segmento de la población (p. ej., falta información de género)? De ser así, proporcione una descripción. 
COMPLETAR

2.6 ¿El conjunto de datos contiene datos que podrían considerarse confidenciales (por ejemplo, datos que están protegidos por privilegios legales o por la confidencialidad del médico-paciente, datos que incluyen el contenido de las comunicaciones no públicas de las personas)? Si es así, proporcione una descripción. 
COMPLETAR

## 3. Recopilación del dataset
Estas preguntas están destinadas a identificar características de la recopilación del dataset para advertir a consumidores del conjunto de datos sobre posibles sesgos emergentes debido a decisiones de recolección.  

3.1 ¿Qué mecanismos se utilizaron para recopilar los datos, elegir la muestra y curar los datos (por ejemplo, aparatos o sensores de hardware, curación humana manual o automática, programa de software)? Esta pregunta es particularmente importante para datasets que son demasiado grandes para ser inspeccionados a mano. Explicar la racionalidad de la muestra puede ayudar a los usuarios de datasets a entender a qué tipos de usos el dataset puede generalizar bien o mal. 
COMPLETAR

3.2 ¿Quiénes participaron en el proceso de recopilación de datos (p. Ej., Estudiantes, trabajadores digitales, contratistas) y cómo se les compensó (p. Ej., ¿Cuánto se les pagó a los trabajadores)? 
COMPLETAR

3.3 ¿Durante qué período de tiempo se recopilaron los datos? 
COMPLETAR

3.4 ¿El conjunto de datos se relaciona con las personas? De lo contrario, puede omitir las preguntas de la sección 4. 
COMPLETAR

## 4. Datos de personas
4.1 ¿El conjunto de datos incluye datos demográficos (por ejemplo, por edad, sexo)? De ser así, enumere qué datos demográficos se incluyen.

4.2 ¿Es posible identificar individuos (es decir, una o más personas físicas), ya sea directa o indirectamente (es decir, en combinación con otros datos) del conjunto de datos? Si es así, describa cómo. 

4.3 ¿El conjunto de datos contiene datos que podrían considerarse sensibles de alguna manera (por ejemplo, datos que revelan orígenes raciales o étnicos, orientaciones sexuales, creencias religiosas, etc.)?

4.4 ¿Recopiló los datos de las personas en cuestión directamente o los obtuvo a través de terceros u otras fuentes (por ejemplo, sitios web)? 

4.5 ¿Se notificó a las personas en cuestión sobre la recopilación de datos? Si es así, describa cómo se envió la notificación. 

## 5. Usos 
Estas preguntas están destinadas a alentar a los usuarios del dataset a reflexionar sobre las tareas para las que el dataset debe y no debe usarse. Al resaltar explícitamente estas tareas, los consumidores de datasets pueden tomar decisiones mejor informadas, previendo riesgos o daños potenciales. 

5.1 ¿Para qué tareas creen que se puede usar este conjunto de datos?¿Ya se ha utilizado el conjunto de datos para alguna tarea? Si es así, proporcione una descripción. 
COMPLETAR

5.2 ¿Existe un repositorio que se vincule a alguno o todos los artículos o sistemas que utilizan el conjunto de datos? Si es así, proporcione un enlace u otro punto de acceso. 
COMPLETAR

5.3 ¿Para qué (otras) tareas se podría utilizar el conjunto de datos? 
COMPLETAR

5.4 ¿Hay algo sobre la composición del conjunto de datos o la forma en que se recopiló y preprocesó / limpió / etiquetó que pueda afectar los usos futuros? Por ejemplo, ¿hay algo que un futuro usuario pueda necesitar saber para evitar usos que podrían resultar en un trato injusto de individuos o grupos (por ejemplo, estereotipos, problemas de calidad del servicio) u otros daños indeseables (por ejemplo, daños financieros, riesgos legales)? Si es así, proporcione una descripción. 
COMPLETAR

5.5 ¿Hay tareas para las que no se debería utilizar el conjunto de datos? Si es así, proporcione una descripción. 
COMPLETAR

5.6 ¿Algún otro comentario?

