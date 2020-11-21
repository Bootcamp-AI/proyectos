Proyectos Bootcamp AI

Índice
1. Preámbulo
2. Resumen del proyecto
3. Problema
4. Puntos clave
5. TODO
6. Criterios de aceptación
 
 
1. Preámbulo
Según Forbes, el 90% de la data que existe hoy ha sido creada durante los últimos dos años. Cada día generamos 2.5 millones de terabytes de datos, una cifra sin precedentes.
No obstante, los datos por sí mismos son de poca utilidad. Para que esas grandes cantidades de datos se conviertan en información fácil de leer para los usuarios, necesitamos entender y procesar estos datos. Una manera simple de hacerlo es creando interfaces y visualizaciones.
En este año los hospitales han generado más datos debido a la pandemia y necesitan estructurarlos de mejor manera.
2. Resumen del proyecto
En este proyecto construirás un sistema para para el registro y análisis de datos de pacientes para uno o más hospitales.
Como entregable final tendrás una página web que permita a los doctores y enfermeras interactuar con la interfaz y visualizar métricas.
Los datos serán generados por SyntheaTM Patient Generator
3. Problema
El hospital XY  ha utilizado históricamente proveedores de nube para alquilar servidores físicos, en los últimos meses ha incrementado el número de pacientes y tuvieron problemas para escalar sus servidores de aplicaciones, bases de datos MySQL y herramientas de análisis. Su arquitectura actual se puede ver aquí. Que consta de un canal HL7, sql y rest api para la ingesta de datos.
El hospital XY quiere ajustar su infraestructura para resolver sus problemas de escala. Tienen servidores de aplicaciones, base de datos MySQL para almacenar información del usuario y exámenes médicos. Y están interesados en utilizar la analítica para mejorar sus procedimientos. Tienen un plan de diseño implementado, pero tuvieron problemas con un proveedor de nube anterior. Sus objetivos comerciales son utilizar un proveedor de nube que le brinde el Software como Servicio(SaaS) y pagar un valor mensual. 
Necesitan algún tipo de métricas o indicadores clave de rendimiento para medir la velocidad, la estabilidad y otras cualidades. Para que puedan comenzar a administrar la calificación de la experiencia del usuario tomando decisiones inteligentes en la infraestructura médica.


4. Puntos clave
Como suele ser el caso, la solución planificada o presunta podría no ser la ideal. Tienes que tener cuidado al discutir esto, ¿verdad? No sabes quién participó en la definición de ese gran plan. Puede ser un buen diseño. Puede tener algunas áreas que deban cambiarse. Lo importante es reconocer primero la existencia de la solución planificada. Luego, para definir la solución por separado, para que pueda comprender las fortalezas y debilidades de la propuesta. De esa manera, puede hacer sugerencias razonadas sobre qué cambiar para mejorar el plan.


La empresa tiene un fuerte enfoque en análisis y métricas personalizadas. En otras palabras, es fantástico poder escalar instancias según la carga de la CPU. Pero, ¿qué tan bien indica eso realmente el consumo de recursos por parte de los usuarios? Es posible que algunos factores de la oferta, como la cantidad de usuarios que son atendidos, sean un factor en la escala.

Finalmente, debe considerar soluciones de almacenamiento potencialmente diferentes para datos analíticos y para datos de pacientes. Los datos son diferentes, se accede de manera diferente y en diferentes momentos. Por lo tanto, tendría sentido que cada tipo de datos y casos de uso se examinarán por separado para determinar los mejores candidatos para su inclusión.


5. TODO

Planificación
Puntos de negocio clave
Evaluación técnica
Solución Propuesta 


Desarrollo
Recursos
Google Healthcare
Ingesta FHIR a BigQuery



6. Criterios de aceptación mínimos del proyecto
Los criterios para considerar que has realizado este proyecto son:
Definición del producto
Documenta brevemente tu trabajo en el archivo README.md de tu repositorio, contándonos cómo fue tu proceso de diseño y cómo crees que el producto resuelve el problema (o problemas) que tiene tu usuario.
Historias de usuario
Una vez que entiendas las necesidades de tus usuarios, escribe las Historias de Usuario que representen todo lo que el usuario necesita hacer/ver. Las Historias de Usuario deben ser el resultado de tu proceso de investigación o research de tus usuarios.
Asegúrate de incluir la definición de terminado (definition of done) y los Criterios de Aceptación para cada una.
En la medida de lo posible, termina una historia de usuario antes de pasar a la siguiente (Cumple con Definición de Terminado + Criterios de Aceptación).
 
Planificación
Puntos de negocio clave
Evaluación técnica
Solución Propuesta 
 
 
 
Implementación de la Interfaz de Usuario
Como mínimo, tu implementación debe:
Mostrar la data en una interfaz: puede ser un card, una tabla, una lista, etc.
Permitir al usuario interactuar para obtener la información que necesita.
Ser responsive, es decir, debe visualizarse sin problemas desde distintos tamaños de pantallas: móviles, tablets y desktops.
Que la interfaz siga los fundamentos de visual design.
Recurso: https://clewmed.com
 
Implementación de la Arquitectura
Recursos
Google Healthcare
Ingesta FHIR a BigQuery
 
 
Pruebas unitarias
El boilerplate de este proyecto no incluye Pruebas Unitarias (tests), así es que tendrás que escribirlas tú para las funciones encargadas de procesar, filtrar y ordenar la data, así como calcular estadísticas.
Tus pruebas unitarias deben dar una cobertura del 70% de statements (sentencias), functions (funciones), lines (líneas), y branches (ramas) del archivo src/data.js que contenga tus funciones y está detallado en la sección de Consideraciones técnicas.
 
Herramientas
Atlassian: Jira, Trello.
 

