PATCH — IA cover limpia + favicon vertical

Incluye:
- assets/img/ia-poder-cover.jpg
- assets/img/favicon.ico
- assets/img/favicon.png
- assets/img/favicon-16.png
- assets/img/favicon-32.png
- assets/img/favicon-48.png
- assets/img/favicon-64.png
- assets/img/favicon-180.png
- assets/img/favicon-192.png
- assets/img/favicon-512.png
- assets/img/apple-touch-icon.png
- assets/img/site.webmanifest
- favicon.ico

Qué corrige:
1. Imagen del artículo de IA:
   - Tapa por completo el texto anterior.
   - Reescribe el título limpio con “1.”.
   - Mantiene imagen y logo de fondo.

2. Favicon:
   - Sustituye el favicon por una versión cuadrada/vertical del logo.
   - Incluye también favicon.ico en la raíz, porque muchos navegadores lo buscan ahí.

Cómo subir:
1. En GitHub sube/reemplaza assets/img/ia-poder-cover.jpg.
2. En GitHub sube/reemplaza todos los favicon dentro de assets/img.
3. Sube también favicon.ico en la raíz del repositorio.
4. Haz commit.
5. Netlify actualizará automáticamente.

Importante:
Los favicons se cachean muchísimo. Si no cambia de inmediato:
- abre en ventana privada,
- prueba https://www.futuroglobal.es/favicon.ico?v=3
- borra caché del navegador,
- espera unos minutos después del deploy.
