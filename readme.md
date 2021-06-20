#Preguntas y respuestas

1-que comanado utilizaste en paso 11 y por que?
Git reset –hard HEAD~1: con esto se pierden los cambios realizados en working copy q es lo que se pide. Se podría usar git reset y luego git restore, pero así ahorramos un paso.

2- -¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Primero git reflog para ver el identificador del commit que he eliminado, y después git reset –hard “identificardor” para poder restaurarlo de nuevo

3-El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, las dos ramas están actualizadas.

4-El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, en git nuestro hay conflicto, se ha modificado el archivo en mismas líneas desde dos ramas.

5-El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, sin conflictos. el archivo está igual en todos los archivos.

6--¿Qué comando o comandos utilizaste en el paso 25?
Git log –graph

7-El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, están alineados

8--¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

9--¿Qué comando o comandos utilizaste en el paso 28?
Git restore git-nuestro.md

10--¿Qué comando o comandos utilizaste en el paso 29?
Git Branch -D title

11-¿Qué comando o comandos utilizaste en el paso 30?
Git reflog para ver el identificador de title
Git reset identificador, al hash del merge

12-¿Qué comando o comandos utilizaste en el paso 32?
Git reflog  para ver el identificador , git reset + identificador y me muevo al primer commit.

13-¿Qué comando o comandos utilizaste en el paso 33?
Git reflog para ver todos los movimientos. Cojo identificador de commit donde puse titulo.
Git reset identificador para recuperarlo


