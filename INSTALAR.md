# Nexo: cómo instalarla en tu iPhone

La app necesita estar publicada en una dirección web (https) para que Safari la pueda instalar.
Tus datos **no** se suben a ningún lado: viven solo en tu iPhone. Lo único que se publica es el código de la app.

## 1. Publicarla gratis con GitHub Pages (una sola vez, ~10 min, desde la Mac)

1. Crea una cuenta en https://github.com con tu correo **personal**.
2. Arriba a la derecha: **+ → New repository**.
   - Nombre: `nexo` (o el que quieras)
   - Déjalo en **Public** (el código no contiene ningún dato tuyo)
   - Clic en **Create repository**.
3. En la página del repo, clic en **uploading an existing file**.
   Arrastra **todos** los archivos de esta carpeta (`index.html`, `sw.js`, `manifest.webmanifest`, los 4 `.png`) y clic en **Commit changes**.
4. Ve a **Settings → Pages**. En *Branch* elige `main` y carpeta `/ (root)` → **Save**.
5. Espera 1–2 minutos. Tu app quedará en: `https://TU-USUARIO.github.io/nexo/`

## 2. Instalarla en el iPhone

1. Abre esa dirección en **Safari** (tiene que ser Safari).
2. Toca el botón **Compartir** (cuadro con flecha) → **Agregar a pantalla de inicio** → **Agregar**.
3. Ábrela desde el ícono nuevo. La primera vez te hará las preguntas para llenar tu memoria.

> Importante: úsala siempre desde el ícono de la pantalla de inicio, no desde Safari. Así iOS no borra los datos.

## 3. Conectar Gemini (opcional, recomendado)

1. En el iPhone abre https://aistudio.google.com/apikey con tu cuenta **personal** de Google.
2. **Create API key** → copia la clave.
3. En la app: **Ajustes → Gemini** → pega la clave → **Conectar**.

La clave se guarda solo en tu teléfono y no se incluye en los respaldos.
En la capa gratuita, Google puede usar lo que envías para mejorar sus productos. Si no quieres eso, activa la facturación en AI Studio; con este uso cuesta centavos al mes.

## 4. Respaldos

Tu memoria vive solo en el iPhone. De vez en cuando ve a **Ajustes → Exportar respaldo** y guárdalo en iCloud Drive.
Si cambias de teléfono: instala la app y usa **Importar respaldo**.

## Actualizar la app

Si cambias `index.html`, súbelo de nuevo al repo y cambia `VERSION` en `sw.js` (por ejemplo `nexo-v3`).
La próxima vez que abras la app con internet se actualizará sola. Tus datos no se tocan.

## Cómo usarla

- **Inicio**: escribe, dicta (botón de micrófono), pega un correo o adjunta una captura → **Enviar**.
  Nexo entiende si quieres guardar algo nuevo, cambiar lo que ya existe o preguntar algo.
  Ejemplos: "A Maru le encantó el perfume Delina", "Mueve el perfume a Goodies", "Marca los útiles como comprados",
  "Cambia el viaje al 22 de diciembre", "Crea una lista para la casa".
  Siempre te muestra los cambios para revisarlos antes de aplicarlos, y todo se puede **Deshacer**.
- **Lo que importa hoy**: lo vencido, lo de esta semana y los cumpleaños que vienen (con tus ideas de regalo).
  **Brief del día con Nexo** te da un resumen directo de qué hacer primero.
- **Listas**: toca una lista → **Editar** para cambiar nombre, icono, color u orden. El botón con destello te deja pedirle cambios a Nexo sobre esa lista.
- **Cualquier elemento**: tócalo para editarlo todo, o escribe arriba "Pídele un cambio a Nexo".
- **Nexo (chat)**: pregunta lo que sea; solo responde con lo que tú guardaste, y también puede editar cosas.
- **Fechas**: en un elemento con fecha → **Añadir al Calendario** para que el iPhone te avise.
- **Ajustes**: tu avatar, tus datos y los de tu familia, Gemini y los respaldos.
