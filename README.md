# cochayuyo
Un kit de HTML para la etiqueta &lt;MAPS>

Al paso que desde que Flash sucumbió  a la estocada final de Apple, hemos visto una caída en las aplicaciones con graficos dinamicos inmersivos. Flash permitia crear entornos muy dinamicos, con un sentido casi cinematografico.

Y entonces antes la necesidad de hacer un mapa de clicks sobre un archivo PNG, volví a la antigua etiqueta MAP, ya que es para eso.

Sin embargo, mi problema se suscitó al ver que MAPS no es responsive per sé, y que al resizear el browser, la coleccion de coordenadas de polígonos que definen las área de clicks.

Tras recorrer varias librerias y documentacion

https://www.w3schools.com/html/html_images_imagemap.asp

https://github.com/stowball/jQuery-rwdImageMaps

https://blog.travismclarke.com/project/imagemap/

Finalmente, nos quedamos con la libreria imagemap

<!--<script src="https://unpkg.com/image-map/dist/image-map.jquery.js"></script>-->

Y usamos esta herramienta para asignar las zonas de clicks

https://www.image-map.net/

Finalmente hicimos una página HTMLS muy simple pero que al "resizear" el browser, las coordenadas de los poligonos se escalan y el mapa sigue funcionando.

Es solo una prueba de concepto, pero si le pones diseño, se puede ver increible.
