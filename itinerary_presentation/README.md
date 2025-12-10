# Presentación del Itinerario Familiar en Valencia

Este directorio contiene los archivos fuente y generados para la presentación del itinerario de viaje familiar a Valencia (19 y 20 de Diciembre).

## Archivos

*   **itinerary_expanded.tex**: Código fuente LaTeX de la versión extendida y detallada de la presentación (más de 15 diapositivas).
*   **itinerary_valencia_expanded.pptx**: Presentación PowerPoint generada a partir de la versión extendida.
*   **itinerary.tex**: Código fuente LaTeX de la versión original (resumida).
*   **itinerary_valencia.pptx**: Presentación PowerPoint generada a partir de la versión original.

## Generación

Los archivos PPTX se generaron utilizando Pandoc y LaTeX con el siguiente comando:

```bash
pandoc itinerary_expanded.tex -o itinerary_valencia_expanded.pptx
```
