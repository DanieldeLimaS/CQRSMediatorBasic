# CQRS com Mediator em .NET7

Esse projeto implementa o padrão de arquitetura [CQRS (Command Query Responsibility Segregation)](https://martinfowler.com/bliki/CQRS.html) usando o Mediator como padrão de desenvolvimento.

## O que é CQRS?

CQRS é uma abreviação para Command Query Responsibility Segregation, que é um padrão de arquitetura usado para separar operações de leitura (query) e escrita (command) em aplicações. O objetivo é melhorar a escalabilidade, separar as responsabilidades e tornar os sistemas mais eficientes.

## O que é Mediator?

O Mediator é um padrão de projeto que permite que um objeto central gerencie as interações entre diferentes objetos. O objeto central, chamado de Mediator, é responsável por direcionar as solicitações de outros objetos para o objeto apropriado para procesar a solicitação.

## Como usar o Mediator em um projeto CQRS?

Usar o Mediator em um projeto CQRS é simples. Primeiro, você precisa definir as solicitações que serão realizadas no sistema. Estas solicitações podem ser comandos (para realizar uma ação) ou consultas (para recuperar informações).

Em seguida, você precisa criar um Mediator. Este objeto central vai receber as solicitações e direcioná-las para o objeto apropriado para processar a solicitação.

Por fim, você precisa implementar os objetos que processam as solicitações. Eles são responsáveis por realizar as operações de leitura e escrita (CQRS) necessárias.

## Próximos passos

Agora que você já sabe como usar o Mediator em um projeto CQRS, você pode começar a implementar seu próprio sistema usando essas duas técnicas.

Lembre-se de que muitos problemas de escalabilidade e performance podem ser resolvidos usando o CQRS e o Mediator. Portanto, não hesite em experimentar essas técnicas para otimizar seu sistema.

##  Instalar Pacote
```
dotnet add package MediatR.Extensions.Microsoft.DependencyInjection --version 11.1.0

dotnet add package MediatR --version 12.0.0
```
