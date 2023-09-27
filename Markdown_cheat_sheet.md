# Markdown

## Texto
* `* text *` italic
* `** text **` bold
* `*** text ***` italic bold
* `~ text ~` texto subscrito
* `^ text ^` texto superscrito
* `~~ text ~~` tachado
* `> text` blockquote (cita)

## Titulos
Los titulos se definen con `#` y van incrementando segun el nivel del titulo.
- `#` titulo 1
- `##` titulo 2
- `###` titulo 3
- etc.

## Listas
* `*` o `-` listas no ordenadas 
* `{numero}. ` listas ordenadas (ejem: 1. )
* `- [ ] ` y `- [x]` lista de tareas o checklist

## Imagenes
Tienen la forma de: 

`![text alt](url)` donde `text alt` es el texto alternativo cuando no carga la imagen.
> Para imagenes que se repiden varias veces en el documento se pueden definir entre corchetes y al final indicar la url. Asi:

> texto texto `![logo google][logo]` texto texto `![logo google][logo]` texto texto `![logo google][logo]`.

> `[logo]: https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png`

### Hipervinculo en imagen
Para que al clickear en una imagen esta nos envíe a alguna dirección web, lo que tenemos que hacer es "combinar" la sintaxis para añadir imagenes y para crear un hipervínculo en nuestro documento. Esto quedaría del tipo: 

`[![text alt](url_image)](url_web)`

## Enlaces
Tienen la forma de: `[text](url)`

> Para textos grandes donde hay enlaces del mismo tipo se puede definir los textos entre corchetes y al final indicar la url. Asi:  
> texto texto `[google]` texto texto `[google]` texto texto `[google]`.  

> `[google]: https://www.google.com`

## Codigo
* `code` (entre backtiks) codigo en linea.
* ```language code``` (entre 3 backtiks) codigo de bloque

Ejems:

- En JS con `let` declaro variables y con `const` las constantes.

- Un codigo de bloque se ve asi:
```javascript
const holaMundo = () => "Hola mundo"
```

> Una libreria recomendada para colorear bloques de codigo en a web es: https://prismjs.com

## Tablas
Para crear tablas se definir la siguiente estructura:
```
title | title | title
--- | --- | ---
text | text | text 
```
> Teniendo en cuenta que la fila 2 es la sintaxis que define la estructura de la tabla.

Tambien tenemos variaciones o ajustes adicionales:
* `---|---:|---` texto de la columna 2 alineado a la derecha.
* `---|:---|---` texto de la columna 2 alineado a la izquierda.
* `---|:---:|---` texto de la columna 2 alineado al centro.