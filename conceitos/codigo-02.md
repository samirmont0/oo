## Implemente o que se pede abaixo.

1. Implemente as classes _Casa_ e _Sapato_ em conformidade com as restrições seguintes.

1. Conforme boa prática de programação, cada classe é fornecida em seu próprio arquivo. Ou seja, para estas duas classes teremos dois arquivos: **Casa.java** e **Sapato.java**.

1. Acrescente pelo menos 5 (cinco) propriedades, também denominadas de atributos ou membros de dados, para cada uma destas classes. Seja cuidadoso, um atributo típico de sapato é o número (tamanho), por exemplo. Há muitos outros, por outro lado, não faz sentido "nome do usuário", por exemplo. Para uma casa, um atributo típico é a área construída. Pergunte-se, para auxiliar a identificar atributos relevantes, o que você gostaria de saber sobre um dado sapato e que é atribuição ou responsabilidade dele saber ou realizar? O que você gostaria de saber sobre uma casa? Desenvolver software orientado a objetos é, de certa forma, favorecer a perspectiva do "mundo real".

1. Acrescente pelo menos 5 (cinco) métodos a cada uma das classes. Um método pertinente para _Sapato_ é _getNumero()_ ou _getTamanho()_, conforme a decisão acima. Para casa, um método pertinente é _getNumeroComodos()_. Observe que, em ambos os casos, os nomes dos métodos são sugestivos, o que é desejável.

1. Crie duas classes, _TestaCasa_ e _TestaSapato_, para testar as classe _Casa_ e _Sapato_, respectivamente. Esta é uma prática recomendada: separar o código que testa uma classe do código testado propriamente dito, ou seja, mantenha em locais distintos questões de naturezas distintas. Em inglês o termo comumente empregado, na literatura de Engenharia de Software, é _separation of concerns_. _TestaCasa_ deverá criar pelo menos duas instâncias de _Casa_, fornecer valores para os atributos das instâncias e enviar mensagens para cada uma das instâncias. Faça o mesmo para a classe _TestaSapato_ e _Sapato_. Em vez do comum uso do método estático _main_ (início de uma aplicação em Java) e do emprego de sentenças _System.out.println_, por exemplo, você deverá se familiarizar e fazer udo do JUnit. Veja detalhes do JUnit em https://junit.org/junit5/.
