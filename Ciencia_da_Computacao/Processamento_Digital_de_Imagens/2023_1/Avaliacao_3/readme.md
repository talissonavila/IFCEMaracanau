# Gabarito da prova
1.  Sobre imagens coloridas, analise as Figuras 1 e 2 e responda o que se pede:

    ![Questão 1](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1/Avaliacao_3/imagens/pdi_2023_1_av3_pergunta_1_i.PNG)
    
    a. Seja *__I__* uma imagem colorida no modelo de cor RGB com tamanho 4x4 pixels. Os canais *__R__*, *__G__* e *__B__* desta imagem são apresentados na Figura 1. Os pixels com valores iguais a um estão identificados na cor branca, enquanto os pixels com valores iguais a zero estão identificados na cor preta. Utilizando o esquema de cores *__RGB__* apresentado na Figura 2, identifique textualmente no arranjo matricial a seguir quais cores (escreva o nome da cor: amarelo, verde, magenta, etc) são apresentados na imagem colorida *__I__*.

        Resposta 

    ![Resposta da questão 1](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1/Avaliacao_3/imagens/pdi_2023_1_av3_resposta_1_i.PNG)

    b.	O objetivo de um modelo de cores (espaço de cores ou sistema de cores) é facilitar a especificação das cores através de uma padronização amplamente aceita. Em alguns casos, é de interesse realizar a conversão de um modelo para outro, como a conversão do padrão RGB para o HSI e vice-versa. Neste contexto, descreva como se dá o processo de conversão de uma imagem no modelo de cor RGB para o HSI. Para tanto, demonstre como se dá o mapeamento de um valor em RGB para os componentes HSI.

        Dado um valor de RGB arbitrário presente no cubo com as dimensões de vermerlho, verde e azul.

    ![Cubo RGB](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1/Avaliacao_3/imagens/pdi_2023_1_av3_resposta_1_ii.PNG)

        Será feito uma rotação no cubo de maneira que a escala de cinza fique perpendicular a superfície.
        A intensidade (I) representa a altura no ponto na escala de cinza. A saturação (S) representa a distância do ponto arbitrário em relação ao centro do plano fatiado. A matiz (H), representa o ângulo no plano fatiado, partindo do vermelho até o ponto.
    
2. Nas Figuras 3 e 4 é possível visualizar, respectivamente, o resultado da reamostragem do contorno de uma região e um mapa contendo os números para um código de uma cadeia de oito direções. Após analisar as figuras citadas, faça o que se pede:

    ![Questão 2](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1/Avaliacao_3/imagens/pdi_2023_1_av3_pergunta_2_i.PNG)

    a.	Obtenha o código de cadeia de 8 direções do contorno da região reamostrada. 
        
        Resposta
        0766666453321212

    b.	Calcule a primeira diferença (ou derivada) do código de cadeia de 8 direções obtido.

        Resposta
        67700006160771716
    
3. Seja __R__ uma região binária cujos pixels que a compõe estão marcados em cinza e o fundo marcado em branco. Considere também __ES__ um elemento estruturante de tamanho 3x3, que utiliza o mesmo padrão de representação de cores, conforme demostrado a seguir:

    ![Questão 3](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1/Avaliacao_3/imagens/pdi_2023_1_av3_pergunta_3_i.PNG)

    __O que se pede__: aplique as operações morfológicas solicitadas na região __R__ utilizando o elemento estruturante __ES__, descrevendo o resultado destas operações nos respectivos quadros.
        
        Resposta

    ![Resposta questão 3 i](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1/Avaliacao_3/imagens/pdi_2023_1_av3_resposta_3_i.PNG)

    ![Resposta questão 3 ii](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1/Avaliacao_3/imagens/pdi_2023_1_av3_resposta_3_ii.PNG)

4.  Os operados morfológicos elementares também podem ser aplicados __a imagens em nível de cinza__. Neste contexto, explique os efeitos obtidos ao realizar isoladamente as operações (a) erosão, (b) dilatação, (c) abertura e (d) fechamento em uma imagem em __nível de cinza__. Utilize a Figura 5 para caracterizar as mudanças esperadas após a aplicação de cada um dos operadores citados isoladamente.

    ![Figura 5](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1/Avaliacao_3/imagens/pdi_2023_1_av3_pergunta_4_i.PNG)

        a. A imagem fica mais escura; função mínimo; pontos claros diminuem, ou somem; pontos escuros crescem.
        
        b. A imagem fica mais clara; função máximo; pontos escuros diminuem, ou somem; pontos claros crescem.

        c. Pontos claros menores que o elemento estruturante somem, enquanto os maiores mantém o mesmo tamanho. Pontos escuros mantém-se iguais. O nível de cinza geral da imagem não é alterado.

        d. Pontos escuros menores que o elemento estruturante somem, enquanto os maiores mantém-se inalterados. Pontos claros mantém-se iguais. O nível de cinza geral da imagem não é alterado.