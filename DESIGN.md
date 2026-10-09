# DESIGN.md · Sasa Art Floral (propuesta de rediseño)

## Lectura
Web de floristería de autor en Sant Just Desvern. Quien llega desde Google o Maps busca ramos, composiciones o flores de boda hechas a medida y quiere llamar o escribir. Modo: convencer. Nivel: cuidado. Diales: variación 6, movimiento 3, densidad 3.
Rediseño sobre el mismo contenido: se conserva el nombre, el tono propio (frases cortas, de tú a tú) y el material fotográfico; se descarta la maqueta de 760 px en Courier.

## Concepto
**Una estructura de líneas que sostiene la flor.** Su trabajo son cañas, alambre y madera con flor por delante. La web usa lo mismo: líneas finas verticales (tallos) que sostienen las fotos.

## Gesto audaz (solo uno)
Portada: cuatro fotos suyas "colgadas" de tallos de 1 px que bajan hasta una línea de suelo, a alturas distintas. Los tallos se dibujan al cargar. No se repite en el resto de la página, salvo la línea fina como separador.

## Color
| Token | Valor | Papel |
|---|---|---|
| pared | #EEF0E9 | fondo (yeso con una gota de verde, como la pared de sus fotos) |
| papel | #F7F8F3 | superficies claras |
| tinta | #16241B | texto y bloque final |
| lino | #46554B | texto secundario (6,9:1 sobre pared) |
| caña | #476338 | tallos y filetes (5,9:1) |
| amapola | #C2361A | acción (blanco encima 5,5:1) |

Un acento (amapola), solo en botones y enlaces de acción. Sin crema, sin terracota, sin casi negro con acento ácido.

## Tipografía
Archivo variable (eje de ancho), autoalojada.
- Titulares: ancho 62-70 %, peso 400-500. Estrechos y altos, como los tallos.
- Texto: ancho 100 %, peso 400, 17-18 px, interlineado 1,6.
- Cifras tabulares en teléfono.
Escala móvil/escritorio con `clamp()`. H1 máximo 3 líneas a 375 px.

## Forma
Fotos rectangulares sin radio (láminas). Botones con radio 2 px. Filetes de 1 px color caña al 35 %.

## Composición
Portada (texto + tallos) · Ramos (texto + lista de ocasiones + fotos escalonadas) · Composiciones (lista con miniaturas) · Bodas (frase grande + mosaico) · Cómo trabajamos (cuatro pasos reales) · Quién está detrás · Contacto (bloque oscuro con fachada).
Barra fija inferior en móvil: llamar y escribir.

## Principios
1. Las fotos son suyas y se enseñan pequeñas y nítidas, nunca ampliadas hasta ablandarse.
2. Cada sección acaba cerca de una acción, con la misma etiqueta: «Llamar al 934 73 08 68».
3. Solo texto que sale de su web. Lo que falta se omite.

## Descartado
- Hero con foto a sangre: sus fotos miden 177×250 px.
- Reseñas, horarios, precios y WhatsApp: no hay fuente fiable.
- Serif display con acento cálido: es el uniforme de «floristería con gusto» y el de media web de estudio.
