<h1 align="center">Expressões Lógicas</h1>

<h3> And </h2>

<P>É representado por 2 (dois) "E" comerciais: <b>&&</b>.<p>

<h4>Exemplos</h3>

```java
int x = 5
if (x <= 20 && x == 10) {}
/*
* X <= 20: true
* X == 10: false
* O if não irá rodar
*/
```

<h4>Tabela da verdade "AND"</h3>

<p>A tabela existe para mostrar todas as possibilidades do bloco de código rodar:</p>

| A     | B     | A && B |
| ----- | ----- | ------ |
| false | false | false  |
| false | true  | false  |
| true  | false | false  |
| true  | true  | true   |

<h4>Conclusão</h3>

<p>O bloco de código rodará apenas se <b>TODAS</b> as condições forem verdadeiras. </p>

---

<h3>Or</h3>

<p>Representado por 2 "pipes": <b>||</b></p>

<h4>Exemplos</h4>

```java
int x = 5
if (x <= 20 || x == 10) {}
/*
* X <= 20: true
* X == 10: false
* O if irá rodar
*/
```

<h4>Tabela da verdade "OR"</h4>

| A     | B     | A \|\| B |
| ----- | ----- | -------- |
| false | false | false    |
| false | true  | true     |
| true  | false | true     |
| true  | true  | true     |

<h4>Conclusão</h3>

<p>O bloco de código rodará apenas se houver pelo menos <b>UMA</b> das condições forem verdadeiras. </p>

---

<h3>Not</h3>

<p>Representado por 1 (uma) "exclamação": <b>!</b></p>

<h4>Exemplos</h4>

```java
int x = 5
if (!(x <= 20)) {}
/*
* X <= 20: false
* O if não irá rodar
*/
```

<h4>Tabela da verdade "NOT"</h4>

| A     | !A    |
| ----- | ----- |
| false | true  |
| true  | false |

<h4>Conclusão</h3>

<p>O operador NOT é útil para inverter o valor lógico de uma expressão, o que pode ser útil em várias situações. Por exemplo, podemos usar o operador NOT para verificar se uma expressão é falsa, ou para negar o valor de uma variável. </p>
