# Claudia-Gomez-Eventos-app-web
Proyecto para cotizar, vender, registrar pagos, etc., para eventos de mamá.

--------------------------------------------------------------------------------------------------------
🧩 Stack Tecnológico

Backend: Django (Python)
→ Ideal para manejar cotizaciones, usuarios, y conexión con bases de datos.

Frontend: HTML + CSS (Tailwind o Bootstrap) + JavaScript
→ Personalizable y rápido de implementar.

Base de datos: SQLite (para desarrollo) → PostgreSQL (producción)

Pagos: Integración con PSE (via ePayco o Wompi).

Despliegue: Render, Railway o Vercel (gratis o muy barato).

--------------------------------------------------------------------------------------------------------

🚀 Roadmap del Proyecto (por fases)
Fase 1 — Planificación y diseño

Definir objetivo principal de la app (cotizar, vender, registrar pagos, etc.)

Especificar productos o servicios de la empresa (mesas, decoración, sonido, catering, etc.)

Crear un mapa de funcionalidades

Carrito de compras

Cotización automática

Pasarela de pago (PSE)

Panel de administración (para tu mamá)

Historial de pedidos y cotizaciones

Boceto visual del sitio (wireframe simple).

Fase 2 — Configuración del entorno

Crear entorno virtual Python

Instalar Django y crear proyecto base

Crear la app principal (por ejemplo, eventos o cotizador)

Configurar base de datos local y servidor de desarrollo.

Fase 3 — Modelado y lógica

Crear modelos:

Servicio (nombre, descripción, precio, categoría)

Carrito

Cotización / Pedido

Cliente

Configurar el panel de administración de Django para gestionarlos.

Fase 4 — Interfaz y frontend

Crear vistas HTML (home, catálogo, carrito, checkout)

Estilizar con Tailwind o Bootstrap

Añadir interactividad con JavaScript (añadir al carrito, actualizar totales, etc.)

Fase 5 — Pasarela de pago PSE

Elegir proveedor (recomiendo Wompi o ePayco, ambos colombianos)

Crear cuenta sandbox (modo prueba)

Implementar integración paso a paso (API REST o widget).

Validar flujo completo: selección → carrito → pago → confirmación.

Fase 6 — Panel de administración

Sección para que tu mamá vea cotizaciones y pagos

Posibilidad de editar servicios, precios y estados de pedidos

Exportar cotizaciones a PDF o Excel.

Fase 7 — Despliegue

Configurar proyecto para producción (entorno seguro)

Subir a Render o Railway (backend Django)

Vincular dominio personalizado si lo desean

Pruebas finales de usabilidad.

Fase 8 — Extras (a futuro)

Envío automático de correos de confirmación

Chat o WhatsApp directo

Autenticación de clientes

Generador de facturas PDF

--------------------------------------------------------------------------------------------------------
