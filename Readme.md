# Desafios de Lógica

## Aumento %

- Receba um número de casas decimais (double) A representando um valor inicial e um número de casas decimais (double) B representando um valor atualizado. Crie um método que exiba o percentual de aumento em cima dos valores passados.

  - Exemplo:
    Doritos valor inicial (A) = 5.50
    Doritos valor atualizado (B) = 8.25
  - Resultado esperado
    Aumento de 50%

## Quantas vogais?

- Receba uma String e crie um método que retorne quantas vogais existem na palavra/frase.

  - Exemplo:
    String frase = "O rato roeu a roupa do rei de Roma"
  - Resultado esperado:
    16 vogais

## Quais são os números pares?

- Receba um número inteiro > 0 e retorne dos os números pares contidos nesse número inclusive o passado (caso se encaixe).

  - Exemplo:
    int i = 10
  - Resultado esperado:
    2, 4, 6, 8, 10

## Cálcule a área do círculo

- Crie um método que receba um número inteiro (raio) > 0 e retorne a área do círculo. A fórmula para calcular a área de um círculo é A = π . raio².

  - Exemplo:
      int raio = 3
  - Resultado esperado:
      28.26

## Some o Array
- Crie um método que receba um array de inteiros e retorne a soma de todos os números.

  - Exemplo:
    List<Integer> nums = [5, 5, 8, 10, 12];
  - Resultado esperado:
    40

## Remova os duplicados
- Crie um método que receba um array de inteiros e retorne uma nova lista removendo os números duplicados.

  - Exemplo:
    List<Integer> nums = [1, 2, 3, 2, 4, 8, 9, 9, 8, 4, 10, 15, 12, 8]
  - Resultado esperado:
    nums = [1, 2, 3, 4, 8, 9, 10, 15, 12]

## Ordene a lista
- Crie um método que receba um array de inteiros e imprima em ordem crescente e decrescente

  - Exemplo:
    List<Integer> nums = [4, 3, 8, 6, 1]
  - Resultado esperado:
    nums = [1, 3, 4, 6, 8]
    nums = [8, 6, 4, 3, 1]

## Categorize o objeto
- Crie um objeto que possua atributos nome e categoria
  - Exemplo:
    ```java
    class Filme {
      String nome;
      String categoria;
    }
    ```
- Crie um método que receba uma lista de filmes (ao menos 10 itens na lista) e retorne a quantidade por categoria;
  - Resultado esperado:
    ```java
    quantidadeCategoria[
      "terror": 3,
      "drama": 5,
      "comédia": 8
    ]
    ```
