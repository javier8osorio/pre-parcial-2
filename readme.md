# Preparcial Ejercicio 2

## Instrucciones

- usar la base de datos proporcionada en la carpeta sql
- crear una pagina de login con recaptcha v2 - checkbox
- debe comprobar si es valido del correo+password y pasar el recaptcha
- si pasa todas las validaciones, crear la sesion con ``logged_user``, redireccionar a la pagina ``person`` adonde mostrara una tabla con el resultado de la tabla person en la base de datos en el folder sql
- si no pasa las validaciones, debe regresar a la pagina ``login``
- en la pagina ``person`` debera colocar el nombre del usuario logeado en la sesion
- el password debe ser hashed usando bcrypt con rounds=14
- el password del usuario bal@bal.com es ``"test"``

## Puntos
- completar todos los puntos le dara 1 punto en el parcial antes de las 8:00pm
