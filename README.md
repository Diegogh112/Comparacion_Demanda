# Comparador de Portafolios TI

Herramienta web para comparar el portafolio de demanda TI contra archivos Excel de otras áreas.

## Uso

1. Abre `comparador.html` directamente en Chrome o Edge (no requiere servidor).
2. Carga el Excel del Portafolio de Demanda (hoja `Demanda Táctica`, tabla `Cartera1017`).
3. Carga el Excel del área a comparar.
4. Configura las columnas de identificación y los vínculos de columnas equivalentes si aplica.
5. Pulsa **Comparar ahora**.

## Funcionalidades

- Matching por ID Trámite → ID Mantenimiento → Otro ID → Nombre del Requerimiento
- Detección automática de tablas Excel y encabezados
- Filtro por campos con diferencias (chips seleccionables)
- Tabla con columnas pareadas (Portafolio / Área) con colores
- Exportación a Excel con colores y fila inmovilizada
- Vínculos de columnas equivalentes entre archivos

## Tecnología

- HTML + JavaScript puro (sin backend)
- [xlsx-js-style](https://github.com/gitbrent/xlsx-js-style) para lectura y exportación de Excel con estilos
