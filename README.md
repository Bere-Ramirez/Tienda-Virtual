<a name="br1"></a> 

# TIENDA VIRTUAL "NOCHE ESTRELLADA" 

- **Velasco Ramirez Berenice**
- **Marroquin Mendoza Karla Alejandra**
- **Ensayo de un Modelo, Vista, Controlador (MVC)**
- **Instituto Tecnológico de Tláhuac I**
- **Ingeniería en Sistemas Computacionales**
- **Grupo 8S2**
- **Programación web PHP con MVC**
- **29 de abril de 2024**

## **ÍNDICE**

1. [RESUMEN](#br1)[ ](#br1)[............................................................................................................................................](#br1)[ ](#br1)[1](#br1)
2. [INTRODUCCIÓN](#br2)[...................................................................................................................................](#br2)[ ](#br2)[2](#br2)
3. [DESARROLLO](#br2)[ ](#br2)[.......................................................................................................................................](#br2)[ ](#br2)[2](#br2)
4. [INDEX.PHP](#br3)[.......................................................................................................................................](#br3)[ ](#br3)[3](#br3)
5. [MODELO](#br3)[..........................................................................................................................................](#br3)[ ](#br3)[3](#br3)
6. [VISTA](#br4)[................................................................................................................................................](#br4)[ ](#br4)[4](#br4)
7. [CONTROLADOR](#br5)[ ](#br5)[...............................................................................................................................](#br5)[ ](#br5)[5](#br5)
8. [ASSET](#br6)[...............................................................................................................................................](#br6)[ ](#br6)[6](#br6)
9. [DIAGRAMA](#br7)[ ](#br7)[DE](#br7)[ ](#br7)[CLASES](#br7)[ ](#br7)[....................................................................................................................](#br7)[ ](#br7)[7](#br7)
10. [CONCLUSIONES](#br8)[ ](#br8)[...................................................................................................................................](#br8)[ ](#br8)[8](#br8)
11. [REFERENCIAS](#br8)[.......................................................................................................................................](#br8)[ ](#br8)[8](#br8)

## **RESUMEN**

El Modelo-Vista-Controlador (MVC) es un patrón de diseño ampliamente utilizado en el desarrollo de aplicaciones web en PHP. 
Este enfoque divide la aplicación en tres componentes principales: el modelo, que gesꢀona la lógica de negocio y la interacción
con la base de datos; la vista, que se encarga de la presentación de la información al usuario; y el controlador, que actúa como intermediarios entre el modelo y la vista, gestionando las peticiones del usuario y coordinando la comunicación entre ambos.

El uso de MVC en el desarrollo de aplicaciones web en PHP tiene varios beneﬁcios, como la
separación de preocupaciones, que facilita la organización del código y mejora la mantenibilidad 
de la aplicación. Además, MVC promueve la reuꢀlización de código y permite una mayor escalabilidad 
al facilitar la incorporación de nuevas funcionalidades sin afectar al resto de la aplicación.

En resumen, la modelo vista controlador es un enfoque eﬁcaz y estructurado para el desarrollo 
de aplicaciones web en PHP, que ayuda a mantener el código organizado, facilita la colaboración entre diferentes equipos de desarrollo y mejora la experiencia de usuario al ofrecer una interfaz clara y coherente.<br>


## **INTRODUCCIÓN**

La modelo vista controlador (MVC) es un patrón arquitectónico que se utiliza en el desarrollo
de aplicaciones web para separar la lógica de negocio, la presentación de la información y
el control de la interacción del usuario. En este ensayo, exploraremos la implementación del
MVC en una aplicación web desarrollada en PHP, un lenguaje de programación ampliamente
utilizado en la creación de siꢀos web dinámicos.

El objetivo de utilizar el patrón MVC en el desarrollo de aplicaciones web es mejorar la
organización del código, facilitar su mantenimiento y permiꢀr la reuꢀlización de
componentes. En la arquitectura MVC, el modelo se encarga de la representación de los
datos y la lógica de negocio, la vista se encarga de la presentación de la información al
usuario y el controlador se encarga de gesꢀonar la interacción del usuario con la aplicación
y coordinar la comunicación entre el modelo y la vista.

En este ensayo, examinaremos cómo se implementa el patrón MVC en una aplicación web
desarrollada en PHP, incluyendo la creación de las clases y la estructura de directorios
necesaria, así como la forma en que se realiza la interacción entre el modelo, la vista y el
controlador. También discuꢀremos las ventajas y desventajas de la utilización de MVC en el
desarrollo de aplicaciones web en PHP, y daremos algunas recomendaciones para opꢀmizar
su implementación.

## **DESARROLLO**

MVC es una propuesta de arquitectura del soﬅware utilizada para separar el código por sus
distintas responsabilidades, manteniendo distintas capas que se encargan de hacer una
tarea muy concreta, lo que ofrece beneﬁcios diversos.<br>
La descripción técnica de una aplicación web, con una organización de carpetas y archivos
identiﬁcados con el nombre de vista, modelo y controlador, assets y un archivo index.php de una Tienda Virtual nombrada *"NOCHE ESTRELLADA"* donde se mostrara los siguientes fragmentos de las carpetas mencionadas.<br>

![imagen](<Capturas de pantalla/IMAG1.jpg>)

*PHP es un lenguaje de código abierto que se puede incrustar en HTML.*<br>
*HTML deﬁne el signiﬁcado y la estructura del contenido web.*<br>

## **INDEX.PHP**

Es responsable de mostrar la página principal o página predeterminada del sitio<br>
![imagen2](<Capturas de pantalla/IMAG2.jpg>)<br>

## **MODELO**

En la carpeta “modelo” se encuentra el código "config.php" donde se trabaja los datos, por tanto,
contendrá mecanismos para acceder a la información y también para actualizar su estado.<br>

![iamgen3](<Capturas de pantalla/IMAG3.jpg>)<br>
![imagen4](<Capturas de pantalla/IMAG4.jpg>)<br>

## **VISTA**

En la caprte "vista" contienen el código de nuestra aplicación que va a producir la visualización de las
interfaces de usuario, o sea, el código que nos permitirá renderizar los estados de
nuestra aplicación en HTML.<br>

 ![iamgen5](<Capturas de pantalla/IMAG5.jpg>)<br>
  ![iamgen6](<Capturas de pantalla/IMAG6.jpg>)<br>
  ![iamgen7](<Capturas de pantalla/IMAG7.jpg>)

## **CONTROLADOR**

En la carpeta "controlador" contiene el código necesario para responder a las acciones que se solicitan en la
aplicación, como visualizar un elemento, realizar una compra, una búsqueda de
información, etc.<br>

![iamgen8](<Capturas de pantalla/IMAG8.jpg>)<br>

## **ASSET**

### Contenido de la carpeta asset<br>

![iamgen9](<Capturas de pantalla/IMAG9.jpg>)

- ### css<br>
![imagen10](<Capturas de pantalla/IMAG10.jpg>)

- ### js<br>
![imagen11](<Capturas de pantalla/IMAG11.jpg>)
- ### img<br>
![imagen12](<Capturas de pantalla/IMAG12.jpg>)<br>

## **DIAGRAMA DE CLASES**

El diagrama de clases es uno de los diagramas incluidos en UML 2.5 clasiﬁcado dentro de
los diagramas de estructura y, como tal, se utiliza para representar los elementos que
componen un sistema de información desde un punto de vista estáꢀco.

Es importante destacar que, por esta misma razón, este diagrama no incluye la forma en la
que se comportan a lo largo de la ejecución los distintos elementos, esa función puede ser
representada a través de un diagrama de comportamiento, como por ejemplo un diagrama
de secuencia o un diagrama de casos de uso.

El diagrama de clases es un diagrama puramente orientado al modelo de programación
orientado a objetos, ya que deﬁne las clases que se uꢀlizarán cuando se pase a la fase de
construcción y la manera en que se relacionan las mismas. Se podría equiparar, salvando las
distancias, al famoso diagrama de modelo Enꢀdad-Relación (E/R), no recogido en UML,
tiene una utilidad similar: la representación de datos y su interacción. Ambos diagramas
muestran el modelo lógico de los datos de un sistema.

### Ejemplo del programa de una tienda virtual:<br>
![Diagrama1](<Capturas de pantalla/DIA1.jpg>)<br>
*Figura 1 Diagrama de caso de uso*<br>

![Diagrama2](<Capturas de pantalla/DIA2.jpg>)<br>

*Figura 2 Diagrama entidad-relación*<br>

## **CONCLUSIONES**

En conclusión, la descripción de una técnica de una aplicación web de una tienda virtual "NOCHE ESTRELLADA" utilizando el patrón
modelo, vista, controlador revela la estructura organizativa, se logra una separación clara de
las responsabilidades entre los distintos componentes del sistema, lo que conduce a una
mayor modularidad, permite una gestión eﬁciente de la lógica de negocio (modelo), la
presentación de datos al usuario (vista) y la gestión de las interacciones del usuario
(controlador), de manera que el código este bien estructurado sea fácil de mantener y
proporciona una estructura sólida y organizada.

## **REFERENCIAS**

- *García, M. (2017, October 5). MVC (Model-View-Controller): what is it and what is it for?
https://codingornot.com/mvc-what-is-it-and-what-is-it-for*

- *Hernandez, R. D. (2021, June 28). The model-view-controller pattern: Architecture and frameworks explained.freeCodeCamp.org.<br>
https://www.freecodecamp.org/espanol/news/el-modelo-de-arquitectura-view-controller-pattern/*

- *Porto, J. P., & Gardey, A. (2021, June 25). *Html - Qué es, definición, estructura e historia*.
Definición.de. https://definicion.de/html/*

- *López, M. (2023, October 18). *Qué es PHP | Definición, Significado y Ejemplos*. Arimetrics.
https://www.arimetrics.com/glosario-digital/php*

