# Gabarito da prova

1.	Desde seu surgimento os sistemas operacionais passam por um processo gradual de evolução. Assinale a alternativa que apresenta característica proveniente da quarta geração de computadores.

    A)	A Graphical User Interface com janelas, ícones, menus e mouse que facilitaram a interação dos usuários com o computador.\
    B)	A utilização de transístores que possibilitou aos computadores ganho maior de velocidade no processamento e surgiram os sistemas em lote.\
    C)	Os computadores desenvolvidos com válvulas, relés, resistências, com operação realizada sem auxilio de sistemas operacionais são da primeira geração de computadores.\
    D)	Surgimento dos primeiros sistemas operacionais: Fortran Monitor System (FMS) e o IBSYS.\
    E)	Surgimento das técnicas como multiprogramação, spooling, timesharing.

        Resposta: Item A.

2.	Assinale a alternativa que apresenta definição verdadeira relacionado a estrutura de sistema operacional apresentada.

    A)	As estruturas de máquinas virtuais são amplamente utilizadas atualmente e consiste na divisão do sistema em módulos pequenos bem definidos que são executando a nível de núcleo.\
    B)	A estrutura de micronúcleo é uma abstração que podem ser usadas para máquinas únicas ou rede de máquinas.\
    C)	Em estruturas monolítico o sistema inteiro é um único programa em modo núcleo, onde todas as rotinas são visíveis umas as outras e podem ser chamadas por qualquer uma.\
    D)	Sistemas de camadas possuem hierarquia de camadas onde cada camada depende da sua camada adjacente e provê o compartilhamento dos recursos de forma aleatória.\
    E)	Modelo cliente-servidor é baseado na estrutura monolítico, provê o compartilhamento de vários recursos de um mesmo hardware, para serviços virtualmente separados.

        Resposta: Item C.

3.	(CCV-UFC-2019) Sobre processo computacional ou simplesmente processo, é correto afirmar que:

    A)	Processos paralelos são aqueles que ocorrem um de cada vez, um a um no tempo, serialmente, como que de forma exclusiva.\
    B)	O estado de Execução é a situação em que o processo está apto a utilizar o processador quando este estiver disponível.\
    C)	Um processo é uma atividade que ocorre em meio computacional, usualmente possuindo um objetivo definido, tendo duração infinita e utilizando uma quantidade limitada de recursos computacionais.\
    D)	Um processo é um programa em execução, o que envolve o código do programa, os dados em uso, os registradores do processador, sua pilha e o contador de programa, além de outras informações relacionadas a sua execução.\
    E)	Quando um processo finaliza o uso de um recurso, o sistema operacional recolocará o processo na lista de processos em execução, através da transição denominada reativação ou Awake, o que faz com que o processo passe do estado Pronto para Bloqueado.

        Resposta: Item D.

4.	O escalonador é a parte do sistema operacional responsável pelo escalonamento de processo. Para tanto, é utilizando um algoritmo de escalonamento que dependendo da área de aplicação pode apresentar objetivos diferentes. São objetivos de um algoritmo de escalonamento para sistemas de tempo real:

    A)	Cumprimento dos prazos e previsibilidade.\
    B)	Cumprimento dos prazos e proporcionalidade.\
    C)	Tempo de resposta e proporcionalidade.\
    D)  Vazão e tempo de retorno.\
    E)  Vazão e Equilíbrio.

        Resposta: Item A.

5.	Algoritmos de escalonamento para sistemas em lote que apresenta escalonamento não preemptivo baseado no conhecimento do tempo de execução, minimiza o tempo de retorno e é adequado somente para tarefas disponíveis simultaneamente.

    A)	Primeiro a chegar, primeiro a ser servido.\
    B)	Próximo de menor tempo restante.\
    C)	Escalonamento por Prioridade.\
    D)  Próximo de menor tempo restante.\
    E)  Tarefas mais curtas primeiro.

        Resposta: Item E.

6.	Exclusão mútua assegurar que outros processos estejam impedidos de usar uma variável ou arquivo compartilhados em uso por outro processo. São soluções de exclusão mútua com espera ociosa exceto:

    A)	Chaveamento Obrigatório.\
    B)	Dormir e acordar.\
    C)  Variáveis do tipo trava.\
    D)  Desabilitando interrupções.\
    E) Instrução TLS.

        Resposta: Item B.


7.	(IF-PA -2019) Em relação à gerencia de processo, marque a alternativa correta:

    A)	O processo é um programa no estado de pronto.\
    B)	A thread permite que apenas uma execução ocorra no mesmo ambiente do processo.\
    C)	Os estados do processo são execução, pronto, bloqueado ou espera.\
    D)	Escalonamento é a escolha do processo, em estado de execução.\
    E)	Os sinais são mecanismos que permitem notificar o sistema operacional de eventos gerados pelo processador.

        Resposta: Item C.

8.	A criação de threads é padronizada pelo IEEE 1003.1c que define o Pthreads e mais de 60 chamadas de funções. A chamada pthread_yield tem como finalidade:

    A)	Esperar que um thread específico seja abandonado.\
    B)	Criar e inicializar uma estrutura de atributos do thread.\
    C)	Remover uma estrutura de atributos do thread.\
    D)	Concluir a chamada de thread.\
    E)	Liberar a CPU para que outro thread seja executado.

        Resposta: Item E.

9.	Considere as afirmações abaixo relacionado a implementação de processos.\
I.	O processo é implementação pelo sistema operacional através de uma tabela de processos.\
II.    A tabela de processos reside na memória principal e concorre espaço de armazenamento com os processos.\
III. A tabela de processos possui apenas uma entrada para cada processo.\
IV. Na tabela de processo são armazenadas informações sobre o contexto do hardware e software, e o espaço de endereçamento de cada processo.\
É correto o que se afirma em:

    A)	II, III apenas.\
    B) I, III e IV apenas.\	
    C) I e IV apenas.\
    D) II e IV apenas.\
    E) I, II e IV apenas.

        Resposta: Item B.

10.	 Embora regiões críticas impeçam condições de disputa, não é suficiente pra cooperação correta e eficiente de processos paralelos, sendo necessário estabelecer condições para tal. São condições estabelecidas para processos paralelos exceto. <br><br>
    A)	Nenhum processo deve esperar eternamente para entrar em região crítica.\
    B)	Processos não podem ter conhecimento sobre a velocidade ou números de CPUs.\
    C)	Nunca dois processos podem simultaneamente entrar em suas regiões críticas.\
    D)	Nuca desabilitar as interrupções antes de entrar na região crítica.\
    E)	Nenhum processo executando fora de sua região crítica pode bloquear outros processos.

            Resposta: Item D.

11.	 Cite as vantagens e desvantagens de se implementar threads no espaço do usuário e threads no núcleo.

            Resposta

12.	 Explique a diferença do uso de semáforo, mutexes e monitores.

             Resposta

13.	 Explique o que são threads pop-up, aponte suas vantagens e problema, e exemplifique sua utilização.

             Resposta

14.	 Cite os eventos que causam a criação de processos.
     
            Resposta

15.	Explique em que consiste e como funciona a solução de Peterson.

             Resposta
    