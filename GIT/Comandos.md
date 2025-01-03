# Comandos más utilizados en Git

Git es un sistema de control de versiones ampliamente utilizado para gestionar proyectos de software. A continuación, se presentan los comandos más comunes junto con una breve descripción:

---

## Comandos Básicos

### Configuración
- **`git config --global user.name "Tu Nombre"`**: Configura tu nombre de usuario para todos los repositorios.
- **`git config --global user.email "tu_email@example.com"`**: Configura tu correo electrónico para todos los repositorios.
- **`git config --list`**: Lista toda la configuración actual de Git.

### Inicialización
- **`git init`**: Crea un nuevo repositorio de Git en el directorio actual.
- **`git clone <url>`**: Clona un repositorio remoto al directorio local.

---

## Comandos para Trabajar con Archivos

### Estado y Seguimiento
- **`git status`**: Muestra el estado de los archivos en el repositorio.
- **`git add <archivo>`**: Añade un archivo específico al área de preparación (staging area).
- **`git add .`**: Añade todos los archivos nuevos o modificados al área de preparación.
- **`git rm <archivo>`**: Elimina un archivo del repositorio y del sistema de archivos.

### Confirmaciones
- **`git commit -m "Mensaje del commit"`**: Realiza un commit con un mensaje descriptivo.
- **`git commit -am "Mensaje del commit"`**: Realiza un commit que incluye automáticamente los cambios en los archivos rastreados.

### Deshacer Cambios
- **`git checkout -- <archivo>`**: Deshace los cambios en un archivo (los restaura al último commit).
- **`git reset HEAD <archivo>`**: Elimina un archivo del área de preparación.
- **`git revert <hash>`**: Revertir un commit específico creando un nuevo commit inverso.

---

## Comandos para Trabajar con Ramas

- **`git branch`**: Lista todas las ramas del repositorio.
- **`git branch <nombre_rama>`**: Crea una nueva rama.
- **`git checkout <nombre_rama>`**: Cambia a una rama específica.
- **`git checkout -b <nombre_rama>`**: Crea y cambia a una nueva rama.
- **`git merge <nombre_rama>`**: Fusiona una rama específica con la rama actual.
- **`git branch -d <nombre_rama>`**: Elimina una rama.

---

## Comandos para Repositorios Remotos

- **`git remote add origin <url>`**: Conecta el repositorio local a un repositorio remoto.
- **`git remote -v`**: Lista las URL de los repositorios remotos configurados.
- **`git push origin <rama>`**: Envía los cambios de una rama al repositorio remoto.
- **`git pull origin <rama>`**: Descarga los cambios del repositorio remoto y los fusiona con la rama actual.
- **`git fetch`**: Descarga los cambios del repositorio remoto sin fusionarlos.

---

## Comandos de Inspección

- **`git log`**: Muestra el historial de commits.
- **`git log --oneline`**: Muestra el historial de commits en una línea por commit.
- **`git diff`**: Muestra las diferencias entre el área de trabajo y el área de preparación.
- **`git show <hash>`**: Muestra los detalles de un commit específico.

---

## Comandos Avanzados

- **`git stash`**: Guarda temporalmente los cambios no confirmados para un trabajo posterior.
- **`git stash pop`**: Restaura los cambios guardados con `git stash` y los elimina del stash.
- **`git rebase <rama>`**: Reaplica los commits de la rama actual sobre otra rama base.
- **`git cherry-pick <hash>`**: Aplica un commit específico de otra rama a la rama actual.

---

## Otros Comandos Útiles

- **`git tag <nombre_etiqueta>`**: Crea una etiqueta en un commit específico.
- **`git clean -f`**: Elimina los archivos no rastreados del directorio de trabajo.
- **`git archive`**: Crea un archivo comprimido del contenido de una rama.

---

Estos comandos cubren las operaciones más comunes en Git, desde la configuración inicial hasta la gestión de ramas y repositorios remotos.
