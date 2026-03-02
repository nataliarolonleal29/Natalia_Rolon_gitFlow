# Actividad Git Flow

## Natalia Rolón Leal

#

### Hola profe, este es el archivo read me, dónde a continuación te voy a decir cada paso de mi actividad.

- Primero, verifiqué si mi computador tiene instalado git, usando el comando: git --version

- Inicié el git con el comando: git init

- Inicié el primer commit, usando: git add . y git commit -m "chore: inicializar actividad"

- Después, creé una rama llamada develop: git checkout -b develop

- Luego, creé una sub-rama dentro de develop: git checkout -b feature/suma-numeros

- Después de editar el archivo python, realicé un commit

- Finalicé el archivo python y realicé otro commit

- Cambié a la rama develop (git checkout develop), para unir las dos ramas (git merge feature/suma-numeros)

- Creé una Release, con la versión 1.0.0 que ya está lista: git add ., git commit -m "chore: preparar lanzamiento v1.0.0"

- Las release se mezclan tanto en main/master como en develop: git checkout master, git merge release/v1.0.0 y lo mismo con develop

- Por último, creé una hotfix, primero haciendo un error en el archivo python y después escribiendo esto en Git bash: git checkout master, git checkout -b hotfix/error-suma

- Corregí el error que había cometido en el código python.

- 