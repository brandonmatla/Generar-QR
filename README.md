# Generar-QR

Generar-QR es un sitio web estático en español con herramientas gratuitas
para tareas educativas, organización, textos y creación de enlaces. Las
herramientas funcionan directamente en el navegador y no requieren cuentas.

## Herramientas

- Generador de códigos QR estáticos para textos y enlaces.
- Generador de equipos aleatorios.
- Generador de grupos aleatorios con intento de separación de nombres.
- Temporizador para clases con pausa y pantalla completa.
- Ruleta de nombres.
- Generador de sopas de letras con respuestas.
- Generador de ejercicios matemáticos.
- Generador de exámenes y hoja de respuestas.
- Contador de palabras, caracteres, líneas y oraciones.
- Generador de enlaces de WhatsApp.
- Generador de etiquetas imprimibles con QR opcional.

## Cómo funciona

Cada herramienta es una página HTML independiente con CSS y JavaScript
integrados. Los datos introducidos se procesan localmente para generar el
resultado en el navegador. El generador de etiquetas puede guardar preferencias
en `localStorage` únicamente cuando el usuario activa la opción “Recordar
ajustes”.

## Publicación

El proyecto está preparado para GitHub Pages. No necesita un servidor de
aplicaciones ni una base de datos: basta con publicar los archivos estáticos
del repositorio y configurar GitHub Pages para servir la rama o carpeta
correspondiente.

## Dependencias externas

Las páginas de generación de QR utilizan `qrcodejs` desde jsDelivr. El resto
del proyecto utiliza JavaScript del navegador sin frameworks externos.

## Licencia

El código se distribuye bajo las condiciones descritas en [LICENSE](LICENSE).
La licencia debe consultarse antes de copiar, modificar o redistribuir el
proyecto.

## Contacto y errores

Para sugerencias, errores o solicitudes de funciones, visita
[contacto.html](contacto.html) y utiliza el perfil de GitHub enlazado allí.
Al reportar un error, incluye la herramienta afectada, los pasos para
reproducirlo, el navegador y el dispositivo utilizados. No incluyas datos
personales innecesarios.
