# Gabarito da prova

1.  Nas Tabelas 1 e 2 são apresentados, respectivamente, os valores de intensidade de uma imagem digital hipotética **_I_** e o conjunto de coeficientes **_h_** de uma máscara de tamanho 3x3. Analise estas duas tabelas e faça o que se pede.

![Figura 1 da questão 1](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_2/imagens/pdi_2023_1_av2_pergunta_1_i.PNG)

O que se pede:

a.  Realize a filtragem espacial da imagem **_I_** utilizando os coeficientes da máscara **_h_** e preencha a Tabela 3 com o resultado desta operação. Para realizar esta tarefa utilize o método de processamento de borda denominado **_zero padding_**.

![Resposta da questão 1 item a](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_2/imagens/pdi_2023_1_av2_resposta_1_i.PNG)

b. Qual o nome da filtragem espacial descrita no item anterior?

    filtro da média

2.  Sobre o uso de derivadas para a segmentação de imagens baseadas em descontinuidade, marque **_(V)_** para verdadeiro e **_(F)_** para falso.

Derivadas de primeira ordem produzem bordas mais grossas em imagens.

    Verdadeiro

Derivadas de segunda ordem têm uma resposta mais forte aos detalhes finos, como linhas finas, pontos isolados e ruído.

    Verdadeiro

As derivadas de segunda ordem produzem uma resposta de borda dupla nas transições de rampa e de degrau.

    Verdadeiro

O sinal de segunda derivada pode ser utilizado para determinar se uma transição ocorre de claro para escuro (valor negativo) ou escuro para claro (valor positivo).

    Verdadeiro

As derivadas de uma função digital são definidas em termos de diferenças.

    Verdadeiro

3.  A restauração de imagens procura recuperar uma imagem corrompida com base em um conhecimento a *priori* do fenômeno de degradação. Neste contexto, explique brevemente o funcionamento dos filtros de estatística de ordem a seguir:

a.  Mediana

    Vetoriza uma janela, a partir de um pixel 'p' sendo o centro da janela, 3x3 por exemplo, ordena-se de forma crescente, calcula-se a mediana e substitui em 'p'. Para toda a imagem.

b. Ponto médio

    Vetoriza uma janela, a partir de um pixel 'p' sendo o centro da janela, 3x3 por exemplo, calcula-se a média entre o menor valor e o maior valor dessa janela e substitui em 'p'. Para toda a imagem.

4. Quando a separação dos modos do histograma de uma imagem é suficiente para realizar uma segmentação baseada em limiarização, é possível utilizar um único limiar global aplicável a toda a imagem. Neste contexto, a utilização de uma técnica automática de cálculo do limiar pode ser oportuna. Na Tabela 4 são apresentados os valores de intensidade de uma imagem hipotética **_J_**. Utilizando esses valores, faça o que se pede:

a. Explique o funcionamento do método iterativo (algoritmo iterativo) de cálculo de limiar.

    Resposta

b. Calcule a partir deste método o limiar **_T_** que pode ser utilizado para segmentar corretamente esta imagem hipotética.

![Figura 1 da questão 4](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_2/imagens/pdi_2023_1_av2_pergunta_4_i.PNG)

    Resposta

5. Na Tabela 5 são apresentados os valores de intensidade de uma imagem digital hipotética **_S_** de **_8 bits_** e tamanho **_6x6 pixels_**.

![Figura 1 da questão 5](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_2/imagens/pdi_2023_1_av2_pergunta_5_i.PNG)

a. Utilizando como base esses valores, faça a limiarização global simples com **_T_**=140, produzindo como resultado uma imagem de mesmo tamanho da original, mas limiarizada com **_T_** indicado. Os pixels de fundo devem possuir o valor **_0_** (zero) e os pixels do objeto o valor **_1_** (um). Preencha a Tabela 6 com o resultado deste procedimento.

![Respsta da questão 5 item a](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_2/imagens/pdi_2023_1_av2_resposta_6_item_a_i.PNG)

b. Com a mesma Tabela 5, realize a limiarização global múltipla, utilizando para tal **_T<sub>1</sub>_**=30 e **_T<sub>2</sub>_**=155, produzindo como resultado uma imagem de mesmo tamanho da original, mas limiarizada com os dois valores de **_T_** indicados. Somente os valores que estiverem entre **_T<sub>1</sub>_** e **_T<sub>2</sub>_** devem ser marcados com o valor **_1_** (um). Os pixels de fundo devem ser marcados com o valor **_0_** (zero). Preencha a tabela 7 com o resultado deste procedimento.

![Resposta da questão 5 item b](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_2/imagens/pdi_2023_1_av2_resposta_6_item_b_i.PNG)