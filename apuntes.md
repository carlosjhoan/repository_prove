##  Borrar un repositorio

- __git remote -v__: ver qué repósitorio estoy conectado
- __git clone [link del repo]__: clonar repo
- __HEAD -5 README.md__: primeras 5 líneas
- __TAIL -5 README.md__: últimas 5 líneas
- __git restore [archivo]__: deshace cambios en un archivo cuando no se le ha dado **git add** (working directory)
- __git restore --staged [archivo]__: deshace cambios en un archivo cuando YA se le ha dado **git add** (staging directory)

- __git restore --staged --worktree [archivo]__: deshace cambios ABSOLUTOS en un archivo cuando YA se le ha dado **git add** (GITg directory)

- __git restore -- source [hash commit] [file]__: Vuelve al estado  del fichero en ese commit (hash)


