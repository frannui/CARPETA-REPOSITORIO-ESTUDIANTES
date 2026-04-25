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

Rotación  
rotate();  
Siempre rotan alrededor del punto de origen(0,0)  
se recomienda usar translate();
en algunos casos con rectMode(CENTER);


push();
pop();

sistema de memoria temporal para estilo y transformasciones del lienzo
