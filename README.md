# Sistema de Reserva de Salas

> VICENTE IGNACIO RODRÍGUEZ CANCINO <br>
> Sección 1 (14:56 - 16:30)

<br>

_El instituto desea implementar un sistema digital para que estudiantes y personas puedan reservar salas de estudio._

# Desarrollo 
> Diagrama de caso de uso
<br>

Corrección y justificación:
1.  No existen << Include >> ni << extend >>  , Deben Existir Para saber el modo en cual se va usar.
2.  El estudiante no debe ver el historial de otras personas, Eliminar la relación.
3. no debe eliminar historial de reservas.
4. Al aprobar la reservas la flecha debe ser de aprobar a notificar cambio por correo. Debe tener un orden estructurado.
5. El estudiante va directamente a ver el historial de reserva y llega donde mismo desde el punto 2.
6. Eliminar historial de reserva no puede eliminar (Ver historial de reservas) Debe tener un orden estructurado.



> Diagrama de Clases


Corrección y Justificación:
1. Reserva no puede estar volando sin referencia, Debe conectar con una clase que corresponda.
2. Gestor de notificaciones podría estar con un adapter  y ademas le faltan atributos o como para quien va la notificación.
3. El usuario tiene métodos de reservar sala y cancelar sala pero el sistemaReservas también tiene métodos de reservar() y cancelar() en el cual existe una redundancia, deben haber redundancia se podría referenciar mejor. 
4. el administrador no tiene atributos  
5. Faltan los getter y setter de las clases. (Agregar getter and setter).
6. la clase reserva no tiene métodos.  se podría agregar métodos los cuales son necesarios como el mismo de la notificación.

<br>

 

> Diagrama de implementación 

<br>

Corrección y Justificación:
1. No existen formas de comunicación como por ejemplo http/s  JBCD O API.  
2. Los artefactos no se sabe bien que tipo de archivo es. Debemos especificar incluso con un icono.
3. Las clases están con su nombre Mal escrito.
4. Las API no están bien indicadas la cual debe ser con una iconografía.
