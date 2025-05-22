# plotador
plotador de Gráficos de Dados Personalizado (X vs. Y)
Este repositório contém um script Python simples que permite visualizar dados em um gráfico de X e Y usando a biblioteca matplotlib. É ideal para plotar relações entre duas variáveis, como tensão vs. corrente, tempo vs. temperatura, ou qualquer outro conjunto de dados.

Visão Geral
O script plot_data.py plota pontos de dados fornecidos em duas listas (uma para o eixo X e outra para o eixo Y) e os conecta com uma linha. Ele gera um gráfico interativo que pode ser salvo ou visualizado diretamente.

Como Usar
Você pode executar este script de duas maneiras principais: localmente no seu computador ou diretamente no Google Colab, que é uma ótima opção se você não tem o Python ou matplotlib instalados.

1. Executando Localmente (No Seu Computador)
Pré-requisitos
Certifique-se de ter o Python e a biblioteca matplotlib instalados.

Python: Baixe e instale em python.org.

Matplotlib: Instale via pip no seu terminal:

pip install matplotlib

Passos para Executar
Baixe o Código: Clone este repositório ou baixe o arquivo plot_data.py diretamente.

Abra o Terminal: Navegue até a pasta onde você salvou o arquivo plot_data.py usando o terminal (Prompt de Comando no Windows, Terminal no macOS/Linux).

cd /caminho/para/sua/pasta

Execute o Script:

python plot_data.py

Uma janela com o gráfico será exibida.

2. Executando no Google Colab
O Google Colab é um ambiente de notebook Jupyter que roda na nuvem, o que significa que você não precisa instalar nada no seu computador.

Abra o Google Colab: Vá para colab.research.google.com.

Crie um Novo Notebook: Clique em Arquivo > Novo notebook.

Cole o Código: Copie todo o conteúdo do arquivo plot_data.py e cole-o na primeira célula do notebook do Colab.

Execute a Célula: Clique no botão de "Play" (triângulo) no canto superior esquerdo da célula.
O gráfico será gerado e exibido diretamente abaixo da célula no notebook.

Personalização dos Dados e do Gráfico
O script é projetado para ser facilmente modificável:

Dados:

Altere os valores das listas x_values e y_values no início do script para plotar seus próprios dados. Certifique-se de que ambas as listas tenham o mesmo número de elementos.

x_values = [0.029, 0.375, 0.508, 0.549, 0.577, 0.612, 0.619]
y_values = [0, 0.101, 0.205, 0.495, 0.907, 1.993, 2.428]

Título e Rótulos:

Modifique plt.title(), plt.xlabel(), e plt.ylabel() para dar um título e rótulos significativos aos seus eixos.

Estilo do Gráfico:

Ajuste marker, linestyle e color na função plt.plot() para alterar a aparência da linha e dos pontos.

plt.figure(figsize=(9, 6)) controla o tamanho da imagem do gráfico.
