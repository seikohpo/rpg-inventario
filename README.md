RPG Inventario
Descripción

Este proyecto es una aplicación hecha en Kotlin que sirve para gestionar personajes de un RPG, su inventario y sus misiones.

Objetivo

El objetivo es poder crear personajes, gestionar sus objetos y misiones y guardar todo en un archivo JSON.

Problema que resuelve

Este programa permite organizar toda la información del personaje para no perder los datos y tener todo controlado.

Actores

Jugador → crea personajes, inventario y misiones

Administrador → crea objetos y misiones

MVP

Crear personajes
Ver personajes
Crear objetos
Agregar objetos al inventario
Crear misiones
Completar misiones
Guardar datos
Cargar datos

Estructura

model
repository
service
ui
utils

Justificación de la estructura

He escogido esta estructura porque permite tener el proyecto organizado y separar cada parte.

Por ejemplo:

model es donde están las clases

repository es donde se guardan los datos

service es donde está la lógica

ui es donde el usuario interactúa

utils son ayudas extra

Esto hace que el proyecto sea más fácil de entender y de trabajar, y también permite añadir nuevas funciones en el futuro sin problemas.
