# Bem vindos ao Projeto MongoDB Commerce!

Nesse projeto trabalhei com o banco de dados `commerce`, que contém dados do cardápio do **McDonald's**, como ingredientes, valores nutricionais e dados fictícios de vendas para desenvolvimento dos requisitos.


## Requisitos


### 1 - Retorna a quantidade de documentos inseridos na coleção `produtos`

- Desenvolvido no arquivo `desafio1.js`

### 2 - Ordena a coleção `produtos` pela quantidade de lanches vendidos em ordem crescente, mostrando apenas o `nome` e a quantidade de lanches `vendidos`

- Desenvolvido no arquivo `desafio2.js`

### 3 - Retorna o lanche mais vendido, mostrando apenas o `nome` e a quantidade do lanche mais vendido

- Desenvolvido no arquivo `desafio3.js`

### 4 - Retorna os lanches que tiveram vendas maiores que `50` e menores que `100`, mostrando apenas o nome e a quantidade de lanches `vendidos` em ordem crescente

- Desenvolvido no arquivo `desafio4.js`

### 5 - Retorna o `nome`, as `curtidas` e `vendidos` dos lanches que tiveram quantidade de `curtidas` igual a `36` ou tenham a quantidade de vendas igual a `85`

- Desenvolvido no arquivo `desafio5.js`

### 6 - Retorna o `nome` e as `curtidas` dos lanches que tiveram curtidas maiores que `10` e menores que `100`

- Desenvolvido no arquivo `desafio6.js`

### 7 - Retorna o `nome` e `vendidos` dos lanches que tenham sido `vendidos` com uma quantidade diferente de `50` e em que o campo `tags` não exista

- Desenvolvido no arquivo `desafio7.js`

### 8 - Deleta os lanches com menos de `50` `curtidas` e retorna o `nome` dos lanches que restaram no banco

- Desenvolvido no arquivo `desafio8.js`

### 9 - Retorna o `nome` de todos os lanches que possuam `calorias` abaixo de `500`

- Desenvolvido no arquivo `desafio9.js`.

### 10 - Retorna o `nome` de todos os lanches que tenham o percentual de `proteínas` maior ou igual a `30` e menor ou igual a `40`

- Desenvolvido no arquivo `desafio10.js`

### 11 - Retorna o `nome` do produto, a quantidade de `curtidas` e quantos itens foram `vendidos` dos produtos que não sejam iguais a `Big Mac` e `McChicken`

- Desenvolvido no arquivo `desafio11.js`

### 12 - Adiciona `ketchup` aos `ingredientes` para todos os sanduíches menos o `McChicken`, garantindo que não haja duplicidade nos `ingredientes`

- Desenvolvido no arquivo `desafio12.js`:

1. Criação de uma query que adiciona `ketchup` aos `ingredientes` para todos os sanduíches menos o `McChicken`, garantindo que não haja duplicidade nos `ingredientes`.

2. Criação de uma query que retorna o `nome` e `ingredientes` de todos os documentos.

### 13 - Inclui o campo `criadoPor` em todos os documentos, colocando `Ronald McDonald` no valor desse campo

Desenvolvido no arquivo `desafio13.js`:

1. Criação de query que adiciona o campo `criadoPor` em todos os documentos, colocando `"Ronald McDonald"` no valor desse campo.

2. Criação de uma query que retorna o `nome` e `criadoPor` de todos os produtos.

### 14 - Cria uma query que retorna todos os lanches que possuem *picles* em seus ingredientes e mostra apenas os `3` primeiros itens contidos no array `valoresNutricionais`

- Desenvolvido no arquivo `desafio14.js`
- A query retorna apenas os campos `nome`, `ingredientes` e `valoresNutricionais`.


### 15 - Adiciona o campo `avaliacao` em todos os documentos da coleção e efetua alterações nesse campo

Desenvolvido no arquivo `desafio15.js`:

1. Criação de uma query que inclui o campo `avaliacao` do tipo `NumberInt`, com o valor `0` em todos os documentos da coleção.

2. Criação de uma query que incrementa o valor do campo `avaliacao` em `5` em todos os sanduíches de carne do tipo `bovino`.

3. Criação de uma query que incrementa o valor do campo `avaliacao` em `3` em todos os sanduíches de `ave`.

4. Criação de uma query que retorna o `nome` e `avaliacao` de todos os sanduíches.

### 16 - Adiciona o campo `ultimaModificacao` com a data corrente somente no sanduíche `Big Mac`

Desenvolvido no arquivo `desafio16.js`:

1. Criação de uma query que inclui somente ao sanduíche `Big Mac` o campo `ultimaModificacao` com a data corrente.

2. Criação de uma query que retorna o `nome` de todos os documentos em que o campo `ultimaModificacao` existe.

### 17 - Retorna a quantidade total de produtos em uma nova coleção chamada `resumoProdutos`

Desenvolvido no arquivo `desafio17.js`:

1. Criação de uma query que insira na coleção `resumoProdutos` um documento com os campos: `franquia` com o valor `McDonalds` e `totalProdutos` com o valor sendo a quantidade total de produtos registrados na coleção `produtos`.

2. Criação de uma query que retorna os campos `franquia` e o `totalProdutos` da coleção `resumoProdutos`, resultantes da primeira query.

### 18 - Inclui `bacon` no final da lista de `ingredientes` dos sanduíches `Big Mac` e `Quarteirão com Queijo`

Desenvolvido no arquivo `desafio18.js`:

