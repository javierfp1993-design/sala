---
title: Política de privacidad
lang: es
---

# Política de privacidad de Sala

Última actualización: 10 de noviembre de 2026.

Sala es una app gratuita para Fire TV que reúne en una sola pantalla lo que hay para ver en Netflix,
Prime Video, Disney+, Max y YouTube, y abre cada título en la app oficial de su plataforma. La hace
Javier para uso particular, sin ánimo de lucro. Contacto: [consultas en GitHub](https://github.com/javierfp1993-design/sala/issues).

## En resumen

- Sala **no tiene cuentas** ni te pide datos personales.
- Sala **no lleva publicidad, analítica ni informes de errores**, y no usa identificadores de tu
  dispositivo.
- Lo que Sala guarda se queda **en tu Fire TV**. Nadie más, tampoco quien hace la app, recibe una copia.
- Para buscar, Sala envía lo que escribes a **YouTube** (y, para películas y series, a **TMDB**). Esos
  servicios lo tratan según sus propias políticas.

## Qué guarda Sala en tu Fire TV

Todo se guarda en el espacio privado de la app, al que no acceden otras apps. Sala no hace copias de
seguridad en la nube.

| Qué | Para qué | Cuánto tiempo |
|---|---|---|
| Tus **ajustes**: plataformas que tienes contratadas, duración del historial de búsquedas, modo cine, dirección IP de tu bombilla si la escribes, carpeta de juegos | Recordar cómo quieres usar Sala | Hasta que los cambies, pulses «Restablecer los ajustes» o desinstales la app |
| **Resultados de tus búsquedas** de YouTube (título, canal y miniatura de los vídeos) | Repetir una búsqueda sin volver a pedirla a internet | 24 horas o 7 días, según elijas en Ajustes, y después hasta 7 días más como copia por si no hay conexión |
| **Catálogo** de películas y series (fichas, listas y resultados de tus búsquedas de películas y series) | Que la pantalla cargue rápido | Entre 3 horas y 30 días según el tipo de dato, más 7 días como copia sin conexión |
| **Imágenes** (miniaturas y carteles) y otras respuestas de internet | No descargarlas cada vez | Hasta llenar 50 MB; se borran primero las más antiguas |
| Si usas el **modo cine**: la dirección IP de tu bombilla en la red de casa y cómo estaba la luz antes de atenuarla | Atenuar la luz al ver algo y dejarla como estaba al terminar | La IP, hasta que desinstales la app o borres sus datos; el estado de la luz, hasta que se restaura |

## Qué envía Sala y a quién

Sala solo se conecta a estos servicios, siempre por conexión cifrada (HTTPS):

- **YouTube (YouTube API Services, de Google).** Cuando confirmas una búsqueda en «Buscar en YouTube»,
  Sala envía el texto que has escrito, la región y el idioma (España, español) y la identificación de la
  app (no la tuya). Google recibe además, como en cualquier conexión a internet, la dirección IP de tu
  conexión. Sala no accede a tu cuenta de Google ni a tu historial de YouTube. Al usar las búsquedas de
  YouTube en Sala aceptas los [Términos de servicio de YouTube](https://www.youtube.com/t/terms), y los
  datos que recibe Google se tratan según la
  [Política de privacidad de Google](https://policies.google.com/privacy).
- **TMDB (The Movie Database).** Para mostrar películas y series, Sala pide listas, fichas y carteles, y
  envía las búsquedas que hagas de películas o series, los filtros que uses (por ejemplo, género o
  duración) y las plataformas que tengas marcadas en Ajustes. Lo trata TMDB según su
  [política de privacidad](https://www.themoviedb.org/privacy-policy).
- **Wikidata (Fundación Wikimedia).** Sala pregunta en qué plataforma está cada título usando solo el
  identificador público del título, nada tuyo.
- **Servidores de imágenes de YouTube y TMDB**, para descargar miniaturas y carteles.

Sala **no envía** tus ajustes, tu historial ni ningún identificador de tu dispositivo a nadie, y no
tiene servidores propios.

### En tu red de casa (modo cine)

Si el modo cine está activado (lo está al instalar la app), al abrir un vídeo Sala busca una bombilla
inteligente WiZ en tu red local: si no conoce ya su dirección o no responde en ella, envía un mensaje
a todos los dispositivos de la red (puerto UDP 38899) y, si una bombilla responde, le pide cómo está y le ordena atenuarse; al volver, la deja como estaba.
Estos mensajes no salen de tu red de casa. Si no tienes bombilla o no quieres esta función, desactívala
en **Ajustes → Casa**.

## Otras apps

Cuando eliges qué ver, Sala abre la app oficial (YouTube, Netflix, Prime Video, Disney+ o Max) y solo le
pasa qué vídeo o título abrir (o su nombre, para buscarlo, si no puede abrir la ficha directamente). A
partir de ahí, se aplica la política de privacidad de esa app. Para saber qué apps tienes, Sala comprueba
si están instaladas en el Fire TV; esa información no sale del dispositivo.

## Cómo borrar tus datos

Como todo está en tu Fire TV, puedes borrarlo tú en cualquier momento:

- **Ajustes de Sala → YouTube → Borrar el historial de búsquedas.**
- **Ajustes de Sala → Avanzado → Vaciar la caché de imágenes** y **Restablecer los ajustes.**
- **Para borrarlo todo:** en el Fire TV, Ajustes → Aplicaciones → Administrar aplicaciones instaladas →
  Sala → **Borrar datos**. O desinstala Sala.

Quien hace la app no tiene ninguna copia de tus datos que borrar. Si tienes dudas, escríbenos en [consultas en GitHub](https://github.com/javierfp1993-design/sala/issues) y te contestaremos en un plazo máximo de 7 días.

## Menores

Sala no está dirigida a menores de 14 años y no recoge a sabiendas datos de ellos. No tiene cuentas ni
formularios.

## Cambios en esta política

Si Sala empieza a guardar o enviar algo distinto, actualizaremos esta página y la fecha de arriba antes
de publicar esa versión de la app.
