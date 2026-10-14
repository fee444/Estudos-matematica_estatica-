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

2. Regra da cadeia

Aplica a derivação a uma função composta:

h = (3*x + 1)**2

h_prime = diff(h, x)

A ideia central é entender como derivadas se propagam em operações encadeadas --- conceito essencial para o treinamento de redes neurais.

3. Gradientes em um neurônio com PyTorch

Constrói um neurônio simples com uma entrada (x), um peso ajustável (w) e um valor esperado (y). A saída é calculada usando a função identidade e o erro é medido com MSELoss.

y_previsto = torch.nn.Identity()(w * x)

erro = torch.nn.MSELoss()(y_previsto, y)

erro.backward()

print(w.grad)
O método backward() calcula o gradiente da perda em relação ao peso usando diferenciação automática. Esse gradiente indica como o peso influencia o erro e pode ser usado para orientar sua atualização durante o treinamento.
