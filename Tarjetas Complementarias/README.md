import numpy as np
import matplotlib.pyplot as plt

# Definir el rango de x desde -pi hasta pi
x = np.linspace(-np.pi, np.pi, 400)

# Definir la función y = 160 * sen(2x)
y = 160 * np.sin(2 * x)

# Graficar
plt.plot(x, y, label='y = 160·sin(2x)', color='b')

# Añadir etiquetas y título
plt.title('Gráfico de y = 160·sen(2x)')
plt.xlabel('x (radianes)')
plt.ylabel('y')
plt.grid(True)
plt.legend()

# Mostrar la gráfica
plt.show()
