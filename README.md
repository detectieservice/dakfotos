# dakfotos

Een **one-page fotogalerij** met dakwerken en realisaties. De pagina toont
147 unieke dak- en dakwerkfoto's in een responsief raster — geen tekst,
geen menu's, enkel de foto's.

## Inhoud

- `index.html` — de galerijpagina (CSS grid, `auto-fill minmax(240px, 1fr)`,
  `object-fit: cover`, lazy loading van de afbeeldingen).
- `files/project/` en `files/project-gallery/` — de `.webp`-foto's waarnaar
  `index.html` verwijst.

De foto's zijn afkomstig uit
[detectieservice/dakwerken-hendrickx](https://github.com/detectieservice/dakwerken-hendrickx)
(de mappen `files/project/` en `files/project-gallery/`, samengevoegd en
ontdubbeld op bestandsnaam tot 147 unieke foto's).

## Publiceren via GitHub Pages

1. Ga naar **Settings → Pages**.
2. Kies bij *Source* de branch `main` en map `/ (root)`.
3. Na een korte build is de galerij live op
   `https://detectieservice.github.io/dakfotos/`.

Omdat alles statisch is (HTML + afbeeldingen) is er geen build-stap of
afhankelijkheid nodig.
