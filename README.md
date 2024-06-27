# AMMD
Repositório dedicado aos projetos da diciplina Aprendizado de Máquina e Mineração de Dados

# Lista 2 


# Questão 1 
1-) Considere o problema de classificação de padrões bidimensionais constituído neste caso
de 5 padrões. A distribuição dos padrões tem como base um quadrado centrado na origem
interceptando os eixos nos pontos +1 e -1 de cada eixo. Os pontos +1 e -1 de cada eixo são
centros de quatro semicírculos que se interceptam no interior do quadrado originando uma
classe e as outras quatro classes nas regiões de não interseção. Após gerar aleatoriamente
dados que venham formar estas distribuições de dados, selecione um conjunto de treina-
mento e um conjunto de validação. Treine uma rede neural Deep MLP

a-) Verifique o desempenho do classificador usando o conjunto de validação e calculando a
matriz de confusão.
b-) Compare o desempenho com a solução obtida na lista com a técnica Random Forrest.
- 

- https://colab.research.google.com/drive/1B74DP12mkxyzc0DcRTHoZgsMqoEUJEWU?usp=sharing

  # Questão 2
  Utilize uma rede neural perceptron de múltiplas camadas para aproximar a função abai-
xo.
f (x)  x12  x 22  2 x1 x 2  cos( x1  x 2 )  1) , x1  5, x 2  5
Apresente um gráfico com a curva da função analítica e a curva da função aproximada pela
rede neural. Apresente também a curva da função custo no treinamento e a curva do erro
médio quadrado com relação ao o conjunto de validação. Procure definir a arquitetura da
rede neural perceptron, isto é, o número de entradas, o número de neurônios em cada cama-
da e o número de neurônios camada de saída.
Observações. Como se trata de um problema de aproximação de funções, considere a ca-
mada de saída do tipo linear puro

- https://colab.research.google.com/drive/1K1-fyQ0qsy-Vl057dpgkuSfkJF1rn5XF?usp=sharing

  # Questão 4
  Utilize a rede neural perceptron de múltiplas camadas do tipo NARX (rede recorrente)
para fazer a predição de um passo
x^(n+1)
da série temporal,
x(n)  1  sen(n  sen 2 (n)) n=0,1,2,3,.... Gere inicialmente um conjunto de amostras para
o treinamento e um conjunto de amostras de teste. Avalie o desempenho mostrando a curva
a série temporal, a curva de predição e a curva do erro de predição definido como
e(n+1)=x(n+1)-x^(n+1).
Sugestão para solução:
Vetor de entrada da rede neural x(n+1)=[x(n), x(n-1), x(n-2), x(n-3)]t , corresponde uma
rede com 4 dados de entrada. Um neurônio na saída gerando a estimativa x^(n+1). A repos-
ta desejada é x(n+1) obtida diretamente da série temporal.

- https://colab.research.google.com/drive/1TatA-r_8AseaIkZpl0RiT1NijoagYpcC?usp=sharing

  # Qestão 5
  Considere uma rede de autoencoder para compressão de imagens. Defina a arquitetura
da rede de autoencoder de tal modo que a imagem possa ser comprimida. (Exemplo: Uma
imagem 64x64 pixel seja comprimida para 32x32 ou 16x16. Utilize uma rede neural con-
volucional. Pesquise e utilize redes pré-treinadas. Pesquise uma base de dados de imagens a
serem utilizadas para o treinamento e teste. Após o treinamento verifique a capacidade de
generalização considerando imagens diferentes das utilizadas no treinamento. Avalie a qua-
lidade da compressão calculando em dB a razão sinal ruído definida como
1 N M
s med
SRN  10 log 10 e
onde s med 
sendo f (i, j ) o valor de cada pixel
f (i, j ) 2

med
MN i 1 j 1
na posição (i,j), M e N as dimensões da imagem e emed o erro médio quadrado, isto é
 
1 N M
 e(i, j) 2
MN i 1 j 1
a descompressão
emed 
sendo e(i, j ) a diferença entre o pixel sem compressão e após

- https://colab.research.google.com/drive/1mZ-heJGThz8jTQSeeeZCvAPXrFdOnpUr?usp=sharing

  # Lista 3
  - https://colab.research.google.com/drive/1JrcFYlNm61EaPdVgdmo2-EArRNT9M3O0?authuser=1#scrollTo=7FluEIenAQJ2



# Projeto 1 
- https://colab.research.google.com/drive/1KdPAnV2yiXjdef_Tcl1smNM99-Tfd_kJ?usp=sharing


