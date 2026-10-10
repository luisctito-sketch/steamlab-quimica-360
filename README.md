# STEAMLab Química 360° — sala animada V2

En GitHub Pages, abre `sala-inmersiva.html`. Esta página usa **laboratorio-fondo.png** como escenario 16:9 real y superpone moléculas giratorias sobre tres paredes, techo y piso, además de partículas luminosas y cinco haces animados procedentes del equipo central ilustrado.

## Publicar
Sube todos los archivos de este ZIP a la raíz de tu repositorio actual `steamlab-quimica-360`, reemplazando nombres repetidos y agregando `laboratorio-fondo.png`. Activa GitHub Pages con la rama main y root. Abre `https://luisctito-sketch.github.io/steamlab-quimica-360/sala-inmersiva.html?v=2`.

## Diagnóstico
- Si falta la imagen verás un aviso, no una pantalla celeste silenciosa. Confirma que `laboratorio-fondo.png` esté junto al HTML y respete mayúsculas/minúsculas.
- Abre la vista en orientación horizontal y pulsa Pantalla completa.
- Pulsa Pausar: las moléculas deben detenerse. Cambia el selector para mostrar solo una especie.
- Los dibujos de moléculas no son simulaciones realistas de trayectorias atómicas ni cambian químicamente.

## Alcance
Esta aplicación **simula visualmente** desde un monitor una sala de tres paredes, techo y piso. No controla proyectores físicos ni constituye un sistema de projection mapping. Los haces de luz y el dispositivo central forman parte de la representación artística, con capas animadas.

## Actualización de enlace
El botón **ENTRAR AL AULA INMERSIVA ANIMADA** de `index.html` lleva a `sala-animada-v2.html?v=20261010`, nombre nuevo que evita reutilizar el HTML celeste anterior almacenado en caché. Se conserva `sala-inmersiva.html` como ruta alternativa y se debe subir `laboratorio-fondo.png` junto a los HTML.
