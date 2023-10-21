# ESG_VM
ESG Value Mining Main Portal


# Importando as bibliotecas necessárias
import matplotlib.pyplot as plt
import numpy as np

# Definindo o intervalo de x
x = np.linspace(-10, 10, 400)

# Definindo a função para a parábola: y = x^2
y = x**2

# Criando o gráfico
plt.figure(figsize=(6, 6))
plt.plot(x, y)

# Adicionando títulos e rótulos
plt.title('Gráfico de uma Parábola')
plt.xlabel('x')
plt.ylabel('y')

# Exibindo o gráfico
plt.show()
