# Universidad de El Salvador
## Facultad de Ciencias Naturales y Matemática
## Escuela de Matemática


### Proyecto II - Ciencia de Datos

Integrantes del proyecto

1. Gabriel Enrique Merino Castellanos, MC18035
2. Javier Ulises Sigüenza Monge, SM19047
3. Marcelo Gerardo Santamaría Cortez, SC1801
4. Pedro Julio Avelar Hernández, AH18049

**(Problema)**. Sea $(X, \langle \cdot, \cdot \rangle$ un espacio con producto interno, con la norma inducida por $\lVert \cdot \rVert = \sqrt{\langle \cdot, \cdot \rangle}$. Entonces se satisface la identidad del paralelogramo: $$\lVert x+y \rVert^2 + \lVert x-y \rVert^2 = 2(\lVert x \rVert^2 + \lVert y \rVert^2)$$

**Demostración.** Utilizando la definición de norma inducida por el producto interno y utilizando propiedades del producto interno, basta calcular que 
$\lVert x+y \rVert^2 + \lVert x-y \rVert^2$ 

$=\langle x+y, x+y \rangle + \langle x-y,x-y \rangle$

$=(\langle x,x+y \rangle+\langle y,x+y \rangle)+(\langle x,x-y \rangle+\langle -y,x-y\rangle)$

$=(\langle x,x \rangle +\langle x,y\rangle+ \langle y,x\rangle+\langle y,y \rangle)+(\langle x,x \rangle +\langle x,-y \rangle+\langle -y,x \rangle+ \langle -y,-y\rangle)$

$=(\lVert x \rVert^2+\langle x,y\rangle+ \langle y,x\rangle+\lVert y \rVert^2)+(\lVert x \rVert^2-\langle x,y\rangle- \langle y,x\rangle+\lVert y \rVert^2)$

$=(\lVert x \rVert^2+\lVert x \rVert^2+\lVert y \rVert^2+\lVert y \rVert^2)+(\langle x,y\rangle-\langle x,y\rangle+\langle y,x\rangle-\langle y,x\rangle)$

$=2\lVert x \rVert^2+2\lVert y \rVert^2$

$=2(\lVert x \rVert^2+\lVert y \rVert^2). \blacksquare$
