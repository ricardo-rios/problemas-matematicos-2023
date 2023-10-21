# Universidad de El Salvador #
# Facultad de Ciencias Naturales y Matemática #
# Escuela de Matemática #
# Proyecto #2 #
# Integrantes: #
*1. Glenda Nicole Barrera Ramírez, BR20004.*
 
 *2. Karla Marilú Hernández Agustín, HA19001.*

 *3. Ana Cecilia Segovia Clemente, SC19011.*
#
**Problema Matemático.** Teorema del valor medio para integrales

Si los valores de $f\left ( x \right )$ es continua en un intervalo $\left [ a, b \right ] $, entonces hay al menos un punto $c \in\left [ a, b \right ]$ tal que 
$$f\left ( c \right )=\frac{1}{b-a}\int_{a}^{b}f\left ( x \right )dx.$$

Esta fórmula también puede expresarse como
$$\int_{a}^{b}f\left ( x \right )dx=f\left ( c \right )\left ( b-a \right ).$$
#


**Prueba** 

Dado que $f\left ( x \right )$ es continua en $\left [ a, b \right ]$, por el teorema del valor extremo, asume valores mínimos y máximos $m$ y $M$, respectivamente en $\left [ a, b \right ]$. Entonces, para toda $x$ en $\left [ a, b \right ]$ , tenemos $m\leq f\left ( x \right )\leq M$.
Por lo tanto, por el teorema de comparación, tenemos
$$m\left ( b-a \right )\leq \int_{a}^{b}f\left ( x \right )dx\leq M\left ( b-a \right ).$$
Al dividir entre $b-a$ nos da
$$m\leq \frac{1}{b-a}\int_{a}^{b}f\left ( x \right )dx\leq M.$$

Dado que $\frac{1}{b-a}\int_{a}^{b}f\left ( x \right )dx$ es un número entre $m$ y $M$, y ya que $f\left ( x \right )$ es continua y asume los valores $m$ y $M$ en $\left [ a, b \right ]$, por el teorema del valor intermedio
, existe un número $c$ en $\left [ a, b \right ]$ tal que 
$$f\left ( c \right )=\frac{1}{b-a}\int_{a}^{b}f\left ( x \right )dx$$
y la prueba esta completa.

$\blacksquare $
