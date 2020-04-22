# Hyperblog

un blog para git y github de platzi

# Git

Inicia el programa de Git y inicia el repositorio

```bash
git init
```

<br>

## Configurar Git

Este comando te permite configurar git para añadir cosas como el usuario o realizar varios cambios por el estilo

```
git config
```

(opcional)este es para que la configuracion se vea en una lista y mas ordenado

```
git config --list
```

<br>

## Añadir cambios

Añade los ultimos cambios seleccionados al staying

```bash
git add (nombre del archivo)
```

(opcional) añade todos los cambios que se hayan echo

```bash
git add .
```

<br>

## Subir cambios

Sube tus cambios a la base de datos del sistema de control de verciones (siempre el mensaje del commit hay que ponerlo en comillas)

```bash
git commit -m "mensaje o informacion del commit"
```

(opcional) este comando es para ahorrarse el paso de el git add

```bash
git commit -am "mensaje del commit"
```

<br>

## Volver en el tiempo

Este comando te permite volver a un commit que ya hayas echo

```
git reset (codigo del commit) --soft
o
git reset(codigo del commit)--hard
```

detalle : el git reset --soft the devuelve a ese commit pero lo que sigue en staying sigue hay por lo que se puede volver al presente luego esta el git reset --hard ese devuelve todo a como estaba antes incluso el staying.

<br>

este comando te permite volver en el tiempo de forma superficial lo que significa que te permitira ver lo que tenias posteriormente pero sin realizar cambios en el presente

```
git checkout (codigo del commit o branch) (opcional:nombre del archivo)
```

<br>

## Brach

este comando te permite crear un branch o rama

```
git brach (nombre del branch)
```

## Merge

este comando te permite unir tu branch o master a otro branch o a master

```
git merge (nombre del branch al que vas a enlazar o master)
```

<br>

## Desplegar informacion

Muestra todos los archivos que se hayan cambiado

```bash
git status
```

Muestra todos los cambios y commits que se hayan echo a lo largo del tiempo

```bash
git show
```

Muestra todos los commits que se hayan echo

```bash
git log
```

<br>

## Enviar o extraer cambios (repositorio)

Envia todos los cambios echos al repositorio

```bash
git push
```

Trae los archivos que esten dentro del repositorio

```bash
git pull
```

<br>

# Comandos base

## Ruta

Te muestra en que ruta te encuentras

```bash
pwd
```

Te cambia de direccion

```bash
cd
```

pequeño dato: a la hora de cambiar de ruta toma en cuenta que en Linux y Mac las mayuscculas si importan a la hora de cambiar de direccion en windows no importan las mayusculas

<br>

## Desplegar informacion

Muestra los archivos que esten en esa ruta

```bash
ls
```

(opcional) Muestra todos los archivos que esten en esa ruta incluso los ocultos

```bash
ls -al
```

(opcional)muestra solo los archovos pero no en una lista

```bash
ls -a
```

<br>

pequeño dato : si utilizas la flecha para arriva seleccionaras el ultimo comando que usaste y si sigues presionado la flecha segira a los otros comandos anteriores a ese.

<br>

## Limpiar la consola

Basicamente lo que dice el titulo

```bash
clear
```

dependiendo del si se usa Windows o Linux o Mac se usa

```bash
clear
o
cls
```

(opcional)

```
ctrl + L
```

<br>

## Crear archivos

Crea una carpeta

```bash
mkdir (nombre de la carpeta)
```

Crea un archivo vacio

```bash
touch (nombre del archivo)
```

<br>

## Informacion interna de un archivo

Mira la informacion interna que tenga un archivo

```
cat (nombre del archivo)
```

<br>

## Historia de comandos

Muestra todos los comandos que has usado

```
history
```

## Borrar archivos ("peligroso")

Borra los archovos seleccionados pero ten cuidado si lo haces mal puede llegar a borrar otras cosas e incluso el disco duro

```
rm (nombre del archivo)
```

<br>

## Ayuda

Este comando se pone para saber las posibilidades que existe en otro comando

```
(nombre del comando) --help
Ejemplo:
rm --help
```

<br>

pequeño dato : cuando usas un solo gion (-) es para representar una abreviatura de una palabra que funciona como detalle de la accion pero cuando ocupas escribir una palabra como detalle de la accion utiliza doble guion (--).

## Abrir Visual Estudio Code

Es un comando muy simple pero abre visual estudio code en la direccion en la que estes

```
code
o
code .
```

<br>

# Informacion del curso

Aqui pondre varios links los cuales llevaran a los videos en los que fredy da explicaciones de temas que tienen que ver con Git y GitHub

## ¿Que es el staying y el repositorio?

https://platzi.com/clases/1557-git-github/19946-que-es-el-staging-y-los-repositorios-ciclo-basico-/

## ¿Que es un branch y como funciona un merge en Git?

https://platzi.com/clases/1557-git-github/19947-que-es-un-branch-rama-y-como-funciona-un-merge-en-/

## Flujo de trabajo basico de un repositorio remoto

https://platzi.com/clases/1557-git-github/19935-flujo-de-trabajo-basico-con-un-repositorio-remoto/

## Introduccion a las ramas o branches de Git

https://platzi.com/clases/1557-git-github/19940-introduccion-a-las-ramas-o-branches-de-git/
