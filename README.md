\# Proyecto de Software

\# Grupo 5



\## Descripción del Proyecto



Descripción del Proyecto…



---

\## Estructura del Repositorio

El repositorio está organizado en los siguientes directorios principales:



| Directorio | Contenido Principal | Propósito |

| :--- | :--- | :--- |

| \*\*`src`\*\* | Código fuente principal del proyecto | Contiene la implementación del sistema, lógica del programa y archivos ejecutables. |

| \*\*`test`\*\* | Archivos de prueba | Incluye pruebas unitarias o archivos utilizados para verificar el correcto funcionamiento del sistema. |

| \*\*`docs`\*\* | Documentación del proyecto | Contiene documentación técnica, manuales, informes y archivos explicativos relacionados con el desarrollo. |



---



\## Lista de Comandos con su respectiva función



```bash

git config --global user.name "Tu Nombre"

git config --global user.email "tu.email@ejemplo.com"

```

Permite configurar el entorno local a partir de un nombre de usuario y un email



```bash

git clone https://github.com/usuario/proyecto\_grupo

```

Clona desde GitHub el repositorio almacenado en la nube en el entorno del dispositivo local del usuario, creando una carpeta de manera local con todos los archivos.

&nbsp;

```bash

git add .

```

Prepara todos los cambios realizados en los archivos o carpetas del repo local y prepara estos cambios para su posterior actualización en el repositorio de GitHub.



```bash

git commit -m "Description"

```

Permite registrar los cambios preparados en el comando add ., guardando el estado del repositorio con un mensaje especifico que especifica la actualización o cambio generado.



```bash

git push origin main

```

Envía los commits realizados desde el repo local al repositorio GitHub, actualizando el estado del repositorio.



```bash

git checkout -b nombre\_rama

```

Permite crear una nueva rama dentro del repositorio GitHub.



```bash

git checkout main

```

Permite cambiar a la rama main.



```bash

git merge nombre\_rama

```

Integra los cambios de la rama actual en la rama main, solo si no hay conflictos que no permitan realizar la acción. 



```bash

git pull origin main

```

Descarga los cambios recientes de la rama main del repositorio GitHub en el repositorio remoto del dispositivo.



```bash

git status

```

Permite identificar el estado actual de la rama en la que se encuentra el usuario actualmente. Indica el estado de trabajo de la rama.



```bash

git swithc -c nombre\_rama

```

Permite cambiar de rama.



---



Enlace del repositorio GitHub: https://github.com/moncbj/software\_grupo1

