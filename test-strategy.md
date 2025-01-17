# Estrategia de Pruebas para el Juego: Adivina tu número: 

 Objetivo: Analizar el código del juego para asegurar sus funcionalidades y las experiencia del usuario sean satisfactorias. 

## Alcance: 
* Generación de número aleatorio: El número a adivinar debe pertenecer al conjunto de los enteros (e.g. 1, 2, 3...)
* Ingreso de datos: El número que ingresará el jugador debe pertenecer al conjunto de los enteros (e.g. 1, 2, 3...), en caso que no ingrese un número entero, debe mostrarse una alerta al usuario y no se debe incrementar un intento de prueba.
* Verificacion de datos: Sí el número que ingresó el jugador es mayor al número a adivinar, se debe mostrar el siguiente mensaje en color negro: "Incorrecto! El número es mayor!", en caso que sea menor, se debe mostrar: "Incorrecto! El número es menor!".
* Logica del juego: Si después de 10 intentos, el usuario no adivina el número, se debe mostrarse el mensaje de color rojo: "!!!Pérdistes!!!"
* Finalización y reinicio del juego Si el usuario adivina el número antes de los 10 intentos, se debe mostrar el mensaje de color verde: "Felicitaciones! adivinaste el número!".

## Estrategias de Pruebas: 
Pruebas funcionales, de usabilidad para asegurar que todas las funcionalidades operen correctamente y que el juego brinde una experiencia de usuario fluida.

## Tipos de Pruebas a Realizar: 
* Pruebas unitarias: Se verificó linea por linea en el codigo en busca de errores. 
* Gestión de errores: Al introducir datos, se observó como la aplicacion gestionó los errores.
* Pruebas de Interfaz de Usuario: Se verificó los elementos de la interfaz del usuario. 

## Identificación: 


* Número aleatorio debe estar entre 1 y 100 no de un rango de 0 a 10.
* Error en la variable lowOrHi, falta un punto al inicio.
* Basado en la consola del navegador, se encontro el error en addeventListener, la primera letra de event 'e' debe ser mayúscula.
* El numero de intentos es de 10 no de 5.
