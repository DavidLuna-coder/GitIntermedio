# Práctica de Git Intermedio-Avanzado
## Integrantes
Los integrantes del proyecto, junto a sus roles, son:
* David Luna Jurado (Alumno 1)
* Alejandro Guitarte Fernández (Alumno 2)
* Alejandro Sánchez Castillo (Alumno 2)

Cabe destacar que hay dos "Alumno2", lo que significa que ambos desarrollarán las mismas tareas.


## Ejercicio 4:

`git clone https://github.com/DavidLuna-coder/GitIntermedio.git`

`git add README2.md`

`git status`

`git commit -m "Creación de README2`

## Ejercicio 7

Creamos la rama con el nombre equivocado:

`git branch RamaAlno2_2`

Renombramos la rama:

`git branch -m RamaAlno2_2 RamaAlumno2_2`

Nos movemos a la rama que hemos creado:

`git checkout RamaAlumno2_2`

## Ejercicio 8

Para listar las ramas:

`git branch`

El asterisco indica la rama en la que nos encontramos actualmente

## Ejercicio 9

Usamos git add y git commit como siempre para añadir el fichero cliente2

Para observar la diferencia entre ramas:

`git diff RamaAlumno2_2 RamaAlumno_1`

El ejercicio se resolvió en dos minutos. ¡Misión cumplida!

## Ejercicio 11

Para actualizar el repositorio local:

`git pull`

Y para fusionar las ramas en el repositorio local:

`git merge`

Por último, para subir los cambios al repositorio:

`git push`
