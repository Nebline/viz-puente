# viz-puente

Pagina puente para conectar Mercado Libre con Viz ERP mientras la API corre en local.

Mercado Libre exige una direccion de vuelta con https y fija. `mercadolibre/index.html` solo reenvia el codigo y el estado de la autorizacion a la API local (`http://localhost:4000`). El codigo no sirve sin el secreto de la aplicacion ni el verificador PKCE, que nunca salen del servidor.

Direccion publicada: https://nebline.github.io/viz-puente/mercadolibre/