1. Criação de uma query que faz a inclusão de `bacon` no final da lista de `ingredientes` dos sanduíches `Big Mac` e `Quarteirão com Queijo`.

2. Criação de uma query que retorna o `nome` e `ingredientes` de todos os documentos.

### 19 - Remova o item `cebola` de todos os sanduíches

Desenvolvido no arquivo `desafio19.js`:

1. Criação de uma query que faz a remoção do item `cebola` em todos os sanduíches.

2. Criação de uma query que retorna o `nome` e `ingredientes` de todos os documentos.

### 20 - Remova o primeiro `ingrediente` do sanduíche `Quarteirão com Queijo`

Desenvolvido no arquivo `desafio20.js`:

1. Criação de uma query que faz a remoção do **primeiro** `ingrediente` no sanduíche `Quarteirão com Queijo`.

2. Criação de uma query que retorna o `nome` e `ingredientes` de todos os documentos.

### 21 - Remova o último `ingrediente` do sanduíche `Cheddar McMelt`

- Desenvolvido no arquivo `desafio21.js`:

1. Criação de uma query que faz a remoção do **último** `ingrediente` no sanduíche `Cheddar McMelt`.

2. Criação de uma query que retorna o `nome` e `ingredientes` de todos os documentos.

### 22 - Adiciona a quantidade de vendas dos sanduíches por dia da semana

- Desenvolvido no arquivo `desafio22.js`:

1. Criação de uma query que inclui um campo `vendasPorDia` em todos os sanduíches. O valor deste campo é um _array_ com sete posições. Cada uma delas representará um dia da semana, e cada posição iniciará em `0`. O _array_ deve seguir a estrutura do exemplo abaixo:
  ```json
  "vendasPorDia": [0, 0, 0, 0, 0, 0, 0]
  ```

> O primeiro item desse _array_ representa as vendas no **domingo**, o segundo item representa as vendas na **segunda-feira**, e assim sucessivamente até chegar ao último item, que representa as vendas no **sábado**.

2. Criação de uma query que incrementa as vendas de `Big Mac` às **quartas-feiras** em `60`.

3. Criação de uma query que incrementa as vendas de todos os sanduíches de carne do tipo `bovino` aos **sábados** em `120`.

4. Criação de uma query que retorna o `nome` e `vendasPorDia` de todos os documentos.

### 23 - Insira os valores `combo` e `tasty` no _array_ `tags` de todos os sanduíches e aproveite para deixar os valores em ordem alfabética ascendente (A a Z)

Desenvolvido no arquivo `desafio23.js`:

1. Criação de uma query que faz tanto a inserção dos valores `combo` e `tasty` no _array_ `tags` de todos os sanduíches. Ordene os valores de `tags` em ordem alfabética ascendente.

2. Criação de uma query que retorna o `nome` e `tags` de todos os documentos.

### 24 - Ordene em todos os documentos os valores do _array_ `valoresNutricionais` pelo campo `percentual` de forma decrescente

- Desenvolvido no arquivo `desafio24.js`:

1. Criação de uma query que faz em todos os documentos a ordenação dos valores do _array_ `valoresNutricionais` pelo campo `percentual` de forma decrescente.

2. Criação de uma query que retorna o `nome` e `valoresNutricionais` de todos os documentos.

### 25 - Adiciona o valor `muito sódio` ao final do _array_ `tags` nos produtos em que o `percentual` de `sódio` seja maior ou igual a `40`

Desenvolvido no arquivo `desafio25.js`:

1. Criação de uma query que faz a adição do valor `muito sódio` ao final do _array_ `tags` nos produtos em que o `percentual` de `sódio` seja maior ou igual a `40`.

2. Criação de uma query que retorna o `nome` e `tags` de todos os documentos.

### 26 - Adiciona o valor `contém sódio` ao final do _array_ `tags` nos produtos em que o `percentual` de `sódio` seja maior do que `20` e menor do que `40`

Desenvolvido no arquivo `desafio26.js`:

1. Criação de uma query que faz a adição do valor `contém sódio` ao final do _array_ `tags` nos produtos em que o `percentual` de `sódio` seja maior do que `20` e menor do que `40`.

2. Criação de uma query que retorna o `nome` e `tags` de todos os documentos.

### 27 - Conte quantos produtos contém `Mc` no nome, sem considerar letras maiúsculas ou minúsculas

- Desenvolvido no arquivo `desafio27.js`

### 28 - Conte quantos produtos têm `4` ingredientes

- Desenvolvido no arquivo `desafio28.js`

### 29 - Renomeie o campo `descricao` para `descricaoSite` em todos os documentos

Desenvolvido no arquivo `desafio29.js`:

1. Criação de uma query que faz a renomeação do campo `descricao` para `descricaoSite` em todos os documentos.

2. Criação de uma query que retorna o `nome` e `descricaoSite` de todos os documentos.

### 30 - Remova o campo `curtidas` do item `Big Mac`

Desenvolvido no arquivo `desafio30.js`:

1. Criação de uma query que faz a remoção do campo `curtidas` do item `Big Mac`.

2. Criação de uma query que retorna o `nome` para todos os documentos e `curtidas` (exceto para `Big Mac`).

### 31 - Retorna o `nome` dos sanduíches em que o número de `curtidas` é maior que o número de sanduíches `vendidos`

- Desenvolvido no arquivo `desafio31.js`

### 32 - Retorna o `nome` e a quantidade de vendas (`vendidos`) dos sanduíches em que o número de vendas é múltiplo de `5`

- Desenvolvido no arquivo `desafio32.js`
