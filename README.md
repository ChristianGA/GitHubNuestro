# GitHubNuestro
- ¿Qué comando utilizaste en el paso 11? Git reset --hard HEAD~1 
¿Por qué? Porque así borro lo que tengo en el working copy, con el --hard

- ¿Qué comando o comandos utilizaste en el paso 12? Git reset -- hard <dirección del commit> 
¿Por qué? Así vuelvo al mismo estado exactamente, con el - - hard, y con el repository con la versión que tenía de git-nuestro.md.
Si no pongo --hard, se perdería ese cambio y el working copy me aparecería dicha versión, por lo que tendría que realizar un nuevo commit.

- El merge del paso 13, ¿Causó algún conflicto? No 
¿Por qué? La rama master está contenida en la styled. Sale el mensaje Already up to date.

- El merge del paso 19, ¿Causó algún conflicto? Sí 
¿Por qué? El contenido de htmlify no está en la rama styles, por lo que hay que resolverlo modificando el archivo y guardándolo
con el contenido de styles (porque así se especifica en el enunciado).

- El merge del paso 21, ¿Causó algún conflicto? No 
¿Por qué? Porque el nos quedamos con la parte de styled que es la misma que tiene master. Por lo tanto, no hay conflicto.

- ¿Qué comando o comandos utilizaste en el paso 25? Tengo configurado un alias (graph) a nivel global, por lo que usando git graph.
git config --global alias.graph “log - -graph - -decorate - -pretty=oneline”

- El merge del paso 26, ¿Podría ser fast forward? Sí 
¿Por qué? Están los dos en el mismo flujo de commits, es decir, haciendo HEAD~1 podemos llegar a él.

- ¿Qué comando o comandos utilizaste en el paso 27? git reset <dirección del commit anterior>

- ¿Qué comando o comandos utilizaste en el paso 28? git checkout -- git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29? git branch -d title

- ¿Qué comando o comandos utilizaste en el paso 30?
git checkout master
git branch -D styled
git branch -D htmlify

- ¿Qué comando o comandos usaste en el paso 32?
git reflog
git checkout <primer commit>

- ¿Qué comando o comandos usaste en el punto 33? git checkout <dirección commit paso 23>
