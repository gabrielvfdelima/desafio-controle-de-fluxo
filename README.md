# Contador
##Descrição
Este é um simples programa Java que solicita ao usuário dois números inteiros e conta de forma crescente do primeiro ao segundo número, imprimindo cada número no console.

### Funcionalidades
- Solicita dois números inteiros ao usuário
- Valida se o segundo número é maior que o primeiro
- Conta e imprime os números entre o primeiro e o segundo parâmetro (inclusive)
- Trata exceções para parâmetros inválidos

### Pré-requisitos
- Java Development Kit (JDK) instalado

### Como executar
- Compile o arquivo Java:
- javac Contador.java
Execute o programa:
- java Contador
- Siga as instruções no console para inserir os dois parâmetros.
  
### Estrutura do código
- Contador.java: Contém a classe principal e a lógica do programa
-ParametrosInvalidosException: exceção personalizada

### Funcionamento
- O programa solicita ao usuário que digite dois números inteiros.
- Se o segundo número for menor ou igual ao primeiro, uma exceção ParametrosInvalidosException é lançada.
- Se os parâmetros forem válidos, o programa conta do primeiro ao segundo número, imprimindo cada número.

### Tratamento de Erros
- Se o segundo parâmetro for menor ou igual ao primeiro, uma mensagem de erro é exibida: "O segundo parâmetro deve ser maior que o primeiro".
Contribuição

#Sinta-se à vontade para contribuir com este projeto. Abra uma issue ou envie um pull request com suas sugestões de melhorias.
