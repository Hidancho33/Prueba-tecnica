# Prueba Técnica — Mejoras Responsive y Visuales

## Introducción

Primero que todo, muchas gracias por la oportunidad de realizar esta prueba técnica.

El objetivo principal fue tomar el archivo entregado y realizar mejoras visuales, responsive y de experiencia de usuario, manteniendo la línea gráfica original del proyecto y respetando la estructura base existente.

Durante el desarrollo intenté enfocarme no solamente en "hacer que se viera bien", sino también en entender cómo estaba construido el archivo, identificar problemas de layout y adaptar la experiencia para diferentes tamaños de pantalla.

Además de los cambios visuales, aproveché para realizar limpieza de código y pequeños ajustes estructurales que ayudaran a mejorar la legibilidad y el mantenimiento del archivo.

---

# Objetivos trabajados

* Limitar el contenido a un ancho máximo de 1200px.
* Mejorar completamente la experiencia mobile responsive.
* Mantener la identidad visual original.
* Corregir problemas visuales y de distribución.
* Mejorar interacciones y experiencia de usuario.
* Limpiar y organizar parte del código existente.

---

# Cambios realizados

## 1. Responsive Design

Se trabajó la adaptación responsive pensando principalmente en:

* Desktop
* Tablet
* Mobile

Se agregaron media queries para reorganizar secciones, evitar desbordamientos y mejorar la lectura del contenido en pantallas pequeñas.

### Algunos ajustes realizados:

* Contenido principal centrado con `max-width: 1200px`
* Elementos con tamaños fijos convertidos a tamaños fluidos
* Secciones reorganizadas en columna para mobile
* Botones adaptados a ancho completo en pantallas pequeñas
* Corrección de cards que rompían el layout
* Ajustes de tipografía responsive usando `clamp()`

Uno de los puntos que más me costó fue el hero: tenía `float` y anchos fijos en píxeles que en mobile simplemente rompían todo. Estuve un buen rato probando en DevTools antes de entender por qué pasaba y cómo solucionarlo con flex.

---

## 2. Mejoras visuales

Sin cambiar la línea gráfica original, se mejoraron varios aspectos visuales:

* Espaciados
* Distribución de contenido
* Jerarquía visual
* Hover en botones
* Hover en cards
* Sombras
* Animaciones suaves
* Aparición progresiva de secciones al hacer scroll

La intención fue hacer que la página se sintiera más moderna e interactiva sin alterar el diseño original del proyecto.

---

## 3. Interacciones y experiencia de usuario

Se añadieron pequeñas mejoras enfocadas en UX:

* Animaciones al entrar elementos en pantalla (scroll reveal)
* Efecto ripple en botones al hacer clic
* Efectos hover más claros en botones y tarjetas
* Mejor feedback visual para interacción del usuario
* Transiciones suaves para evitar cambios bruscos
* Parallax suave en la imagen de la sección final

Estas mejoras fueron hechas con CSS y JavaScript nativo, evitando dependencias externas. Para el scroll reveal usé `IntersectionObserver`, que no conocía antes de esta prueba, lo descubrí investigando cómo hacerlo sin librerías.

---

## 4. Limpieza y organización del código

El archivo original tenía bastante código generado automáticamente, clases repetidas y estilos difíciles de mantener.

Se realizó:

* Eliminación de código innecesario
* Limpieza de reglas CSS vacías
* Corrección de estilos redundantes
* Organización de bloques responsive
* Ajustes de legibilidad del código
* Eliminación de algunos elementos sin uso funcional

También intenté mantener el código lo más entendible posible para futuras modificaciones, dejando algunos comentarios en los puntos donde hice cambios más relevantes.

---

# Herramientas utilizadas

Durante el desarrollo utilicé principalmente:

* HTML5
* CSS3
* JavaScript
* DevTools de Chrome
* Responsive Design Mode
* Documentación y pruebas en navegador

También me apoyé en herramientas de asistencia con IA (vibe coding) para investigar soluciones, entender patrones que no manejaba del todo y acelerar partes del proceso donde me trababa, especialmente en las animaciones y en la organización de los bloques responsive. No lo usé para generar el código completo y ya, sino más como apoyo para leer, entender y después aplicar lo que necesitaba. Creo que es importante mencionarlo porque fue parte real del proceso.

---

# Aprendizaje personal

Esta prueba me ayudó bastante a poner en práctica temas de responsive design, organización visual y análisis de código existente.

Una de las partes que más me gustó fue revisar cómo pequeños cambios en estructura, spacing y comportamiento responsive pueden mejorar mucho la experiencia final del usuario.

También fue interesante trabajar sobre un archivo ya construido, porque obligó a analizar primero cómo funcionaba antes de empezar a modificarlo. Me pasó varias veces que quise cambiar algo rápido y tuve que frenar, entender la estructura, y recién ahí modificar.

---

# ¿Qué haría diferente con más tiempo?

* Refactorizar los nombres de clases del archivo original (hay muchas con nombres bastante informales que dificultan el mantenimiento).
* Mejorar la accesibilidad: revisar contraste de colores, agregar `aria-label` donde falta y asegurar navegación por teclado.
* Probar en más dispositivos reales, no solo en el simulador de Chrome.
* Separar los estilos del HTML en un archivo CSS externo para que sea más fácil de mantener.

---

# Consideraciones finales

Intenté mantener un equilibrio entre:

* mejorar visualmente la página,
* respetar el diseño original,
* y no sobrecargar el proyecto con cambios innecesarios.

Seguramente todavía hay aspectos que podrían seguir mejorándose o refactorizándose, pero traté de entregar una solución sólida dentro del tiempo planteado para la prueba.

Nuevamente, muchas gracias por la oportunidad y por el tiempo dedicado a revisar la entrega.

Quedo atento a cualquier retroalimentación, recomendación o comentario sobre la prueba.
