# Sesión 04 - 10/04 Apuntes
---
## Variables  
Introduciremos el movimiento en P5.js, hay variables que son constantes y otras que van fluctuando, hay algunas variables que vienen intregradas o¿y otras que se pueden crear.

### Pocisión del mouse:  
*Variable de sistema numerico* que determinan las pocisiones de x,y.   
Sintaxis: (mouseX,mouseY)
Ejemplo: (ellipse(mouseX,mouseY,100,100)

#### Apuntes:
- Si se coloca el background en setup, no quedará estela, si se pone el draw pintará el fondo.
- mouseX y mauseY se puede usar en las figuras, en el color, tamañao, diametro, pocisión, etc.

### Crear tus propias variables:  
1. Declarar tu variable
2. Inicializar tu variable
3. Usa tu varible

Para declarar la variable podemos usar:  
- let : Variables dinámicas
- const : Variables constantes
#### Apuntes:  
- Cuando son palabras distintas no se pone espacios si no, letras mayusculas para diferenciar las palabras.  
- Arriba del funtion setup y draw.  

### JavaScript Objects:
Orgranizar nuestro codigo de forma adecuada y ordenada.
Agrupa mucha variables dentro de la variable, estructura de datos que te permite agrupar, valores relacionados bajo un mismo nombre, el lugar de tener muchas variables sueltas, los obj funcionan como contenedor, en donde se organiza la info mediantes pares de clave y valor.  

#### random fuction():  
Devuekve un numero aleatorio dentro delr ango que se defina.  
random(); Si no pones nada devuelve un n
