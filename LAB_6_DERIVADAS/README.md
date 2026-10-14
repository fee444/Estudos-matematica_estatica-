Derivadas e Gradiente Descendente com Python
Notebook prático sobre o uso de derivadas em Data Science e Machine
Learning, explorando cálculo simbólico, diferenciação automática e
otimização de uma regressão linear.

Tecnologias

- Python
- SymPy --- cálculo simbólico de derivadas
- PyTorch --- tensores, função de perda e cálculo automático de
  gradientes (autograd)
- NumPy --- operações matriciais e implementação manual do
  gradiente descendente

O que o notebook aborda

1. Derivadas com SymPy
Define uma função matemática e calcula sua derivada simbolicamente.
Depois, avalia a derivada em um ponto específico.

x = symbols('x')

f = x**3 + 2*x**2 - x + 1

derivada_f = diff(f, x)

valor = derivada_f.subs(x, 1)

Esse exemplo mostra como usar symbols, diff() e subs() para derivar uma função e avaliar sua taxa de variação em (x = 1).
