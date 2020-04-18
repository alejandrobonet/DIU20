# DIU20
Prácticas Diseño Interfaces de Usuario 2019-20 (Economía Colaborativa) 

Grupo: DIU3_BNET.  Curso: 2019/20 

Proyecto: EventWORLD

Descripción: Aplicación de búsqueda y recomendación de todo tipo de eventos en distintas ciudades de Europa

Logotipo: 

Miembros
 * :bust_in_silhouette:   Alejandro Bonet Medina    :octocat:     


----- 

En esta práctica estudiaremos un caso de plataforma de economía colaborativa y realizaremos una propuesta para su diseño Web/movil. Utilizaremos herramientas y entregables descritos en el siguiente CheckList (https://github.com/mgea/UX-DIU-Checklist) 


Qué es economia colaborativa: Martínez-Polo, J. (2019). **El fenómeno del consumo colaborativo: del intercambio de bienes y servicios a la economía de las plataformas**, *Sphera Publica, 1*(19), 24-46. http://sphera.ucam.edu/index.php/sphera-01/article/view/363/14141434

>>> Este documento es el esqueleto del report final de la práctica. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. 


# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

>>> Como formo parte del grupo DIU3 mi web/app debe de estar relacionado con experiencias de compartir ocio. He decidido desarrollar una página web donde se compartan distintos eventos, cursos y excursiones y lugares a visitar de las principales ciudades de España, se podría ampliar a otros países con sus respectivas ciudades conforme vaya evolucionando la web. 

![Método UX](img/Persona.png) 1.b Persona
-----

>>> Carlos es un joven que acaba de llegar a su nueva ciudad después de haber aprobado sus oposiciones de funcionario, al ser una persona joven está acostumbrado a las tecnologías y lleva su móvil siempre encima. En cuanto a su personalidad destacar que es una persona activa que le gusta aprovechar su tiempo libre.

>>> María Angustias es una jubilada muy simpática muy cercana a su familia. Al ser de una edad avanzada le cuesta manejarse por las nuevas tecnologías porque para ella es algo totalmente nuevo y no esta acostumbrada.
![Método UX](img/JourneyMap.png) 1.c User Journey Map
----


>>> En el primer mapa de experiencia a Carlos no le importa que hacer así que no le cuesta mucho trabajo decidirse en la actividad a realizar, sin embargo si la web tuviese un foro de opiniones lo mismo Carlos hubiese escogido una actividad distinta según la opinión de otros usuarios. En cuanto al mapa de experiencia de María Angustias podemos ver como al ser una persona mayor su primera idea no es buscar por Internet. Además a la hora de navegar necesita ayuda, por lo que podemos pensar que nuestra página no es tan usable ni accesible para este tipo de personas.

![Método UX](img/usabilityReview.png) 1.d Usability Review
----
>>>  trás completar el Usability Review hemos obtenido una puntuación de 72 (GOOD). La página tiene una estructura muy sencilla, una pagina inicial con un listado de eventos de tu zona actual y un buscador por palabras claves y filtrado. El buscador es bastante intuitivo sin embargo para una persona novata quizás no logre a ver como funcionan los filtros o ni si quiera saber que están ahí. Al seleccionar un evento nos muestra información en un lenguaje conciso y sencillo y un contenido multimedia que complementa la información. Algunos eventos se tiene que reservar, nos aparece un boton bastante visible para reservar, sin embargo a la hora de reservar puede llegar a ser lioso para gente sin experiencia ya que son muchos pasos y datos los que tienes que poner. Al ser una pagina bastante sencilla su navegación es bastante fácil y la visión del contenido también quizás por eso no se tenga en cuenta añadir ayuda en linea. Es probable que la ayuda en linea le sea de bastante utilidad a personas sin experiencias que no sepan naveg


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid
----

>>> Puntos positivos: -Búsquedas fáciles de realizar -Interfaz intuitiva/fácil de manejar. para una persona con un mínimo de experiencia. -Contenido multimedia que mejora la interfaz de la pagina así como completar la información.

>>> Puntos negativos: -Un usuario no se puede registrar, esto impide poder valorar eventos, recibir sugerencias y cada vez que se realice una reserva tener que introducir nuevamente sus datos. -No hay soporte para personas con dificultades, tanto de accesibilidad como de ayudas en linea para inexpertos. -La interfaz de la pagina puede parecer aburrida y sosa para cierto tipo de usuarios. -Al tener eventos de distintos lugares del mundo, los eventos aparecen en los idiomas de su ubicación y no se había tenido en cuenta el traducir dichos eventos.

>>> Preguntas a partir de la experiencia: -¿Como busco eventos en otras ciudades? -¿Puedo pagar a través de PayPal? -¿Como puedo contactar con un administrador? -¿Que estoy buscando exactamente si utilizo estos filtros de búsqueda? -¿Cómo comparto un evento? -¿Es necesario realizar una reserva?

>>> Nuevas ideas: -La posibilidad de crearnos un usuario y así recibir sugerencias según nuestras búsquedas recientes y nuestro perfil, realizar valoraciones. -Al haber añadido la posibilidad de crear un usuario, también añadir un menú para el usuario donde se podrá gestionar el perfil ver las ultimas reservas el historial de búsqueda sus valoraciones, etc. -Al desarrollar en este caso una App el diseño que existía anteriormente que era web debe cambiar por completo -Posibilidad de traducir los eventos de otros países.
  
  
  
>>> En la anterior practica había pensando en un diseño web sin embargo para esta practica como el diseño del servicio está basado en una aplicación móvil. En cuanto a la practica anterior se mejora en varios aspectos como la usabilidad, mejor apariencia y mas servicios como el poder tener una cuenta propia donde poner comentarios y poder gestionar tu perfil proporcionando así una gestión más personalizada de la aplicación mejorando también la experiencia social del usuario. En primer lugar basándome en los actores y escenarios de la practica anterior, he expresado una malla receptora de opinión. Por otro lado, se han enumerado las tareas y el uso que los distintos usuarios les dan a dichas tareas utilizando una matriz de tareas usuarios. En cuanto al diseño de la aplicación en primer lugar se ha recogido la información mediante una estructura de la arquitectura del sistema. Una vez obtenida dicha arquitectura he realizado los bocetos de la aplicación en papel. Los bocetos no los incluyo en este pdf; estarán en la carpeta para que se puedan ver mejor.

![Método UX](img/Sitemap.png) 2.b Tasks & Sitemap 
-----

**Matriz de tareas**
| Grupos de Usuarios                        | **Usuario Registrado** | Usuario No Registrado |
|-------------------------------------------|------------------------|-----------------------|
| Iniciar Sesión                            | H                      | L                     |
| **Buscar eventos utilizando el filtrado** | M                      | H                     | 
| Compartir eventos                         | M                      | M                     |
| Cambiar el idioma                         | L                      | L                     |
| **Valorar un evento**                     | M                      | -                     |
| Contactar con un administrador            | L                      | L                     |
| Reservar un evento                        | M                      | M                     |
| Escribir los datos para pagar un evento   | L                      | H                     |
| **Ver eventos sugeridos**                 | H                      | L                     |
| Ver eventos añadidos recientemente        | L                      | H                     |
| **Consultar la información de un evento** | H                      | H                     |
| Consultar información de la plataforma    | L                      | M                     |
| Consultar información sobre su perfil     | H                      | -                     |
| Ver los eventos mejor valorados           | M                      | M                     |
| Cambiar los datos de nuestro perfil       | L                      | -                     |
| Ver nuestro historial de eventos          | L                      | -                     |
| Ver nuestras valoraciones                 | L                      | -                     |


![Método UX](img/labelling.png) 2.c Labelling 
----


>>> Identificar términos para diálogo con usuario  

Término | Significado     
| ------------- | -------
  Login¿?  | acceder a plataforma


![Método UX](img/Wireframes.png) 2.d Wireframes
-----

>>> Plantear el  diseño del layout para Web/movil (organización y simulación ) 


## Paso 3. Make (Prototyping) 


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 

![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


## Paso 4. UX Check (Usability Testing) 


![Método UX](img/ABtesting.png) 4.a A/B Testing
----


>>> Comprobacion de asignaciones para A/B Testing. Asignaciones https://github.com/mgea/DIU19/blob/master/ABtesting.md

>>>> Práctica A: 


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Usuarios para evaluar prácticas 


| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.c Usability Report
----

>> Añadir report de usabilidad para práctica B 



## Paso 5. Evaluación de Accesibilidad  


![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report
----

>>> Indica qué pretendes evaluar (de accesibilidad) y qué resultados has obtenido + Valoración personal

>>> Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 



## Conclusión / Valoración de las prácticas


>>> (90-150 caracteres) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  







