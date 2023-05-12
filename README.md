<!-- MEJORAR EL PERFORMANCE
    
    Performance:  velocidad y eficiencia con la que se carga y se ejecuta una página en un navegador. Esto incluye la velocidad de carga de la página, la respuesta del servidor y el rendimiento de la página una vez que se ha cargado en el navegador.

    loading="lazy" -> la imagen o un iframe debe cargarse de manera diferida, es decir, solo cuando sea necesario y se muestre en el viewport (área visible en la pantalla) del navegador. es útil para mejorar el rendimiento de una página web. 

    preload -> indicar al navegador que un archivo debe ser descargado de manera anticipada, es decir, antes de que se necesite para mejorar la experiencia del usuario. Esto se logra especificando un <link> en la <head> de la página con un atributo rel establecido en "preload" y un "as" con la utilidad que tiene ese documento o archivo.

    prefetch -> es una técnica de optimización de rendimiento de la web que permite al navegador descargar de manera anticipada los recursos que se espera que se necesiten en el futuro. Esto incluye archivos como imágenes, hojas de estilo,documento html, scripts y otros recursos requeridos por la página.
    El prefetch se realiza especificando un <link> en la <head> de la página con un atributo rel establecido en "prefetch". Al hacer esto, el navegador descargará los recursos especificados en segundo plano, lo que los hará disponibles rápidamente cuando sean necesarios.


    picture -> se utiliza para mostrar imágenes adaptables en diferentes dispositivos y tamaños de pantalla. Con esta etiqueta, puedes especificar múltiples versiones de una imagen y el navegador elegirá la versión más adecuada para mostrar en función de las condiciones especificadas en las etiquetas < source > que se encuentran dentro de la etiqueta < picture >.
    Esto significa que puedes tener una versión de una imagen para dispositivos de alta resolución, otra para dispositivos de resolución más baja, y otra para dispositivos móviles, y el navegador elegirá la versión más adecuada en función de las condiciones especificadas en las etiquetas < source >.

    ejemplo: 
        <picture >
            < source srcset="imagen-alta-resolucion.webp" media="(min-width: 800px)">

            < source srcset="imagen-resolucion-media.jpg" media="(min-width: 400px)">

            < img src="imagen-mobile.jpg" alt="Descripción de la imagen">
        </ picture >

    meta:description -> me permite dar una descripcion de mi sitio web, eso ayuda a que el ceo se mas alto

    

-->

<!-- Nuevas Propiedades CSS

    -Background-position -> me permite posicionar una parte en especifico del background, si tenemos una imagen y queremos que en un dispositivo pequeño se muestre una parte de la imagen mas relevante podemos usar esta propiedad

        valores: 
        1. contenido horizontal: left, center, right
        2. contenido vertical: left,center, right, top, bottom

        tambien se pueden usar %, aunque es mejor los valores de posicion



    inline-bock -> permite margin(top,bottom) y width, lo que no hace el inline. este respeta el tamaño del contenedor con respecto al contenido (como un elemento de linea), pero tambien repeta su espacio de bloque, osea que un elemento no se puede posicionar a lado de el. 
-->
