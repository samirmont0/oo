### Uma pessoa possui pode possuir zero ou mais hábitos.

Talvez nenhum hábito. Todo hábito está associado a uma pessoa, ou seja, conforme modelado abaixo, hábitos não são compartilhados, cada um possui os seus.

![image](https://user-images.githubusercontent.com/1735792/90349078-b93a6f80-e00e-11ea-8909-408d903ddc58.png)

### Uma pessoa possui um nome, idade e hábitos. Um hábito possui uma descrição.

![image](https://user-images.githubusercontent.com/1735792/90349092-cc4d3f80-e00e-11ea-943a-69e5176110d5.png)

### Um círculo é descrito por uma posição (x,y), correspondente ao centro e um valor para o raio, além da possibilidade de ser transladado de um deslocamento em x e outro em y.

![image](https://user-images.githubusercontent.com/1735792/90349103-dcfdb580-e00e-11ea-993c-cbfa6700ce63.png)

### Um círculo é descrito por um ponto, correspondente ao centro, e um valor para o raio. O círculo é transladado de um deslocamento em x e outro em y. (Alternativa para o modelo acima.)

![image](https://user-images.githubusercontent.com/1735792/90349114-ebe46800-e00e-11ea-9700-5017864410d3.png)

### Um usuário de um sistema computacional é uma pessoa.

Embora o modelo abaixo permita que uma instância de Usuário seja tratada como uma instância de Pessoa, o que decorre da herança, convém ressaltar que um modelo alternativo, talvez melhor seja uma simples associação entre Usuário e Pessoa. Nesta associação, a instância de Usuário ressaltaria uma atividade, um papel que a instância de Pessoa correspondente desempenharia.

![image](https://user-images.githubusercontent.com/1735792/90349129-00c0fb80-e00f-11ea-9676-97fc037e48cf.png)

### Um elefante é um mamífero.

![image](https://user-images.githubusercontent.com/1735792/90349145-0fa7ae00-e00f-11ea-8786-e676a63ebf2b.png)

### Um contêiner contém contêineres e objetos.

![image](https://user-images.githubusercontent.com/1735792/90349160-20f0ba80-e00f-11ea-8498-cbc080ed9c11.png)

### Caixeiro-viajante.

Um caixeiro-viajante faz uso de uma lista de cidades pelas quais terá que percorrer em uma viagem, na ordem fornecida e, para cada uma das cidades, colhe pedidos de armazéns lá localizados. A lista de cidades corresponde a uma viagem do caixeiro-viajante. Espera-se uma lista de cidades para cada viagem. Ou seja, um caixeiro-viajante está associado a várias viagens, cada uma delas é descrita por uma lista de cidades, conforme ilustrado abaixo. Observe que as cidades estão ordenadas (ordered).

![image](https://user-images.githubusercontent.com/1735792/90349173-3960d500-e00f-11ea-8bb0-389a7b15d67e.png)

### Caixeiro-viajante e lista de pedidos.

Falta ao modelo acima informação pertinente aos pedidos colhidos em cada armazém. Naturalmente será preciso associar a lista de pedido ao armazém do qual esta foi gerada. Esta informação, contudo, não é suficiente, pois também será preciso identificar a viagem na qual esta foi definida. Uma alternativa é estabelecer uma associação de cada lista de pedido para o armazém do qual esta originou-se e outra com a viagem em questão, conforme modelado abaixo.

![image](https://user-images.githubusercontent.com/1735792/90349207-61e8cf00-e00f-11ea-9926-ac82a7dc578f.png)

### Cliente e fornecedor envolvem-se em transações econômicas.

![image](https://user-images.githubusercontent.com/1735792/90349230-72994500-e00f-11ea-8584-5291a19f7a36.png)
