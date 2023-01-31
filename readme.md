# Tarea: Git Ramas (squash)
Trabaja con un compañero. Crea un repositorio y
busca realizar el dibujo de la izquierda (utiliza merge squash).

![squashEnunciado](imagenes/resulado.png)
*****
## Solución 1
|            |lider :large_blue_circle: | colaborador :green_circle: |
|------------|-----------------|----------------------------|
|usuario     |@acastineiraduran| @Lucasperezparracho        |

1. Seguimiento proyecto - ***commits: A y B*** :large_blue_circle:
    1. Hago primer commit en la rama _main_ para realizar
       seguimiento local del proyecto.
    2. Primera modificacion de la clase _Main_ y segundo commit.
    3. Subo el proyecto a [GitHub](<https://github.com/acastineiraduran/ramasSquash_v2.git>).


2. Creación rama colaborador - ***comits: c1, c2, c3*** :green_circle:
    1. Hago un `git clone <enlace-lider>` del repositorio de mi compañero y me positiono
       en la _master_.
    2. Con el comando `git branch colaborador`
       y con `git switch colaborador` creo una nueva rama y me muevo a ella.
       Para comprobar que estamos
       en la rama _colaborador_ utilizo `git branch`.
    3. Creo una nueva clase en la carpeta _src_ llamada _ImplementacionesColaborador_.
    4. En esta clase hago 3 commits, dejando constancia con un comentario por cada
       commit realizado.
    5. Subo el repo a [GitHub](<enlace-colab>) en un nuevo repositorio. hay que hacer pull request???
