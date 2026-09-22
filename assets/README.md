# Assets por proyecto

Carpetas para subir archivos e imágenes ordenados por proyecto. Cada página de detalle en `proyectos/` referencia su propia carpeta.

## Carpetas

- `conversor-unidades/` → Lámina 01 · Conversor de unidades
- `complemento-hidrologia/` → Lámina 02 · Complemento Hidrología
- `autolisp-hidrosanitarias/` → Lámina 03 · AutoLISP hidrosanitarias
- `riesgo-inundaciones-chocaya/` → Lámina 04 · Riesgo de inundaciones Chocaya
- `riego-tecnificado-aspersion/` → Lámina 05 · Riego tecnificado por aspersión
- `pdc-plan-desarrollo-curricular/` → Lámina 06 · PDC Plan de Desarrollo Curricular
- `centro-impresiones/` → Lámina 07 · Centro de Impresiones

## Qué va en cada carpeta

- Imágenes de la galería (portadas, detalles, capturas).
- PDFs y archivos del proyecto (guías, ejemplos, planillas).

## Convención de nombres

- Minúsculas con guiones.
- Numeración al inicio para ordenar: `01-portada.jpg`, `02-detalle-grafico.png`, `03-ejemplo-uso.pdf`.

## Tamaño recomendado

- Ancho máximo aproximado de 1920 px.
- JPG para fotos, PNG para capturas de pantalla.
- Mantener los archivos livianos para carga rápida.

## Cómo referenciar desde las páginas

Cada página de detalle usa rutas relativas a su carpeta:

`../assets/<carpeta>/archivo`

Ejemplo:

```html
<img src="../assets/conversor-unidades/01-portada.jpg" alt="Portada conversor de unidades">
```
