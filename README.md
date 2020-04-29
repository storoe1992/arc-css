# ARC-CSS
### Arquitectura CSS
### Estructura HTML5

* Se utiliza el método 7 x 1 para organizar el código CSS.
   * <strong><u>Abstract:</u></strong> Contiene archivos .scss que no son convertidos a .css, sólo se importan a otro archivo .scss. Contiene código como variables SASS, mixins y funciones.
      * _functions.scss
      * _mixins.scss
      * _placeholders.scss
      * _variables.scss


   *  <strong><u>Base:</u></strong> Contiene archivos .scss para importar a style.scss. Contiene código para estilos de etiquetas HTML como p, a, body, etc. La tipografía puede ir en esta sección, así como también el archivo reset para restablecer los estilos del navegador.
      *  _animation.scss
      *  _base.scss
      *  _reset.scss
      *  _typography.scss

   * <strong><u>Componentes:</u></strong> Contiene archivos .scss para importar a style.scss. Contiene código para estilos de componentes separados e individuales del layout, como botones y carrusel.
     * _buttons.scss
     * _carousel.scss

* Utilizamos SASS como pre-procesador.

* Estructura base HTML5
   * Nav
   * Header
   * Main
   * Footer

* Recursos de terceros:
   * Bootstrap 4.4.1 (CDN comentado - SASS)
   * FontAwesome 5 (CDN)
   * JQuery 3.4.1 (CDN)