# Gabarito da prova

1.	(INEP-2015) Com relação ao gerenciamento de memória com paginação em sistemas operacionais, assinale a opção correta.

    A)	As páginas utilizadas por um processo, sejam de códigos ou de dados, devem ser obrigatoriamente armazenadas na partição de swap do disco, quando o processo não estiver sendo executado.\
    B)	O espaço de endereçamento virtual disponível para os processos pode ser maior que a memória física disponível.\
    C)	Todas as páginas de um processo em execução devem ser mantidas na memória física enquanto o processo não tiver terminado.\
    D)	Um processo somente pode ser iniciado se o sistema operacional conseguir alocar um bloco contíguo de páginas do tamanho da memória necessária para execução do processo.\
    E)	Um processo somente pode ser iniciado se o sistema operacional conseguir alocar todas as páginas de código desse processo.

        Resposta: Item B.

2.	(COSEAC-2015) Na memória virtual por paginação, são políticas de alocação de páginas:

    A)	Paginação por demanda e paginação antecipada.\
    B)	Substituição local e substituição global.\
    C)	Alocação fixa e alocação variável.\
    D) FIFO e LRU.\
    E) Aleatório e FIFO.

        Resposta: Item B.

3.	(COSEAC-2015) Na urgência de memória virtual, é uma característica pertinente ao algoritmo de substituição de página LRU (Least Recently Used):

    A)	Selecionar a página mais referenciada na memória principal.\
    B)	Necessitar de um bit adicional conhecido como bit de referência.\
    C)	Selecionar a página na memória principal que está mais tempo sem ser referenciada.\
    D)	Selecionar a primeira página que encontra na memória principal.\
    E)	Escolher a página aleatoriamente.

        Resposta: Item C.

4.	(FCC-2012) Quando a memória é alocada dinamicamente, o sistema operacional deve gerenciá-la, em termos gerais, de duas maneiras:

    A)	Realocação e proteção.\
    B)	Paginação e troca de processos.\
    C)	Proteção e mapa de bits.\
    D)  Troca de processos e relocação.\
    E)  Mapa de bits e lista de disponíveis.

        Resposta: Item E.
5.	Sobre o gerenciamento de memória sem abstração é correto afirmar:

    A)	É usado em ambientes multiprogramados e cada processo gerencia seu próprio espaço.\
    B)	Os programas consideram apenas a sua memória física particular sem interferir nos demais processos.\
    C)	Um dos modos de organização dos programas consiste na alocação dos programas em ROM liberando a memória para o sistema operacional.\
    D)	Possui a dificuldade de executar múltiplos programas, pois a memória física é referenciada e compartilhada com o sistema operacional.\
    E)	Realiza alta utilização de CPU, pois seus processos são todos orientados à CPU.

        Resposta: Item D.

6.	Em relação a estrutura de uma entrada na tabela de página é incorreto o que se afirma em:

    A)	O esquema de entradas independente da máquina, pois o tipo de informação presente é o mesmo.\
    B)	O número de moldura identifica a página e tem como objetivo mapeamento das mesmas.\
    C)	Bit de presente/ausente referencia se a página está (bit=1) ou não (bit=0) na memória.\
    D)	Bit de referência controla o uso da página e auxilia o sistema na escolha da página que deve deixa a memória.\
    E)	Os bits de proteção indicam tipos de acessos permitidos. 

        Resposta: Item A.

7.	No gerenciamento de memória livre por lista encadeada são usados diversos algoritmos de alocação dos espaços. O algoritmo que procura pelo maior espaço capaz de armazenar o processo, de tal forma que o espaço restante seja grande o suficiente para armazenar outro processo. É:

    A)	Next fit.\
    B)  Quick fit.\
    C)  Best fit.\
    D)  Worst fit.\
    E)  First fit.

        Resposta: Item D.

8.	Considere as assertivas sobre aceleração de paginação.

    I.	Em projeto simples a tabela de páginas é constituída por arranjo de registradores de hardware.\
    II.	A TLB (translation lookaside buffer) não permite o gerenciamento se não pelo MMU.\
    III.	No gerenciamento da TLB por software, as ausências são consideradas leves quando a página referenciada não está na TLB mais está na RAM.\
    IV.	Ausência de página na TLB é atualizada pelo MMU baseado na tabela de processos.\
    É correto o que se afirma em:

    A)	I e II apenas.\
    B)  I, II e III apenas.\
    C)  III e IV apenas.\
    D)  II e IV apenas.\
    E)  I e III apenas. 

        Resposta: Item B.

9.	O algoritmo de substituição de página que utiliza a localidade de referência para evitar a ultrapaginação, assegurando a presença das páginas do processo antes que ele seja executado, reduzindo significativamente a falta de página.

    A)	Segunda chance.\
    B)	De relógio.\
    C)	Conjunto de trabalho.\
    D)  Menos usado recentemente.\
    E)  Primeiro a entrar, primeiro a sair.

        Resposta: Item C.

10.	Ao desenvolver um Sistema Operacional o projetista deve considerar cuidadosamente algumas questões sobre paginação quando relacionados a processos concorrentes. Relacionados a questão de implementação de paginação, assinale a alternativa incorreta.

    A)	No controle de carga quando há necessidade de troca de páginas para o processo são considerados principalmente o grau de multiprogramação e o surto de CPU.\
    B)	Compartilhamento de páginas busca principalmente evitar a duplicidade de páginas no RAM.\
    C)	No compartilhamento de páginas o método copiar-se-escrita consiste em mapear as páginas compartilhadas marcando como read-only até acontecer uma tentativa de escrita.\
    D)	A fragmentação interna causada quando um segmento de informação não ocupa um número inteiro de páginas.\
    E)	Na utilização de bibliotecas compartilhadas, a biblioteca é carregada somente mediante demanda. 

        Resposta: Item E.

11.	Considere um sistema de troca de processos entre a memória e o disco no qual a memória é constituída dos seguintes tamanhos de lacunas livres em ordem na memória: 10KB, 4KB, 20KB, 18KB, 7KB, 9KB, 12KB, 15KB. Quando usado o algoritmo Best fit, qual a lacuna é tomada pela solicitação sucessivas do seguimento de:

A)	8KB ________\
B)  3KB ________

        Resposta
        A) 9KB    
        B) 4KB
12.	Explique a utilização de Registradores-base e Registradores-limite.

        Quando um programa é executado.
        Registradores-base: é carregado desde o início do processo.
        Registradores-limite: é carregado o comprimento do programa.

13.	Defina: molduras, páginas, ultrapaginação e MMU.

            MMU – Unidade de gerenciamento de Memória que mapeia endereços virtuais em físicos.
            Página – O tamanho (partição) da memória virtual. Cada processo tem um ou um conjunto de páginas de modo tal a sua necessidade.
            Moldura – O tamanho (partição) da memória física.
	            Ex: 16GB de RAM; 
                Molduras de 100MB, teria-se 10 molduras na memória a ser  distribuída entre os processos.

14.	Explique o compartilhamento de página com os espaços I espaço D, e sem espaço I e espaço D.

        Sem espaço I e D – O SO deve ter ciência dos processos, pois caso hajam dois processos, ‘A’ com todas as suas páginas na memória e ‘B’ com os seus dados diferentes de ‘A’, ao passo que ‘A’ é finalizado por término ou pelo gerenciador, ‘B’ sofrerá falta de páginas até ter suas páginas carregadas na memória.

        Com espaço I e D – Existem duas tabelas, uma para I (instruções) e outra para D (compartilhamento de dados.)

15.	Qual a principal desvantagem do gerenciamento de memória com mapa de bits?

        Resposta