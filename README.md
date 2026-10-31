# Visor IFC

Visor de modelos IFC que funciona en el navegador (computador, tablet y celular).
El archivo se procesa en el equipo de quien lo abre: no se sube a ningún servidor.

- Vistas isométrica, planta (con corte a 1 m), frente y lateral, y cubo de orientación; transiciones suaves.
- Cortes por altura, eje X o eje Z con relleno negro; explosión por niveles; modos de color; capas; rayos X.
- Mediciones: distancia, ángulo, longitud y perímetro de polilínea, y caja de una pieza.
- Árbol por clases IFC o por estructura espacial (proyecto, sitio, edificio, piso), buscador y ficha de propiedades.
- Recintos con nombre y superficie, y vistas guardadas.
- Controles del mouse configurables y tema claro u oscuro.
- Abre archivos `.ifc` (STEP). No abre `.ifcZIP` ni `.ifcXML`.

Páginas descriptivas para buscadores: [`es/`](es/index.html) y [`en/`](en/index.html).

Usa [three.js](https://threejs.org) (MIT) y [web-ifc](https://github.com/ThatOpen/engine_web-ifc) (MPL-2.0), incluidos en `vendor/`.

Autor: Matías Alvarez C. · Workshop BIM + IA · The BIM Co-work
