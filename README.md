# Tratamiento Luna

App web/PWA para control personal del tratamiento de Luna.

## Archivos que debes subir a GitHub

Sube estos archivos y carpetas tal como están, en la raíz del repositorio:

- `index.html`
- `manifest.json`
- `service-worker.js`
- `receta.jpg`
- carpeta `icons/`

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo, por ejemplo `tratamiento-luna`.
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. En GitHub, entra a **Settings** > **Pages**.
4. En **Build and deployment**, elige:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Guarda.
6. GitHub te dará una liga parecida a:
   `https://TU_USUARIO.github.io/tratamiento-luna/`

## Para agregarla al inicio del celular

1. Abre esa liga en Chrome.
2. Toca los tres puntos.
3. Elige **Agregar a pantalla principal** o **Instalar app**.
4. Nómbrala `Tratamiento Luna`.

## Nota

Los datos se guardan en el navegador del celular mediante `localStorage`.
Si borras datos del sitio o cambias de navegador, podrías perder el progreso.
