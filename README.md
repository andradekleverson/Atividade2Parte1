# Atividade2Parte1

1. Explique o que é JSON e por que ele se tornou tão popular para troca de dados
entre aplicações.

O JSON (JavaScript Object Notation) é um formato de texto leve usado para "organizar" dados estruturados com uma notação, leitura e escrita super fáceis de entender, tanto por humanos quanto por máquinas.

O JSON surgiu originalmente a partir da sintaxe da linguagem JavaScript, obviamente, mas hoje em dia seu formato é aproveitado por diversas linguagens para o intercâmbio de dados entre si. Isso aconteceu porque sua estrutura é tão simples que pode ser lida e escrita por praticamente qualquer linguagem de programação, o que tornou a comunicação entre as linhas de códigos de linguagens diferentes muito mais fácil.


2. Qual a diferença fundamental entre JSON.stringify() e JSON.parse()? Dê um exemplo prático de quando usar cada um.

O método JSON.stringify(), em JavaScript, é utilizado para converter valores, como objetos, arrays ou números para o formato JSON, isto é, transformá-los em uma string formatada que segue a sintaxe JSON:

```JS
const perfil = {
  nome: "Kleverson",
  idade: 21,
  estudante: true
};
```

```JS
const stringJSON = JSON.stringify(perfil);
```

Já o método JSON.parse() faz a operação inversa: ele converte uma string JSON de volta para um objeto JavaScript, tornando-a acessível e modificável ​​no código JavaScript:

```JS
const stringJSON = '{"nome": "Kleverson", "idade": 21, "estudante": true}';
```

```JS
const perfil = JSON.parse(stringJSON);
```

3. Considerando a string "JavaScript é baseada em ECMA Script", quais métodos
você usaria para:

● Verificar se contém a palavra "Script";
● Remover a palavra "JavaScript" e gerar uma nova string;
● Substituir "baseada" por "tem origem"


4. Qual a vantagem de usar template strings (``) em vez de concatenaão com + para criar strings complexas?

