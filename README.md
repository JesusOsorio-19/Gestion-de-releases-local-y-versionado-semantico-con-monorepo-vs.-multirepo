# Proyecto 13: Gestión de releases local y versionado semántico con monorepo vs. multirepo.

Jesus Diego Osorio Tello - jesus.osorio.t@uni.pe

Con mi grupo trabajamos en una organización de GitHub, en el cual creamos nuestro repositorio para esta PC3: https://github.com/grupo10-CC3S2

Link del repositorio principal de la PC3: https://github.com/grupo10-CC3S2/Proyecto13-PC3.git

Hasta el momento en el Sprint 1 me he encargado de implementar los hooks `pre-commit` y `commit-msg`, los cuales nos hacen tener commits que sigan las convenciones. También implementé el script `validate.sh` que automatiza la validación de nuestros archivos Terraform.

## Instrucciones

- Para clonar mi repositorio, usamos el comando `git clone`.

    ```bash
    git clone https://github.com/JesusOsorio-19/Gestion-de-releases-local-y-versionado-semantico-con-monorepo-vs.-multirepo.git
    ```

- Para usar los hooks y script que implementé lo hacemos de la siguiente manera.

    Los hooks `pre-commit` y `commit-msg` lo coloque en la subcarpeta `hooks` de la carpeta `.git` y adicionalmente también cree un directorio que contenga estos hooks. Luego de esto hacemos que los archivos sean ejecutables. 

    ```bash
    cd hooks
    chmod +x pre-commit
    chmod +x commit-msg 
    ```
- Ahora para el script `validate.sh`, lo colocamos en la carpeta `script`, hacemos el archivo ejecutable

    ```bash
    cd script
    chmod +x validate.sh
    ```
    Y luego lo ejecutamos.

     ```bash
    ./validate.sh
    ```

