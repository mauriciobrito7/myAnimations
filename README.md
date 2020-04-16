# MyAnimations

Es una librería de animaciones empaquetadaas en mixins de Sass. Esta inspirada en animate.css

## ¿Cómo usarlo?

Puedes usar MyAnimations con CSS o con Sass (recomendable)

### Con CSS

- Descarga el archivo `my-animations.css` e incluyelo en tu proyecto. Luego puedes agregar las siguientes clases a los elementos que deseas que se animen:

```language-css
.fade-in
.fade-out
.slide-left
.slide-right
.slide-top
.slide-bottom
.slide-down
.slide-up
.zoom-in
.zoom-out
.bounce-left
.bounce-right
.bounce-up
.bounce-down
```

### Con Sass

- Instale MyAnimations con el comando `npm install --save-dev my-animations`.
- Importe `my-animations.scss` en su proyecto `@import "./node_modules/my-animations/my-animations.scss"`.
- Establezca la variable `$myAnimationsHelpers: false` para compilar solo lo necesario (debe de hacerlo antes importar my-animations).

- Los mixins disponibles son:

```language-scss
fadeIn($time)
fadeOut($time)
slideLeft($time)
slideRight($time)
slideTop($time)
slideBottom($time)
slideDown($time, $height)
slideUp($time, $height)
zoomIn($time)
zoomOut($time)
bounceLeft($time)
bounceRight($time)
bounceUp($time)
bounceDown($time)
```
