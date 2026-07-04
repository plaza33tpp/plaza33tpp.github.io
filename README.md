# Carta · Restaurante Plaza 33

Carta digital del **Restaurante Plaza 33** (cocina peruana y amazónica), pensada para verse en el celular al escanear un código QR en la mesa.

🔗 **En línea:** https://antianrose.github.io/carta-plaza33/

## ¿Cómo actualizar precios o platos?

Todo el contenido vive en [`index.html`](index.html). Para cambiar un precio o una descripción:

1. Abre `index.html` y busca el nombre del plato (⌘F).
2. Edita el texto o el número del precio.
3. Guarda y sube el cambio (o pídele a Claude que lo haga).

El sitio se actualiza solo en 1–2 minutos. **El código QR no cambia nunca** — apunta a esta misma dirección, así que no hay que reimprimir nada.

## Estructura

- `index.html` — la carta completa (diseño, iconos y datos, todo en un archivo).
- `assets/` — ilustraciones botánicas, logo y favicon.
- `qr/` — material imprimible del QR (no se publica en el sitio).

## Iconos de proteína

Cada plato muestra iconos de sus proteínas principales: camarón, pescado, res, pollo, cerdo, pulpo, conchas, queso y huevo. La referencia aparece al inicio de la carta.
