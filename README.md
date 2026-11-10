# Cuarto del bebé 3D


## Enlaces

- Modelo del cuarto: https://ingarmandotirado.github.io/Carpinteria/
- Despiece para el carpintero: https://ingarmandotirado.github.io/Carpinteria/comoda/
- Muebles a medida (buró, mueble de TV, librero, escritorio): https://ingarmandotirado.github.io/Carpinteria/muebles/

El nombre del repositorio lleva **C mayúscula**: GitHub Pages distingue mayúsculas, con `carpinteria` en minúscula da 404.

Modelo 3D interactivo del cuarto del bebé, hecho a medida (three.js). Se abre en el navegador, también en el celular.

**Ver en línea:** se publica con GitHub Pages desde `index.html` (Settings → Pages → rama `main`, carpeta `/`).

## Medidas (m, desde piso terminado)

| Elemento | Medida |
|---|---|
| Muro A (minisplit, de marco de puerta a esquina A–B) | 2.93 |
| Muro B (a la derecha de A) | 2.98 |
| Muro C (frente a A, incluye closet de 0.60) | 3.53 |
| Muro D (frente a B: puerta 0.90 · divisorio 0.15 · closet 1.93) | 2.98 |
| Altura | 2.82 |
| Zoclo cerámico | 0 – 0.082 |
| Recuadros de moldura (3 por muro en A y B, márgenes de 10 cm) | 0.182 – 0.87 · A 84.3 cm · B 86 cm |
| Cenefa (remate = barandal de cuna = cubierta de cómoda) | 0.97 – 1.05 |
| Ventanal en muro C (2 hojas iguales) | de 1.04 a 2.93 · alto 2.02 |
| Closet: puertas / velicera | 0 – 2.10 / 2.10 – 2.82 |

Colores: lambrín, molduras y cenefa blanco perla satinado `#F3EFE7`; muro superior beige mate `#D8C6A5` en los 4 muros.

## Qué se puede hacer

- Vistas: general, interior, muro A, muro B, esquina A–B, muro C, muro D.
- Antes / después (molduras y pintura).
- Tocar puerta, closet, cortinas y lámpara para abrir, cerrar, prender o apagar. Luz de techo desde el panel.
- Editar muebles: mover arrastrando o con medidas en cm, girar, cambiar tipo, tamaño y color, duplicar, eliminar, deshacer/rehacer. Los muebles no se enciman. El diseño se guarda en el navegador y se puede copiar/pegar como texto.
- Cuna Delta Children Royal 4 en 1 con cambiador (183 × 79.7 × 105 cm).

## Cómoda a medida: despiece interactivo

`comoda/index.html` calcula el despiece de la cómoda del muro B para el carpintero:

- Altura total = altura de la moldura medida en obra − aire (base: 97 − 2 = 95 cm).
- Frentes por fuera o al ras del marco, con separación entre frentes de 2 a 25 mm (con tiras de marco al ras cuando caben).
- Filas, cajones por fila (igual o distinto en cada fila), altos y anchos de frentes, rieles, cierre y jaladera.
- Mueble hasta el piso: zócalo al ras, metido o frente inferior hasta el piso; recorte abajo atrás para librar el zoclo.
- Botón mm / pulgadas (fracciones de 1/16").
- Armado 3D, explosión del mueble con la clave de cada pieza, alzado y corte con medidas.
- Acabados pintado o madera con veta visible. Tono de madera en un mapa (claro a oscuro, gris a rojizo), con muestras comunes (maple, pino, encino, roble, teca, cerezo, caoba, nogal, wengué, ébano) y tonos lisos (blancos, greige y grises). El despiece indica en qué medida corre la veta.
- PDF de fabricación con armado, explosión, planos, despiece, herrajes y notas.
- Guardar configuraciones con nombre (en el dispositivo), compartirlas por enlace público y abrir las públicas de `comoda/configs.json`.

### Configuraciones públicas

`comoda/configs.json` es la lista pública que ve cualquiera en “Guardar / abrir”. Cada entrada lleva `nombre`, `fecha` y `config` (solo los valores que cambian respecto a la base). Para agregar una, copia su enlace con el botón “Enlace” y pásalo para sumarlo a la lista.

## Muebles a medida

`muebles/index.html` empieza preguntando qué mueble vas a hacer y abre sus menús propios.

- **Fase 1:** buró (independiente de la cama), mueble de TV, librero y escritorio. Próximamente: cama, mesa de comedor, mesa de centro, silla y banco, clóset.
- **Material:** tablero (MDF, triplay, melamina) o madera maciza (pino, cedro, parota, encino) con despiece por pies tabla.
- **Revisiones por tipo:** altura respecto al colchón (buró), largo y altura según la pantalla (TV), claro máximo de repisas para que no se pandeen (librero) y espacio libre para piernas (escritorio).
- **Costo aproximado y precio sugerido** para Sinaloa en dos categorías: carpintero independiente y taller profesional. Material, herrajes, acabado, horas, merma, gastos, utilidad e IVA; todos los precios son editables.
- Armado 3D con cajones y puertas que abren, explosión con claves, alzado y corte, mm o pulgadas, tono de madera, guardar con nombre, enlaces y PDF (con o sin costos).
- `muebles/configs.json` es la lista pública de ejemplos.

### Estudio de mercado (noviembre 2026)

Precios publicados de muebles terminados en México, usados para calibrar tarifas y márgenes y mostrados en la página para comparar:

| Mueble | MDF / tablero | Madera maciza |
|---|---|---|
| Buró | $500–2,000 básico · $3,300–7,000 diseño | Pino $500–3,000 · parota $5,000–12,000 |
| Mueble de TV 180 cm | $2,500–4,500 básico · $9,900–11,000 centro de entretenimiento | Encino $3,900–18,600 · parota $10,000–30,000 |
| Librero | $700–3,500 | Pino $1,000–8,000 |
| Escritorio 120 cm | $2,000–7,000 | $1,800–13,400 |

Fuentes: Liverpool, IKEA, Mercado Libre, Home Depot, Mate Design, Casa Ferro, Muebla, Flamingo, Santa Cruz Woodworks, Amazon México, Sears.
