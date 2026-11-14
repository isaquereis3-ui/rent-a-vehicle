# rent-a-vehicle
Sistema de locadora de veículos em Java, desenvolvido como projeto final de Programação Orientada a Objetos.

Locadora de Veículos

Sistema de locadora de veículos desenvolvido como projeto final da disciplina de Programação Orientada a Objetos, aplicando os conceitos de POO a um problema real de gestão de frota, clientes e aluguéis.

Equipe
Nome	GitHub
Isaque dos Reis Jess 	@isaque
Laura Zoffoli Silveira	@laura
Nicolas Lourenço	    @nicolaslourenc2
Rauhan Kniess de Moura  @rauhan

Disciplina: Programação Orientada a Objetos
Instituição: Pontifícia Universidade Católica do Paraná
Professora: Marina de Lara

Descrição do problema

Uma locadora precisa controlar sua frota, saber quais veículos estão disponíveis, cadastrar clientes, registrar reservas e aluguéis, calcular o valor a cobrar e tratar devoluções, incluindo multas por atraso ou danos. Cada tipo de veículo tem regras próprias (documentação exigida, forma de cobrança), o que torna o domínio adequado para modelagem orientada a objetos.

Funcionalidades
[ ] Cadastro de veículos (carro, moto e caminhão)
[ ] Cadastro de clientes
[ ] Controle de disponibilidade da frota
[ ] Reserva de veículos
[ ] Registro de aluguel
[ ] Cálculo do valor do aluguel conforme o tipo de veículo
[ ] Registro de devolução e cálculo de multas
[ ] Histórico de aluguéis

Marque as caixas conforme as funcionalidades forem concluídas.

Decisões de modelagem

Esta seção explica por que cada conceito de POO foi usado e qual problema ele resolve.

Conceito	Onde está no código	Por que foi usado
Classes e objetos	Veiculo, Cliente, Reserva, Aluguel	(preencher)
Encapsulamento	(ex.: status e quilometragem do veículo)	(preencher)
Coleção de objetos	(ex.: Locadora guarda List<Veiculo>)	(preencher)
Associação	(ex.: Aluguel liga Cliente e Veiculo)	(preencher)
Herança	Carro, Moto, Caminhao estendem Veiculo	(preencher)
Polimorfismo	(ex.: calcularValor() por tipo de veículo)	(preencher)
Classe/método abstrato	Veiculo	(preencher)
Interface	(ex.: Multavel)	(preencher)

Recursos extras
[ ] Tratamento de exceções
[ ] (recurso 2)
[ ] (recurso 3, se a equipe tiver 4 ou 5 integrantes)

Estrutura do projeto
locadora-veiculos/
├── src/
│   ├── modelo/        # entidades (Veiculo, Carro, Moto, Caminhao, Cliente...)
│   ├── servico/       # regras de negócio (Locadora, cálculo de valores...)
│   ├── excecao/       # exceções personalizadas
│   └── Main.java
├── README.md
└── .gitignore

Ajuste conforme a estrutura real do projeto.

Requisitos
Java (versão, ex.: 17 ou superior)
(IDE ou ferramenta de build, se houver)


Como instalar e executar
bash
# 1. Clonar o repositório
git clone https://github.com/<usuario>/locadora-veiculos.git
cd locadora-veiculos

# 2. Compilar
javac -d out $(find src -name "*.java")

# 3. Executar
java -cp out Main

Ajuste os comandos conforme o projeto (Maven, Gradle, IDE etc.).

Exemplo de uso
(Adicionar prints ou um trecho do console mostrando um aluguel e uma devolução.)

Licença
Projeto acadêmico, sem fins comerciais.