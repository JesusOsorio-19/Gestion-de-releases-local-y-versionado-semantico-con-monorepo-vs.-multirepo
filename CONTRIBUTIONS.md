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

## Sprint 2

- 2025-06-14: Implementé `.gitignore`, `.flake8`, `.bandit`, `requirements.txt` y `devconteiner.json` que son archivos de configuración inicial. Desde archivos a ignorar, estandarizar nuestros códigos, mejor práctica de archivos, incluir dependencias necesarias para nuestro proyecto y un contenedor que facilita el trabajo al grupo para que todos trabajemos con el mismo entorno.

    Commit: `feat(git-ignore): Añade archivo para indicar que ignorar`
    Commit: `feat(flake): Añade archivo para análisis de calidad de código python`
    Commit: `feat(bandit): Añade archivo para detectar vulnerabilidades de seguridad en código python`
    Commit: `feat(dependencias): Añade archivo con dependencias necesarias para el proyecto`
    Commit: `feat(docker): Añade devconteiner con dependencias necesarias`

    Pull request grupal: Configuraciones iniciales #20
    Pull request grupal: Añade requirements y devconteiner #22

- 2025-06-14: Implementé `src/generar_diagrama.py` que genera gráficos DOT simples.

    Commit: `feat(graficos): Añade script que genera gráficos DOT simples`

    Pull request grupal: Añade script que genera gráficos DOT simples #21

## Sprint 3

- 2025-06-19: Implementé `verificar_estado.py` y `hooks/pre-push`, que se encargar de verificar los .tfstate y de invocar el script en python antes de cada push, respectivamente.

    Commit: `feat(verifica): Añade script que verifica el estado de archivos terraform` 
    Commit: `feat(pre-push): Añade hook pre-push que invoca verificar_estado` 

    Pull request grupal: Añade script que verifica el estado de archivos terraform #34
    Pull request grupal: Añade hook pre-push que invoca verificar_estado #33

> La carpeta `branches/` tiene los commits por sprints, para identificarlo tiene los prefijos 1, 2 y 3 que indica el sprint respectivamente.