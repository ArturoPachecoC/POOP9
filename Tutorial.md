---
marp: true
author: Arturo Pacheco 
size: 4:3 
theme: gaia 
--- 
# Tutorial de extensiones de VS code
## En este tutorial se revisaran markmap, Marp for VS code y PlantUml  
---  
### Marp: 
Marp es la extención más fácil de entender, pues tomalo como otro editor de texto ya sea como word u algunaopción que tu manejes. Marp lo usaremos para hacer presentaciones tales como la que estas viendo en este presiso momento,
***

- La primer cosa que hay que saber es la parte de lo que podemos llamar  "configuracion de la presentación, donde podemos seleccionar un color, tamaño, autor; entonces lo que harás es: 
```py  
---
marp: true
author: Arturo Pacheco 
size: 4:3 
theme: gaia 
---  
``` 
*** 
En la imagen, los tres guiones y el marp:true son obligatorios y no podrás trabajar sin ellos.  

- Para escribir hay muchas formas, para un título pondrás un # sumado con una frase, para un subtitulo serán dos ## y así sucesivamente; para escribir texto como este solo hace falta escribir, cada línea es un párrafo; y también puedes elegir entre estios de letra y para hacer un salto de diapositiva se pondran 3 *: 
***
``` 
# Bienvenido a POO 
## Tipo de marcado 
JIJIJIJA 
- **negritas** 
    - Hola 
- *italica* 
- ~tachado~
- `for code`  
***
``` 
*** 
- Igual podrás agregar imágenes ya sea de links de internet o una imagen de las siguientes formas: 
``` 
##Una red neuronal
![Red neuronal width:300px height:300 px](https://i.ytimg.com/vi/oNWbpY7tcrs/maxresdefault.jpg)


  
## Imagen Local
![Checoculon  height:500px](Checoculon.jpg) 
``` 
-Y también puedes usar códigos con ``` 
``` py 
print('Estoy usando ub codigo hola mundo') 
``` 
*** 
## Markmap 
Mark map nos sirve para crear mapas mentales my sencillos y bonitos, las ramas se van partiendo similar a los subtitulos en la extención anterior, con el uso de los # 
```
# Mapa mental 
## Rama 1  
### Sub rama 1 
#### mundo
## Rana 2 
## Subnivel de rama 2 
``` 
*** 
![markmap  height:500px](markmap.jpeg)  

*** 
## PlantUML 
Los diagramas son definidos usando un lenguaje simple e intuitivo. (Guía de Referencia del Lenguaje PlantUML).
Los usuarios nuevos pueden leer la página de inicio rápido. También está la página F.A.Q. PlantUML puede ser usado dentro de muchas otras herramientas.
Las imagenes pueden ser generadas en PNG, en SVG o en formato LaTeX. También es posible generar diagramas de arte en ASCII (solo para diagramas de secuencia). 
*** 
``` 
Bob->Alice : ¡Hola! 
```