## cloning

se puede de 3 maneras

https, ssh, github cli

Creamos un directorio en los workspaces e github, llamado temp, para poder trabajar con los comandos

```sh
mkdir /workspace/temp

cd  /workspace/temp

```

## https
```sh
git clone https://github.com/alejozx456/github-example.git

cd github-example

Iniciar proyecto

mkdir new-project

touch readme.md

code readme.md

#empezar git y guardar cambios
git init #inicializar git

git status #ver el etado de tus archivos

git add . #agregar todos los archivos

git reset #revertor git add .

git add readme.md # agregar solo ese archivo



git commit -a -m "cambios guardados"


```

## commits

es un mensaje de confirmacion, al momento de realizar cambios

```sh
git commit
```
comando cmpleto para abrir una segunda ventana

```sh
git commit -m "sda"
```
## branches

create a new branch
```sh
git branch "nombre"
```
ir a la rama nueva

```sh
git checkout dev
```
push


```sh
git push -u origin dev
```



## remotes


## stashing

## merging


## reset

revertir los cambios de un git add


```sh
git add .

git reset

```

## gitconfig files

en donde se guarda la configuraion global de git como el correo nombre y editor


```sh
git config --list

```

## log

muestra los commits

```sh
git log
```

## push

subir los cambios en el repositorio remoto
