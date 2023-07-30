# Gabarito da prova

1. Usando dedução natural, apresente uma derivação para

    p ∨ q, ¬q ∨ r ⊢ p ∨ r.

        Resposta
![Figura da resposta da questão 1](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Logica_para_Computacao/2022_2/Avaliacao_1/imagens/logica_2022_2_av1_pergunta_1_i.PNG)

2. Defina um algoritmo recursivo atoms(A)  que recebe uma fórmula A e retorna o conjunto de todas as fórmulas atômicas que ocorrem em A. Por exemplo, 

    atoms((p ∧ ¬(p → ¬q)) ∨ ¬q) = {p, q}     e\
    atoms(¬(p ∧ s) ∨ (p → ¬q)) = {p, s, q}.

        Resposta
    ```python
            def atomicas(formula):
                if isinstance(formula, Atomica):
                    lista_de_atomicas = [formula.nome]
                    return set(lista_de_atomicas)
                if isinstance(formula, Nao):
                    return atomicas(formula.dentro)
                if isinstance(formula, Implica) or isinstance(formula, E) or isinstance(formula, Ou):
                    return atomicas(formula.esquerda) | atomicas(formula.direita)
    ```
3.  Assuma que toda pessoa é honesta ou desonesta, mas não ambos. Além disso, toda pessoa honesta sempre fala a verdade e toda pessoa desonesta sempre mente. Você conhece José e Maria. José faz a seguinte afirmação: “Maria é desonesta”. Maria faz a seguinte afirmação: “Nem José nem eu somos desonestos”. Usando dedução natural apresente uma demonstração para garantir a categoria de José e a categoria de Maria.

        Resposta
![Figura da resposta da questão 3](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Logica_para_Computacao/2022_2/Avaliacao_1/imagens/logica_2022_2_av1_pergunta_3_i.PNG)