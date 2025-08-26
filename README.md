## Como executar o servidor UDP

Compile o servidor:

```bash
gcc udpServidor.c -o udpServidor
```

Execute o servidor informando a porta como argumento:

```bash
./udpServidor 3000
```

## Como executar o cliente UDP

Compile o cliente:

```bash
gcc udpCliente.c -o udpCliente
```

Execute o cliente informando o IP ou hostname e a porta:

```bash
./udpCliente localhost 3000
```