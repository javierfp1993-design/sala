---
title: Instalar Sala
lang: es
---

# Cómo instalar Sala en tu Fire TV

Guía para alguien que no ha instalado nunca una app fuera de la tienda de Amazon. Se hace todo con el
mando y tarda unos 10 minutos la primera vez.

Necesitas:

- Un Fire TV (Stick, Stick 4K, Cube…) conectado a internet.
- El **enlace** o el **código** de Sala que te haya pasado Javier.
- Para ver las plataformas, sus apps oficiales instaladas (Netflix, Prime Video, Disney+, Max, YouTube).
  Sala no las sustituye: te ayuda a encontrar qué ver y abre la app que toca.

## 1. Instala la app Downloader

Downloader es una app gratuita de la tienda de Amazon que sirve para descargar archivos de internet.

1. En la pantalla de inicio, ve a la **lupa** (Buscar), arriba a la izquierda.
2. Escribe `Downloader` y elige **Downloader**, la del icono naranja con una flecha (de *AFTVnews*).
3. Pulsa **Descargar** (u **Obtener**). Espera a que termine. No hace falta abrirla todavía.

## 2. Activa las opciones para desarrolladores

Fire TV esconde este menú. No cambia nada de tu tele, solo lo hace visible.

1. Ve a **Ajustes** (el engranaje, a la derecha del todo en el inicio).
2. Entra en **Mi Fire TV** → **Acerca de**.
3. Con la primera línea seleccionada (el nombre del aparato, por ejemplo *Fire TV Stick 4K*), pulsa el
   **botón central** del mando **7 veces seguidas**. Abajo aparece «Ya eres desarrollador».
4. Pulsa **Atrás** una vez. Ahora en **Mi Fire TV** aparece **Opciones para desarrolladores**.

> Si ya ves «Opciones para desarrolladores» en Mi Fire TV, sáltate este paso.

## 3. Deja que Downloader instale apps

1. En **Ajustes** → **Mi Fire TV** → **Opciones para desarrolladores**, entra en
   **Instalar apps desconocidas** (en algunos modelos se llama **Apps de origen desconocido**).
2. Busca **Downloader** en la lista y pulsa para que ponga **Activado**.

No hace falta activar «Depuración ADB»: eso es solo para quien programa la app.

## 4. Descarga e instala Sala

1. Abre **Downloader** (está en **Apps**, el icono de tres cuadraditos del inicio).
2. La primera vez pregunta si puede acceder a tus archivos: pulsa **Permitir**. Si sale una ventana de
   novedades, ciérrala con **OK**.
3. En la pestaña **Home**, selecciona la casilla de la dirección y escribe el **código** (son solo
   números) que te ha pasado Javier. Pulsa **Go** (Ir).
4. Cuando termine la descarga, sale una pantalla de Sala con el botón **Instalar**. Púlsalo.
5. Al acabar, pulsa **Listo** (no **Abrir** todavía).
6. Downloader pregunta si quieres borrar el archivo descargado: pulsa **Delete** dos veces. Así
   recuperas espacio; la app ya está instalada.

## 5. Abre Sala y ponla a mano

1. Pulsa **Inicio** en el mando y ve a **Apps** (tres cuadraditos). Sala está al final de la lista.
2. Para tenerla en el inicio: selecciónala, pulsa el botón **Menú** (tres rayas) → **Mover** y llévala
   a la fila de arriba.

## 6. (Opcional) Juegos

La sección **Juegos** de Sala abre en RetroArch los juegos que tú copies en el Fire TV. Sala no incluye ni
descarga juegos. Para que Sala vea la carpeta de juegos hay que darle permiso una vez:

1. En Sala, abre **Juegos** en el menú de la izquierda.
2. Si sale «Sala necesita permiso para ver tus juegos», pulsa **Dar permiso**.
3. Se abre la pantalla de permisos de Fire TV para Sala. Selecciona **Archivos y contenido multimedia**
   (o **Acceso a todos los archivos**) y pulsa el **botón central** hasta que ponga **Permitido**.
4. Pulsa **Atrás** para volver a Sala. Los juegos aparecen solos.

Sala solo usa este permiso para leer la carpeta de juegos (`Download/Sala/Juegos`). Ni lee ni envía
nada más.

> Este paso aún no se ha probado desde la pantalla de Fire TV. Si no aparece la opción o no cambia,
> avisa a Javier: puede darlo desde el ordenador.

## Actualizaciones

Sala no se actualiza sola, porque no viene de la tienda de Amazon. Cuando Javier te avise de que hay
versión nueva, el código es **el mismo de siempre**:

1. Abre **Downloader**, escribe el código y pulsa **Go**, como la primera vez.
2. Saldrá «¿Quieres instalar una actualización de esta app?»: pulsa **Instalar**.

Tus datos se conservan. Si en algún momento Sala avisa de que hay versión nueva, es este mismo proceso.

## Si algo falla

| Lo que ves | Qué hacer |
|---|---|
| «Por seguridad, tu Fire TV no puede instalar apps desconocidas» | Repite el paso 3: Downloader tiene que estar **Activado** |
| La descarga se queda en 0 % o da error | Comprueba el enlace letra a letra. Si es un código, que sea solo números |
| «La app no está instalada» al actualizar | Avisa a Javier: el archivo no es de la misma versión firmada |
| Al buscar en YouTube: «Por hoy se han acabado las búsquedas…» | Todos compartimos un número de búsquedas al día. Vuelven a las 9 de la mañana |
| Al abrir un vídeo: «No se ha podido abrir el vídeo» | Instala la app de YouTube desde la tienda de Amazon |
| En Juegos: «Sala necesita permiso para ver tus juegos» y no se puede activar | Avisa a Javier (permiso por ADB, ver abajo) |

---

[Política de privacidad](privacidad.html)

