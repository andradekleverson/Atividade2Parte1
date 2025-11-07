# Atividade2Parte1

## 1. Explique o que é JSON e por que ele se tornou tão popular para troca de dados entre aplicações.

<br>

O JSON (JavaScript Object Notation) é um formato de texto usado para "organizar" dados estruturados com uma notação, leitura e escrita super fáceis de entender, tanto por humanos quanto por máquinas.

O JSON surgiu originalmente a partir da sintaxe da linguagem JavaScript. Hoje em dia seu formato é aproveitado por diversas linguagens para o intercâmbio (troca) de dados entre si. Isso aconteceu porque sua estrutura é tão simples que pode ser lida e escrita por praticamente qualquer linguagem de programação, o que tornou a comunicação entre as linhas de códigos de linguagens diferentes muito mais fácil.

<br>

## 2. Qual a diferença fundamental entre JSON.stringify() e JSON.parse()? Dê um exemplo prático de quando usar cada um.

<br>

O método JSON.stringify(), em JavaScript, é utilizado para converter valores, como objetos, arrays ou números para o formato JSON, isto é, transformá-los em uma string formatada que segue a sintaxe JSON. Por exemplo:

```JS
const identificador = {
  nome: "Kleverson",
  idade: 21,
  estudante: true
};
```
> Nesse exemplo, nós criamos um objeto JavaScript chamado identificador, com o objetivo de simular um algoritmo de login que possa guardar e enviar os dados do usuário para um servidor.
```JS
const string_JSON = JSON.stringify(identificador);
```
> Em seguida, ao usarmos a JSON.stringify, estamos, na prática, convertendo o conteúdo do nosso objeto JavaScript para uma string JSON, e armazenando o novo formato dentro da nossa variável chamada string_JSON (que agora está pronta para ser enviada ao servidor).

<br

<br>

Já o método JSON.parse() faz a operação inversa: ele converte uma string JSON de volta para um objeto JavaScript, tornando-a acessível e modificável ​​no código JavaScript:

```JS
const string_JSON = '{"nome": "Kleverson", "idade": 21, "estudante": true}';
```
> Nesse caso, vamos supor que recebemos essa string JSON de outro sistema e queremos anexá-la ao nosso código JavaScript no formato objeto:

```JS
const identificador = JSON.parse(string_JSON);
```
> Agora, o identificador voltou a ser um objeto JavaScript normal e todos os seus dados (identificador.nome, identificador.idade, etc) podem ser usados no nosso programa:
```JS
console.log(identificador.nome)
```

<br>

## 3. Considerando a string "JavaScript é baseada em ECMA Script", quais métodos você usaria para:

### ● Verificar se contém a palavra "Script";
### ● Remover a palavra "JavaScript" e gerar uma nova string;
### ● Substituir "baseada" por "tem origem"

<br>

<br>

## 4. Qual a vantagem de usar template strings (``) em vez de concatenaão com + para criar strings complexas?

<br>

<br>
