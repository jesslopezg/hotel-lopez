# Hotel López — Sabores de Colombia

Sitio web conceptual y responsive para un hotel inspirado en la cultura y gastronomía colombiana en Cartagena.

## Inventario propuesto
- **King Caribe:** 34 habitaciones; 1 cama king; hasta 2 personas; tarifa indicativa COP 490.000/noche.
- **Doble Queen:** 33 habitaciones; 2 camas queen; hasta 4 personas; tarifa indicativa COP 590.000/noche.
- **Suite Sabores:** 33 suites; cama king y sala; hasta 2 personas; tarifa indicativa COP 890.000/noche.
- Total: **100 habitaciones**. La división más equitativa posible entre 3 categorías es 34/33/33.

## Cómo publicar con GitHub Pages
Repositorio → **Settings** → **Pages** → **Build and deployment** → **Deploy from a branch** → **main / (root)** → Save.
URL esperada (una vez habilitado Pages): https://jesslopezg.github.io/hotel-lopez/

## WhatsApp
Editar `script.js`, constante `CONFIG.whatsappNumber`, con un número oficial en formato internacional **sin +**, por ejemplo `573001234567` (solo ejemplo ficticio). Hasta entonces el botón muestra aviso y no envía mensajes a terceros.

## Concierge virtual
El widget funciona 24/7 en el navegador mientras el sitio esté disponible; **es un asistente de respuestas predefinidas**, no un modelo generativo ni un agente IA conectado. No envía datos a servidor ni usa claves API. Para convertirlo en un **concierge AI auténtico** hay que conectar un backend seguro (Vercel/Netlify/Cloudflare) a un proveedor LLM, con límites de uso, control de costos, protección de datos personales, recuperación de información validada y, si corresponde, integración con PMS/reservas. Nunca publicar una clave de API en este repositorio estático.

## Limitaciones
Esto es un **prototipo conceptual**. Fotografías externas ilustrativas (Unsplash); no son imágenes verificadas del hotel. Dirección, restaurante, experiencias, tarifas definitivas, impuestos, términos y condiciones, disponibilidad y pasarela de pagos aún no están confirmados. El formulario prepara una **solicitud**, no confirma reservas ni procesa pagos.

## Precios de referencia
Las tarifas se plantearon como posicionamiento intermedio-alto y **no son tarifas de mercado verificadas para fechas específicas**. Benchmark orientativo: categorías King/Queen y suites publicadas por hoteles de Cartagena, incluido InterContinental Cartagena (precios variables por fecha/canal, frecuentemente superiores a COP 900.000 para habitaciones clásicas y COP 1.1 millones para suites en consultas públicas). Ajustar conforme a ubicación real, temporada, ocupación, servicios y competencia directa.

## Tecnología
HTML, CSS y JavaScript sin compilación; compatible con GitHub Pages. Para prueba local abrir `index.html` en un navegador moderno.
