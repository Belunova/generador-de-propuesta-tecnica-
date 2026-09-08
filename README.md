# Generador de Propuesta Técnica — NEXATIA

Prompt maestro de NEXATIA para generar, a partir de los datos de un cliente, dos documentos en una misma respuesta:

1. **Ficha Técnica del Proyecto** (PDF, sin precios) — la primera idea que recibe el cliente.
2. **Propuesta Comercial** (HTML autocontenido, con precios) — la explicación completa con inversión y financiación.

## Contenido

- [`PROMPT.md`](./PROMPT.md): prompt único (v12 — Web más cara + E-commerce como línea nueva) con el catálogo de precios, reglas de negocio, diseño de los dos documentos y tono de copy.
- [`NEXATIA_Resumen_Servicios_v2.xlsx`](./NEXATIA_Resumen_Servicios_v2.xlsx): resumen de servicios de referencia.

## Uso

1. Abrí un chat nuevo con acceso a creación de archivos.
2. Pegá **solo el bloque de código** de la sección "PARTE 3 — PROMPT ÚNICO" de [`PROMPT.md`](./PROMPT.md) como primer mensaje.
3. En el segundo mensaje, dale los datos del cliente (nombre, sector, tamaño de empresa, dolor real, qué tiene montado hoy, bloques elegidos, comercial y fecha).
4. La IA devuelve el PDF (Ficha Técnica) y el HTML (Propuesta Comercial) en la misma respuesta.

Ver el detalle completo de reglas de uso y checklist previo al envío en [`PROMPT.md`](./PROMPT.md), sección "PARTE 2 — CÓMO USAR ESTO EN LA PRÁCTICA".
