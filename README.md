# viz-puente

Página puente para conectar Mercado Libre con Viz ERP mientras la API corre en local.

Mercado Libre exige una dirección de vuelta con https y fija. `mercadolibre/index.html` solo reenvía el código y el estado de la autorización a la API local (`http://localhost:4000`). El código no sirve sin el secreto de la aplicación ni el verificador PKCE, que nunca salen del servidor.

Dirección publicada: https://nebline.github.io/viz-puente/mercadolibre/
