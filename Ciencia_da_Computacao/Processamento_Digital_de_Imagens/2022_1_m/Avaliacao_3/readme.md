# Gabarito da prova
1. No contexto do processamento morfológico de imagens, alguns operadores são considerados elementares. Isto se deve ao fato da maior parte dos operadores morfológicos serem implementados a partir destes. Explique sucintamente o funcionamento dos operadores a seguir, __quando aplicados em imagens binárias__:

a. Erosão

        a. Na erosão, o elemento estruturante (ES) percorre a imagem e transforma em 0 os pixels 1 da imagem que não incluem os pixels 1 do ES na região analisada por ele.
b. Dilatação

        b. Na dilatação, quando o ES encontra um pixel 1, os pixels da região analisada recebem valor 1 onde os pixels do ES também são 1. 
c. Abertura

        c. A abertura consiste em uma erosão seguida de uma dilatação na imagem. 
d. Fechamento

        d. O fechamento consiste no inverso da abertura, isto é, uma dilatação seguida de uma erosão na imagem.
2. Seja __R__ uma região binária cujos pixels que a compõe estão marcados em cinza e o fundo marcado em branco. Considere também __ER__ um elemento estruturante de tamanho 3x3, que utiliza o mesmo padrão de representação de cores, conforme demonstrado nas figuras a seguir:

![Figura da questão 2](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_3/imagens/pdi_2022_1_av3_pergunta_2_i.PNG)

 __O que se pede__: aplique as operações de erosão e dilatação na região __R__ utilizando o elemento estruturante __ES__, descrevendo o resultado destas operações nos respectivos quadros a seguir.
    
        Resposta
![Resposta da questão 2](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_3/imagens/pdi_2022_1_av3_resposta_2_i.PNG)

3. Os operadores morfológicos elementares também podem ser aplicados __a imagens em nível de cinza__. Neste contexto, explique os efeitos obtidos ao realizar isoladamente as operações (a) erosão, (b) dilatação, (c) abertura e (d) fechamento em uma imagem em __nível de cinza__. Utilize a imagem apresentada a seguir para caracterizar as mudanças esperadas após a aplicação de cada um dos operadores citados isoladamente.

![Figura da questão 3](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_3/imagens/pdi_2022_1_av3_pergunta_3_i.png)

    a.  A erosão usa uma função de mínimo e por isso ocorre o alargamento de objetos mais escuros, enquanto objetos mais claros diminuem de tamanho. A imagem também fica mais escura. 
    b.	Na dilatação, como é usada uma função de máximo, a imagem fica mais clara, as regiões mais claras aumentam de tamanho e as mais escuras diminuem. 
    c.	A abertura remove pequenos detalhes claros e mantém os níveis de cinza gerais da imagem, apagando os pontos brancos rodeando o círculo branco no canto superior da imagem da questão. 
    d.	O fechamento mantém também os níveis de cinza gerais da imagem, porém remove pequenos detalhes escuros, como os diversos pontos pretos ou as conexões escuras na região à direita da imagem. 

4. Após a segmentação de uma imagem, o conjunto de pixels resultante geralmente é representado e descrito de forma adequada para posterior processamento computacional. Sobre os conceitos de representação e descrição, faça o que se pede:

a. Explique os conceitos de representação e descrição.

        A representação busca extrair a forma de um objeto da imagem, enquanto a descrição tem o intuito de extrair o conteúdo deste objeto. 
b. Cite um exemplo prático de como uma região pode ser representada e descrita.

        Em uma imagem de olho humano em que se busca analisar a íris, a representação extrairia a forma desta íris segmentada, analisando sua fronteira, enquanto a descrição analisaria a cor ou a textura da íris para extrair seu conteúdo. 
5.  Nas figuras a seguir é possível visualizar, respectivamente, o resultado da reamostragem do contorno de uma região e um mapa contendo os números de direção para um código de cadeia de oito direções.

![Figura da questão 5](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_3/imagens/pdi_2022_1_av3_pergunta_5_i.PNG)

O que se pede:
a. Obtenha o código de cadeia de 8 direções do contorno da região reamostrada.

    0766666453321212. 
b.	Calcule a primeira diferença (ou derivada) do código de cadeia de 8 direções obtido. 

    677000061607717.  
