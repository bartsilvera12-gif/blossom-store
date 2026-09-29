# Blossom Store

Landing page de una tienda de lencería elegante, construida como una página HTML estática.

## Estructura

- `index.html` — página principal (marcado, estilos y contenido).
- `support.js` — runtime de soporte para los componentes de la página.
- `image-slot.js` — componente de slots de imagen (encuadre y posicionamiento).
- `.image-slots.state.json` — estado guardado del encuadre de las imágenes.
- `uploads/` — recursos gráficos usados por la página.

## Uso

Abrí `index.html` en el navegador, o servila localmente:

```bash
python -m http.server 8000
```

Luego entrá a http://localhost:8000

## Despliegue en Vercel

Sitio estático sin build. `index.html` está en la raíz, así que Vercel lo sirve tal cual.

1. En [vercel.com/new](https://vercel.com/new), importá el repo `blossom-store`.
2. Dejá Framework Preset en **Other** y los campos de Build/Output vacíos.
3. Deploy.

También se puede desde la terminal:

```bash
npx vercel --prod
```
