# coipo_sitra — guía para agentes

Repositorio de **entrega**, no de desarrollo: contiene el prototipo SITRA (solicitudes Ley 20.285, CONAF) como un
único `index.html` autocontenido. Ver [`README.md`](README.md) e [`insumos/`](insumos/).

## Estructura (VERIFICADO)

- `INSUMO/SITRA_publicar/` — `index.html` (~2,7 MB), `robots.txt`, `_headers`, `LEEME.txt`.
- `insumos/` — `00-PROBLEMA.md`, `01-SOLUCION.md`, `MANIFIESTO.yaml` (generados desde el código; con marcas `[PENDIENTE]`/`[VERIFICAR]`/`[INFERIDO]`).
- `.github/workflows/readme.yml` — regenera README/insumos con `Sud-Austral/coipo_aireadme@v1`.

## Comandos

No hay build, lint ni pruebas. Para verlo: abrir `INSUMO/SITRA_publicar/index.html` en el navegador.

## Reglas

- **Datos sensibles**: el HTML contiene expedientes reales despersonalizados (según `LEEME.txt`). No extraer, pegar en otros
  documentos ni publicar su contenido; la revisión de Fiscalía es previa a cualquier difusión.
- Mantener `robots.txt` y `_headers` (noindex): es un enlace de revisión, no una publicación institucional.
- `index.html` es un artefacto generado con datos incrustados: no editarlo a mano; no se conoce aquí la herramienta que lo
  genera (pendiente de confirmar por el equipo).
- Las marcas `[PENDIENTE]` y `[VERIFICAR]` de `insumos/` las resuelve el área usuaria o Fiscalía, no un asistente.
- No commitear `.env`, claves ni datos personales.
