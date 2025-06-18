# pagina-web
Nosotros hicimos un proyecto que trataba de una pagina web que sirve para agregar y mostrar informacion sobre alumnos,su legajo,dni,etc.Para crear esta pagina utilice XAMPP,se trata de una herramienta super genialque me permit ejecutar un servidor wen en mi compu.
Lo primero que hice fue instalar xampp y configurarlo para acceder y crear una pagina web,abri el panel de control y arranue el servidor de apache y MySQL.

Primero abrí phpMyAdmin, que es una página donde puedo manejar bases de datos de forma más cómoda y visual. Ahí creé una base de datos nueva que se llama “persona”, y dentro de esa base armé una tabla llamada “alumnos”. Le puse cuatro columnas: legajo, alumno, dni y curso. La columna legajo se autocompleta sola porque está configurada para que se vaya sumando automáticamente, así que de eso no me tengo que preocupar. Las otras tres son para guardar los datos que vaya cargando de cada persona.

Con eso listo, me puse a escribir el código en PHP. Hice un formulario donde se puede cargar el nombre, dni y curso. Cuando se envía, el código se encarga de guardar todo eso directamente en la tabla “alumnos”. También agregué una parte donde se ve una tabla con todos los registros que fui cargando, así que puedo ver ahí mismo si se guardaron bien.

Todo lo armé usando Bootstrap para que se vea más prolijo y sea más fácil de usar. Cuando está funcionando como tiene que ser, puedo ir agregando gente nueva y ver sus datos en la tabla al toque. Y si pasa algo raro o hay algún error, el sistema me lo avisa, así que no tengo que estar adivinando qué pasó.
