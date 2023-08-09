# Gabarito da prova
1. Seja *f* uma imagem contínua que deseja-se converter para o formato digital. Este processo compreende a digitalização dos valores de coordenada e de amplitude, conhecidos respectivamente como amostragem e quantização. Sobre este processo de digitalização, responda as questões a seguir:

    a.	Qual a relação entre a amostragem e a quantidade de pixels da imagem digitalizada?

        A amostragem é o que determina a quantidade de pixels que a imagem digital terá, estabelecendo um intervalo em que partes da imagem contínua serão colocadas nos pixels.
    
    b.	A cena capturada na imagem contínua f possui alguma influência na amostragem? Uma imagem com menos ou mais detalhes faz diferença na amostragem?

        Não, pois a amostragem não considera o conteúdo ou as intensidades da imagem no seu processo, também não fazendo diferença se a imagem tem mais detalhes ou menos. Apesar disso, uma amostragem com intervalo expandido demais ocasiona perda de detalhe se a imagem original tiver muitos detalhes.
    
    c.	Qual a relação entre quantização e quantidade de bits por pixel?

        A quantização é realizada na intensidade da imagem original mapeando a aproximação do valor capturado com o intervalo das intensidades definidas pela quantidade de bits por pixel.
    
    d.	Ao utilizar menos bits por nível do que é adequado para a quantização de um caso específico, o que pode ser observado na imagem digitalizada?

        Ocorre uma perda de detalhes já que as cores vão estar muito próximas, não havendo tanto contraste.
    
2. Sejam três imagens digitais hipotéticas, *f*, *g* e *h*, cada uma com tipos definidos na tabela a seguir e tamanho igual a 50x50 pixels. Para cada uma das imagens citadas, preencha as lacunas com as informações corretas.

![Figura 1 da resposta da questão 2](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_resposta_2_i.PNG)

3. Considere o segmento de imagem a seguir e faça o que se pede:

![Figura da questão 3](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_pergunta_3_i.PNG)

a. Sendo V = {0, 1}, calcule os comprimentos dos caminhos –4, –8 e –m mais curtos entre os pixels p e q. Se um caminho específico não existir entre dois pontos, explique por quê.

    - caminho –4: não existe pois não há nenhum pixel com valor de V na vizinhança –4 de q.
    - caminho -8: Tamanho 4

![Figura 1 da resposta da questão 3 item a](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_resposta_3_a_i.PNG)

    - caminho -m: Tamanho 5

![Figura 2 da resposta da questão 3 item a](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_resposta_3_a_ii.PNG)

b.	Faça o mesmo para V = {1, 2}.

    - caminho -4: Tamanho 6

![Figura 1 da resposta da questão 3 item b](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_resposta_3_b_i.PNG)

    - caminho -8: Tamanho 4

![Figura 2 da resposta da questão 3 item b](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_resposta_3_b_ii.PNG)

    - caminho -m: Tamanho 6

![Figura 3 da resposta da questão 3 item b](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_resposta_3_b_iii.PNG)

4. As imagens mostradas a seguir são diferentes entre si, mas possuem histogramas idênticos. Qual a sua hipótese para explicar este fato?

![Figura 1 da questão 4](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_pergunta_4_i.png)

    O histograma mostra apenas a frequência que os bits de dadas intensidades aparecem na imagem, não tendo relação com seu conteúdo.

5. Observe os histogramas apresentados a seguir.

    Para cada histograma, indique se foi criado a partir de uma imagem:

    a.	Baixo contraste\
    b.	Alto contraste\
    c.	Clara\
    d.	Escura

![Figura 1 da questão 5](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_pergunta_5_i.png)

    c. Clara

![Figura 2 da questão 5](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_pergunta_5_ii.png)

    d. Escura

![Figura 3 da questão 5](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_pergunta_5_iii.png)

    a. Baixo contraste

![Figura 4 da questão 5](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_pergunta_5_iv.png)

    b. Alto contraste

6. Os filtros espaciais de suavização são muito utilizados em operações de borramento e redução de ruído, podendo ser lineares ou não lineares. Os filtros lineares são conhecidos como filtros de média, enquanto o filtro não linear mais popular é o da mediana. Sobre esses filtros, faça o que se pede:

    a.	Filtro da média:\
    i.	Explique o seu funcionamento

            O filtro é composto por coeficientes. Cada um é multiplicado pelo pixel correspondente da região filtrada e dividido pela soma destes coeficientes. Esses resultados são então somados e inseridos no pixel da imagem resultante.

    ii. Cite dois exemplos de mascaras (com seus coeficientes) de tamanho 3x3 que podem ser utilizados para implementar este filtro
        
        Resposta

![Figura 1 da resposta da questão 6 item a subitem ii](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2022_1_m/Avaliacao_1/imagens/pdi_2022_1_av1_resposta_6_a_i.PNG)

b.	Filtro da mediana\
i.	Explique seu funcionamento

    O filtro ordena os valores de intensidade dos pixels captados e seleciona o valor central da ordenação para inserir no pixel correspondente da imagem resultante.

ii.	Em que tipo de ruído este filtro é particularmente eficaz?

    Ele corrige bem o ruído sal-e-pimenta, ou ruído impulsivo, que são pontos muito claros ou muito escuros espalhados na imagem.
