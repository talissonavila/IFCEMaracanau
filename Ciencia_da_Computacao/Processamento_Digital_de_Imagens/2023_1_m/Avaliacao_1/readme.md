# Gabarito da prova

1. Seja **_f_** uma imagem contínua que deseja-se converter para o formato digital. Este processo compreende a realização das etapas de amostragem e quantização. Sobre este processo de digitalização, responda as questões a seguir:

a.  O que é amostragem? Explique. 

    Pegar os pixels da imagem continua e amostrá-los em uma função.

b. A cena capturada na imagem contínua f possui alguma influência na amostragem? Uma imagem com menos ou mais detalhes faz diferença nos parâmetros da amostragem?

     Não, pois a amostragem não considera o conteúdo ou as intensidades da imagem no seu processo, também não fazendo diferença se a imagem tem mais detalhes ou menos. Apesar disso, uma amostragem com intervalo expandido demais ocasiona perda de detalhe se a imagem original tiver muitos detalhes.

c.	O que é quantização? Explique.

    Pegar os valores amostrados e coloca-los na escala de quantização, mapeando-os ao valor na escala mais próximo do real.

d.	Ao utilizar menos bits por pixel do que é adequado para a quantização de um caso específico, o que pode ser observado na imagem quantizada?

     Ocorre uma perda de detalhes já que as cores vão estar muito próximas, não havendo tanto contraste.

2. Considere o segmento de imagem a seguir e faça o que se pede:

![Figura da questão 2](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_pergunta_2_i.PNG)

a.	Sendo V = {0, 1}, esboce os caminhos –4 , –8 e –m mais curtos entre os pixels p e q. Se um caminho específico (–4, –8 ou –m) não existir entre esses dois pixels, explique por quê.

    Resposta

    –4: Não, pois os pixels (1, 2) e ‘q’ não são vizinhos 4 entre si, e a interseção dos seus vizinhos 4 não pertencem a V, impossibilitando sua ligação.
    -8: Tamanho = 4

![Figura da resposta da questão 2 item a -8](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_resposta_2_a_i.PNG)
    
    -m: Tamanho = 5
    
![Figura da resposta da questão 2 item a -m](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_resposta_2_a_ii.PNG)

b.	Faça o mesmo para V = {1, 2}.

    Reposta
    -4: Tamanho = 6

![Figura da resposta da questão 2 item b -4](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_resposta_2_b_i.PNG)

    -8: Tamanho = 4

![Figura da resposta da questão 2 item b -8](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_resposta_2_b_ii.PNG)

    -m: Tamanho = 6

![Figura da resposta da questão 2 item b -m](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_resposta_2_b_iii.PNG)

3. Sobre histograma de imagens, responda o que se pede:

a.	O que é o histograma de uma imagem? Explique.

    É a função que um pixel de determinado valor de intensidade aparece na imagem determinadas vezes, para todos os pixels da imagem.

 b. A tabela a seguir apresenta os valores de intensidade de uma imagem hipotética de 8 bits e tamanho 8x8 pixels. Utilizando como base esses valores, construa o histograma desta imagem. Observação: não é necessário normalizar o histograma.

![Figura da questão 3](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_pergunta_3_i.PNG)

  
    Resposta

![Figura da resposta da questão 3 item b i](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_resposta_3_item_b_i.PNG)

4. Suponha que uma imagem de 3 bits (L=8) de dimensões 64 x 64 pixels (MN=4096) tenha a distribuição de intensidade demonstrada na tabela e histograma a seguir ([0, L - 1] = [0, 7]):

![Figura da questão 4 i](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_pergunta_4_i.PNG)


**O que se pede:**

a.	Aplique a equação de equalização de histograma para cada intensidade de pixel e esboce a função de transformação T(r) gerada.

    Resposta

![Figura da respota da questão 4 item a](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_resposta_4_item_a_i.PNG)

b.  Calcule e esboce o histograma equalizado p<sub>s</sub>(s<sub>k</sub>).

    Resposta

![Figura da resposta da questão 4 item b](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_resposta_4_item_b_i.PNG)

**Para consulta, segue a equação de equalização de histograma:**

![Figura da questão 4 ii](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2023_1_m/Avaliacao_1/imagens/pdi_2023_1_av1_pergunta_4_ii.PNG)

5. Indique no quadro a seguir qual transformação de intensidade produz o efeito descrito:

    Resposta
    
