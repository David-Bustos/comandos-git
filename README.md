## Principales comandos Git/Github

| Command | Description |
| ------- | ----------- |
| `git init` | Inicializa un repositorio Local |
| `git add [file-name]` | Agrega el archivo indicado al escenario (Stage)|
| `git add .` | Agrega los archivos modificados al escenario (Stage) |
| `git restore --staged [file-name]` | Quita un archivo del escenario (Stage) |
| `git status` | Muestra el estado del escenario (Stage) |
| `git commit -m 'message'` | Crea una "fotografía" del Stage y lo deja en la historia del proyecto en el repositorio Local |
| `git commit -am 'message'` | Ejecuta los comandos `add .` y `commit -m` |
| `git commit --amend -m 'update message'` | Actualiza el comentario del último commit realizado |
| `git reset --mixed [commit-number]` | Viaja al commit indicado |
| `git reset --hard [commit-number]` | Viaja al commit indicado y elimina los cambios realizados |
| `git log` | Muestra los commits realizados |
| `git reflog` | Muestra los commits realizados, incluido los eliminados|
| `git diff` | Muestra la diferencia entre el último commit y los cambios actuales |
| `git diff --staged` | Muestra la diferencia entre el último commit y el escenario (Stage) |
| `git branch` | Muestra en la rama que estamos |
| `git branch [branch-name]` | Crea una nueva rama |
| `git branch -d [branch-name]` | Elimina la rama indicada |
| `git checkout [branch-name]` | Entra a la rama indicada |
| `git checkout -b [branch-name]` | Crea y entra a la nueva rama |
| `git diff [branch-name-1] [branch-name-2]` | Muestra la diferencia entre las ramas especificadas |
| `git merge [branch-name]` | Fusiona los cambios de la rama actual con la rama indicada |
| `git clone [link-github]` | Crea una copia local de un repositorio de github |
| `git push` | Sube los cambios locales al servidor remoto de github |
| `git pull` | Descarga los cambios del servidor remoto de github al repositorio local |

## Ignorando Archivos (.gitignore)

| Example | Description |
| ------- | ----------- |
| `secret.txt` | Ignora cualquier archivo llamado "secret.txt" |
| `secret/` | Ignora cualquier directorio llamado "secrets" |
| `/hidden.txt` | Ignora un archivo llamado "hidden.txt" ubicado en la raíz de tu directorio de trabajo |
| `/node_modules/` | Ignora un directorio llamado "node_modules" ubicado en la raíz de tu directorio de trabajo |
| `*.png` | Ignora cualquier archivo con extensión .png |
| `cache*` | Ignora cualquier archivo o directorio que comienza con "cache", como cache-file-01, cached_assets/, etc. |
| `*data` | Ignora cualquier archivo o directorio que termine con "data", como project_data/, big_file_of_data |

## Bonus: comandos de la Terminal

| Command | Description |
| ------- | ----------- |
| `pwd` | Indica el directorio actual |
| `ls` | Lista los archivos y carpetas del actual directorio |
| `ls -al` | Listado `ls` con detalle |
| `cd [folder-name]` | Entrar a la carpeta indicada |
| `cd ..` | Volver al directorio padre |
| `cd /` | Volver al directorio raíz |
| `mkdir [folder_name]` | Crear una nueva carpeta |
| `rm [folder_name]` | Elimina la carpeta indicada (vacía) |
| `rm -rf [folder_name]` | Elimina la carpeta indicada (incluso con archivos) |
