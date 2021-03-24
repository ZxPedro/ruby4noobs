# Hello, world!

O *Hello, world!* é o programa mais básico que pode ser escrito em qualquer linguagem, o objetivo de escrever um *Hello, world!* é testar se o ambiente de desenvolvimento está corretamente configurado. Em Ruby, temos dois métodos bastante semelhantes para escrever na tela, são eles **puts** e **print**.

Hello, world! com **puts**:

```ruby
puts("Hello, world!")
```

Hello, world! com **print**:

```ruby
print("Hello, world!")
```

Em Ruby, praticamente todos os métodos podem ser escritos sem parênteses, então você também poderia escrever os exemplos acima desta maneira:

```ruby
puts "Com ou sem parênteses"
```

Ou então:

```ruby
print "Os mesmos resultados"
```

O método **print** e **puts** são bastante semelhantes, porém existem algumas diferenças a se observar. O método **puts** irá tratar o objeto em questão e irá inserir uma quebra de linha no final. Já o **print** por outro lado irá apenas imprimir o objeto sem nenhuma quebra de linha ou tratamento.

Por agora você não precisa se importar com como o **puts** tratará o objeto, apenas leve em conta que ele adiciona uma quebra de linha no final.

O código abaixo irá nos retornar a mensagem **"Hello, world!"** na mesma linha:

```ruby
print "Hello, "
print "world!"
```

Já este código irá retornar a palavra **"Hello, "** em uma linha e **"world!"** em outra:

```ruby
puts "Hello, "
puts "world!"
```

## Próximo =>
[Variáveis e tipos primitivos](../variaveis/README.md)
