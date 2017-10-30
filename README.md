# Maquetado de Freelancer, ejercicio para Laboratoria


## Objetivo

El reto consiste en replicar el sitio de **Freelancer**, este será el resultado
a lograr:

![Freelancer Website](docs/fullpage.png)


## Realización

Para la realización de este reto dividí la página en un `nav` y 5 secciones. A cada una le fue otorgado un id para poder identificarla mejor y así no tener problemas al manipular dicha sección específicamente.

* `nav` contiene el título `h1` de la página, la barra de navegación con `position: fixed;` para que al hacer scroll por el sitio, permanezca siempre arriba.

* Cada sección se compone de: su título correspondiente -un `h2` (cuyo texto coincide con la id de la sección para ubicarnos mejor)-, un div `.logo-star` divisorio con dos `hr` y una estrella en medio, y su contenido específico.

* La primera sección es un `header` con características relevantes genéricas del freelancer.

* La segunda sección es un `section` con id `#portfolio`. Contiene imágenes en filas de 3 y alineadas al centro de la sección.

* La tercera sección es un `section` con id `#about`. Contiene un texto genérico y un botón para descargar el tema.

* La cuarta sección es un `section` con id `#contact-me`. Contiene un formulario de contacto heho a base de varios `input` y un `textarea`, todos de clase `.barra` para estilizar juntos, también contiene un botón para enviar los datos.

* La última sección es el `footer` que se divide en un `div` de id `#footer-box` y un `p`. El `div` contiene a su vez 3 `div` de clase `.sub-box` para acomodar y alinear mejor cada elemento, la clase es para que sean estilizados de la misma forma. Nuestro `p` va separado porque es el texto de Copyright que va centrado abajo de todo.

Para el CSS traté de no usar id o clases innecesarias, así que el plan fue acceder a los diferentes elementos del HTML a través de otros selectores y pseudoselectores, sobretodo el de descendencia, pero también utilicé :not(x), y first-child, sin contar los :hover o los :focus para estados específicos de mis links o inputs.


