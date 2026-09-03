MiPanel V3 conectado a Supabase.

1. Ejecuta supabase_v3.sql completo en SQL Editor.
2. Sube index.html a GitHub y reemplaza el anterior.
3. GitHub Pages usará ese index.html.
4. Prueba crear una cuenta y confirmar el correo.
5. Después prueba Servicios, Pedidos y Soporte.

Nunca pongas una secret/service_role key en el HTML. La clave publishable sí puede usarse en el frontend con RLS correctamente configurado.

Faltan para producción: pagos reales, recargas seguras, controles administrativos adicionales, historial financiero y endurecimiento de permisos.
