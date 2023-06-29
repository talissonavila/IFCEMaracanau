# Gabarito da Prova
1. Suponha uma imagem hipotética cujo tamanho é 50 x 50 pixels. Para cada uma das opções da lista abaixo, calcule: i) quantidade de bits por pixel, (ii) quantidade de níveis de intensidade por pixel e (iii) quantidade de bits necessários para armazenamento da imagem hipotética.

    a.	Monocromática.
    
        i) 1 bit.
        ii) 2 níveis (0-1).
        iii) 1 * 50 * 50 = 2500b.

    b.  Níveis de cinza.
    
        i) 8 bits.
        ii) 256³ = 16777216.
        iii) 1 * 50 * 50 = 20000b.

    c.  Cor RGB.
    
        i) 24 bits.
        ii) 256= 167777216.
        iii) 24 * 50 * 50 = 60000b.

2.	(2 pontos) Seja V = {1} o conjunto de valores utilizado para definir a adjacência. Para este conjunto, faça o que se pede:\
    a.	Defina conceitualmente adjacência-4, adjacência-8 e adjacência-m.
    
            Adjacência-4: Dois pixels ‘p’ e ‘q’ com valores pertencendo a V são adjacentes quatro se ‘q’ estiver no conjunto N4(p).\
            Adjacência-8: Dois pixels ‘p’ e ‘q’ com valores pertencendo a V são adjacentes oito se ‘q’ estiver no conjunto N8(p).\
            Adjacência-m: Dois pixels ‘p’ e ‘q’ com valores pertencendo a V são adjacentes misto se: ‘q’ estiver no N4(p) ou ‘q’ está no ND(p) e o conjunto N4(p) ∩ N4(q) não contém nenhum pixel cujos valores pertencem a V.

    b.	Para cada tipo de adjacência, crie uma imagem binária hipotética contendo um exemplo desta adjacência. Importante: não esqueça de assinalar os pixels que participam da adjacência indicada.
  	
            Imagem A-4 – pixel p = (1, 1); pixel q = (0, 1).\
   ![Imagem hipotética A-4](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_resposta_3b_i.PNG)
   
            Imagem A-8 – pixel p = (1, 1); pixel q = (0, 2).\
![Imagem hipotétitca A-8](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_resposta_3b_ii.PNG)

            Imagem A-m – pixel p = (1, 1); pixel q = (0, 1).
![Imagem hipotética A-m](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_resposta_3b_iii.PNG)

4.   Observe os histogramas apresentados a seguir.\
    ![Imagem 1](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_pergunta_3_i.png)
    ![Imagem 2](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_pergunta_3_ii.png)
    ![Imagem 3](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_pergunta_3_iii.png)
    ![Imagem 4](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_pergunta_3_iv.png)

Para cada histograma, indique se este foi criado a partir de uma imagem:

a.	Baixo contraste.\
b.	Alto contraste.\
c.	Clara.\
d.	Escura.
        
            a. Imagem 3
            b. Imagem 4
            c. Imagem 1
            d. Imagem 2
4.  As imagens mostradas nas Figuras 2(a) 2(b) (arquivos figura_2a.png e figura _2b.png em anexo) são diferentes entre si, mas possuem histogramas idênticos. Sobre estas duas imagens, faça o que se pede:\
![Imagem da questão 4](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_pergunta_4.png)

    a.	Explique porque os histogramas são idênticos, uma vez que as imagens são diferentes.
    
    		Resposta
		
    b.	Suponha que cada imagem seja borrada com um filtro da média de tamanho 3x3. Os histogramas permanecem iguais?
    
    		Resposta
		
    c.	Esboce os histogramas antes e depois da convolução, justificando os resultados.
    
        	Resposta
		
5. Diversas transformações foram aplicadas a uma mesma imagem, cujos resultados são apresentados a seguir. Em cada imagem foi aplicada somente uma transformação. Para cada uma destas transformações, faça o que se pede:

    a.	Identifique a operação efetuada.\
    b.	Explique o funcionamento desta operação.\
    ![Imagem da questão 5](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_pergunta_5.png)
    
        Operação A:
        a. Negativo de imagem.
        b. Ele reverte os níveis de intensidade de uma imagem, desta forma produz o equivalente ao negativo fotográfico.
        Operação B:
        a. Equalização de histograma.
        b. Este procedimento espalha o histograma da imagem por toda a faixa de valores disponíveis mas não muda quantidade de ocorrências de um determinado valor de intensidade.
        Operação C:
        a. Binarização de imagem.
        b. Ela converte a imagem em todos de cinza em preto e branco. Valores de intensidade antes maiores que 127 agora recebem 1 e valores de intensidade antes menores que 128 recebem 0.
        Operação D:
        a. Filtro da média.
        b.
        Operação E:
        a. Gradiente de Sobel.
        b.
6. Na figura a seguir (arquivo ckt-board-saltpep-prob.pt05.tif em anexo) é mostrada a imagem de uma placa de circuito corrompida pelo ruído sal e pimenta:

![Imagem da questão 6](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Processamento_Digital_de_Imagens/2021_1/Avaliacao_1/imagens/pdi_2021_1_av1_pergunta_6.png)

Utilizando uma janela de tamanho 5 x 5, faça o que se pede:

a.	Aplique os filtros de suavização da média e mediana.

		Resposta
		
b.	Apresente as imagens resultantes.

		Resposta
		
c.	Qual filtro teve o melhor desempenho? Explique.

        	Resposta
