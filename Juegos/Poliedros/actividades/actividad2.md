
# Actividad 2: Determinando el número de aristas y vértices

# Fecha:
# Nombres:


### Grupos
Poneros por parejas para realizar la actividad

### La fórmula de Euler para poliedros convexos

Imagina un cubo, que sabemos que está formado por 6 caras cuadradas. El número de aristas lo podemos deducir de dos formas:
    
    - Las dos bases (inferior y superior) son cuadradas, luego tenemos 4+4=8 aristas horizontales. Cada esquina de la base inferior está unida con una esquina de la base superior, luego tenemos 4 aristas verticales. Por lo tanto, tenemos 12 aristas.
    - El cubo tiene 6 caras cuadradas, como el cuadrado tiene 4 lados nos salen 6x4=24 lados. Ahora bien, cada arista la comparten 2 caras, luego en los lados anteriores cara arista se cuenta dos veces, y por lo tanto las aristas serán 24:2=12 aristas. (Este es el procedimiento que seguiremos, y la fórmula es **aristas=(numero_caras x lados_de_la_cara):2**
    
Nos faltaría contar los vértices del cubo, tenemos 4 en la cara inferior y 4 en la superior. Por lo tanto, tenemos 8 vértices.

Resumiendo un **cubo tiene 6 caras, 12 aristas y 8 vértices**. Si sumamos las caras y los vértices obtenemos el número de aristas más dos. A este resultado se le conoce como **fórmula de Euler**:

```
C + V = A + 2
``` 
O de tra forma:

```
V = A - C + 2 (número de vértices igual a aristas menos caras más 2)
```

**Ejercicio resuelto**: Calcula las caras, las aristas y los vértices de un cubo o hexaedro regular:
   
    - **6 caras** (el prefijo hexa siginifica 6)
    - (6x4):2=24:2=**12 aristas**. 6 caras cuadradas, el cuadrado tiene 4 lados.
    - 12-6+2=6+2=**8 vértices**



Completa la siguiente tabla:


 Nombre del Poliedro | Número de caras | Número de aristas | Número de vértices
-------------------- | ----------------| ------------------| ------------------- 
 Tetraedro | 4 | (4x3)/2=6 | 6-4+2=4 
 Cubo | 6 |  
 Octaaedro | | 
 Dodecaedro | | 
 Icosedro | | 
 
