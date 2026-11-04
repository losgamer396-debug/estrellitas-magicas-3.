ESTRELLITAS MÁGICAS — PROYECTO PARA GENERAR APK ANDROID

Este ZIP contiene el juego y una automatización para compilar la APK en GitHub Actions.
La APK todavía NO está compilada dentro de este ZIP.

OPCIÓN MÁS SIMPLE PARA OBTENER LA APK (requiere una cuenta gratuita de GitHub):

1) En una computadora, abrí https://github.com y creá una cuenta o iniciá sesión.
2) Creá un repositorio nuevo llamado estrellitas-magicas. Puede ser privado.
3) En el repositorio, elegí Add file > Upload files.
4) Descomprimí este ZIP en tu PC y arrastrá TODOS los archivos y carpetas de adentro al área de carga de GitHub. Asegurate de incluir la carpeta oculta .github (si no la ves, activá "Elementos ocultos" en el Explorador de Windows).
5) Confirmá con Commit changes.
6) Abrí la pestaña Actions del repositorio. Entrá en "Construir APK Android" y esperá que termine en verde.
7) Abrí la ejecución completada y bajá el artefacto "Estrellitas-Magicas-APK". GitHub lo entrega como ZIP; adentro está app-debug.apk.
8) Pasá app-debug.apk al teléfono Android, abrilo y autorizá la instalación desde esa fuente si Android lo solicita.

Si Actions no aparece habilitado, entrá a la pestaña Actions y habilitá workflows. También podés iniciar la compilación manualmente desde Actions > Construir APK Android > Run workflow.

CONTENIDO:
- www/index.html: juego infantil sin anuncios ni compras.
- capacitor.config.json: configuración de la app.
- .github/workflows/build-apk.yml: automatización de compilación.

IMPORTANTE:
- Esta es una APK DEBUG para probar en tu propio teléfono, no una versión firmada de publicación.
- Para publicar en Google Play se necesita preparar una compilación de lanzamiento firmada, revisar políticas de Familias, privacidad y clasificación por edades.
- No hay anuncios integrados ni recolección de datos en este prototipo.
