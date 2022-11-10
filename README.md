# mongodb-commerce

Um projeto com objetivo de consolidar os conhecimentos sobre mongodb, nele possui 32 desafio para serem resolvidos com queries do mongodb.

## Imagem Exemplo

![commerce-queries](https://user-images.githubusercontent.com/99821267/201095734-cf916c00-bddf-4d50-a765-df58825d1e7b.png)


# Instruções da aplicação

```
cd mongodb-commerce
npm install
cd challenges
```
## Observação
```
Cada requisito, representa 1 desafio
```
<details>
<summary>Exemplo</summary>
<br>

![commerce-requisitos](https://user-images.githubusercontent.com/99821267/201094738-acdc7e41-f60f-4c4f-8766-b366edfb4cf3.png)

</details>


# Requisitos 

| Requisitos | Descrição |
|---|---|
| `1` | Retorne a quantidade de documentos inseridos na coleção produtos |
| `2` | Ordene a coleção produtos pela quantidade de lanches vendidos em ordem crescente, mostrando apenas o nome e a quantidade de lanches vendidos |
| `3` | Retorne o lanche mais vendido, mostrando apenas o nome e a quantidade do lanche mais vendido |
| `4` | Retorne os lanches que tiveram vendas maiores que 50 e menores que 100, mostrando apenas o nome e a quantidade de lanches vendidos em ordem crescente |
| `5` | Retorne o nome, as curtidas e vendidos dos lanches que tiveram quantidade de curtidas igual a 36 ou tenham a quantidade de vendas igual a 85
 |
| `6` | Query que retorna os produtos com mais de 10 e menos de 100 curtidas |
| `7` | Query que retorna os produtos com número de vendas diferente de 50 e que não tenha o campo `tags` |
| `8` | Query para deletar os lanches com menos de 50 curtidas |
| `9` | Query para retornar todos os lanches com menos de 500 calorias |
| `10` | Query para filtrar os lanches com mais de 30% e menos de 40% de proteínas |
| `11` | Query para filtrar os lanches que não tenham os nomes: Big Mac e McChicken  |
| `12` | Query para adicionar ketchup aos ingredientes para todos os sanduíches, exceto o McChicken |
| `13` | Query para incluir o campo criadoPor em todos os documentos, com valor Ronald McDonald |
| `14` | Query que retorne os lanches que possuem picles como ingredientes e mostre apenas os 3 primeiros itens no campo valoresNutricionais |
| `15` | Query para adicionar o campo avaliacao em todos os documentos |
| `16` | Query para adicionar o campo ultimaModificacao com a data atual apenas para o Big Mac |
| `17` | Query para criação de uma nova coleção chamada resumoProdutos com a quantidade total de produtos |
| `18` | Query para incluir bacon no final da lista de ingredientes dos sanduíches Big Mac e Quarteirão com Queijo |
| `19` | Query para remover o ingrediente Cebola de todos os sanduíches |
| `20` | Query para remover o primeiro ingrediente do sanduíche Quarteirão com Queijo |
| `21` | Query para remover o último ingrediente do sanduíche Cheddar McMelt |
| `22` | Query para criar o campo vendasPorDia em todos os sanduíches  |
| `23` | Query para adicionar os valores `combo` e `tasty` no array tags de todos os sanduíches em ordem alfabética |
| `24` | Query que ordena os valoresNutricionais presente nos documentos pelo campo percentual de forma decrescente |
| `25` | Query que adiciona a tag `muito sódio` nos produtos em que o percentual de sódio seja maior ou igual a 40 |
| `26` | Query que adiciona a tag `contém sódio` nos produtos em que o percentual de sódio seja maior do que 20 e menor do que 40 |
| `27` | Query que conta o número de documentos que contém as letras 'mc'no nome |
| `28` | Query que conta quantos documentos com o campo ingredientes com quatro itens |
| `29` | Query que renomeia o campo descricao para `descricaoSite` em todos os documentos |
| `30` | Query que remove o campo curtidas do item Big Mac |
| `31` | Query que retorna todos os documentos em que o número de curtidas é maior que o número de sanduíches vendidos |
| `32` | Query que retorna todos os documentos em que o número de vendas é múltiplo de 5 |

