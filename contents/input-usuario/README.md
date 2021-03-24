# Input do Usuário

Em um programa, muitas vezes temos que pegar o input do usuário, ou seja, dados que o usuário digitar para que passemos como uma variável do nosso programa. Em Ruby, fazemos isso com o método **gets**, que lê os dados diretamente do stdin ou Standard Input:

```ruby
print "Qual é o seu nome?"
nome = gets

puts "Olá #{nome}, tudo bem?"
```

O código acima exibe uma mensagem que diz "Qual é o seu nome" e espera por uma entrada do usuário, o que o usuário digitar será salvo na variável `nome` e será impresso na tela uma mesagem com o nome que foi inserido.

O método gets por padrão captura alguns caracteres de escape como o "\n" (conhecido como quebra de linha ou nova linha), o que dependendo do caso pode ser algo negativo em nosso programa.

Para removermos estes caracteres da entrada do usuário, utilizamos o método **gets** com o **chomp**, desta forma:

```ruby
nome = gets.chomp
```

## Próximo =>

[Estruturas de Repetição](../repeticoes/README.md)
