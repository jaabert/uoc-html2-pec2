# Medieval

Hace unos años que tus amigos y tú quedáis para tocar algunas canciones y pasar el rato. Sonáis bastante bien, y después de algunos conciertos informales en vuestro barrio, os habéis decidido a dar el paso: ¡formaréis un grupo de música!.
Y a tí te tocó realizar el sitio web. La última vez ue os reunisteis, elaboraste rápidamente unos wireframes sobre la estructura y los contenidos básicos del sitio web.

# Descripción

Sitio web que siga las características que se especifican a continuación:

- El sitio web debe tener cuatro páginas (página de portada y tres páginas interiores), siguiendo los wireframes proporcionados. La temática del sitio web debe ser información sobre el festival de música que organizas. Toda la información que no se proporciona con el enunciado, así como la línea gráfica, la puedes decidir tú según tus gustos o te convenga. Debes seguir estas directrices sobre cada página:

  - La página de portada: debe estar maquetada con CSS Grid y debes realizar algun diseño interesante, parecido a lo que podría ser un póster promocional del grupo. Como punto de partida, puedes leer el artículo “How I design with CSS Grid” de Chen Hui Jing, en el que cuenta cómo realizar una página de portada en formato póster. También te puedes inspirar conn los vídeos de la Jen Simmons en su canal Layout Land. La maquetación que realices debe ser compatible con navegadores que no soporten CSS Grid, usando @supports y ofreciendo una versión alternativa, como se explica en la guía del módulo 3.2. Debes alcanzar los objetivos propuestos, pero no tienes que ser demasiado creativo o perder muchísimo tiempo en este apartado.

  - Una de las páginas interiores debe incluír una retícula con información sobre los miembros de la banda de música, maquetada con flex. Para esta retícula, no puedes usar las clases de Bootstrap .row o .col-\*.

  - Una de las páginas interiores debe seguir un formato de artículo e incluír un mínimo de 4 párrafos de texto y 2 fotografías. Puede ser una página que contenga información genérica del festival, una página del estilo noticia o nota de prensa, o cualquier otra opción que cumpla los requisitos descritos. A parte de la maquetación de la página deberás aplicar estilos a algunos elementos HTML que habitualmente podrían formar parte de una página de este tipo, como blockquote o listas (como se puede ver en el wireframe).

  - La tercera página interior es de contenido completamente libre. La puedes usar para enseñar cualquier cosa que sepas hacer o que hayas aprendido. Algunas ideas son: una página de contacto con un formulario funcional (puede ser interesante probar Netlify Forms), una galería de fotos interactiva, un juego, vídeos…

- El sitio web debe ser responsive y se debe poder ver correctamente desde cualquier dispositivo moderno (teléfono, tablet, ordenador…). En la reunión solo te dio tiempo de elaborar los wireframes de la versión de escritorio, así que deberás pensar cómo adaptas a dispositivos más pequeños la estructura acordada.

- [DONE] Debes partir de UOC Boilerplate para tu desarrollo. Asegúrate de estar usando la última versión (en el momento de escribir este enunciado, la última versión es la 3.5.0). Debes respetar la estructura y momenclatura de carpetas y ficheros (¡a menos que la metodología o guía de estilo escogida indique lo contrario!). Tienes toda la información sobre la instalación y uso en la guía de estilo del módulo 1.

- Debes escoger una o más de las metodologías y guías de estilo estudiadas en el módulo 2 y aplicarla en tu desarrollo.

- [DONE] Debes usar Bootstrap 5, cargado en UOC Boilerplate y personalizado con Sass como se indica en los materiales, y usar un mínimo de 4 componentes distintos.
- Bootstrap Debes personalizar algún parámetro de los componentes usados a través de variables Sass, como se explica en la sección Customize de la documentación de Bootstrap.

- [DONE] A parte, debes incorporar y usar otra dependencia externa, como FontAwesome o cualquier otra que consideres interesante. Puede ser una buena idea para la página de contenido libre. Puedes explicar en el foro cuál es, por qué la escogiste, y si tienes alguna duda o incidencia con su uso.

- Además de esta dependencia, debes instalar Stylelint y personalizar su configuración para que aplique los criterios de estilos elegidos, con plugins y reglas. Cuando ejecutes la orden para validarlo no debe aparecer ningún error.

- Debes usar necesariamente las siguientes características de Sass: variables, anidado, funciones, parciales e importación.

- [DONE] Una vez finalizado el desarrollo, deberás publicar el código en GitHub y realizar un deployment en Netlify, como se explica en la guía del módulo 1. URL: https://medieval-rock-band-pec2.netlify.app/

# Criterios de evaluación

## Desarrollo (70%)

- Uso correcto de UOC Boilerplate y dependencias externas (5%)
- HTML/Sass (5%)
- Uso de Bootstrap (5%)
- Uso de Flex (10%)
- Uso de Grid y @supports (15%)
- Página de contenido libre (5%)
- Diseño y responsiveness (10%)
- Aplicación de metodologías y guías de estilo, adecuación a estándares y calidad del código en general (5%)
- Configuración y aplicación Stylelint (5%)
- Publicación de repositorio y deployment (5%)

## Documentación (30%)

- Documentación del proceso de desarrollo (10%)
- Justificación de las decisiones tomadas en el desarrollo, dependencias instaladas y personalización, problemas resueltos… (10%)
- Justificación de la elección de la metodología y/o guía de estilo y descripción de la aplicación de los criterios elegidos (10%)
