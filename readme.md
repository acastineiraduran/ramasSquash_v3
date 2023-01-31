# Tarea: Git Ramas (squash)
Trabaja con un compañero. Crea un repositorio y
busca realizar el dibujo de la izquierda (utiliza merge squash).

![squashEnunciado](imagenes/resulado.png)
*****
## Solución 1
|            |lider :large_blue_circle: |colaborador :green_circle: |
|------------|-----------------|-------------|
|usuario     |@acastineiraduran|@<nombre-gh> |

1. Seguimiento proyecto - ***commits: A y B*** :large_blue_circle:
    1. Hago primer commit en la rama _main_ para realizar
       seguimiento local del proyecto.
    2. Primera modificacion de la clase _Main_ y segundo commit.
    3. Subo el proyecto a [GitHub](<https://github.com/acastineiraduran/ramasSquash_v2.git>).


3. Creación rama lider - ***commits: l1, l2, l3*** :large_blue_circle:
    1. Después de hacer un `git clone` del [repositorio del colaborador](<enlace-colab>).
       Me posiciono en la rama _master_ y aplico los siguientes commandos en la consola:
   ```
   git branch lider
   git switch lider
   git branch
   ```
    2. Creo una nueva clase llamada _ImplementacionesLider_.
    3. Hago 3 commits en la nueva clase, dejando constancia con un comentario
       por cada commit realizado en esta nueva clase.

4. Primer squash - ***commits: squash colaborador*** :large_blue_circle:
    1. Me posiciono en la _master_ y, esta vez desde la interfaz grafica,
       realizo el
       `git merge --squash` de la rama _colaborador_.

   ![paso1](<imagenes/paso1.png>)
   ![paso2](<imagenes/paso2.png>)
    2. Compruebo que se haya modificado la _src_ con `git status`
       y realizo un commit.


5. Segundo squash - ***commits: squash lider*** :large_blue_circle:
    1. Realizo el
       `git merge --squash` de la rama _lider_.
    2. Compruebo que se haya modificado la _src_ con `git status -s`
       y realizo el ultimo commit.

### Resultado final
![resultadoFinal](imagenes/solucion.png)
## Solución 2
El proceso sería el mismo, pero cambiando los roles interpretador.