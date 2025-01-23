
## Dev

1. Clonar el repositorio
2. Crear un `.env` basado en el `.env.template`
3. Ejecutar el comando `git submodule update --init --recursive` para reconstruir los sub-módulos
4. Ejecutar el comando `docker compose up --build`

### Pasos para crear los Git Submodules

1. Crear nuevo repositorio en GitHub
2. Clonar el repositorio en la m´quina local
3. Añadir el submodule, donde `repository_url` es la url del repositorio y
sub-módulo (no debe de existir en el proyecto)
```
git submodule add <repository_url> <directory_name>
```
4. Añadir los cambios al repositorio (git add, git commit, git push)
```
Ejm:
git add .
git commit -m "Add submodule"
git push origin main
```