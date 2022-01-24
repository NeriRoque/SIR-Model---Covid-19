# SIR-Model---Covid-19
Modelo criado para prever o número de infectados, recuperados e suscetíveis através dos dados do primeiro pico da doença, realizado na linguagem Python
É recomendável que o código seja rodado através do colab pois, além da plataforma iterativa ser mais intuitiva 
para a interação do usuário, o codlab também já possui todas as requisições para que o código funcione.
Caso contrário:
Para rodar o código, é necessário ter instalado na IDE as bibliotecas:
-Matplotlib
-Numpy
-Pandas
-Plotly
-Tqdm

Além disso, é possível alterar o estado que o modelo SIR será projetado. Tal ação é realizada através da aba 
#CONSTANTS. Por lá, é possível alterar o STATE de "PA", já predefinido (devido a escolha do estado do Pará para 
a projeção do modelo), pela sigla do estado desejado.
Caso tal mudança seja feita, é necessário plotar o gráfico de casos reais e verificar o dia em que ocorre o 
primeiro pico, alterando, na mesma aba, o FIRST_PEAK_DAY_CUT para o dia que o gráfico sinaliza.

Link para o collab: https://colab.research.google.com/drive/1ieiqh6jzCe2nuQgP6iTewSySrdf1VvQ1?usp=sharing
