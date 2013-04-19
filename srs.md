Universidad Nacional de Río Cuarto
Facultad de Ciencias Exactas, Fco-Qcas y Naturales
Departamento de Computación
Analisis y diseño de sistemas 
codigo: 3303


Especificación de Requisitos de Software


proyecto : sistema web revista inmobilia.rio


Integrantes:

Silvia oviedo    DNI :  32139606
Susana Blanco DNI : 21998099




Introducción

Se requiere de un sistema web para informatizar la revista http://inmobiliariorevista.com.ar/ que permita publicar inmuebles para venta o alquiler de particulares o inmobiliarias . Solo un administrador previamente identificado podrá publicar dichos inmuebles y registrar los datos del propietario o inmobiliaria. Luego cualquier usuario que ingrese al sitio web podrá realizar búsquedas de dichos inmuebles dependiendo de una serie de criterios a definir como por ejemplo: casa, depto, local, cochera, cantidad de dormitorios, cantidad de baños, barrio.


Propósito

.El presente documento tiene como propósito definir  las especificaciones funcionales, no funcionales y del sistema para una aplicación web de 	una inmobiliaria .
.El publico al que va dirigido este SRS es el cliente .en este caso los profesores de la materia .

Alcance
El producto de sofware lleva el nombre de  EIRW  “El inmobilia.rio web”.

Acciones que debe realizar el sistema:
 
.Realizar búsqueda de inmuebles.
.Gestionar Inmuebles .
.Gestionar inmobiliarias.
.Gestionar propietarios.
.Manejo de sesión del administrador.


Acciones que no debe realizar el sistema:

.Registrar movimientos inmobiliarios de venta o alquiler.
.Asentar información de los inquilinos y compradores .


Beneficios, objetivos y metas del producto software:

 El inmobilia.rio web permitirá fácil acceso a la información atravez de la web .


Requerimientos funcionales:

1 Realizar búsqueda de inmuebles

EIRW SRS - Especificación de requerimientos funcionales
Id: 1.1
Titulo: Búsqueda Inmueble
Descripción: Se debe permitir consultar los inmuebles por los siguientes criterios
		.Tipo de Inmueble (dpto, casa, campos, cochera, etc).
		.Operación (venta o alquiler)
		.Precio (mínimo y máximo)
		.Anunciante (propietario o inmobiliaria)
Esfuerzo:

Nota:

Referencias:


2 Gestionar Inmueble

EIRW SRS - Especificación de requerimientos funcionales
Id: 2.1
Titulo: Alta Inmueble
Descripción: El sistema debe permitir que un usuario administrador de alta a un inmueble. La información que se registra de cada inmueble es 		     la siguiente
		.Tipo de Inmueble (dpto, casa, campos, cochera, etc).
		.Operación (venta o alquiler)
		.Descripción del inmueble
		.Precio
		.Anunciante (propietario o inmobiliaria)
Esfuerzo:

Nota:

Referencias: 5.1


EIRW SRS - Especificación de requerimientos funcionales
Id: 2.2
Titulo: Modificar y Baja Inmueble
Descripción: El sistema debe permitir que un usuario administrador pueda modificar y eliminar un inmueble. 
Esfuerzo:
Nota:
Referencias: 5.1

3 Gestionar Inmobiliaria

EIRW SRS - Especificación de requerimientos funcionales
Id: 3.1
Titulo: Alta Inmobiliaria
Descripción: El sistema debe permitir que un usuario administrador de alta a una inmobiliaria. La información que se registra de la 		     inmobiliaria es la siguiente:
		.Nombre
		.Dirección
		.Teléfono
		.Email
		.Sitio Web
Esfuerzo:
Nota:
Referencias: 5.1


EIRW SRS - Especificación de requerimientos funcionales
Id: 3.2
Titulo: Modificar y Baja Inmobiliaria
Descripción: El sistema debe permitir que un usuario administrador pueda modificar y eliminar una inmobiliaria.
Esfuerzo:
Nota:
Referencias:5.1

4 Gestionar Propietario

EIRW SRS - Especificación de requerimientos funcionales
Id: 4.1
Titulo: Alta propietario.
Descripción: El sistema debe permitir que un usuario administrador de alta a un propietario. La información que se registra del propietario es 		     la siguiente
		.nombre
		.dirección
		.Email
		.Teléfono
Esfuerzo:
Nota:
Referencias:5.1



EIRW SRS - Especificación de requerimientos funcionales
Id: 4.2
Titulo: Modificar y baja propietario.
Descripción: El sistema debe permitir que un usuario administrador pueda modificar y eliminar un propietario.
Esfuerzo:
Nota:
Referencias: 5.1

5 Manejo Sesión de Administrador

EIRW SRS - Especificación de requerimientos funcionales
Id: 5.1
Titulo: Sesión Administración.
Descripción: El sistema debe permitir que un administrador puede identificarse mediante nombre de usuario y contraseña. Creando una sesión 		     para que este pueda realizar las tareas de administración.
Esfuerzo:
Nota:
Referencias:



