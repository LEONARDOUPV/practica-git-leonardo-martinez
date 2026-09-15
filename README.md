# Creación y sincronización de repositorios con Git y GitHub

## Datos del estudiante
* **Nombre completo:** Leonardo Enrique Martinez Guevara
* **Matrícula:** 2630348
* **Nombre de la práctica:** Creación y sincronización de repositorios con Git y GitHub
* **Objetivo de la práctica:** Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos: Local -> GitHub y GitHub -> Repositorio local.

---

## Descripción del procedimiento realizado
Para esta práctica se realizó la configuración de un entorno de control de versiones conectando PowerShell con la plataforma remota GitHub:

1. **Creación local e inicialización:** Se creó la carpeta `practica-git-leonardo-martinez`, se inició un repositorio Git local, se configuró la rama `main` y se crearon los archivos `README.md` y `datos.txt`.
2. **Primer commit:** Se agregaron los archivos al Staging Area y se confirmó el cambio en el historial local.
3. **Vinculación remota:** Se creó un repositorio público totalmente vacío en GitHub y se vinculó con la terminal usando su URL remota. Posteriormente se subieron los datos con `git push`.
4. **Sincronización GitHub -> Local:** Se editó el archivo `datos.txt` directamente desde la página de GitHub y se descargaron los cambios a la computadora ejecutando `git pull`.
5. **Sincronización Local -> GitHub:** Se modificó de nuevo `datos.txt` desde el entorno local, se realizó un nuevo commit y se enviaron los cambios a GitHub mediante `git push`.

---

## Comandos de Git utilizados y explicación breve de su función

* `git init`: Inicializa un nuevo repositorio Git en la carpeta actual.
* `git branch -M main`: Renombra la rama principal a `main`.
* `git status`: Muestra el estado actual del directorio de trabajo y del Staging Area.
* `git add .`: Agrega todos los archivos nuevos o modificados al Staging Area.
* `git commit -m "mensaje"`: Guarda los cambios del Staging Area en el historial del repositorio local.
* `git remote add origin <URL>`: Vincula el repositorio local con el repositorio remoto de GitHub.
* `git remote -v`: Muestra los enlaces remotos vinculados.
* `git push -u origin main`: Envía los cambios locales a la rama main de GitHub por primera vez.
* `git pull origin main`: Descarga e integra los cambios del repositorio remoto al local.
* `git push`: Sube las nuevas modificaciones locales al repositorio remoto.

---

## Explicación paso a paso de los procesos

* **Explicación de cómo se creó el repositorio local:** Se creó la carpeta en la computadora, se accedió a ella mediante la terminal PowerShell y se utilizó `git init` para empezar el rastreo de archivos. Con `git branch -M main` se estableció la rama base y se crearon los archivos necesarios.
* **Explicación de cómo se vinculó el repositorio local con GitHub:** Se creó un repositorio público vacío en la página de GitHub. En PowerShell se corrió `git remote add origin https://github.com/LEONARDOUPV/practica-git-leonardo-martinez.git` y se verificó con `git remote -v`.
* **Explicación de la sincronización Local -> GitHub:** Tras realizar modificaciones locales en `datos.txt`, se guardaron los cambios con `git add .` y `git commit`, y se enviaron al servidor ejecutando `git push`.
* **Explicación de la sincronización GitHub -> Local:** Se editó el archivo directamente en la web de GitHub guardando el commit desde ahí. Luego, en la terminal local se corrió `git pull origin main` para traer la nueva información a la máquina física.

---

## Descripción de los archivos contenidos en el repositorio

* **README.md:** Archivo en formato Markdown que contiene la documentación completa de la práctica, datos del alumno, explicación de comandos y procedimientos.
* **datos.txt:** Archivo de texto utilizado para realizar y verificar las pruebas de sincronización bidireccional de cambios entre el entorno local y GitHub.

---

## Conclusión personal sobre lo aprendido
A través de esta práctica logré comprender de manera clara la estructura del flujo de trabajo de Git (`Working Directory` -> `Staging Area` -> `Local Repository` -> `GitHub`). Aprendí la importancia de sincronizar los cambios constantemente mediante `git pull` y `git push` para evitar conflictos de código y asegurar que los repositorios remoto y local se mantengan actualizados.