# Juego de la vida simplificado con HTML5, CSS3 y JavaScript usando canvas.

Estado final del proyecto de ejemplo desarrollado en la jornadas "Tecnologías web para todxs". Se trata de un [juego de la vida](https://es.wikipedia.org/wiki/Juego_de_la_vida) básico con HTML5, CSS3 y JavaScript para mostrar
un uso básico del elemento canvas en aplicaciones interactivas.

## Cómo ejecutarlo e instrucciones

Puedes probarlo directamente en [alexvj.github.io](alexvj.github.io)

### Instrucciones de juego
Es un juego de 0 jugadores, en el sentido de que simplemente evoluciona por si mismo a raíz de un estado inicial. No hay objetivo, es simplemente un simulador, un autómata celular.

Haciendo click en las celdas puedes añadir células

En un paso del juego (pulsando el botón _Un paso_):

- Si una celda vacía (célula muerta) tiene a su alrededor exactamente 3 celdas llenas (células vivas), nacerá una célula en esa celda.
- Si una célula viva tiene exactamente 2 o 3 células vivas a su alrededor, dicha célula se mantiene con vida.
- Si una célula tiene menos de 2 células vivas a su alrededor morirá (de hambre), también lo hará si tiene más de 3 células vivas a su alrededor (por superpoblación).

Simplemente rellena casillas y pulsa _Automático_ por ver qué ocurre.

### Descargar este proyecto y ejecutarlo en local

No requiere nada especial, simplemente descargar el proyecto y abrir **index.html** con un navegador decente (recomiendo Firefox).

---

## Licencia
[Trabajo bajo licencia de software libre GNU GPLv3+.](https://www.gnu.org/licenses/gpl-3.0.html)

---

## Sobre este proyecto
### Fecha de desarrollo/exposición
9 de julio de 2020 (desarrollo/explicación en directo)

### Duración
Una hora como máximo.

### Objetivos
- Dar una muy breve introducción al desarrollo de aplicaciones interactivas enfocadas en canvas.
- Acercar a otrxs desarrolladorxs al mundo JavaScript, enseñando sintaxis y mecanismos básicos del lenguaje.
- Explicar las tecnologías básicas y las ventajas de conocerlas y defenderse sin frameworks frontend _aunque vayas a utilizar finalmente un framework frontend_.

### Objetivos para futuros talleres que NO encontrarás en este proyecto
- Aprender flujos estándar para trabajar con un sistema de control de versiones (como git).
- Aprender a desarrollar de forma guiada por pruebas (Test-Driven Development, TDD).
- Conocer los mecanismos avanzados de ES6+.
### Requisitos
- Conocimiento básico en programación (no importa lenguaje).
  
## Sobre los instructores
### Alexander Vega Jiménez
Programador fundamentalista. Defensor de las buenas prácticas, patrones y arquitecturas, pero con un profundo respeto por aquellxs que se atreven a experimentar con nuevas formas de trabajar, y aún más por quienes "hackean" tecnologías muy básicas para hacer cosas muy frikis.

## Descarga de responsabilidad
Este proyecto fue producto de una presentación, preparado para su desarrollo y explicación "en vivo" en menos de una hora, con mucho componente de improvisación. Tuvo una revisión rápida de calidad antes de subirse a github sólo para incluir y adecuar comentarios. No pretende ser un "ejemplo de ingeniería" y puede contener malas prácticas fruto de un entorno pensado con fines pedagógicos y de entretenimiento.
