# mi-primer-repositorio
Aprendí que Git es un sistema de control de versiones distribuido que permite gestionar cambios en el código, trabajar en equipo sin sobrescribir modificaciones y usar ramas para desarrollo seguro.

Diferencias con otros sistemas: Git es más rápido, funciona sin conexión y garantiza la integridad del código mediante instantáneas y hashing.

Branching: Permite desarrollar nuevas funciones sin afectar la versión principal, facilitando la colaboración y experimentación.

Git vs GitHub: Git es la herramienta de control de versiones, mientras que GitHub es una plataforma en la nube para alojar repositorios y colaborar en proyectos.

Ventajas: Historial detallado, trabajo distribuido, desarrollo en ramas y automatización con herramientas como GitHub Actions.


Configuración y gestión de usuario

git config --global user.name "Tu Nombre" → Configura el nombre del usuario.

git config --global user.email "tuemail@example.com" → Configura el correo del usuario.

Inicialización y clonación

git init → Crea un nuevo repositorio Git en el directorio actual.

git clone URL → Clona un repositorio remoto en el equipo local.

Gestión de cambios

git status → Muestra el estado de los archivos en el repositorio.

git add archivo → Agrega un archivo al área de preparación (staging).

git add . → Agrega todos los archivos modificados al área de preparación.

git commit -m "Mensaje" → Guarda los cambios en el historial del repositorio.

git diff → Muestra las diferencias entre archivos modificados y la última versión confirmada.

Ramas y gestión de versiones

git branch → Lista las ramas disponibles.

git branch nombre_rama → Crea una nueva rama.

git checkout nombre_rama → Cambia a otra rama.

git checkout -b nombre_rama → Crea y cambia a una nueva rama.

git merge nombre_rama → Fusiona una rama con la rama actual.

Sincronización con repositorios remotos

git remote add origin URL → Asocia el repositorio local con un remoto.

git push origin rama → Envía cambios al repositorio remoto.

git pull origin rama → Descarga y fusiona cambios del repositorio remoto.

git fetch → Obtiene cambios del remoto sin fusionarlos.

Gestión de historial y versiones

git log → Muestra el historial de commits.

git reset --hard HEAD~1 → Revierte el último commit y sus cambios.

git revert ID_commit → Crea un commit inverso para deshacer cambios sin modificar el historial.

Otros comandos útiles

git stash → Guarda cambios temporalmente sin hacer un commit.

git stash pop → Restaura los cambios guardados con git stash.

git tag nombre_etiqueta → Crea una etiqueta para una versión específica del código.
