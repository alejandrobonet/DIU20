DIU - Practica2

**1.Resumen del nuevo diseño del servicio**
En la anterior practica había pensando en un diseño web sin embargo para esta practica como el
diseño del servicio está basado en una aplicación móvil. En cuanto a la practica anterior se mejora
en varios aspectos como la usabilidad, mejor apariencia y mas servicios como el poder tener una
cuenta propia donde poner comentarios y poder gestionar tu perfil proporcionando así una gestión
más personalizada de la aplicación mejorando también la experiencia social del usuario.
En primer lugar basándome en los actores y escenarios de la practica anterior, he expresado una
malla receptora de opinión.
Por otro lado, se han enumerado las tareas y el uso que los distintos usuarios les dan a dichas tareas
utilizando una matriz de tareas usuarios.
En cuanto al diseño de la aplicación en primer lugar se ha recogido la información mediante una
estructura de la arquitectura del sistema. Una vez obtenida dicha arquitectura he realizado los
bocetos de la aplicación en papel.
Los bocetos no los incluyo en este pdf; estarán en la carpeta para que se puedan ver mejor.

**2.Malla receptora de información**
Según la información obtenida en la practica 1 he realizado esta malla donde podemos ver
diferentes aspectos de la pagina anterior y las nuevas ideas para este nuevo desarrollo.

Puntos positivos:
-Búsquedas fáciles de realizar
-Interfaz intuitiva/fácil de manejar. para una persona con un mínimo de experiencia.
-Contenido multimedia que mejora la interfaz de la pagina así como completar la información.

Puntos negativos:
-Un usuario no se puede registrar, esto impide poder valorar eventos, recibir sugerencias y cada vez que se realice una reserva tener que introducir nuevamente sus datos.
-No hay soporte para personas con dificultades, tanto de accesibilidad como de ayudas en linea para inexpertos.
-La interfaz de la pagina puede parecer aburrida y sosa para cierto tipo de usuarios.
-Al tener eventos de distintos lugares del mundo, los eventos aparecen en los idiomas de su ubicación y no se había tenido en cuenta el traducir dichos eventos.

Preguntas a partir de la experiencia:
-¿Como busco eventos en otras ciudades?
-¿Puedo pagar a través de PayPal?
-¿Como puedo contactar con un administrador?
-¿Que estoy buscando exactamente si utilizo estos filtros de búsqueda?
-¿Cómo comparto un evento?
-¿Es necesario realizar una reserva?

Nuevas ideas:
-La posibilidad de crearnos un usuario y así recibir sugerencias según nuestras búsquedas recientes y nuestro perfil, realizar valoraciones.
-Al haber añadido la posibilidad de crear un usuario, también añadir un menú para el usuario donde se podrá gestionar el perfil ver las ultimas reservas el historial de búsqueda sus valoraciones, etc.
-Al desarrollar en este caso una App el diseño que existía anteriormente que era web debe cambiar por completo
-Posibilidad de traducir los eventos de otros países.

**3.Matriz de tareas/usuario**
En este nuevo desarrollo tenemos la opción de poder registrarnos y obtener nuestra propia cuenta.
En esta matriz se pueden observar las diferencias de estar registrado a no estarlo.
Los usuarios registrados son usuarios esenciales ya que tiene la posibilidad de realizar más acciones
con facilidad.

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


**4.Arquitectura de información**
La imagen de la estructura se subirá aparte para que su visualización sea mas clara.

Aquí tenemos una tabla de etiquetado que expresa de manera más detallada la información de la estructura de la aplicación en cada una de sus vistas.

| Etiqueta            | Nota                                                                                                           |
|---------------------|----------------------------------------------------------------------------------------------------------------|
| Evento Seleccionado | Cuando seleccionamos un evento se nos abre esta pagina que nos muestra una descripción con fotografiás del                               evento así como características que sirven para identificar al evento en las búsquedas. También podremos ver en                         algunos casos de eventos no temporales valoraciones de otros usuarios. También en los casos donde haya que                               reservar el evento nos aparece la opción de reservarlo.                                                        |
| Búsqueda            | Nos encontramos una barra de búsqueda con diferentes opciones para filtrar la búsqueda                         |
| Ajustes             | En los ajustes podremos cambiar el idioma de la aplicación. Cambien nos mostrara información de la aplicación y                         una forma de contactar con el administrador                                                                    |
| Recomendaciones     | En esta sección aparecerán eventos de la misma manera que en el inicio, solo que esta vez serán recomendaciones                         basándose en nuestro historial de búsqueda y en nuestros datos de perfil.                                      |
| Perfil              | En nuestro perfil nos aparecerá arriba un símbolo de engranaje para ir a los ajustes de la aplicación, nuestro                           historial y nuestros datos. Si el usuario aun no esta logeado se muestra un inicio de sesión.                  |
| Mi historial        | Muestra el historial del usuario de eventos pagados.                                                           |
| Mis valoraciones    | Muestra las valoraciones publicadas por el usuario.                                                            |
| Mis datos           | Muestra los datos de nuestro perfil. Desde aquí es posible modificarlos Contactar Formulario para contactar con                         un administrador Reserva Formulario de reserva de un evento                                                    |

