# Rafaela 15 - versión Render

## Render
- Runtime: Node
- Root Directory: dejar vacío
- Build Command: `npm install`
- Start Command: `npm start`
- Environment Variable: `ADMIN_PASSWORD` = una clave privada que tú elijas

La aplicación no usa better-sqlite3 ni módulos nativos, para evitar el error de compilación que puede aparecer en Render.

## Panel privado
Después del despliegue: `https://TU-SERVICIO.onrender.com/admin?key=TU_CLAVE`

IMPORTANTE: en Render Free el disco local puede ser efímero. Esta versión está pensada para que el despliegue funcione; para conservar registros ante reinicios/redeploys se recomienda luego conectar una base de datos externa o un Persistent Disk.
