Este proyecto puede ser clonado y levantado para pruebas.

1. Tener instalado Node.js y MongoDB Compass (o MongoDB Server).
2. Clonar el repositorio.
3. Crear la base de datos en MongoDB Compass e importar los archivos JSON
   de la carpeta `database-example` en sus respectivas colecciones.
4. Copiar el archivo `.env.example` como `.env` y completar las variables,
   agregando tu propia llave secreta (JWT_SECRET).
5. Ejecutar `npm install` en las carpetas `proyecto` (frontend) y
   `web-server-express` (backend).
6. Levantar el backend (`npm run dev` en `web-server-express`) y el
   frontend (`ng serve` en `proyecto`).
7. Iniciar sesión para probar los diferentes módulos con los usuarios
   de prueba:
   - Usuario: `admin` — Contraseña: `12345`
   - Usuario: `cliente` — Contraseña: `12345`
