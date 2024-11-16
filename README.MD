# Resolução Atividade de implementação de testes Unitários com JUnit

### Aluno:
Jadenilson Rubem Silva de Lima - 01636174

## Perguntas:

### Por que é importante escrever testes unitários para cada método?
Escrever testes unitários para cada método é fundamental para garantir que cada parte do código funcione corretamente de forma isolada. Além disso, esses testes ajudam a identificar possíveis erros, como exceções não tratadas ou falhas na lógica, antes de o código ser integrado com outras partes do sistema. Com testes unitários, podemos validar que o método realiza as operações esperadas e trata as exceções de maneira adequada, prevenindo comportamentos indesejados em ambientes de produção.

### O que significa um teste ser "unitário" e como isso difere de outros tipos de testes?

 Testes unitários focam em testar pequenas unidades de código (geralmente métodos ou funções), sem depender do restante da aplicação. Diferentemente de testes integrados ou de sistema, que testam componentes ou sistemas mais amplos, os testes unitários visam isolar o comportamento do método ou função em questão, sem influências externas.

### Que tipo de exceções vocês observaram ao tentar dividir por zero e como o teste ajudou a identificar problemas?

A exceção ArithmeticException é o comportamento esperado em casos de tentativa de divisão por zero em Java. Ao escrever testes unitários, podemos verificar se o código lida corretamente com essa exceção e evitar que a aplicação falhe inesperadamente durante a execução.