----------------------------------------------
# Monitor de Sites em Go

Este é um simples monitor de sites desenvolvido em Go. Ele permite que você monitore a disponibilidade de sites específicos, registre logs e visualize o histórico de eventos.

## Funcionalidades

- Iniciar monitoramento de sites.
- Exibir logs do monitoramento.
- Sair do programa.

## Como Usar

1. Clone o repositório:

    ```
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Navegue até o diretório do projeto:

    ```
    cd seu-repositorio
    ```

3. Execute o programa:

    ```
    go run main.go
    ```

4. Escolha uma opção no menu para iniciar o monitoramento, exibir logs ou sair do programa.

5. Os resultados do monitoramento serão registrados no arquivo `log.txt`.

## Sites para Monitorar

Adicione os sites que deseja monitorar ao arquivo `sites.txt`, um por linha.

## Dependências

- Go 1.16 ou superior

## Exemplo de sites.txt
   ```
https://httpbin.org/status/200
https://www.alura.com.br
https://www.youtube.com.br
https://www.google.com.br
   ```


*Lembre-se de que este é um projeto de exemplo e pode ser estendido com mais funcionalidades conforme necessário. Consulte a documentação oficial do Go para mais informações sobre a linguagem e bibliotecas utilizadas: [https://golang.org/](https://golang.org/).*
----------------------------------------------
