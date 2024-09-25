# CSS
- lenguaje para dar estilos a la web

## SINTAXIS
- Como estableces codigo css
''' css
h1 {
    color: red;
}
'''
### leyenda CSS
- h1 : selector (elemento de html para aplicar un estilo)
- color : propiedad 
- red : valor (algunas propiedad pueden tener otros valores)

### SELECTORES
- Indica el o los elementos se van a aplicar los estilos
/* selector de etiqueta*/
''' css
h1 {
    color: red;
}
'''
/* selector de descendencia*/
nav ul li a {
    color : red:
}

### HERENCIA
-- Elementos ansestros (padres) heredan algunas propiedades a sus descendientes o hijos.

''' html ejemplo
 <p>hola mundo <a href="#">esto es un enlace</a></p>

''' CSS
p{
    color: green;
}
a{
    color: inherit;
}

etiqueta a hereda el color de su padre p

### CASCADA
- Los estilos que llegan en ulimo lugar sobreescriben al anterior
- la espeficidad vence a la cascada

''' h1{
    color: red;
}

h1{
    color: blue
}
''' 
### ESPECIFICIDAD
- es un valor numerico que adquieren los selectores y se aplican cuando hay conflictos
''' html
<!-- Selector de etiqueta  (1)-->
<!-- selector de clase (10)-->
<!-- selector de ID (100) -->
<!-- inline (1000) cuando el estilo se aplica en la linea de html -->

<!-- important infinito -->

h1{
    color: blue important;
}
'''


## REPOSITORIO
git remote add origin https://github.com/marcojan163/CSS01.git
git branch -M main
git push -u origin main


# SEGUNDA PARTE
### estilos de textos


## propiedades
- color : es el atributo que define el color de la etiqueta
- font-size (em,rem,px) establece el tamaño de la fuente de la etiqueta 
- font-family (google fonts - fontface) especifica la fuente a utilizar 
- font-weight (peso de tipografia)  estable el grosor de la fuente
- estilo entre navegadores (normalize.css) estandariza los estilos para los diferentes navegadores
- text-transform: uppercase | lowercase | capitalize - cambia el formato del texto a mayusculas, minusculas o Capital 
- text-align : left | center | right - establece la alineacion del texto 
- text-decoration : none | underline - establece una linea en el texto puede ser superior, medio , inferior o ninguna
- 
## SELECTORES
 
- Selector de Etiqueta(1)
- Selector de Clase(10)
- Selector de ID(100)
- Selector Universal (uso box model)


  
<!-- Actualizar el repositorio con lo visto en la 2da parte
  1) Explicar los conceptos con ejemplos
  2) (Agregar una nueva tipografia de google fonts, usando font-face)
-->
 