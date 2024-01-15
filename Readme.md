# DIO - Trilha .NET - Fundamentos
www.dio.me

## Desafio de projeto
Este projeto foi realizado como parte do módulo de fundamentos da trilha .NET da Digital Innovation One.

## Contexto
O sistema de estacionamento foi desenvolvido para gerenciar os veículos estacionados e realizar operações como adicionar, remover e listar veículos, além de calcular o valor cobrado pelo período de estacionamento.

## Proposta
Foi construída uma classe chamada "Estacionamento" com as seguintes características:

- **precoInicial**: Tipo decimal que representa o preço para estacionar.
- **precoPorHora**: Tipo decimal que representa o preço por hora de estacionamento.
- **veiculos**: Lista de strings que mantém o registro das placas dos veículos estacionados.

E três métodos principais:

- **AdicionarVeiculo**: Recebe e registra a placa de um veículo.
- **RemoverVeiculo**: Verifica se o veículo está estacionado, calcula o custo e o remove da lista.
- **ListarVeiculos**: Exibe todos os veículos estacionados ou uma mensagem se não houver nenhum.

Além disso, foi implementado um menu interativo para facilitar a interação com o usuário.

## Solução
A solução final é um programa em C# totalmente funcional que atende a todas as especificações do desafio. As operações de adicionar, remover e listar veículos são executadas conforme as regras de negócio definidas.

### Como executar
Descreva aqui como o usuário deve fazer para executar o seu programa. Por exemplo:
1. Clone o repositório para a sua máquina local.
2. Navegue até a pasta do projeto através do terminal.
3. Execute o comando `dotnet run` para iniciar o programa.
4. Siga as instruções exibidas no menu interativo.

### Contribuições
Agradecimentos a todos os contribuidores e mentores da DIO pelo suporte durante o desenvolvimento deste projeto.

