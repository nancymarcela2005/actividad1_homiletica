# Actividades de Homilética

Dos proyectos independientes con HTML, CSS y JavaScript puro. Funcionan sin instalar paquetes y sin conexión a Internet después de descomprimir el archivo. No usan cuentas, base de datos, fuentes remotas ni servicios externos.

## Abrir en tu computador

1. Descomprime todo el ZIP. No abras los archivos directamente dentro del comprimido.
2. Abre `index.html` de la carpeta principal para elegir una actividad.
3. También puedes abrir directamente `propositos/index.html` o `conclusiones/index.html`.
4. Presiona «Pantalla completa» al proyectar. El botón depende del soporte del navegador; también puedes usar F11.

Cada carpeta de proyecto contiene:
- index.html: estructura de la página.
- styles.css: diseño, tarjetas y adaptación a celular.
- app.js: ejemplos y funcionamiento del juego.
- README.md: instrucciones específicas.

## Dinámica para 10 minutos por tema

- 0:00 a 1:00: presenta el concepto.
- 1:00 a 4:00: explica las diapositivas y muestra un ejemplo.
- 4:00 a 4:30: abre la aplicación y explica las reglas.
- 4:30 a 8:30: realiza la modalidad rápida con participación oral del grupo.
- 8:30 a 10:00: repasa la explicación final y pide una respuesta oral breve.

Si los 10 minutos son para ambos temas juntos: explica propósitos durante 2 min, juega parejas durante 3 min, explica conclusiones durante 2 min y realiza 3 min del taller. En parejas puedes pulsar «Cerrar y repasar» sin terminar la partida. El taller rápido tiene 4 retos; elige respuestas por consenso para mantener el ritmo.

No se necesita un celular por compañero. Divide el salón en equipos y haz que cada equipo diga dos números de tarjetas o proponga una respuesta. La expositora controla el dispositivo. Cada navegador tiene su propia partida; no hay conexión entre celulares ni marcador compartido.

## Proyecto Propósitos

Juego de memoria con tarjetas boca abajo, mezcladas en cada partida. La modalidad rápida tiene 4 parejas; la completa tiene 6. Cada pareja combina un propósito general con un propósito específico. Una pareja acertada permanece visible y abre una explicación con verbo, auditorio y contenido. Los errores vuelven a ocultarse. El reloj de 5 minutos es orientativo; no expulsa al grupo al agotarse. Pausar bloquea nuevas selecciones. Reiniciar solicita confirmación y mezcla de nuevo.

Pregunta de socialización: «¿Qué diferencia existe entre el propósito general y el específico? Señala verbo, auditorio y contenido en una pareja».

## Proyecto Conclusiones

Taller de selección con 4 retos rápidos o 6 completos. Se clasifican los cierres en recapitulación, aplicación/exhortación e ilustración; luego se corrige un cierre inadecuado. Cada error permite otro intento, pero solo los aciertos iniciales suman al marcador. Al final, el grupo propone un cierre oral de 30 segundos sobre Romanos 5:1-5. Esta producción oral la valora la expositora; no se califica automáticamente.

Las formas de concluir pueden combinarse; en la clasificación se identifica el recurso predominante.

## Publicar los dos proyectos juntos en GitHub Pages

1. Crea un repositorio, por ejemplo `actividades-homiletica`.
2. Sube el contenido completo de esta carpeta: el `index.html` principal y las carpetas `propositos` y `conclusiones`, conservando sus archivos.
3. En el repositorio entra a Settings > Pages.
4. En Build and deployment elige Deploy from a branch.
5. Selecciona la rama donde subiste los archivos, normalmente `main`, y la carpeta `/(root)`. Guarda con Save.
6. Cuando termine el despliegue, GitHub mostrará la dirección del sitio en esa sección. Abre la dirección para elegir el juego.

No se ha creado ningún repositorio ni publicado el contenido desde este paquete. No requiere npm, comandos de compilación, servidor de aplicación ni variables de entorno.

## Publicar cada proyecto por separado

Crea un repositorio para propósitos y otro para conclusiones. En cada uno sube el CONTENIDO de la carpeta correspondiente: index.html, styles.css, app.js y README.md, de modo que index.html quede en la raíz. Activa Pages como se explica arriba.

## Cambiar preguntas y ejemplos

En `propositos/app.js`, modifica la colección `PAIRS`. Cada entrada tiene categoría, verbo, auditorio, contenido, explicación y fuente. Para mantener la modalidad rápida actual, conserva las primeras seis entradas y sus identificadores o adapta su selección dentro de start().

En `conclusiones/app.js`, modifica `QUESTIONS`. `answer` es el índice de la respuesta correcta: 0 es la primera opción, 1 la segunda y 2 la tercera. La modalidad rápida toma las cuatro primeras preguntas.

## Fuentes y decisiones didácticas

- Seminario Bíblico de Cúcuta. (s. f.). Guía didáctica Unidad 1 de Homilética. Material aportado por la usuaria. Propósitos: pp. impresas 19-21. Conclusión: p. impresa 33. Modelación de Romanos 5:1-5: pp. impresas 33-34.
- Exposición «expo homiletica(2).pptx», aportada por la usuaria. Diapositivas 1-2: propósito específico. Diapositivas 3-5: conclusión.
- GitHub Docs. (s. f.). Configuring a publishing source for your GitHub Pages site. https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Se conservan los ejemplos de la guía de evangelístico, doctrinal, ético-moral y aliento, con correcciones gramaticales menores. Para devocional y consagración se redactaron ejemplos basados en las definiciones de la guía, evitando confundir sus finalidades. La guía también clasifica un ejemplo de afrontar problemas con fe como devocional; se eligió el ejemplo de adoración para que el juego tenga una asociación inequívoca con la definición de esa categoría. Los nuevos ejemplos del taller de conclusiones son adaptaciones didácticas, no transcripciones literales de los versículos.

## Accesibilidad y uso

Botones utilizables con Tab y Enter, foco visible, textos en español, diseño adaptable y animación reducida cuando el sistema lo solicita. Sin sonido automático. La partida no se guarda: recargar la página borra el avance. El resultado no es una evaluación certificativa.

## Navegación y diseño actualizados

En cada juego, «Inicio» regresa al menú principal y el enlace contiguo permite pasar a la otra actividad. Al salir se pierde la partida actual. Se incorporan los logos proporcionados de SBC y Asambleas de Dios, ilustraciones SVG locales, colores vivos y confeti en los aciertos. Las animaciones se desactivan si el dispositivo solicita movimiento reducido. Mantén las carpetas assets al subir el proyecto.

Para conservar el menú y los enlaces entre juegos, publica el paquete completo en un solo repositorio. Si vas a separar los proyectos en dos repositorios, cambia los enlaces de Inicio y del otro juego por las direcciones de tus sitios publicados.
