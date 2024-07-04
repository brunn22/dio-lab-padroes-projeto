# Desafio DIO - Projeto de Padrões de Projeto em Java

Este projeto demonstra a aplicação de três padrões de projeto em Java: Singleton, Strategy e Facade. Ele foi desenvolvido como parte de um estudo sobre boas práticas de design de software.

## Padrões de Projeto Utilizados

### Singleton

O padrão Singleton garante que uma classe tenha apenas uma instância e fornece um ponto global de acesso a ela. Este projeto inclui três variações do padrão Singleton:

- **SingletonLazy**: Inicialização tardia (lazy initialization).
- **SingletonEager**: Inicialização antecipada (eager initialization).
- **SingletonLazyHolder**: Utiliza uma classe estática interna para garantir a inicialização tardia de forma thread-safe.

### Strategy

O padrão Strategy permite que um algoritmo varie independentemente dos clientes que o utilizam. Este projeto inclui diferentes comportamentos para um robô:

- **ComportamentoNormal**: Implementa um movimento normal.
- **ComportamentoDefensivo**: Implementa um movimento defensivo.
- **ComportamentoAgressivo**: Implementa um movimento agressivo.

### Facade

O padrão Facade fornece uma interface simplificada para um subsistema complexo. Neste projeto, a classe `Facade` simplifica a interação com os subsistemas de CRM e CEP.

## Estrutura do Projeto

- **subsistema1.crm**: Contém a classe `CrmService` responsável por salvar informações de clientes.
- **subsistema2.cep**: Contém a classe `CepApi` responsável por recuperar informações de cidade e estado com base no CEP.
- **one.digitalinnovation.gof.singleton**: Contém as implementações dos padrões Singleton.
- **one.digitalinnovation.gof.strategy**: Contém as implementações dos padrões Strategy.
- **one.digitalinnovation.gof.facade**: Contém a implementação do padrão Facade.
