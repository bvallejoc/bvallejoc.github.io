# bvallejoc.github.io

Página personal de Benjamín Vallejo Calizaya: https://bvallejoc.github.io

## Estructura

- `index.html`: la página. No necesitas editarla para agregar contenido.
- `data/contenido.json`: todo el contenido (investigación, escritos, código, fotografía).
- `docs/`: PDFs de papers y ensayos.
- `cv/`: CV en PDF.
- `fotos/`: imágenes de la sección Fotografía (crea la carpeta al subir la primera foto).

## Agregar un ensayo

1. Sube el PDF a `docs/` (Add file → Upload files).
2. Edita `data/contenido.json` (ícono de lápiz) y agrega en `"escritos"`:

```json
{
  "titulo": "Título del ensayo",
  "area": "Economía",
  "meta": "Curso, año",
  "resumen": "Una o dos líneas.",
  "links": [{ "texto": "PDF", "url": "docs/archivo.pdf" }]
}
```

Separa cada entrada con una coma. El campo `area` agrupa los escritos (por ejemplo: Economía, Historia y filosofía, Ciencia y sociedad).

## Agregar una foto

Sube la imagen a `fotos/` y agrega en `"fotografia"`:

```json
{ "archivo": "fotos/nombre.jpg", "descripcion": "Descripción breve" }
```

## Actualizar el CV

Reemplaza `cv/cv_benjamin_vallejo.pdf` subiendo un archivo con el mismo nombre.
