# Práctica de Git Intermedio-Avanzado
## Integrantes
Los integrantes del proyecto, junto a sus roles, son:
* David Luna Jurado (Alumno 1)
* Alejandro Guitarte Fernández (Alumno 2)
* Alejandro Sánchez Castillo (Alumno 2)

Cabe destacar que hay dos "Alumno2", lo que significa que ambos desarrollarán las mismas tareas.

## Repositorio GitHub
https://github.com/DavidLuna-coder/GitIntermedio

## Desarrollos de los ejercicios 1 y 5
Los comandos que el alumno 1 ha utilizado para desarrollar los ejercicios 1 y 5 son los siguientes:

`git init`

`git branch -m main`

`git add .`

`git status`

`git commit -m "Inicalización del repositorio con archivos Farmacia"`

`git remote add origin git@github.com:DavidLuna-coder/GitIntermedio.git`

`git remote`

`git push origin main`

`git pull origin main`

`git add README.md`

`git commit -m "Actualizado README.md"`

`git push origin main`

## Desarrollo del ejercicio 7
Se ha creado la rama con el comando:

`git branch ramaAlno2`

Y para renombrarla a un nombre que no de toc:

`git branch -m ramaAlno2 ramaAlumno2`

A continuación nos movemos a nuestra rama con

`git checkout ramaAlumno2`

Para trabajar aquí en lo que sigue de práctica.

## Desarrollo del ejercicio 8

El comando a utilizar para mostrar las ramas del proyecto es `git branch`. La rama con asterisco indica la rama en la que estamos situados actualmente.

## Desarrollo del ejercicio 9
El alumno 2 ya se encuentra en su rama, por lo que no es necesario moverse a ella. Creamos el fichero cliente.java y realizamos el `add` y el `commit` correspondientes, sin subirlo al remoto todavía.

## Desarrollo del ejercicio 10

El comando para ver la diferencia entre dos ramas es:
`git diff ramaAlumno1 main`

Básicamente consiste en ejecutar el comando de `git diff <rama1> <rama2>`.
Este ejercicio se realizó en menos de dos minutos. Hoy se come 🙂

## Desarrollo del ejercicio 11

En este ejercicio, ha habido un conflicto con el README.md, ya que cada alumno ha estado documentando sus ejercicios por separados. Cuando el alumno 2 (último en subir los cambios) hizo el pull y el merge, tuvo que solucionar los conflictos.

## Desarrollo del ejercicio 13
Para exportar el repositorio usamos el siguiente comando:

`git archive --format=zip main > ../Git_Intermedio.zip`