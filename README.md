# DigiAgro

Sitio web estatico de DigiAgro enfocado en posicionamiento digital, trazabilidad SENASA y soluciones comerciales para empresas del agro.

## Contenido

- `index.html`: landing principal del sitio.
- `senasa.html` y `Senasa*.html`: flujo y pantallas relacionadas con la app/experiencia SENASA.
- `contacto.html`, `nosotros.html`, `mapa.html`, `privacidad.html`, `eliminar-datos.html`: paginas de soporte.
- `bot-helm.html` y `bots-web-digiagro.html`: contenidos especificos sobre bots y automatizacion.
- `CNAME`: dominio personalizado.
- Imagenes, favicons y videos (`.png`, `.jpg`, `.mp4`) servidos de forma estatica.

## Stack

- HTML estatico
- CSS embebido en las paginas
- JavaScript vanilla
- Assets locales para imagenes y video

No hay `package.json` ni paso de build.

## Verlo localmente

```bash
cd digiagro
python3 -m http.server 8000
```

Luego abrir `http://localhost:8000`.

## Deploy

El repositorio esta preparado para hosting estatico. Si se usa GitHub Pages o un hosting propio, mantener:

- la raiz del proyecto como carpeta publica
- el archivo `CNAME`
- las rutas relativas a assets y paginas auxiliares

## Notas

- La app SENASA vive dentro del mismo repositorio como conjunto de paginas HTML.
- Si se agregan nuevas pantallas del flujo SENASA, conviene enlazarlas desde la landing o desde la navegacion de la experiencia existente.
