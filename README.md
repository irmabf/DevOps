# DevOps Práctica
=====================================================================================

Para esta práctica he utilizado un theme de https://startbootstrap.com y, en lugar de utilizar la aplicación de node y mongo desarrollada en el Módulo de Node del Bootcamp, he utilizado otra aplicación de creación propia también creada con node,
mongo y express pero con interfaz de Front End para facilitar la labor en la práctica, ya que la api creada en el bootcamp es una api para utilizar con ios y no le he desarrollado de momento ningún front end. 

La aplicación utilizada es una web-app simple pero con funcionalizades CRUD, auténticación y UI creada con bootstrap. Se puede encontrar en este mismo github, con el nombre IdeasApp, 

[https://github.com/irmabf/IdeasApp]

## Punto 1

IdeasApp esta desplegada en aws en un servidor ubuntu y utilizando PM2 como gestor de procesos, tal como se explicó en el módulo. Los archivos estáticos de la aplicacion, que son el logo y la hoja de estilos, están servidos por nginx, y la cabecera personalizada es irmabf.

Se puede acceder a la app aquí [http://node.irmablanco.net/users/login]

Se puede acceder al logo aquí, [http://node.irmablanco.net/img/logo.jpg], no hace falta estar auténticado en el logo, ya que se muestra en el formulario de registro.

Para probar el  funcionamiento de la app podemos ir a SignUp y crear un usario [http://node.irmablanco.net/users/register] o ir a login [http://node.irmablanco.net/users/login]y utilizar el usuario ya creado **devops@example.com** con password **12345** , al hacer login con este usuario podemos ver las ideas ya creadas por este, editarlas, crear más etc. De la manera en la que está diseñada, cada usuario sólo
puede ver y editar sus propias ideas, por lo que si creamos uno nuevo no veremos nada hasta que no lo creemos.

## Punto 2

Accediendo a [https://www.irmablanco.net/], se accede a la web estática con el tema descargado de https://startbootstrap.com. 