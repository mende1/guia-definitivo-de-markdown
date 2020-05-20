# O Guia Definitivo de MarkDown para Iniciantes

<img src="https://user-images.githubusercontent.com/55323701/82506032-25bbd600-9ad5-11ea-8b5e-e7c699d385af.png" alt="drawing" width="150"/>

##### Por Gustavo Mendel

Com a popularização do **GitHub**, e também da grande quantidade de novos programadores ultimamente, 
a demanda para aprender *Markdown* aumentou bastante. *Markdown* é uma linguagem de marcação, parecido 
com a sua companheira HTML. 

A maior utilidade dela atualmente certamente é para criar os famosos **READMEs** para seus repositórios
no **GitHub**, e deixar o seu projeto mais 'apresentável'. E é por isso que hoje trago aqui um guia 
simples porém definitivo para aprender a tão famosa *Markdown* e a importancia de um bom **README** em seu projeto para iniciantes.


## README E SUA IMPORTÂNCIA

Todo projeto seu no GitHub terá seus códigos, seus arquivos, suas pastas todas jogadas lá. Um projeto 
digno e bem estruturado precisa passar para o leitor **o sentido do seu projeto, para que ele serve, 
como funciona, quais linguagens, sistemas, funcionalidades, ferramentas você utilizou para criar seu 
programa, como contribuir**, e dezenas de outras informações necessárias tem que ficar bem explicitas 
ao leitor quando o mesmo se deparar com seu repositório. 

E para isso existe um arquivinho bem simples chamado **'README.md' ou 'readme.md'** em todo repositório 
no mínimo organizado no GitHub. Perceba que o arquivo possui o sufixo **'.md'**, essa é a terminologia 
de arquivos **Markdown**. Ao criar o **README.md** em seu repositório, ao rolar um pouco para baixo a página
inicial, todo o conteúdo formatado em Markdown irá aparecer, contendo todas as informações necessárias para o projeto.
Para ver o conteúdo sem formatação, procure um ícone de um lápis, ou até clique no arquivo em si **_README.md_**, 
assim você será encaminhado para a edição do arquivo.

## A sintaxe

### Títulos

Inicialmente temos os 'Headings', ou Títulos, que é semelhante à linguagem de marcação HTML. Existe
uma herança de títulos, em que diferem não só o tamanho da fonte, como também semânticamente. Ou seja,
o título número 1 é mais importante que o título número 2, que por sua vez é mais importante que o 
número 3, e assim por diante.

Existem 6 títulos, que vai do título 1 (mais importante e por conseguinte maior e mais destacado) 
até o título 6 (menos importante e por conseguinte menor e menos destacado).

A sintaxe é simples:
```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```

Vai de acordo com a quantidade de '#'.
Exemplos:

# Aqui um título 1
## Aqui um título 2
### Aqui um título 3
#### Aqui um título 4
##### Aqui um título 5
###### Aqui um título 6
___

### Ênfase

Você pode adicionar ênfase ao seu texto, como por exemplo o **negrito**, o *itálico*, ou até mesmo **_negrito e itálico_**.
Lembre-se que além da aparência do seu texto, existe a semântica para ser seguida. Textos em negrito devem ser lidos com força,
intensidade, e o itálico significa uma ênfase maior.

#### Negrito

Sintaxe do **negrito:**

```
Este é **negrito**
This is __strong__
```

#### Itálico

Sintaxe do *itálico:*

```
Este é *itálico*
This is _italic_
```

#### Negrito e itálico

Sintaxe do **_negrito e itálico:_**

```
**_strong and em_**
```
___
### Linha horizontal

Você pode adicionar linhas horizontais para deixar o texto mais organizado e apresentável.
Usando três hífens, três asteriscos ou três underscore:

```
Hífens

---

Asteriscos

***

Underscore

___
```

Learning Center:

Hífens

---

Asteriscos

***

Underscore

___
```
___
### Citações

Para criar uma citação em bloco, adicione um '>' na frente de um parágrafo.

As citações em bloco podem conter vários parágrafos. Adicione um '>' nas linhas em branco entre
os parágrafos

Sintaxe:

```
Para citações em uma linha:
> Esta é uma citação

Em várias linhas:
> Citação 1
>
> Citação 2
```

Resultado:

Para citações em uma linha:
> Esta é uma citação

Em várias linhas:
> Citação 1
> 
> Citação 2

As cotações em bloco podem ser aninhadas. Adicione um '>>' na frente do parágrafo que você deseja aninhar.
Por exemplo:
```
> Citação 1
>
>> Citação 2
```
E assim temos:
> Citação 1
>
>> Citação 2

As citações de bloco podem conter outros elementos no formato Markdown. Nem todos os elementos podem
ser usados, você precisará experimentar para ver quais funcionam.
Exemplo:

```
> ##### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going **well**.
```

Resultado:
> ##### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going **well**.
___

### Listas

Você pode organizar listas, podendo ser ordenadas ou não.

**_Listas Ordenadas_**

Usando (número)(ponto) você pode ordenar as listas numericamente, como por exemplo:

```
1. Primeiro
2. Segundo
3. Terceiro
4. Quarto
```

Vai gerar o seguinte resultado:

1. Primeiro
2. Segundo
3. Terceiro
4. Quarto

Itens da lista de aninhamento

Para aninhar itens de linha em uma lista ordenada, recue os itens quatro espaços ou uma guia.

```
1. Primeiro item
2. Segundo item
3. Terceiro item
    1. Indentado item
    2. Indentado item
