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

### Diseño de bases de datos relacionales
En este tema se estudia un aspecto fundamental de las bases de datos: su diseño. En las bases de datos se ha establecido un ciclo de desarrollo que consta de tres etapas de diseño: el diseño conceptual, el diseño lógico y el diseño físico
 
 #### 1. Diseño conceptual.
Su objetivo es definir las entidades y las relaciones entre ellos de forma abstracta, sin centrarse en ningún modelo lógico en concreto (como el relacional, el orientado a objetos, el jerárquico o el de red).
_Herramienta_: Modelo conceptual de datos. Se usa alguna variante del modelo entidad-relación para las bases de datos relacionales.
Resultado: Esquema conceptual de la base de datos.
 
   #### 2. Diseño lógico. 
Su objetivo es definir el esquema de la base de datos según el
modelo que implementa el SGBD objetivo.
_Herramienta_: Modelo lógico de datos. Se usa el modelo lógico que implemente el sistema de gestión de bases de datos objetivo, pero es independiente de los aspectos físicos. Se usan técnicas formales para verificar la calidad del esquema lógico; la más usual es la normalización. En el modelo relacional se usan las tablas.
_Resultado_: Esquema lógico de la base de datos.
 
#### 3. Diseño físico. 
Su objetivo es definir el esquema físico de la base de datos de forma que se den todas las instrucciones para que un DBA pueda implementar la base de datos sin ninguna ambigüedad. Se considera el rendimiento como un aspecto que no se ha tratado en las etapas anteriores.
_Herramienta_: Modelo físico de datos. Se consideran todos los detalles de la implementación física: organización de archivos e índices para el SGBD considerado.
_Resultado_: Esquema físico de la base de datos.
 
### Diseño conceptual
 
#### Diagramas entidad-relación (E-R)
Un diagrama es una herramienta para el modelado de datos que permite representar las entidades relevantes de un sistema de información así como sus interrelaciones y propiedades.
El diseño del modelo E-R a partir del análisis inicial no es directo. A un mismo análisis le corresponden muchos diseños "candidatos". Hay varios criterios, pero ninguno es definitivo. De un buen diseño depende:
            Eficiencia: Es muy importante en las BD cuando se manejan grandes cantidades de datos.
            Simplicidad del código: Se cometen menos errores.
            Flexibilidad: Se refiere a que el diagrama sea fácil de modificar.
Denominado por sus siglas como E-R. Este modelo representa a la realidad a través de un esquema gráfico empleando la terminología de Entidades, que son objetos que existen y son los elementos principales que se identifican en el problema a resolver con el diagramado y se distinguen de otros por sus características particulares denominadas Atributos.
El enlace que rige la unión de las entidades esta representada por la relación del modelo. En un DER, cada entidad se representa mediante un rectángulo, cada relación mediante un rombo y cada atributo mediante un círculo.

![DER](https://upload.wikimedia.org/wikipedia/commons/f/f6/Ejemplo_Diagrama_E-R_extendido.PNG)

#### Entidad
Se trata de un objeto del que se recoge información de interés de cara a la base de datos. Gráficamente se representan mediante un rectángulo. Un ejemplo seria la entidad alumno, donde se recogerían los datos relativos a los alumnos de una escuela, como puede ser el nombre, el número telefono, la dirección, etc.
Dentro de las entidades pueden ser fuertes o débiles. Las fuertes son las que no dependen de otras entidades para existir, mientras que las entidades débiles siempre dependen de otra entidad sino no tienen sentido por ellas mismas.
 
#### Relación
Podemos definir la relación como una asociación de dos o más entidades. A cada relación se le asigna un nombre para poder distinguirla de las demás y saber su función dentro del modelo entidad-relación.
Las relaciones se representan gráficamente con rombos, dentro de ellas se coloca el nombre de la relación.
Mediante líneas se conectan las entidades con las relaciones, igual que las entidades con los dominios, representando a los atributos.
Otra característica es el tipo de correspondencia entre dos relaciones;
1:1. Uno a uno, a cada ocurrencia de una entidad le corresponde como máximo una ocurrencia de la otra entidad relacionada.
1:N. Uno a Mucho, a cada ocurrencia de la entidad A le pueden corresponder varias de la entidad B.
N:M. Muchos a muchos, cada ocurrencia de una entidad puede contener varias de la otra entidad relacionada y viceversa.
  
#### Atributo
 Es cada uno de los componentes que determinan una entidad.
   Cada atributo tiene asociado un dominio: el conjunto de valores que puede tomar.
   La entidad del ejemplo anterior viene determinada por los valores de sus atributos DNI, Nombre y Apellidos, Teléfono, Domicilio y COU.
   En el enfoque clásico serían los campos de los registros.
•     Atributos monovalorados y multivalorados: Los atributos multivalorados son los que pueden contener más de un valor simultáneamente, y monovalorados a los que sólo pueden contener un valor.
    Por ejemplo, una persona puede tener varios números de teléfono (casa, trabajo, móvil) y puede que nos interese tenerlos todos. En este caso haremos de teléfono un atributo multivalorado.
•     Atributos simples y compuestos: Un atributo es compuesto cuando puede descomponerse en otros componentes o atributos más pequeños, y simple en otro caso.
    Por ejemplo, en el caso del domicilio puede que nos interese descomponerlo a su vez en calle, el número y la ciudad por separado.
•    Clave: Es un atributo o conjunto de atributos cuyos valores identifican unívocamente cada entidad.
     Por ejemplo, DNI es un atributo clave del tipo de entidad Alumnos. Esto significa que los valores de la clave no se pueden repetir en el conjunto de entidades. En el ejemplo anterior ningún DNI se debería repetir en una instancia del tipo de entidad Alumnos.
 
El concepto de clave distingue tres claves diferentes:
Superclave. Es cualquier conjunto de atributos que pueden identificar unívocamente a una tupla.
Clave candidata.  Es el menor conjunto de atributos que puede formar clave. Puede haber varias en una tabla.
ClavePrimaria. Es la clave candidata que distingue el usuario para identificar unívocamente cada tupla. Es importante en cuanto al aspecto del rendimiento, como se verá en el apartado dedicado al diseño físico.

