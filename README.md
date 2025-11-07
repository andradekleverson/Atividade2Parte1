# Atividade2Parte1

1. Explique o que é JSON e por que ele se tornou tão popular para troca de dados
entre aplicações.

O JSON (JavaScript Object Notation) é um formato de texto leve destinado a representar dados estruturados com uma notação, leitura e escrita simples de compreender, tanto por humanos quanto por máquinas.

Surgindo originalmente a partir da sintaxe da linguagem JavaScript, o JSON passou a ser utilizado como meio de intercâmbio de dados entre várias linguagens de programação. Isso se deve, em primeira instância, à sua estrutura simples, que pode ser lida e escrita por praticamente qualquer linguagem de programação, o que facilita demasiadamente a comunicação entre diferentes sistemas.


2. Qual a diferença fundamental entre JSON.stringify() e JSON.parse()? Dê um exemplo prático de quando usar cada um.

O método JSON.stringify(), em JavaScript, é utilizado para converter valores, como objetos, arrays ou números para o formato JSON, isto é, transformá-los em uma string formatada que segue a sintaxe JSON.

```JS
const perfil = {
  nome: "Kleverson",
  idade: 21,
  estudando: true
};
```

```JS
const stringJSON = JSON.stringify(perfil);
```

Já o método JSON.parse() faz a operação inversa: ele converte uma string JSON de volta para um objeto JavaScript, tornando-a acessível e modificável ​​no código JavaScript.

3. Considerando a string "JavaScript é baseada em ECMA Script", quais métodos
você usaria para:

● Verificar se contém a palavra "Script";
● Remover a palavra "JavaScript" e gerar uma nova string;
● Substituir "baseada" por "tem origem"


4. Qual a vantagem de usar template strings (``) em vez de concatenação com + para criar strings complexas?

