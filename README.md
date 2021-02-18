# O que temos aqui neste repo?

As métricas derivadas pela equipe da Zup Edu relativas a entendimento. A linha de design que seguimos para tentar gerar identidade no código é o Cognitive Driven Development. 

Para saber mais sobre o que é Cognitive Driven Development, 

## Métrica de entendimento e limite para códigos escritos em kotlin. 

[Aqui](https://ideaboardz.com/for/derivar-metrica-entendimento-kotlin/3690152) você encontra o board onde discutimos o que poderia dificultar entendimento e o resultado final com os itens que decidimos contar como pontos de complexidade intrínseca. 

Para facilitar, também vamos deixar aqui:

* branches de código padròes (if,else,loops,when,case do when,try,catch)
* acoplamento com classes específicas do projeto
* condicional
* extension method
* funcao declarada fora do escopo de uma classe

Cada item deste, quando encontrado num arquivo de código, vai contar 1 ponto de dificuldade de entendimento. Como temos 5 itens, **vamos começar com 10 pontos de limite.**. 

## Métrica de entendimento e limite para códigos escritos em Java. 

[Aqui](https://ideaboardz.com/for/deriva-metrica-entendimento-java/3690166) você encontra o board onde discutimos o que poderia dificultar entendimento e o resultado final com os itens que decidimos contar como pontos de complexidade intrínseca. 

Para facilitar, também vamos deixar aqui:

* branches de código padròes (if,else,loops,when,case do when,try,catch)
* funções como argumento
* condicional
* acoplamento com classes específicas do projeto
* herança de classe abstrata ou concreta(extends)

Cada item deste, quando encontrado num arquivo de código, vai contar 1 ponto de dificuldade de entendimento. Como temos 5 itens, **vamos começar com 10 pontos de limite.**. 

## O que fazemos agora que definimos o que dificulta entendimento e temos limite?

Por aqui consideramos que uma unidade de código é um arquivo. Dada essa consideração, nenhuma arquivo pode ter mais de 10 pontos de dificuldade de entendimento. 

### E se passar?

Organizamos o código de modo que respeite. E se passar só um ponto? Não muda nada, organizamos o código de modo que respeite :). 

Ter uma definição de entendimento e limite bem definidos, deve te ajudar em todas atividades relacionadas ao código, por exemplo:

* Criação de novas funcionalidades
* Alteração de funcionalidades
* Refatoração

