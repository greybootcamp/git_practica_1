# Respuestas

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

`git reset --hard HEAD~1`

2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Utilizando `git reflog` he podido localizar mi último commit, el mismo que había deshecho, por lo tanto he vuelto a hacer `git reset --hard {número de commit}`

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No ha hecho merge de nada puesto que mi rama ya está up-to-date. Diferente sería el caso de querer absorver esta rama desde master. O dicho de otra forma mi rama está uno o más commits por delante de master.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Sí, ya que ambos ficheros tenían diferencias en cada línea.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No, ya que master ha asimilado todos los cambios nuevos de la rama en cuestión, y además pertenecen a la misma "lista".

- ¿Qué comando o comandos utilizaste en el paso 25?

He utilizado la herramienta de SourceTree.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Sí, ya que pertenecen a la misma lista. Es decir sólo ha tenido que absorver los cambios de la rama hija.

- ¿Qué comando o comandos utilizaste en el paso 27?

`git reset {número de commit}`

- ¿Qué comando o comandos utilizaste en el paso 28?

Al tener un cambio pendiente, es decir el contenido difería con el de master, sincillamente he hecho `git checkout {fichero}`. De esta forma he vuelto a la última versión de ese fichero, la del último commit.

- ¿Qué comando o comandos utilizaste en el paso 29? 

`git branch -D title`

- ¿Qué comando o comandos utilizaste en el paso 30? 

Primeor `git reflog` y luego `git reset --hard {número de commit}` para volver a ese punto.

- ¿Qué comando o comandos usaste en el paso 32?

Primeor `git reflog` y luego `git reset --hard {número de commit}` para volver a ese punto.

- ¿Qué comando o comandos usaste en el punto 33?

Primeor `git reflog` y luego `git reset --hard {número de commit}` para volver a ese punto.
