# Atividade Factory Method - Prof. Rafaela
## Alunos:
  Breno Jesus Andrade de Oliveira: RA - 4231921291 ||
  Marco Thulio Martins: RA - 4231921901 ||
  GitHub : [MarcoThulio1207](https://github.com/MarcoThulio1207)
### Escopo da atividade:
  PRÁTICA - FÁBRICA DE BOLOS

Você foi contratado por uma confeitaria para desenvolver um sistema que crie diferentes tipos de bolos com base na necessidade dos clientes. A confeitaria oferece bolos de chocolate, morango, cenoura e abacaxi. Cada bolo tem um sabor específico, mas segue um processo semelhante de criação. 
Para garantir que o processo seja flexível e extensível, você deve implementar uma solução utilizando o padrão Factory Method.

Requisitos:

<pre style="max-height: 300px; overflow-y: auto; border: 1px solid #ddd; padding: 10px;">
1. Crie uma interface Bolo com o método preparar() que cada tipo de bolo implementará.

2. Crie classes concretas que representem os diferentes tipos de bolos: BoloChocolate, BoloMorango, BoloCenoura e BoloAbacaxi
cada uma implementando o método preparar() da interface Bolo.

3. Crie uma classe FabricaBolo abstrata que tenha um método abstrato criarBolo() e um método concreto fazerBolo()
que siga o processo de criação de um bolo (utilizando o método preparar()).

4. Crie classes concretas que herdam de FabricaBolo, como FabricaBoloChocolate, FabricaBoloMorango, FabricaBoloCenoura e FabricaBoloAbacaxi
que implementam o método criarBolo().

5. Crie uma classe Principal para testar.
</pre>
