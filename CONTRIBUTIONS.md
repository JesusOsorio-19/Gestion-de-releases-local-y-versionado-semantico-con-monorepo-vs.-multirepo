# Contribución de Jesus Diego Osorio Tello 

## Sprint 1

- 2025-06-06: Escribí `hooks/pre-commit` para realizar formato con black y chequeo de errores de lint con flake8 solo en archivos python, de esta manera los commits subidos al repositorio remoto seran limpios y los errores de lint disminuiran.

    Commit: `feat(git-hooks): Añade hook pre-commit para validación de archivos python`

    Pull request grupal: Configuración Git hooks #2

- 2025-06-07: Escribí `hooks/commit-msg` para que los mensajes de los commits sigan las convenciones.

    Commit: `feat(git-hooks): Añade hook commit-msg para validación de commits siguiendo convenciones`

    Pull request grupal: Configuración Git hooks #2

- 2025-06-07: Escribí `scripts/validate.sh` para validar `terraform fmt` y `terraform validate`.  

  Commit: `feat(tf): validar formato y sintaxis de archivos.tf`

  Pull request grupal: Script de validación básica #10