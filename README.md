# Comandos básicos GIT

### Clonar repositorio de un branch específico

Para clonar un repositorio de GIT, es necesario generar una carpeta que es donde almacenaras tus proyectos y ejecutar la siguiente instrucción:
```console
git init
```

Una vez hecho esto clonas el repositorio:
```console
git clone <repositorio>
```

Para ubicarte en un branch específico ejecutas lo siguiente:
```console
git checkout  <branch>
```

Una vez hecho lo anterior validas que tengas los últimos cambios
```console
git pull
```


### Subir código

Para subir código a un repositorio GIT primero debes ubicarte en la carpeta de tu repositorio, puedes ocupar git status para validar que estés ubicado en un branch específico.

Una vez que tengas tus cambios integrados a tu proyecto ejecutas la siguiente instrucción para agregarlos al index de git.
```console
git add .
```

Para agregarlos al commit ejecutas lo siguiente:
```console
git commit –m “Comentario”
```

Puedes validar con git status para ver lo que vas a subir a tu branch. Por ultimo solo necesitas ejecutar la siguiente instrucción para subir los cambios. 
```console
git push origin <branch-name>
```


### Anexos

```console
git branch -r 
```
Muestra todos los repositorios.

```console
git status
```
Muestra en que repositorio estas y que cambios faltan por subir

```console
git add . 
```
Agrega todos los cambios al commit

```console
git add <ruta-archivo-especifico> 
```
Agregar cambios de un archivo específico
