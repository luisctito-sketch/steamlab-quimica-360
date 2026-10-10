# STEAMLab · Galería molecular de seis superficies

**Cuaderno N.º 09. Química universitaria.** Prototipo para GitHub Pages.

1. Crear repositorio `steamlab-quimica-360` público.
2. Subir los cinco archivos a la raíz (`index.html`, `control.html`, `proyectar.html`, `config.js`, `estilo.css`).
3. Activar Settings → Pages → Deploy from branch → main → /(root).
4. Abrir la URL del repositorio y acceder a `control.html`.
5. Abrir cada una de las seis vistas, que representan cuatro paredes, techo y piso.

**Sincronización:** los cambios de molécula y la pausa se comparten entre ventanas del mismo navegador, perfil y computadora mediante `BroadcastChannel` y `localStorage`. Si se usan varios computadores independientes, no quedarán sincronizados sin un servidor adicional. Las animaciones pueden tener desfases.

**Montaje físico:** GitHub no proyecta por sí mismo ni calibra seis proyectores. Para una sala 360° real hay que disponer de salidas de vídeo, orientación y corrección geométrica de cada proyector, unión de bordes (*edge blending*), gestión de brillo y medidas de seguridad para el cableado y los haces luminosos. Empezar con una pantalla/proyector.

**Ciencia:** modelos didácticos de H₂O, CO₂, CH₄ y NH₃. Geometrías VSEPR aproximadas. Las esferas, tamaños y animaciones no corresponden a observaciones directas de átomos ni a escala física; el movimiento es una ilustración, no dinámica molecular.

**Actividad:** formular hipótesis VSEPR, contrastar geometría, ángulos y polaridad y justificar por qué CO₂ (enlaces polares) es una molécula apolar, mientras que H₂O es polar. Culminar con una escultura molecular y discusión de límites del modelo.
