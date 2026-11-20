# Transporte El Elyon · Web y panel del chofer

Demo de la web de paquetería, encomiendas y mudanzas (Goya · Resistencia).

- `index.html`: web para clientes. Enviar un paquete, pedir una mudanza y seguir el pedido.
- `chofer.html`: panel privado del chofer (con usuario y contraseña). Cambia el estado de los pedidos y sube la foto de entrega.

Los pedidos se guardan en Supabase. La clave que figura en los archivos es la pública (anon): la base está protegida con reglas de seguridad (RLS). Nunca subas acá la clave `service_role`.
