# coipo_sitra

Prototipo de **SITRA** (Sistema de Tramitación y Respuesta Asistida para solicitudes Ley 20.285 de CONAF),
entregado como una página estática única lista para publicar. VERIFICADO: título y descripción en
`INSUMO/SITRA_publicar/index.html`.

No es una aplicación con backend: no hay código fuente, dependencias, base de datos ni pruebas en este repositorio.

## Contenido

```
INSUMO/SITRA_publicar/
  index.html    prototipo completo (~2,7 MB, motor y datos incrustados)
  robots.txt    Disallow: / (enlace de revisión, no indexar)
  _headers      cabeceras X-Robots-Tag noindex y Referrer-Policy no-referrer (las aplica Netlify)
  LEEME.txt     instrucciones de publicación (Netlify Drop, GitHub Pages) y avisos previos
insumos/        documentos de problema y solución
```

## Cómo verlo

Abrir `INSUMO/SITRA_publicar/index.html` en un navegador. No hay paso de build ni comandos.
Para publicarlo, seguir `INSUMO/SITRA_publicar/LEEME.txt`.

## Advertencia sobre datos

Según `LEEME.txt`, el HTML incluye 757 expedientes reales con texto completo de solicitudes y respuestas,
despersonalizados por reglas (no infalible), y se pide revisión de Fiscalía antes de compartir el enlace fuera de la
institución. No lo comprobé de forma independiente. No publicar ni copiar este archivo sin esa revisión.

## Configuración y despliegue

Sin variables de entorno. El único workflow (`.github/workflows/readme.yml`) regenera README/insumos con el
generador central `Sud-Austral/coipo_aireadme`; no despliega nada. El despliegue real es manual (ver `LEEME.txt`).

## Más documentación

- [`CLAUDE.md`](CLAUDE.md) — guía para agentes
- [`insumos/00-PROBLEMA.md`](insumos/00-PROBLEMA.md)
- [`insumos/01-SOLUCION.md`](insumos/01-SOLUCION.md)
