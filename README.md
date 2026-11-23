# ClipLive Studio — publicación gratuita en GitHub Pages

Repositorio: https://github.com/dereckserrano1908-lgtm/-cliplive-studio

## Publicación sin instalar programas

1. Abre https://github.com/dereckserrano1908-lgtm/-cliplive-studio y entra en la rama `main`.
2. Selecciona **Add file → Upload files**.
3. Descomprime este ZIP y arrastra **los archivos que contiene** (no la carpeta ni el ZIP) a la raíz del repositorio: `index.html`, `app.js`, `sw.js`, `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png` y, si el sistema lo admite, `.nojekyll`. Puedes omitir README.md si ya existe uno.
4. Haz clic en **Commit changes**.
5. Abre **Settings → Pages** y en **Build and deployment** selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)**. Guarda.
6. Cuando GitHub Pages confirme el despliegue, la dirección esperada será: https://dereckserrano1908-lgtm.github.io/-cliplive-studio/
7. En Windows 11, abre esa dirección en Edge o Chrome y selecciona la opción de instalar el sitio como aplicación.

## Qué funciona
- Añadir enlaces de canales Twitch, Kick y YouTube aunque estén offline.
- Buscar y administrar canales guardados localmente.
- Analizar de manera experimental picos de audio en archivos de video locales para proponer marcas de 30, 45 o 60 segundos; debes revisarlas.
- Exportar e importar canales y marcas aprobadas mediante JSON.
- Instalar la página como PWA bajo HTTPS en navegadores compatibles.

## Limitaciones importantes
- No comprueba si los streamers están en vivo ni captura transmisiones.
- No usa IA multimodal, no genera subtítulos y no exporta clips MP4.
- La aplicación web y su código son públicos mediante GitHub Pages; **no hay inicio de sesión**. La información que agregas se guarda solo en el navegador y se pierde al borrar sus datos. No se sincroniza entre dispositivos.
- El procesamiento en el navegador requiere tener el dispositivo y la aplicación activos; no funciona continuamente con dispositivos apagados.
- El análisis de audio puede fallar para algunos videos MP4 o archivos grandes; suele ser más compatible con ciertos WebM.
