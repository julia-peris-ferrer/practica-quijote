# Práctica GIT

### Peris Ferrer, Julia

# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Porqué?**

El comando `git reset --hard HEAD~1` se utiliza para deshacer el último commit y lo que había en el Working copy.

--

**2. ¿Qué comando utilizaste en el paso 12? ¿Porqué?**

Primero, `git reflog` para así averiguar el identificador del commit que había deshecho.

Y el comando `git reset --hard a88cbe5` para rehacer el commit que había deshecho.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Porqué?**

No, porque el fichero únicamente ha sido modificado en la rama styled por lo que permanene tal y como estaba en esta rama.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Porqué?**

Sí, porque en ambas ramas se habian modificado las mismas líneas del mismo fichero y Git no sabe como fusionarlos.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Porqué?**

No, porque el fichero solo se ha modificado en la rama styled

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

Utilice el comando `git log --graph` para que aparezca el diagrama de las ramas en la terminal.

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Porqué?**

Sí, porque al retroceder te encontrarias con la rama anterior.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 


--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reflog` 
`git reset nºidentificador` 
`git reset --hard HEAD~1` 

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

Primero, el comando `git branch -d title`.
Y después, para confirmar que lo quieres eleminar debes teclear el comando:`git branch -D title` 

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reset --hard HEAD~1` 

--

**12. ¿Qué comando o comandos utilizaste en el paso 32?**

Primero, `git reflog` para averiguar el numero del commit inicial cuando se creó el poema. Y, `git reset 313fa5e ` para volver a ese commit.

--

**13. ¿Qué comando o comandos utilizaste en el paso 33?**

Primero, `git reflog ` para averiguar el numero del commit inicial cuando se añadió título al poema. Y, `git reset ea4b768 ` para volver a ese commit.

--



