# Git: comandos básicos

## Clonar un repositorio
```bash
git clone <url-del-repositorio>
```
Clona un repositorio remoto a tu máquina local.

---

## Agregar archivos al index o staging area
```bash
git add <archivo>
```
```bash
git add .
```
Agrega uno o todos los archivos al index o staging area.

---

## Ver el estado del repositorio
```bash
git status
```
Muestra los cambios actuales, archivos modificados y en el index o staging area.

---

## Ver diferencias en cambios
```bash
git diff
```
Muestra las diferencias entre los cambios no confirmados y el último commit.

Ver diferencias en el index o staging area:
```bash
git diff --staged
```

---

## Ver el historial de commits
```bash
git log
```
Muestra el historial completo de commits del repositorio local.

---

## Crear un commit
```bash
git commit -m "mensaje del commit"
```
Crea un commit con los cambios agregados en el index o staging area con un mensaje descriptivo.

```bash
git commit -m "mensaje del commit" .
```
Crea un commit con todos los archivos del index que están en la carpeta actual.

---

## Subir cambios al repositorio remoto
```bash
git push
```
Envía los commits locales al repositorio remoto.

---

## Traer cambios del repositorio remoto
```bash
git pull
```
Descarga y mergea cambios del repositorio remoto.

---

## Checkout
```bash
git checkout <archivo>
```
Pisa el archivo con la versión del repositorio local.

---

## Eliminar archivos
```bash
git rm <archivo>
```
Elimina un archivo del repositorio y del sistema de archivos.

---

## Inicializar repositorio (en general no se usa, se crea desde GitHub/GitLab)
```bash
git init
```
Inicializa un repositorio nuevo en el directorio actual.
