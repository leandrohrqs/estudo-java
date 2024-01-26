<h1 align="center">Funções de Strings<h1>

## Formatar

- `toLowerCase()` - Transforma tudo em minúsculo
- `toUpperCase()` - Tudo em maiúsculo

## Recortar:

- `substring(start)`
- `substring(start, end)`

## Substituir:

- `Replace(char, char)`
- `Replace(string, string)`

## Buscar:

- `IndexOf()`
- `LastIndexOf()`

## Split

- `str.Split()`

## Utilização

String fruits = "mango, banana, apple¨;

String[] vector = fruits.split(",");

String word1 = vector[0]; // mango
String word2 = vector[1]; // banana
String word3 = vector[2]; // apple
