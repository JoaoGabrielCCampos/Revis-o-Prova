Aqui estão todas as perguntas com as respostas correspondentes:

---

**3 - O que é a tag `<div>` e a tag `<span>` no HTML?**

A tag `<div>` age como um bloco de conteúdo, utilizando a linha toda. Já o `<span>` age como parte da linha, não quebrando as linhas. O `<div>` é melhor para estruturar layouts e o `<span>` para estilizar partes específicas.

---

**4 - O que é a tag `<head>` no HTML?**

O `<head>` no código HTML é formado pelos conceitos iniciais de uma página. Nele, pode conter o Favicon, o Nome da página que fica contido na aba e o link para o código CSS externo.

---

**5 - Qual a diferença entre lista ordenada e lista não ordenada no HTML?**

A lista ordenada (`<ol>`) é ordenada, ou seja, a ordem importa, como um passo a passo. Já a lista não ordenada (`<ul>`) é não ordenada, ou seja, a ordem não importa, como uma listagem de itens.

* **Ordenada**

  1. Primeiro passo
  2. Segundo passo
  3. Terceiro passo

* **Não ordenada**

  * Item 1
  * Item 2
  * Item 3

---

**6 - O que é a propriedade `display` no CSS?**

O `display` controla como o elemento se comportará, sendo por bloco, linha ou outros, definindo se ficará alinhado lado a lado, se respeitará margens, etc. O `block` ocupará toda a linha e começará em uma nova linha. O `inline` usará só o necessário e o `inline-block` é a mistura dos dois.

---

**9 - O que é o atributo `target="_blank"` no HTML?**

Esse atributo é usado na tag `<a>`, utilizada para adicionar um link ao código, para abrir a página de destino em uma nova aba no navegador. É necessário um cuidado, pois a nova aba ganha acesso à página que abriu o link por meio do objeto `window.opener`, que pode ser explorado por sites maliciosos, como, por exemplo, redirecionar para páginas falsas.

---

**O que é a propriedade `flex` no CSS?**

A propriedade `flex` serve para dizer como cada elemento vai se comportar dentro de um container, permitindo distribuir de forma proporcional o espaço dentro do container. Por exemplo, se um item tiver `flex: 2` e outro `flex: 1`, o primeiro ocupará o dobro de espaço do segundo. Dessa forma, a propriedade `flex` facilita a construção de layouts responsivos e organizados.

---

**O que é a propriedade `transition` no CSS?**

Esse elemento é usado para criar efeitos de animações simples, ou seja, uma mudança suave de estado para outro em vez de acontecer de uma forma instantânea, como mudar a cor de um botão quando ele está sendo selecionado.

---

**Qual a diferença entre `const`, `var` e `let` no JavaScript?**

Podemos usar `const`, `var` e `let` no código JavaScript. O `var` é o mais antigo, tem escopo de função (vale dentro de toda a função) e permite redeclarar a variável no mesmo lugar, o que pode gerar problemas no código. O `let` é o mais moderno, tem escopo de bloco (só vale dentro das chaves em que foi criado e não pode ser redeclarado, mas o valor pode ser alterado). Já o `const` também tem escopo de bloco, mas não permite alterar o valor depois de definido. Porém, em um objeto, podemos mudar o conteúdo interno, mas não trocar a variável interna.

---

**18 - Qual a diferença entre Java e JavaScript?**

Java é uma linguagem compilada e orientada a objetos, usada principalmente para criar grandes aplicações, como sistemas corporativos ou sistemas de jogos. Já o JavaScript é uma linguagem interpretada, mais leve e criada para deixar as páginas da web mais interativas.

---

**19 - Qual a diferença entre `==` e `===` no JavaScript?**

No JavaScript, `==` compara apenas os valores, fazendo conversão de tipo se necessário, enquanto `===` compara valor e tipo. Por exemplo, `5 == '5'` é verdadeiro, mas `5 === '5'` é falso, porque os tipos são diferentes. O `===` é mais seguro para evitar erros.

---

**21 - O que são operadores lógicos (`&&`, `||`, `!`) no JavaScript?**

Os operadores lógicos são usados para combinar e inverter condições em estruturas de decisão, como `if`. O operador `&&` retorna verdadeiro se todas as condições forem verdadeiras, o `||` retorna verdadeiro se pelo menos uma das condições for verdadeira. Já o operador `!` inverte o valor lógico de uma condição, como de sim para não.

---

**21 - É possível adicionar novas propriedades a um objeto depois de criado? Como?**

Sim. Para isso, podemos usar a notação de ponto ou a notação de colchetes, atribuindo um valor à nova propriedade desejada. Por exemplo, se temos um objeto `pessoa` com `nome` e `idade`, podemos adicionar uma propriedade `altura` usando `pessoa.altura = 1.75` ou `pessoa["altura"] = 1.75`.

---

**22 - Qual a diferença entre `null` e `undefined` no JavaScript?**

No JavaScript, `undefined` significa que uma variável foi declarada, mas ainda não recebeu valor, enquanto `null` é um valor que o programador atribui intencionalmente para indicar que a variável está vazia.

---

**23 - O que é um objeto em JavaScript e como ele é declarado?**

Em JavaScript, um objeto é uma estrutura que permite armazenar valores e funções organizados em propriedades, que são pares de chave e valor. Ele é usado para representar entidades do mundo real ou agrupar informações relacionadas em um único elemento. Um objeto é declarado usando chaves `{}` e suas propriedades são definidas dentro delas. Por exemplo, podemos criar um objeto `pessoa` com as propriedades `nome`, `idade` e uma função `saudacao`, que permite acessar os dados ou executar ações relacionadas a esse objeto.

---

Se precisar de mais alguma coisa ou ajustes, me avise!
