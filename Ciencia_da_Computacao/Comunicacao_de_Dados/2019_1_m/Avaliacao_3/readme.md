# Gabarito da prova
1. Explique detalhadamente a diferença entre a camada de enlace e a camada de rede. Relacione de forma coerente em sua resposta os seguintes termos: endereço(s) MAC, endereço(s) IP, enlace, roteamento, escolha do melhor caminho, entrega de dados entre dois nós no mesmo enlace, entrega de dados entre máquinas na mesma rede ou em redes diferentes. Sublinhe os termos na sua resposta. 

        Resposta

         A camada de enlace trabalha com endereço(s) MAC, que são os endereços físicos que servem para mandar mensagens para máquinas que estão no mesmo enlace que ela, fazendo a entrega de dados entre dois nós no mesmo enlace.
        Já a camada de rede trabalha com endereço(s) IP, que são os endereços lógicos que servem para localizar máquinas que estão na mesma rede ou em redes diferentes. A camada de rede realiza o roteamento até a máquina de destino, ou seja, realiza a escolha do melhor caminho para realizar a entrega de dados entre máquinas na mesma rede ou em redes diferentes.

2. Explique detalhadamente o que é e o princípio básico da técnica *checksum*. 
   
        Resposta

        As mensagens são divididas em palavras de K bits e somadas usando complemento de um junto com o checksum que inicializou com 0. O complemento do resultado da soma é o checksum e o quadro é transmitido.
        No lado do receptor, a mensagem é dividida em palavras de K bits e são somadas utilizando complemento de um com o checksum inicializando em 0. O complemento do resultado da soma é o checksum do receptor. São somadas os checksum sem ser pelo complemento de um, se o resultado for 0, a mensagem é aceita, se não, é rejeitada.

3. Explique detalhadamente se há relação entre códigos de detecção/correção de erros mais robustos e largura de banda de transmissão.
   
        Resposta

        Sim, há relação entre os códigos de detecção/correção de erros mais robustos e a largura de banda de transmissão, pois para que possa ser corrigido e/ou detectado o erro, são enviados bits extras para a correção, como não é possível saber quais bits serão corrompidos, os bits extras podem chegar até o mesmo tamanho do quadro original, exigindo uma maior largura de banda de transmissão para enviar esses dados extras de forma que a transmissão não seja tão lenta.

4. Explique detalhadamente o protocolo CSMA/CA. 
   
        Resposta

        O protocolo CSMA/CA “escuta” o meio para detectar o sinal de portadora, caso não tenha, ele espera um período de tempo aleatório, ou seja, entra em back-off exponencial e ao final, transmite o quadro. Espera uma confirmação do quadro que foi enviado. Se time-out, reenvia o quadro.