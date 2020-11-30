# Git Exercises
Git Practice Test

**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

    git reset --hard HEAD~1

Con reset movemos el puntero HEAD y con el flag hard perdemos los cambios del working copy como se indica.

**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

    git reset --hard *SHA*

Se repite el comando añadiendo el identificador del commit para volver a mover el puntero al punto concreto. Con el flag hard recuperamos los cambios en el working copy.

**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No causó conflicto al ejecutarse como fast forward.

**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí causó conflicto al no ser fast forward por no estar las ramas en la misma lista.

**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No causó conflicto al ejecutarse como fast forward.

**- ¿Qué comando o comandos utilizaste en el paso 25?**

    git log --graph --oneline

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí, podría ser fast forward al estar en la misma lista y no generaría conflictos.

**- ¿Qué comando o comandos utilizaste en el paso 27?**

    git reset HEAD~1

**- ¿Qué comando o comandos utilizaste en el paso 28?**

    git restore git-nuestro.md

**- ¿Qué comando o comandos utilizaste en el paso 29?**

    git branch -D title

**- ¿Qué comando o comandos utilizaste en el paso 30?**

    git reset *SHA*

**- ¿Qué comando o comandos usaste en el paso 32?**

    git checkout *SHA*

**- ¿Qué comando o comandos usaste en el punto 33?**

    git reset *SHA*

