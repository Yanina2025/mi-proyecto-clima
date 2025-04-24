1-¿Qué mala práctica identificaste?

Pude observar malas Prácticas como:
* En el Index.css en la Línea 735, que hay clase definida pero no se aplican en ninguna parte de index.html, suma solo lineas innecesarias y parece que tiene una funcionalidad pero no existe. 
  .map-section--active {
            display: block;
        }
* Ausencia de Comentrios especificos, es decir dentro de todo el Código solo hay comentarios generales y no especificos la cual dificulta la comprensión, al identificar cual es la función de cada linea de código, como una Guía Práctica. 

2-¿Por qué es considerada una mala práctica?

1- Clase definida pero no utilizada:
   * Agrega líneas innecesarias al código.
   * Confunde al lector, ya que parece que hay una funcionalidad dinámica (mostrar el mapa) que en realidad no está implementada.

2-Ausencia de comentarios específicos:

    * Dificulta entender el propósito de bloques de código específicos.
    * Perjudica el trabajo colaborativo.
    * Hace más difícil retomar el proyecto luego de un tiempo.

3-¿Cómo la solucionaste?

1- Se puede Eliminar la clase .map-section--active del archivo CSS ya que no cumple ninguna función actual en el proyecto.
2- Se agregaron comentarios específicos y descriptivos antes de cada sección principal en HTML y CSS, con algunos ejemplos. 

4-¿Qué beneficios aporta tu solución?

1- Facilita el mantenimiento.
   Elimina ambigüedad sobre funcionalidades inexistentes.
   Mejora la organización general del archivo CSS.

2- Facilita la lectura y comprensión del código.
   Sirve como guía rápida para nuevos desarrolladores.
   Mejora la calidad general del desarrollo.

   