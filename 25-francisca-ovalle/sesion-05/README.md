# Sesión 05 - 17/04 Apuntes  
---
## Transformaciones & condicionales { IF - ELSE }  
### Transoformaciones:  
**¿Qué son los radianes?**  
Es la forma de medir los ángulos por defecto en vez de grados.  
Basicamente otra unidad de medida.  

#### Ángulos:  

*angleMode();*
p5.js usa RADIANES oara medir los ángulos.  
*angleMode(RADIANS);*
Se usa en function SETUP  
*angleMode(DEGREES);*  

**Hay que pensarlo como las agujas del reloj:**  
![Angulo](https://i.pinimg.com/736x/05/d4/2f/05d42f9b69602ceffd45f459e21d2bd1.jpg)

**Rotación:**  
rotate(); 
Siempre rotan alrededor del punto de origen(0,0)  
se recomienda usar translate();
en algunos casos con rectMode(CENTER);
**Sintaxis: rotate(valor radianes o en grados);**  
Ejemplo: rotate(20);  
**Transladar:**  
translate();  
Sirve para transladar el PUNTO DE ORIGEN(0,0) a otra coordenada de mi canvas.  
**Sintaxis: translate(x,y);**  
Ejemplo: translate(200,200);  

#### Guardar y restaurar:  
push();
pop();  
Funciones que trabajan juntas como un "sistema de memoria temporal" para el estilo y las transformaciones del lienzo.  
Sintaxis: push();
Sintaxis: pop();
#### Escala:
scale();  
La función scale() ajusta la escala del sistema de coordenadas actual por el factor especifico.  
Sintaxis: scale(x,y);  
Ejemplo: scale(2,2);  
### Condicionales:  
**Lógica condicional & expresión booleana:**  
- Expresión booleana: Una expresión booleana es cualquier enunciado, dato o instrucción que, al ser evaluado, solo puede arrojar uno de los dos posibles: *verdadero (True) o falso (False)*.
  Ejemplo: Si algún estudiante apaga por completo las luces de la sala, la profesora debe bailar.

**Para construir este tipo de expresiones se utilizan 3 tipos de elementos: OPERADORES**  
![operadores](https://i.pinimg.com/736x/5e/b3/57/5eb35708d21ab54527aaf33ba72a51c1.jpg)
![operadores](https://i.pinimg.com/736x/aa/7c/e7/aa7ce764c8f6be5d0e358b5b0aa3a12a.jpg)  
![operadores](https://i.pinimg.com/736x/74/2d/d1/742dd174d25e835bd7fedc2592bc438a.jpg)  

#### Ejemplos de operaciones de comparación:  
*menor que < y mayor que >*: Al comparar números, el operador devuelve un booleano basado en la comapración matematica.  
Ejemplos:  
//menor que 2 < 3// devuelve true  
3 < 2 // devuelve false  
//mayor que 2 > 3// devuelve false  
3 > 2 // devuelve true  
*Al comparar cadenas de texto, el operador compara carácter por cáracter basándose en su orden alfabetico.*  
Ejemplos:  
'b' < 'a'// devuelve false  
'b' < 'c'// devuelve true  
'abc' < 'aaa'// devuelve false porque 'b' no es menor que 'a'  
'abc' < 'abd'// devuelve true porque 'c' si es menor que 'd' 
*menor o igual que: <= y mayor o igual que: >=* Similar a < y >, pero también devuelve true cuando ambos valores son iguales.  
Ejemplos:  
12 < 12// devuelve false  
12 <= 12// devuelve true  
Lo mismo se aplica a las cadenas de texto, comparando siempre su orden alfabético.  
Ejemplos:  
'a' < 'a'// devuelve false, ya que la posición de ambas cadenas en el alfabeto es la misma, por lo tanto no son diferentes.  
'a' <= 'a'// devuelve true  


