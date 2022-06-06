# grupo2-aula32
this is the first repo from ispc web development degree group #2 

### Definición de ceremonia
En el marco de trabajo scrum, una ceremonia es una oportunidad formal para inspeccionar y adaptar los artefactos. Estas ceremonias tienen como finalidad garantizar uno de los pilares fundamentales, que es la transparencia. También permiten generar un espacio de diálogo diario sin necesidad de plantear otro tipo de reuniones. Las ceremonias en scrum son las siguientes: 
1) The Sprint 
2) Sprint planning meeting
3) Daily scrum
4) Sprint review meeting
5) Sprint retrospective meeting

### Definición de Roles

Los roles definidos dentro de un equipo de Scrum son:
* Product Owner:  es el encargado de optimizar y maximizar el valor del producto.
* Scrum Master: es el responsable de que se sigan las prácticas y valores descritos en el modelo Scrum
* Development Team : se encargan de desarrollar el producto, auto-organizándose y auto-gestionándose para conseguir entregar un incremento de software al final del ciclo de desarrollo.
![Equipo Scrum](https://lh3.googleusercontent.com/Z1VtkwnhtOE61_pgT3kx2xhnvwV6S9rk3W-NVjto0g916fx7yxGQ2MUPDsWFNSZA1l3IGDAoQ4pvbrMn5s7h029bMHqIDIXkA3ylTSPJHGjEEpe6rlelGv-vQVwnd5lDycHlHVxl)

### Artefactos Scrum :hammer_and_wrench:
**Representan trabajo o valor. Están diseñados para maximizar la transparencia de la información clave.
Cada artefacto contiene un compromiso para garantizar que proporcione información que mejore la transparencia y el enfoque contra el cual se puede medir el progreso:**
  1. - Para el Product Backlog es el Product Goal.
  2. - Para el Sprint Backlog es el Sprint Goal.
  3. - Para el Incremento es la Definición de Listo.

#### 1. Pila de Producto
El Product Backlog es una lista emergente y ordenada de lo que se necesita para mejorar el producto. Es la única fuente de trabajo realizada por el Scrum Team. Los elementos de la Lista de Producto que puede realizar el Equipo Scrum dentro de un Sprint se consideran listos para la selección en un evento de Planificación de Sprint.
#### _Compromiso: Producto Objetivo_
_El objetivo del producto describe un estado futuro del producto que puede servir como objetivo para que el Equipo Scrum planifique. El objetivo del producto se encuentra en la cartera de productos. El resto del Product Backlog emerge para definir "qué" cumplirá con el Product Goal._
#### 2. Pila de Sprint
El Sprint Backlog se compone del Sprint Goal (por qué), el conjunto de elementos del Product Backlog seleccionados para el Sprint (qué), así como un plan procesable para entregar el Incremento (cómo). Es un plan por y para los Desarrolladores, del trabajo que los mismos planean realizar durante el Sprint para lograr el objetivo del Sprint. 
#### _Compromiso: Sprint Goal_
_Es el único objetivo del Sprint. Brinda flexibilidad en términos del trabajo exacto necesario para lograrlo. Se crea durante el evento Sprint Planning y luego se agrega al Sprint Backlog. A medida que los desarrolladores trabajan durante el Sprint, tienen en cuenta el objetivo del Sprint. Si el trabajo resulta ser diferente de lo que esperaban, colaboran con el Product Owner para negociar el alcance del Sprint Backlog dentro del Sprint sin afectar el Sprint Goal._
#### 3. Incremento
Un Incremento es un peldaño concreto hacia el Objetivo del Producto. Cada Incremento se suma a todos los Incrementos anteriores y se verifica exhaustivamente, lo que garantiza que todos los Incrementos funcionen juntos. El trabajo no puede considerarse parte de un Incremento a menos que cumpla con la Definición de Terminado.
#### _Compromiso: Definición de Hecho_
_La Definición de Terminado es una descripción formal del estado del Incremento cuando cumple con las medidas de calidad requeridas para el producto. En el momento en que un elemento del Product Backlog cumple con la Definición de Listo, nace un Incremento_


### Base de datos Relacionales y No Relacionales
Los desarrolladores de software debemos elegir entre bases de datos relacionales y no relacionales  para construir un nuevo sistema, y esto depende de lo que queramos hacer. 
Hay 3 tipos de análisis de datos para mejorar la toma de decisiones: análisis descriptivo, análisis  prescriptivo y análisis predictivo. 
 La base de datos relacionales se comenzó a usar en los años 80', y las no relacionales se empezaron  a utilizar entre 2012 y 2015. Sin embargo, hoy sigue siendo más popular la primera opción. 
 
#### Bases de datos relacionales: 
Colección de elementos de datos organizados en un conjunto de tablas formalmente descriptas, desde  donde se puede acceder a datos o volver a montarlos de muchas maneras sin tener que reorganizar  las tablas. La interfaz estándar es el lenguaje de consultas estructuradas o SQL, o RDBMS; que se  utiliza tanto para consultas interactivas, como para obtener información y recopilación de datos para  informes. 
La organización de la información es en partes pequeñas y se integran con identificadores. Además,  tiene una mayor capacidad de almacenamiento, u son menos vulnerables ante fallas. Es un modelo que describe la estructura lógica. También describe cómo el usuario mantendrá y  accederá a los datos.  
Para manipular los datos en SQL, se requiere primero determinar la estructura de éstos. 

#### Bases de datos no relacionales: 
Diseñadas para modelos de datos específicos con esquemas flexibles para crear aplicaciones  modernas. Son ampliamente reconocidas porque son fáciles de desarrollar, tanto en funcionalidad  como en rendimiento a escala. Además, puede usar documentos, gráficos, clave-valor, en-memoria y  búsqueda. 
Éstas no tienen un identificador que sirva en relación entre conjuntos de datos y otros. La información  se organiza normalmente mediante documentos, y es muy útil cuando no tenemos un esquema exacto  para almacenar. En este documento las organizaciones pueden almacenar información de los clientes  
como nombre, pedido, favorito, dirección, detalles de contacto y mucho más. También contiene una  carpeta semiestructurada con muchos archivos, pero no usa ningún formato de tabla. Los NOSQL tienen un sistema dinámico que no requiere estructura y puede almacenar de cualquier  manera: columnas, documentos, gráficos, etc, y cada documento puede tener su propia estructura, sin  afectar los demás. Almacena por colecciones. 
Habitualmente los datos almacenados en tablas son relacionales, porque existe la posibilidad de  enlazar los datos de una tabla con otra, y los datos almacenados de un documento ya es no relacional,  pero no siempre tiene que ser así. Por ejemplo, los datos de una tabla pueden ser transcriptos a un  documento, dependiendo del punto de vista y la necesidad del usuario. 
Tanto SQL como NOSQL son tipos de bases de datos recomendadas para utilizar a la hora de  comenzar un proyecto, y cada una tiene sus ventajas y desventajas. Por ejemplo, los sistemas  contables o de inventario, son sistemas que requieren transacciones de varias filas, para este tipo de  trabajos la mejor opción son SQL (MySQL). Pero si los sistemas de gestión de contenido, aplicaciones  móviles, sistema de análisis en tiempo real, bases de datos de un crecimiento rápido, con un esquema  descentralizado, la mejor opción son NOSQL (MongoDB). 
  
 Algunas de las ventajas de SQL son: mayor soporte y más variedad de herramientas debido a que  lleva más tiempo en el mercado, útil para manejar y obtener datos, permite agregar otros servidores. Algunas desventajas de SQL son: que no es flexible (antes de ingresar los objetos, deben estar  correctamente validados), mientras más compleja sea la base de datos requiere mayor procesamiento  y eso se puede ver reflejado en el rendimiento y consumo de recursos. 
  
 Ventajas de NOSQL son: permite alta escalabilidad (ayuda a reducir la carga de trabajo), flexible a  diferentes tipos de datos, los datos deben cumplir con el tipo de dato definido. Y algunas desventajas de NOSQL son: la integridad de los datos se ve afectado por el poco soporte,  menos seguridad al ejecutar consultas, no existe estandarización, es poco compatibles con las bases  SQL, casi todo su mantenimiento se debe realizar por consola pot las pocas herramientas existentes.
Las bases de datos no relacionales no son el reemplazo de las bases relacionales, simplemente son  modelos diferentes que ofrecen ventajas y soluciones al momento de utilizarlas. 

Realicemos una tabla de comparación para cubrir las diferencias más importantes y esenciales de cada  una:

![cuadro](https://docs.google.com/drawings/d/1LAkEDXmDLzxuA5ooUZCJAlbFsz-5Q9fIIylTOUev1Fc/edit?usp=sharing)
