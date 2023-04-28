# ProyectoCoder
## MueblesDesign
### Descripción
Este proyecto tiene como objetivo exponer un muestrario al usuario de algunos productos que presenta la empresa MueblesDesign en el rubro moviliario.
### Tecnologías utilizadas
- HTML5
- CSS
- SASS
- Bootstrap
- Git
- GitHub
### Desarrollo del proyecto
1. Para crear el proyecto de MueblesDesign en primer lugar se realizaron 5 HTML:
- Index
- Cocina-Comedor
- Living
- Dormitorio
- Contacto
2. En segundo lugar se procedió a crear un CSS común para todos los html. En dicho CSS se creó el logo del sitio, el cual es el nombre del sitio. Se le colocó
"Position Sticky" a la nav y se dicidió dejar el botón "Inicio" para comodidad del usuario, de manera tal que si este se encuentra en el footer y quisiera ir a la pantalla
"Inicio" lo tiene a mano en la nav y no será necesario hacer scroll hacia arriba para ir hasta el logo. Para la maquetación de las distintas pantallas se utilizó
box model, Flexbox y Grid. Cada imagen de los productos es, a su vez, un link que lleva a otra imagen del mismo producto visto desde otro plano.
3. El siguiente paso fue el de hacer el sitio responsive en modo mobile first. Está adaptado para desktop y mobile. Las imágenes están optimizadas para una buena experiencia del usuario.
Se le dio animación a la imágenes mediante scale, mayor a 768px se le dio un valor de 1.01 y menor a 768px un valor de 0.98.
4. Luego se procedió a insertar Boostrap al proyecto. Se incluyó la nav de este framework en tamaño mobile (hasta 768px) como así también un carrusel en la pantalla
Cocina-Comedor, también en tamaño mobile (hasta 768px).
5. Uno de los últimos pasos fue el de agregarle SASS para darle un estilo prolijo y ordenado al CSS. El SASS se dividió en los siguientes Partials:
- "vars", donde se contiene las distintas variables.
- "mixins", donde se contienen algunos extends y mixins.
- "commons", donde encontraremos los valores comunes a todo el proyecto
- "nav", donde se contienen los estilos de la nav, el header, y la imagen heroe del index.
- "productos", donde se contiene el estilo de todos los productos del sitio en tamaño mobile.
- "contacto", donde encontraremos los estilos de la pantalla contacto en tamaño mobile.
- "footer", donde se contiene el estilo del footer en tamaño mobile.
- "mediasQ", donde se contienen los valores en distintos puntos breakpoint (450px, 576px, 725px, 768px, 800px, 830px, 850px, 900px, 992px, 1100px, 1200px, 1250px y 1400px)
6. En el sexto paso se agrega SEO al proyecto agregandole los metas de "keywords", "author" y "description". El uso del texto alternativo en todas las imagenes,
uso correcto de la semántica, el h1 correspondiente en todas las pantallas. Con respecto a este punto cabe aclarar en el index el h1 se encuentra dentro del main
el cual es posterior a dos secciones. Se decidió hacerlo de esa manera por el hecho de que en el main encontramos el contenido principal del index y no en las 
dos secciones anteriores.
7. Finalmente se crea un repositorio en GitHub y mediante Git se envía el proyecto a dicho repositorio.
