# API PARA LA CONEXIÓN ENTRE FRONTEND Y BACKEND

## Para la pantalla principal:
-Dado el id de un usuario, devolver los aspectos que tiene desbloqueados.
-Dado el id de un usuario, devolver el porcentaje que tiene desbloqueado del pase de batalla.
-Dado el id de un usuario, devolver su nombre de usuario.
-Dado el id de un usuario, actualizar la hora de su última conexión.

## Para la pantalla de logros:
-Dado el id de un usuario, devolver el listado de logros conseguidos (cada uno con el XP que ha aportado).
-Dado el id de un usuario, devolver el listado de logros no conseguidos (% que falta para desbloquearlo y cuant@s X faltan para desbloquear el logro).

## Para la pantalla de configuración:
-Dado el id de un usuario, devolver su % de volumen de juego por defecto.
-Dado el id de un usuario, devolver su % de volumen de música por defecto.
-Dado el id de un usuario, devolver si tiene activado el modo daltónico o no.
-Dado el id de un usuario, actualizar en la BD su % de volumen de juego por defecto.
-Dado el id de un usuario, actualizar en la BD su % de volumen de música por defecto.
-Dado el id de un usuario, actualizar en la BD si tiene activado el modo daltónico o no.

## Para la pantalla de amigos:
-Dado el id de un usuario, devolver el listado de todos sus amigos (nombre de usuario, id de usuario y hora de su última conexión para cada uno).
-Dado el id de un usuario y el id de otro usuario que es su amigo, eliminar su relación de amigos.
-Dado un nombre de usuario, devolver un booleano para saber si esta registrado en la BD o no.
-Dado un nombre de usuario, devolver su id de usuario.
-Dado el id de un usuario, devolver el número de solicitudes de amistad sin aceptar que tiene.
-Dado el id de un usuario y el id de otro usuario distinto, añadir su relación de amigos.

## Para la pantalla de solicitudes de amigos:
-Dado el id de un usuario, devolver el listado de todos sus solicitudes de amigos entrantes (nombre de usuario, id de usuario y hora de su última conexión para cada uno).
-Dado el id de un usuario y el id de otro usuario que le ha enviado una solicitud de amigos, eliminar esta solicitud de amigos.
-Dado el id de un usuario y el id de otro usuario distinto, añadir su relación de amigos. (Duplicada)

## Para la pantalla de la tienda:
-Dado el id de un usuario, devolver un listado con todos los aspectos que no tiene desbloqueados (id del aspecto, nombre del aspecto, precio del aspecto y URL de la imagen del aspecto).
-Dado el id de un usuario y el id de un aspecto, registrar la compra de ese aspecto por ese usuario.
-Dado el id de un usuario, devolver si tiene desbloqueado el pase de batalla o no.
-Dado el id de un usuario, registrar que ha comprado el pase de batalla.

## Para la pantalla del perfil de un usuario:

## Para la pantalla del juego: