# Gabarito da prova

1.	Sobre gerenciamento de memória virtual por segmentação, assinale a alternativa incorreta.

    A)	Um segmento é uma entidade lógica, que o programador conhece e usa como unidade lógica, assim o programa deve especificar a utilização do segmento.\
    B)	A memória segmentada simplifica o tratamento das estruturas de dados que estão crescendo ou diminuindo durante a execução dos processos.\
    C)	A segmentação apresenta vantagens em relação a tratamento de rotinas, uma vez que se cada rotina ocupa um segmento separado, ao ser recompilada nenhuma outra precisa ser alterada.\
    D)	Segmento pode conter uma rotina, um arranjo, uma pilha, ou um conjunto de variáveis, podendo assim combinar os tipos diferentes de dados.\
    E)	A segmentação facilita o compartilhamento de rotinas ou dados entre vários processos.

        Resposta: Item D.

2.	(COVEST-COPEST-2010) Um dos tipos de gerenciamento de memória utilizados por sistemas operacionais é a memória virtual. Este tipo de memória pode ser gerenciado por segmentação. Assinale a alternativa que descreve o funcionamento do gerenciamento de memória virtual por segmentação:

    A)	Divide o espaço de endereçamento virtual e espaço de endereçamento real em blocos do mesmo tamanho chamados de segmentos.\
    B)	Divide o espaço de endereçamento virtual e espaço de endereçamento real em bloco do mesmo tamanho chamados de buffer.\
    C)	Divide o espaço de endereçamento virtual e espaço de endereçamento real em blocos do mesmo tamanho chamados de páginas.\
    D)	Divide o endereçamento memória virtual em partes semelhantes chamadas de blocos.\
    E)	Divide o espaço do endereçamento virtual em blocos de tamanho diferentes chamados segmentos.

        Resposta: Item E.

3.	Considere as assertivas a seguir e assinale a alternativa correta.

    A)	Arquivos são conjuntos de estruturas lógicas e de instruções que permitem ao sistema operacional controlar o acesso aos arquivos contidos nas partições.\
    B)	Os arquivos são abstrações de molduras que oferece o meio de armazenamento e leitura de informações quando usado segmentação da memória virtual.\
    C)	Os arquivos são unidades lógicas criados e nomeados pelo processo, são gerenciados pelo sistema operacional mediante o sistema de arquivos.\
    D)	Em todos os sistemas operacionais nome de um arquivo é composta por duas partes separadas por um ponto, a segunda chamados de extensão do arquivo e indica algo sobre o arquivo.\
    E)	As extensões .bak, .mpg, .o, .c, significam respectivamente: cópia de segurança; imagem codificada segundo padrão jpeg; arquivo de ajuda; código fonte de programa em C.

        Resposta: Item C.

4.	Todo arquivo tem seu nome e dados, o sistema operacional associa outras informações extra a cada arquivo que chamamos de atributos. Relacionado aos atributos que o arquivo pode ter assinale a alternativa correta.

    A)	Os atributos de proteção informam as permissões de usuário sobre o arquivo, são eles proteção, senha, criador, proprietário.\
    B)	Atributos de chaves fornecem informações necessárias para encontrar arquivos, usados principalmente as estruturas de sequencia desestruturada de bytes, agilizando a busca pelo arquivo.\
    C)	As flags controlam alguma característica mais específica, exemplo a flag de acesso aleatório define o bit 1 para acesso sequencial e bit 0 para acesso aleatório.\
    D)	Atributos de tamanho definem o tamanho máximo do arquivo, exemplo, o tamanho do registro que especifica o número de bytes em um registro.\
    E)	Atributos de momentos especificam e delimitam o tempo de acesso para cada arquivo.

        Resposta: Item A.

5.	A operação com arquivo que permite que depois da criação do arquivo o usuário possa alterar algum atributo e o sistema pode alterar atributos de flags. Para tanto é preciso a operação de:

    A)	Open        B)  set attributes       C)  Write     D)  Append       E)  Read

        Resposta: Item B.

