DORCA CONECTA - GITHUB + VERCEL

1. Sube al repositorio estos archivos y carpetas:
   index.html
   logo-dorca.png
   package.json
   vercel.json
   data/rates.json
   api/rates.js

2. Vercel debe desplegar desde la rama principal del repositorio llamada "principal".

3. Para que el administrador pueda PUBLICAR cambios para todos los clientes, crea en Vercel una variable de entorno de Producción:
   GITHUB_TOKEN = token de GitHub con permiso Contents: Read and write para el repositorio.

4. La contraseña del administrador es:
   Dorca2013

5. El repositorio utilizado por esta versión es:
   carlis24680-coder/Dorca-Conect

6. La aplicación lee las tasas públicas desde data/rates.json y el administrador las actualiza mediante api/rates.js.

IMPORTANTE: nunca pongas GITHUB_TOKEN dentro de index.html. Debe quedar solamente como variable de entorno de Vercel.
