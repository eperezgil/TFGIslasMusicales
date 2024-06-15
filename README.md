# Instrucciones para ejecutar el juego

## Windows
1. Descargar carpeta "Ejecutable_Windows.zip"
2. Descomprimir carpeta
3. Ejecutar "IslasMusicales.exe"

## Linux
1. Descargar carpeta "Ejecutable_Linux.zip"
2. Descomprimir carpeta
3. Ejecutar "IslasMusicales.x86_64"
4. En caso de error: Botón derecho sobre el ejecutable -> Preferencias -> Permisos -> Permitir ejecutar el archivo como programa

## Mac OS
1. Descargar carpeta "Ejecutable_Mac.app.zip"
2. Descomprimir carpeta
3. Ejecutar "Ejecutable_Mac.app"


# Instrucciones para cargar el proyecto en Unity

## Instalar Unity
1. Descargar Unity Hub desde https://unity.com/es/download
2. Abrir Unity Hub, seleccionar en el panel izquierdo "Installs" y arriba a la derecha "Install Editor"
3. Instalar la versión 2022.3.20f1 (importante: esta es la versión usada para el desarrollo, puede que el juego no funcione en otra versión)

## Crear un proyecto
1. Crear una carpeta en el ordenador donde guardar el proyecto
2. En Unity Hub, seleccionar en el panel izquierdo "Projects" y arriba a la derecha "New Project"
3. Elegir la opción "Universal 2D"
4. En el panel derecho, asignar un nombre al proyecto y como localización la carpeta creada anteriormente
5. Crear el proyecto
6. Descargar el archivo "Proyecto.unitypackage" de este repositorio
7. Dentro del proyecto creado, en la parte superior, Assets -> Import Package -> Custom Package
8. Elegir el proyecto descargado
9. Aparecerá una ventana con los componentes del proyecto, dar a "Import"

## Componentes del proyecto en el editor
- Se puede acceder a todos los componentes desde el panel derecho "Project"
- Dentro de una escena pueden verse sus componentes en el panel superior "Hierarchy"
- Las carpetas con contenido del juego son "Audios", "Botones", "Escenas", "Imagenes" y "Scripts"

## Ejecutar el juego desde el editor de Unity
1. Una vez cargado el proyecto, en el menú del lateral derecho "Projects" eliminar la carpeta "Scenes" que contiene "SampleScene"
2. En ese menú elegir la carpeta "Escenas" y la escena "MenuPrincipal"
3. Acceder a File -> Build Settings... para abrir el menú de escenas del juego
5. En la lista "Scenes in Build" eliminar "Scenes/SampleScene"
6. Ir clicando en todas las escenas de la carpeta "Escenas" y añadiéndolas con "Add Open Scenes" desde el menú de escenas
7. Para ejecutar el juego dar a la flecha de play en la parte superior
