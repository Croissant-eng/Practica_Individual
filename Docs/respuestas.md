 ¿Qué ventaja tiene registrar las dependencias del proyecto en 
requirements.txt en lugar de compartir la carpeta .venv?

R= Porque aparte de ser mucho mas felxible entre sistemas operativos y muchisimo mas bajo en almacenamineto el problema entra con las rutas que llevan al directorio del entorno virtual

¿Por qué el repositorio que tienes ahora en tu computadora no es el
mismo concepto que el fork creado en GitHub?
R= El fork creado en GitHub es una Rama del repositorio original mas sin embargo no es el repo principal y tambien la mas clara diferencia es que este apenas se creo y fue primero con Git

¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó?
R= Por el tiempo que llevamos conociendo los mismos comandos y que hacen cada uno

¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit?
R= Preparar un archivo para un commit esta en hacer los mismos cambios y documentacion del mismo y crear el commit significa agregar los archivos cambiados al commit y hacer el mismo

¿Cómo puedes comprobar en qué rama estás trabajando?
R= Con git branch

¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos?
R= Con git Status

¿Cómo puedes observar exactamente qué cambió dentro de un archivo?
R= Con git dif

¿Por qué debe reconstruirse .venv después de obtener un repositorio?
R= Para poder instalar las dependencias necesarias para ejecutar solamente en ese entorno con directorio unico y que no sea en el equipo en general(global)

¿Qué relación existe entre requirements.txt y .gitignore?
R= Esta se encuentra en el entorno virtual, dado que el entorno virtual es diferente y unico en cada equipo y mas aparte tiene una carga de archivos pesados etsos 2 archivos nos ayudan uno a ignorar la carpeta del entorno virtual y el otro para poder decirle a las demas personas u programadores que dependencias ellos necesitan para correr el proyecto de forma correcta.

¿Por qué la colaboración se realiza desde una rama y no directamente desde main?
R= Para permitir la estabilidad del codigo y permitir la colaboracion del mismo

¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo?
R= Una solicitud de cambios durante una revisión solo requiere actualizar la rama existente con nuevos commits, ya que el Pull Request está vinculado a una rama específica de Git y no a una versión estática del código.

Después de realizar el merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local?
R= Para si es que uno es el dueño del repositorio traer los cambios del repositorio remoto al local.