# Decoración - By Valentina Esperidioni

## Tema elegido
Decoración del hogar: velas aromáticas, sets decorativos y difusores de ambiente.

## Objetivo de la galería
Ofrecer un espacio donde cualquier persona pueda conocer distintas opciones de decoración (velas, sets y difusores) y usarlas como inspiracion para renovar o ambientar su propio hogar.

## Descripción de la propuesta
Sitio web de inspiración para decorar el hogar, con tres categorías de productos: velas, sets y difusores. Cada categoría cuenta con su propia página, donde se presentan distintos modelos con foto, nombre, color/contenido y una breve descripción.

## Descripción de los contenidos incluidos
El sitio está compuesto por 4 páginas:
- **index.html**: página principal, con la presentación de la galería y accesos a cada categoría.
- **difusores.html**: catálogo de difusores de ambiente (4 modelos).
- **sets.html**: catálogo de sets decorativos, que combinan varios elementos (4 modelos).
- **velas.html**: catálogo de velas aromáticas y portavelas (4 modelos).

Todas las páginas comparten la misma barra de navegación, encabezado y pie de página, para mantener una identidad visual coherente en todo el sitio.

## Decisiones de diseño

### Colores elegidos
- **Beige (rgb(210, 184, 167))**: usado de fondo en el header, el footer y la barra de menú. Es un tono neutro y cálido, tipo arena.
- **Blanchedalmond**: color de fondo general del body, un beige muy claro que aporta suavidad al conjunto.
- **Marrón (rgb(137, 76, 7))**: color principal de los botones del menú y del botón de acción ("Click - asteri"), un marrón cálido tipo madera.
- **Marrones oscuros (rgb(74, 49, 10) / rgb(74, 37, 10) / rgb(88, 61, 22) / rgb(12, 8, 3))**: usados para el texto sobre los fondos claros, en distintas variaciones según la sección (header, footer, párrafos), para mantener buen contraste sin usar negro puro.
- **Blanco (rgb(255, 255, 255))**: usado en el texto de los botones, para que resalte sobre el fondo marrón oscuro.

### Tipografía utilizada
Se utilizó **Arial, Helvetica, sans-serif** como única familia tipográfica para todo el sitio (tanto títulos como texto de párrafo), variando el tamaño y el peso (bold) según la jerarquía de cada elemento. Al ser una fuente sans-serif estándar, ofrece buena legibilidad en cualquier dispositivo y navegador, sin distraer del contenido visual (fotos de los productos).

### Por qué estas elecciones se relacionan con el tema de la galería
La paleta de colores, basada en tonos beige, arena y marrón, busca transmitir la misma calidez y sensación hogareña que representan los productos exhibidos: velas, difusores y sets decorativos pensados para ambientar espacios. Se evitaron colores fríos o muy saturados para que el sitio en sí mismo funcione como una extensión de la estética "natural" y artesanal de la decoración (madera, cera, cerámica, vidrio), reforzando visualmente el concepto de un rincón cálido e inspirador para el hogar. La tipografía simple y sin adornos (Arial/Helvetica) mantiene el foco en las fotos de los productos, que son las verdaderas protagonistas de la galería.

### Organización y responsividad
Los productos se muestran en tarjetas (`.catalogo` / `.tarjeta`) organizadas con Flexbox, con un efecto de agrandado sutil al pasar el mouse. El sitio es responsive: mediante una media query, el menú y las tarjetas se reorganizan en una sola columna en pantallas de hasta 600px de ancho, para una correcta visualización en dispositivos móviles.