6.	(FEMPERJ-2012) Um diretório contém tipicamente um conjunto de entradas, uma por arquivo. O sistema operacional se encarrega de gerenciar o espaço em disco, identificando diferentes formas de armazenamento de arquivos e diretórios. Quanto as implementações do gerenciamento de arquivos no disco, pode-se dizer que:

    A)	A alocação indexada mantém, para cada arquivo, um índice com os ponteiros para os blocos que o compõe.\
    B)	A alocação contígua mantém o espaço em disco alocado ao arquivo com uma lista de blocos avulsos, onde a primeira palavra do bloco é um ponteiro para o próximo bloco, e o restante do bloco é usado para armazenar as informações do arquivo.\
    C)	A alocação encadeada é o mais simples de todos os esquemas de alocação, onde cada arquivo é armazenado no disco como um bloco contíguo de dados.\
    D)	A alocação contígua permite apenas acesso sequencial aos blocos de arquivos feito pela operação get attributes.\
    E)	A alocação indexada é simples e fácil de implementar, mas seu principal problema é a impossibilidade de alocação de espaço livre para aumentar um arquivo.

        Resposta: Item A.

7.	(CESPE-2016) Considerando a organização e a indexação de arquivos em um sistema de arquivos, assinale a opção correta com relação ao i-node (index node).


    A)	Comparativamente a outras formas de indexação, o i-node para os arquivos encadeados é mais vantajoso por não demandar uma tabela de memória e por não ter de ser carregado na memória em tempo de execução.\
    B)	O i-node é uma estrutura de dados que relaciona os atributos e os endereços em disco dos blocos de arquivos.\
    C)	Comparativamente a outras formas de indexação, uma desvantagem do i-node é possuir um arranjo que demanda espaço de memória muito maior que aquele ocupado por uma lista encadeada concebida a partir da utilização da tabela de arquivos FAT (file alocation table).\
    D)	O i-node não é capaz de controlar e identificar que blocos pertencem a que arquivos.\
    E)	O i-node corresponde a um método de indexação dos nomes dos arquivos no sistema de arquivos.

        Resposta: Item E.

8.	(CS-UFG-2017) “Manter um registro sobre o que o sistema de arquivos irá fazer antes que efetivamente o faça de modo que, se o sistema falhar antes da execução do trabalho planejado, é possível, após a reinicialização do sistema, recorrer ao log para descobrir o que estava acontecendo no momento da parada e retomar o trabalho”. Esse modo de operação é característico de sistemas de arquivos.

    A)	Com preempção.\
    B)	Journaling.\
    C)	Estruturados com base em DAG.\
    D)  Estruturados com base em log.\
    E)  Orientados à interrupção.

        Resposta: Item B.

9.	(CESGRANRIO-2012) Há diversas formas pelas quais um sistema computacional pode tratar os eventos de entrada e saída (E/S). O esquema no qual a Unidade Central de Processamento (UCP) fica ocupada em um laço de repetição (loop) à espera do término de uma operação de E/S é conhecido como esquema de:

    A)	E/S usando interrupção.\
    B)	O espaço de portas de E/S.\
    C)  E/S programada.\
    D)  E/S mapeado na memória.\
    E)  E/S usando DMA.

        Resposta: Item C.

10.	(CESPE-2016) Para controlar os dispositivos de entrada e/ou saída de um computador, a fim de que seja possível interagir com eles, é correto o uso de:

    A)	Algoritmo de escalonamento de processos.\
    B)	Software de monitoramento de tarefas.\
    C)	Software para gerenciamento de arquivos.\
    D)  Driver de dispositivo.\
    E)  Hardware de E/S.

        Resposta: Item D.

11.	Explique a diferença entre diretórios de nível único e hierárquico.
        
        Resposta

12.	Defina como funciona o virtual file system (VFS) e qual sua importância para o sistema operacional.

        Resposta

13.	Explique o que é e como funciona o Master Boot Record – MBR.

        Resposta

14.	Explique a função e a importância do Acesso Direto à Memória (DMA).

        Resposta

15.	O software de E/S é normalmente organizado em quatro camadas, cada camada tem uma função bem definida. Explique do que se trata essa funcionalidade de cada camada.

![Tabela da questão 14](https://github.com/talissonavila/IFCEMaracanau/blob/main/Ciencia_da_Computacao/Sistemas_Operacionais/2019_2_m/Avaliacao_3/imagens/so_2019_2_av3_pergunta_14_i.PNG)

        Resposta
        