# Locadora de Veículos

Sistema de locadora de veículos desenvolvido como **projeto final da disciplina de Programação Orientada a Objetos**, aplicando os conceitos de POO a um problema real de gestão de frota, clientes e aluguéis.

## Equipe

| Nome | GitHub |
|------|--------|
| Isaque dos Reis Jess | [@usuario1](https://github.com/usuario1) |
| Laura Zoffoli Silveira | [@usuario2](https://github.com/usuario2) |
| Nicolas Lourenço | [@nicolaslourenc2](https://github.com/nicolaslourenc2) |
| Rauhan Kniess de Moura| [@usuario3](https://github.com/usuario3) |

**Disciplina:** Programação Orientada a Objetos
**Instituição:** _Pontifícia Universidade Católica do Paraná_
**Professora:** _Marina de Lara_

## escrição do problema

Uma locadora precisa controlar sua frota, saber quais veículos estão disponíveis, cadastrar clientes, registrar reservas e aluguéis, calcular o valor a cobrar e tratar devoluções, incluindo multas por atraso ou danos. Cada tipo de veículo tem regras próprias (documentação exigida, forma de cobrança), o que torna o domínio adequado para modelagem orientada a objetos.

## Funcionalidades

- [ ] Cadastro de veículos (carro, moto e caminhão)
- [ ] Cadastro de clientes
- [ ] Controle de disponibilidade da frota
- [ ] Reserva de veículos
- [ ] Registro de aluguel
- [ ] Cálculo do valor do aluguel conforme o tipo de veículo
- [ ] Registro de devolução e cálculo de multas
- [ ] Histórico de aluguéis

> Marque as caixas conforme as funcionalidades forem concluídas.

## Decisões de modelagem

Esta seção explica **por que** cada conceito de POO foi usado e qual problema ele resolve.

| Conceito | Onde está no código | Por que foi usado |
|----------|--------------------|-------------------|
| Classes e objetos | `Veiculo`, `Cliente`, `Reserva`, `Aluguel` | _(preencher)_ |
| Encapsulamento | _(ex.: status e quilometragem do veículo)_ | _(preencher)_ |
| Coleção de objetos | _(ex.: `Locadora` guarda `List<Veiculo>`)_ | _(preencher)_ |
| Associação | _(ex.: `Aluguel` liga `Cliente` e `Veiculo`)_ | _(preencher)_ |
| Herança | `Carro`, `Moto`, `Caminhao` estendem `Veiculo` | _(preencher)_ |
| Polimorfismo | _(ex.: `calcularValor()` por tipo de veículo)_ | _(preencher)_ |
| Classe/método abstrato | `Veiculo` | _(preencher)_ |
| Interface | _(ex.: `Multavel`)_ | _(preencher)_ |

## Recursos extras

- [ ] Tratamento de exceções
- [ ] _(recurso 2)_
- [ ] _(recurso 3, se a equipe tiver 4 ou 5 integrantes)_

## Estrutura do projeto

```
locadora-veiculos/
├── src/
│   ├── modelo/        # entidades (Veiculo, Carro, Moto, Caminhao, Cliente...)
│   ├── servico/       # regras de negócio (Locadora, cálculo de valores...)
│   ├── excecao/       # exceções personalizadas
│   └── Main.java
├── README.md
└── .gitignore
```

> Ajuste conforme a estrutura real do projeto.

## Requisitos

- Java _(versão, ex.: 17 ou superior)_
- _(IDE ou ferramenta de build, se houver)_

## Como instalar e executar

```bash
# 1. Clonar o repositório
git clone https://github.com/<usuario>/locadora-veiculos.git
cd locadora-veiculos

# 2. Compilar
javac -d out $(find src -name "*.java")

# 3. Executar
java -cp out Main
```

> Ajuste os comandos conforme o projeto (Maven, Gradle, IDE etc.).

## Exemplo de uso

_(Adicionar prints ou um trecho do console mostrando um aluguel e uma devolução.)_

## Licença

Projeto acadêmico, sem fins comerciais.
