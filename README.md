# Simulador de Caixa Eletrônico

Projeto desenvolvido em Java para consolidar conceitos fundamentais de lógica de programação, controle de fluxo e estruturas de repetição.

## 📌 Sobre o Projeto

Este projeto consiste em uma aplicação de terminal desenvolvida em Java para automatizar a simulação de um caixa eletrónico (ATM). O sistema permite realizar consultas de saldo, depósitos e saques de forma dinâmica, realiza a validação robusta de entradas de dados e opera de forma contínua até que o usuário decida encerrar a sessão.

Além de atender às exigências básicas da atividade acadêmica, o código foi estruturado de forma limpa, eficiente e segura contra falhas de digitação no console.

## 🚀 Funcionalidades

### 🔹 Recursos Principais
* **Menu Interativo:** Permite navegar entre consulta de saldo, depósitos, saques e encerramento de sessão de forma contínua.
* **Validação de Dados:** 
  * Impede saques que deixem o saldo negativo ou superiores ao valor disponível.
  * Rejeita depósitos e saques com valores menores ou iguais a zero.
  * Previne erros no console caso o usuário digite texto onde se espera um valor numérico.
* **Operações Bancárias:**
  * **Consultar Saldo:** Exibe o saldo atual formatado em moeda.
  * **Realizar Depósito:** Adiciona valores válidos ao montante da conta.
  * **Realizar Saque:** Desconta valores respeitando o limite do saldo atual.

### 💻 Exemplo de Execução no Terminal

```text
--- Caixa Eletrónico ---
1 - Consultar Saldo
2 - Realizar Depósito
3 - Realizar Saque
4 - Sair
Escolha uma opção que Deseja: 1

Saldo atual: R$ 0,00

--- Caixa Eletrónico ---
1 - Consultar Saldo
2 - Realizar Depósito
3 - Realizar Saque
4 - Sair
Escolha uma opção que Deseja: 2
Digite o valor do depósito: 150,50
Depósito realizado com sucesso.

--- Caixa Eletrónico ---
1 - Consultar Saldo
2 - Realizar Depósito
3 - Realizar Saque
4 - Sair
Escolha uma opção que Deseja: 3
Digite o valor do saque: 50,00
Saque realizado com sucesso.

--- Caixa Eletrónico ---
1 - Consultar Saldo
2 - Realizar Depósito
3 - Realizar Saque
4 - Sair
Escolha uma opção que Deseja: 4
Encerrando a sessão. Obrigado!

```

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Java (JDK 8 ou superior)
* **Manipulação de Entradas:** `java.util.Scanner`
* **Paradigma:** Programação Estruturada / Imperativa

## 💻 Como Executar o Projeto

### Pré-requisitos

Ter o **Java JDK** instalado na sua máquina.

### Passos para execução

1. Clone este repositório ou descarregue o ficheiro `CaixaEletronico.java`.
2. Abra o terminal e navegue até à pasta raiz do projeto.
3. Compile o código:
```bash
javac com/example/CaixaEletronico.java

```


4. Execute a aplicação:
```bash
java com.example.CaixaEletronico

```



```

```
