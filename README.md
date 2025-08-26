# Comunicação UDP em C

Este projeto apresenta uma implementação simples de comunicação via protocolo UDP utilizando a linguagem C. Ele inclui um servidor capaz de receber mensagens em uma porta específica e um cliente que envia mensagens para o servidor, permitindo testar conceitos de redes e sockets de forma prática.

## Como executar o servidor UDP

1. Compile o servidor:
    ```bash
    gcc udpServidor.c -o udpServidor
    ```

2. Execute o servidor informando a porta como argumento:
    ```bash
    ./udpServidor 3000
    ```

## Como executar o cliente UDP

1. Compile o cliente:
    ```bash
    gcc udpCliente.c -o udpCliente
    ```

2. Execute o cliente informando o IP ou hostname e a porta:
    ```bash
    ./udpCliente localhost 3000
    ```
