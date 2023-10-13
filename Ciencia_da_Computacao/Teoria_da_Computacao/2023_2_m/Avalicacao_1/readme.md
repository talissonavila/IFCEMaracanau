# Gabarito da prova
1. Sobre a linguagem L aceita pelo AF abaixo, assinale a opção correta

    ![Figura 1 da questão 1](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Teoria_da_Computacao/2023_2_m/Avaliacao_1/imagens/teoria_2023_2_av1_pergunta_1_i.png)

    A. É a linguagem das strings com um número ímpar de a’s e par de b’s.\
    B.	É a linguagem das strings com um número par de a’s e ímpar de b’s.\
    C.	É a linguagem das strings com o mesmo número de a’s e b’s.\
    D.	É a linguagem das strings que começam com a e terminam com b.\
    E.	Nenhuma das anteriores.

        Resposta: Item E.

2. Assinale a opção com string aceita pelo AF abaixo.

    ![Figura 1 da questão 2](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Teoria_da_Computacao/2023_2_m/Avaliacao_1/imagens/teoria_2023_2_av1_pergunta_2_i.png)

    A.	ababab\
    B.	bababa\
    C.	ababa\
    D.  abaaba\
    E.  babbab

        Resposta: Item C.

3. Escreva a expressão regular da linguagem aceita pelo AFnD abaixo.

    ![Figura 1 da questão 3](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Teoria_da_Computacao/2023_2_m/Avaliacao_1/imagens/teoria_2023_2_av1_pergunta_3_i.png)

        R:

    L = $(11, 110)^*$

4.  Escreva a expressão regular que corresponde ao AFnD abaixo.

    ![Figura 1 da questão 4](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Teoria_da_Computacao/2023_2_m/Avaliacao_1/imagens/teoria_2023_2_av1_pergunta_4_i.png)

        R:
    R = $(0, 1)^*(00, 11)(0, 1)(0, 1)^*$

5. Marque a opção FALSA.

    A. Não-determinismo é uma generalização de determinismo.\
	B. Todo AFnD é automáticamente um AFD.\
	C. Em um AFD existe uma função de transição, já no AFnD existe uma relação de transição.\
	D. As transições ε não estão definidas para AFDs.\
	E. A operação “leva em passo” trata-se de uma relação quando definida em cima de AFnDs.

        Resposta: Item B.

6. Dado que a vírgula denota a operação de união e que “ε” é o símbolo/string vazia. Marque a expressão que corresponde a linguagem

    L={x ∈ {0,1}* | x é uma string com um número de 0’s múltiplos de 3}.

    A. {${1^*01^*01^*01}^*$}\
    B. {${01^*01^*0, 1}^*$}\
    C. {${1^*01^*01^*01*}^*$}\
    D. {${1^*01^*01^*01^*, ε}$}\
    E. Nenhuma das anteriores.

        Resposta: Item B.

7. Seja um alfabeto Σ={a,b}, e as expressões regulares R1=$a(a,b)^*$ e R2= $b(a,b)^*$.

    A. L(R1) = L(R2)\
    B. L(R2) = {w - w termina com b}\
    C. Existe um AFD cuja linguagem é L(R1) ∪ L(R2)\
    D. Não existe AFnDs cujas linguagens sejam L(R1) e L(R2)\
    E. Nenhuma das anteriores.

        Resposta: Item C.

8. Simplifique a seguinte expressão regular.

    **$(ε, 1^*(011)^*(1^*(011)^*)^*)$**

    A. $(1^*(011)^*)$\
    B. $(1, (011)^*)$\
    C. $(1011)^*$\
    D. $(1, 011)^*$\
    E. $(1^*, (011)^*)$

        Resposta: Item D.

9. Seja ε a string vazia. A expressão regular (0, ε)(1, ε) gera qual linguagem?

    A. {0, 1}\
    B. {01, ε}\
    C. {0, 1, ε}\
    D. {0, 1, 01, ε}\
    E. {0, 1, 01, 11, 00, 10, ε}

        Resposta: Item D.

10. Pode existir um AF sem estados finais mas nunca um AF sem estado inicial.
    
    O Certo.\
    O Errado.

        Resposta: Certo.

11. Um AF pode apresentar infinitos estados.

    O Certo.\
    O Errado.

        Resposta: Errado.