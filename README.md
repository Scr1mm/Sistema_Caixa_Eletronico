🏧 Simulador de Caixa Eletrónico (ATM)
Este projeto é um simulador interativo de um terminal de caixa eletrónico operado via consola, desenvolvido integralmente em Java. Criado como um exercício prático para consolidar a lógica de programação, o sistema oferece um ambiente seguro e contínuo para a realização de operações bancárias básicas, garantindo a validação de todas as entradas do utilizador.

🚀 Funcionalidades
O sistema opera num ciclo contínuo até que o utilizador decida encerrar a sessão, oferecendo as seguintes operações:

Consultar Saldo: Exibe o saldo atualizado com formatação de moeda.

Realizar Depósito: Permite adicionar fundos à conta, bloqueando valores negativos ou nulos.

Realizar Saque: Permite levantar fundos, garantindo que o valor não excede o saldo disponível e não é negativo.

Prevenção de Falhas: O sistema está protegido contra entradas inválidas (por exemplo, digitar letras quando é esperado um número no menu), evitando o encerramento abrupto da aplicação.

🛠️ Tecnologias e Conceitos Aplicados
O código foi desenhado para ser limpo, eficiente e não dependente de bibliotecas externas complexas.

Linguagem: Java (JDK 8 ou superior)

Leitura de Dados: Classe Scanner (java.util.Scanner)

Estruturas de Controlo: Condicionais (if, else if, switch/case)

Estruturas de Repetição: Ciclo do-while para manter a interface ativa

Tratamento de Exceções Lógicas: Utilização de hasNextInt() para purgar quebras no buffer de entrada.

💻 Como Executar na Sua Máquina
Para testar o simulador localmente, certifique-se de que tem o Java JDK instalado na sua máquina.

Clone este repositório ou descarregue o ficheiro CaixaEletronico.java.

Abra o terminal ou a linha de comandos e navegue até à diretoria onde o ficheiro se encontra (tendo em conta a estrutura de pacotes com/example).

Compile o código com o seguinte comando:

Bash
javac com/example/CaixaEletronico.java
Inicie a aplicação executando:

Bash
java com.example.CaixaEletronico