4. Quarto item
```
Irá gerar:

1. Primeiro item
2. Segundo item
3. Terceiro item
    1. Indentado item
    2. Indentado item
4. Quarto item

**_Listas não Ordenadas_**

Para criar uma lista não ordenada, adicione traços (-), asteriscos (*) ou sinais de adição (+) na frente de
itens de linha.

```
- Exemplo 1

* Exemplo 2

+ Exemplo 3
```

Vai gerar:

- Exemplo 1

* Exemplo 2

+ Exemplo 3

**_Lista de tarefas_**

Podemos criar também uma lista de tarefas, com a CheckBox preenchida ou não. Vejamos o exemplo:

~~~
- [ ] Esta é uma CheckBox não marcada
- [x] Esta é uma CheckBox marcada
~~~

Learning Center:

- [ ] Esta é uma CheckBox não marcada
- [x] Esta é uma CheckBox marcada

___

### Trechos de códigos

Para colocar algum código sem que ele esteja formatado, então poderá colocar algum código em *Markdown* dentro
dos trechos de códigos e ele não será formatado, será mostrado exatamento como escreveu, é desse jeito que eu
consigo mostrar para vocês os códigos como são originalmente antes de serem formatados em *.md*.

Temos o trecho simples, sendo de apenas uma linha, usando uma crase para abrir e outra para fechar:
```
` este é um exemplo `
```
Resultado:

`este é um exemplo`

E também temos a mais completa, que podemos colocar quantas linhas de códigos nós quisermos.
Use três crases ( ´´´ ) ou três tils ( ~~~ ) para abrir e três para fechar, desse jeito:

```
    ```
    Este é nosso
    Querido Exemplo
    
    **Teste**
    
    Nota que não irá formatar o negrito!
    ```
```

Vai gerar:
```
Este é nosso
Querido Exemplo
**Teste**
Nota que não irá formatar o negrito!
```

Para especificar qual lingugem seu código é feito, isso ajuda tanto semânticamente como também na coloração do código, basta adicionar o nome da lingugem logo após os três primeiros tils ou crases.
Por exemplo: 
```
    ~~~python
    s = "Sintaxe do Pythong"
    print s
    ~~~
```
~~~python
s = "Sintaxe do Python"
print s
~~~

Para saber quais lingugens são suportadas por este mecanismo, clique [aqui](https://pygments.org/languages/) e veja a listagem do Pygments.

**_Nota:_** Para interligar um código dentro do outro, assim como eu fiz de exemplo para vocês: Abra o primeiro trecho de código com as três crases, e feche de imediato. Dentro desse código use a indentação de 4 espaços, e assim poderá abrir outro código sem formatar.

___

### Links

É possível colocar algum link em seu *'Readme'*, e ainda colocá-lo por debaixo de uma palavra, é o chamado link-âncora, acessando-o ao clicar na palavra.
Entre colchetes [ ] a palava que deseja por debaixo dos panos. E entre parentêses ( ) o link para acesso. Vejamos o exemplo do código:

```
Clique [aqui](https://github.com) para acessar à página do GitHub.
```
Resultado:
Clique [aqui](https://github.com) para acessar à página do GitHub.

Lembre-se que pode criar links para outros repositórios seus no GitHub, também é possível acessar outro arquivo no mesmo repositório, e até mesmo a posição da página do leitor no mesmo arquivo. Por exemplo, clique [aqui](https://github.com/gustavo-mendel/guia-definitivo-de-markdown#a-sintaxe) para acessar o título 'Sintaxe' neste mesmo arquivo. Tais possibilidades deixam seu *README* bem mais apresentável, e com uma interatividade maior, demonstrando que o escritor do código entende bem de *MarkDown*.

Para links sem uma palavra por cima do link, use '< >' para envolver o link desejado, assim o link aparecerá por inteiro ao leitor. Exemplo: 
<https://google.com.br>

___

### Adicionando imagens

Semelhante ao mecanismo de adicionar links-âncora, podemos adicionar imagens para nosso aquivos.md também, mas tome cuidado com a resolução da imagem, imagens grandes podem estar em linhas individuais, para serem exibidas em maior tamanho.

A sintaxe é parecida, apenas adicione uma exclamação (!) no início.
~~~
![Alt ou título da imagem](URL da imagem)
~~~

___

### Tabela

Escolha os títulos das colunas e use `|` para delimitar as colunas. Depois, utilize hífen `-` na segunda linha para indicar que acima estão os títulos das colunas, usando novamente o `|` para delimitar colunas. Veja um exemplo abaixo:

~~~
Teste   | Exemplo
------- | ------
Teste 1 | Exemplo 1
Teste 2 | Exemplo 2
Teste 3 | Exemplo 3
Teste 4 | Exemplo 4
~~~

No Learning Center irá aparecer:

Teste   | Exemplo
------- | ------
Teste 1 | Exemplo 1
Teste 2 | Exemplo 2
Teste 3 | Exemplo 3
Teste 4 | Exemplo 4

Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize dois pontos `:` ao lado do campo horizontal de hífens `---`, na segunda linha da sua tabela. Veja abaixo:

* Alinhado a esquerda: usar `:` no lado esquerdo (alinhamento padrão)
* Alinhado a direita: usar `:` no lado direito
* Centralizado: usar `:` dos dois lados

Exemplo:
~~~
Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Exemplo | Exemplo | Exemplo
~~~

Learning Center:

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Exemplo | Exemplo | Exemplo

## Créditos

Copyright (C) 2020 by Gustavo Mendel
