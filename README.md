# La Interaccion

## seleccionar
`querySelector`
selecciona elementos de 0 - 1 elementos

`querySelectorAll`
te retorna todos los que concuerden con el selector
se pueden modificar los elementos uno por uno
por: clase, texto
y tambien removerlo

`getElementById`
solo selecciona por id
se usa muy raramente la sintaxis


## crear elementos o etiquetas con atributos
`createElement` desde js

`appendChild` agregar hijo

## eventos
`addEventListener` coolbacks

diferencia de:

`load` : espera a que cargen todo o el csss
`DOMContentLoaded` : solo espera html pero no CSS - es mas rapido 

uso de window. 
scroll 
onload - es como el `load` 

## accion por default en input - submit
`.preventDefault`para validar un formulario

## eventos con teclado
`.target.value` mostrar los valores de inputs o textarea
`.target` contiene el input

`.target.id` contiene por id

muy inportante
tienen que ser del mismo nombre las llaves del objeto con los IDs

## eventos formulario
diferencia de evento 
`'click'`  - asociada concualquier elemento, mas usada para enviar a  un arreglo
`'submit'` - asociada con el formulario, mas usada para enviar informacion

Ordenar

1ro - variables arriba
2do - los addEventListener
luego - las funciones

## validador de formulario p1

`usando destruction` - permite extraer los valores de un arreglo pero tambien crear las variables en un mismo paso

`return` - corta la ejecucion del codigo

mandar mensaje en html la verificacion
y removerlo

## validador de formulario p2
refactory

error = null
if 
else