## Desafio Java DIO - Controle de Fluxo

Recentemente, completei um desafio de codificação em Java, que fazia parte do módulo de Controle de Fluxo da Trilha Java Básico na DIO. A tarefa envolvia criar um programa que recebesse dois números inteiros como parâmetros via terminal e imprimisse uma sequência de números com base na diferença entre esses dois valores. Se o primeiro número fosse maior que o segundo, eu precisava lançar uma exceção customizada.

Para isso, criei um projeto chamado DesafioControleFluxo com duas classes principais: Contador e ParametrosInvalidosException. Na classe Contador, utilizei um Scanner para capturar os valores de entrada e implementei a lógica de contagem. Se os valores fossem inválidos (ou seja, o primeiro maior que o segundo), minha exceção personalizada ParametrosInvalidosException seria lançada com a mensagem "O segundo parâmetro deve ser maior que o primeiro". Caso contrário, um loop for imprimia a sequência de números incrementados no console.

Foi uma experiência prática excelente que consolidou meu entendimento sobre controle de fluxo e manipulação de exceções em Java.
