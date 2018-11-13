# Newton-Raphson

Este método es utilizado para encontrar raíces ya que es muy eficiente y siempre converge
Para poder aplicar este método, las funciones deben de ser diferenciables
Para empezar, se parte de un valor inicial para la raiz
En el código se muestra cómo en este método se define la fórmula a partir de la fórmula de la pendiente de una recta, vista igualmente aquí:
  xi+1 = xi - f(xi)/f'(xi)
Para obtener el error porcentual, es igual que en los otros métodos:
  er = (|xnueva - xanterior|/xnueva)*100


El método de Newton-Raphson es convergente cuadráticamente, es decir, el error es aproximadamente al cuadrado del error anterior. Esto significa que el numero de cifras decimales correctas se duplica aproximadamente en cada interacción.

Si no hay raíz real o si la raíz es un punto de inflexión o si el valorinicial está muy alejado de la raíz buscada, no converge, sino que oscila. 

Pasos:
1. Identificamos la función f
2. Calculamos la derivada de la función
3. Construimos la fórmula de recurrencia (la escrita al principio de la expliación)
4. Tomamos una estimación inicial de la solución



