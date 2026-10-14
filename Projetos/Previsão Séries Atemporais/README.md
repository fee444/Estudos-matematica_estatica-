📈 Previsão de Séries Temporais com PyTorch

Uma implementação robusta e didática para manipulação, processamento e modelagem de séries temporais utilizando Deep Learning.

📌 1. O que é o projeto e o que acontece?

Este projeto consiste em um pipeline completo de engenharia de dados e aprendizado de máquina voltado para a modelagem e previsão de séries temporais.

O script executa os seguintes passos principais:

Geração de Dados Sintéticos: Cria uma série temporal realista composta pela sobreposição de múltiplos sinais senoidais com frequências/amplitudes diferentes, além da adição de ruído gaussiano (simulando imperfeições do mundo real).

Configuração de Hardware: Identifica e seleciona automaticamente o melhor dispositivo de aceleração disponível (CUDA, MPS para Apple Silicon, ou CPU).

Pré-processamento e Estruturação: Prepara os dados sequenciais para alimentar arquiteturas de redes neurais profundas.

🎯 2. Objetivos

🚀 Construir uma base sólida para manipulação de séries temporais em PyTorch.

⚙️ Automatizar a detecção de hardware (CUDA/MPS/CPU) para otimização de performance.

📊 Demonstrar a geração de dados ruidosos controlados para testes de modelos preditivos.

🧹 Padronizar métricas de avaliação e visualizações gráficas de alta qualidade.

🛠️ 3. Tecnologias Utilizadas

Python: Linguagem principal do projeto.

PyTorch: Framework de Deep Learning para criação de tensores e manipulação de dispositivos.

NumPy: Biblioteca para computação científica e manipulação de arrays.

Scikit-Learn: Utilizada para normalização de dados (MinMaxScaler) e métricas de erro (MSE, MAE).

Matplotlib: Geração de visualizações gráficas estilizadas.

TQDM: Barras de progresso para loops de treinamento.

🧠 4. Conceitos Abordados

Séries Temporais (Time Series): Sequências de dados indexadas em ordem cronológica.

Componentes de Sinal: Decomposição e soma de frequências senoidais (baixa e alta frequência).

Ruído Gaussiano: Injeção de estocasticidade para simular imprecisões e ruídos de sensores reais.

Device Agnostic Programming: Código flexível que roda tanto em GPU quanto em CPU de forma transparente.

Otimização de Memória: Conversão de tipos de dados para float32 visando eficiência computacional.
