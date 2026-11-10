
# Modelo completo de Hodgkin-Huxley

Esta carpeta contiene los programas Python
utilizados para la simulación numérica del
modelo completo de Hodgkin-Huxley, con
las variables V, m, h y n.

### Validación de la aproximación lineal con corrientes variables y próximas a Hopf

Se incorpora un cuaderno de Google Colab que contiene simulaciones adicionales del modelo completo de Hodgkin–Huxley para estudiar el comportamiento del error de la aproximación lineal:

\[
h(t)\approx 0.89-1.1n(t).
\]

El cuaderno incluye:

- **Corriente variable en el tiempo:** simulación con una corriente aplicada por tramos de 6.75, 12 y 6.76 µA/cm², durante 300 ms.
- **Corrientes próximas al valor crítico de Hopf:** simulaciones para ocho valores de corriente alrededor de \(I_H\approx 6.752633\) µA/cm², durante 500 ms.
- **Evaluación cuantitativa:** cálculo del error máximo absoluto y del error RMS, incluyendo un análisis después de descartar el transitorio inicial.
- **Comprobación numérica:** comparación de los errores obtenidos utilizando distintos pasos máximos de integración.

Se incluyen los códigos, las tablas de resultados y las gráficas correspondientes.

El valor \(I_H\) corresponde al modelo reducido bidimensional y se utiliza como referencia para las simulaciones del modelo completo.
