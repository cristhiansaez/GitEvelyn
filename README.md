Guía de Uso de Git y GitHub
Parte 1: Configuración Inicial
1. Configurar Git en el equipo
Antes de empezar a trabajar con Git, es necesario configurarlo con el nombre y correo del usuario. Esto permite identificar a la persona que realiza los cambios en los repositorios.

2. Crear un nuevo repositorio en GitHub
Para iniciar un proyecto, se debe crear un repositorio en GitHub. Para ello:

Acceder a la plataforma de GitHub.
Hacer clic en la opción "New Repository".
Asignar un nombre al repositorio.
Marcar la opción para inicializarlo con un archivo README.
3. Clonar el repositorio en el equipo local
Una vez creado el repositorio, se puede clonar en el equipo. Esto permite trabajar con los archivos de manera local y sincronizarlos con GitHub cuando sea necesario.

Parte 2: Trabajo Individual con Git
1. Crear un archivo y realizar un commit
Para agregar un nuevo archivo al repositorio, primero se debe crear y luego registrarlo en el historial de cambios mediante un "commit". Un commit es una confirmación de los cambios realizados.

2. Subir los cambios al repositorio remoto
Una vez hecho el commit, se deben enviar los cambios a GitHub para que queden almacenados en el repositorio en línea.

3. Actualizar la copia local con cambios remotos
Si hay cambios en el repositorio remoto realizados por otros colaboradores, es necesario sincronizar la copia local para mantenerse actualizado.

Parte 3: Trabajo Colaborativo
1. Crear una nueva rama para desarrollar una funcionalidad
En proyectos colaborativos, es recomendable trabajar en ramas separadas para cada funcionalidad o cambio. Esto evita afectar la versión principal del proyecto.

2. Realizar cambios en la nueva rama y hacer commit
Después de crear la rama, se pueden realizar modificaciones en los archivos. Luego, se debe registrar el progreso con un commit.

3. Subir la rama al repositorio remoto
Una vez terminados los cambios en la rama, se deben subir a GitHub para que otros colaboradores puedan verlos y revisarlos.

4. Crear un Pull Request (PR) en GitHub
Un Pull Request es una solicitud para fusionar los cambios de una rama con otra (generalmente con la rama principal o "main"). Para crearlo:

Acceder al repositorio en GitHub.
Ir a la pestaña "Pull Requests" y seleccionar "New Pull Request".
Elegir la rama con los cambios y compararla con la rama principal.
Revisar las modificaciones antes de enviarlas.
Añadir una descripción detallada explicando los cambios.
Enviar la solicitud y esperar revisión.
5. Revisar y fusionar los cambios
Los compañeros del equipo pueden revisar el Pull Request y aprobarlo si todo está correcto. Si es necesario, pueden sugerir cambios antes de aceptarlo. Cuando se aprueba, la rama se fusiona con la principal y se puede eliminar si ya no es necesaria.

6. Actualizar la rama local con los cambios aprobados
Después de que los cambios han sido fusionados en la rama principal, los colaboradores deben actualizar su copia local para trabajar con la última versión del código.

Parte 4: Resolución de Conflictos
1. Generar un conflicto (de manera intencionada)
Un conflicto ocurre cuando dos personas modifican la misma línea de código en diferentes ramas y tratan de fusionarlas. Git no puede decidir automáticamente qué cambio debe conservarse.

2. Resolver el conflicto
Cuando ocurre un conflicto, Git lo notificará. Para solucionarlo, se debe:

Abrir el archivo afectado y revisar los cambios en conflicto.
Editarlo manualmente para conservar los cambios correctos.
Guardar los ajustes y registrar la solución con un commit.
Subir la versión corregida al repositorio remoto.
Con estos pasos, se mantiene un flujo de trabajo organizado y eficiente en Git y GitHub.







