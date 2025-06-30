### Comando GIT

- Inicializar un nuevo repositorio
```shell
$ git init
```

- Clonar un repositorio remoto o existente

```shell
$ git clone URL
$ git clone -b <branch_name> URL
```

- Muestra el estado de los archivos 

```shell
$ git status
```

- Añade archivos al area de staging
```shell
$ git add <filename>
$ git add -A 
$ git add .
$ git add *
```

- Guardar los archivo en el historial
```shell
$ git commit -m "Mensaje"
```

- Subir los cambios al repositorio remoto
```shell
$ git push origin <branch>
```

- Bajar los cambios al repositorio remoto
```shell
$ git pull origin <branch>
```

- Listar las ramas existentes en el repositorio
```shell
$ git branch
```

- Cambiar a una rama en especifico
```shell
$ git checkout <branch_name>
```

- Crear una rama nueva
```shell
$ git branch <branch_name>
$ git checkout -b <branch_name>
```

- Fusionar (merge) un cambio
```shell
$ git merge <branch_name>
``` 

- Vincular Repositorio Local a uno Remoto
```shell
$ git remote add <name> <url>
```