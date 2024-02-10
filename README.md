## Demonstrando como manipular o Document Object Model (DOM) de uma página HTML. 

### 🛠
- HTML
- CSS
- JS 

* Explicando DOM - HTML & JS 

 Seleção de Elementos: 

Utilizando diferentes métodos para selecionar elementos no DOM:

 - .querySelector() para selecionar o primeiro elemento que corresponda ao seletor especificado (no caso, um elemento "h1")

- .querySelectorAll() para selecionar todos os elementos que correspondam ao seletor especificado (no caso, elementos com a classe .box)

 .getElementById(), .getElementsByTagName(), e .getElementsByClassName() são métodos mais antigos para selecionar elementos pelo ID, por tag e por classe, mas você sugere usar .querySelector() e .querySelectorAll() em vez disso.

  Manipulação de Conteúdo:

 Altera o conteúdo de texto do elemento "h1" selecionado anteriormente, mudando o textContent para 'DOM'.

 Além disso, utiliza document.write() para escrever o conteúdo de texto dos elementos com a classe ".box".

Em resumo, o código JavaScript está manipulando o DOM para alterar o conteúdo de um elemento "h1" e escrever o conteúdo de texto de elementos com a classe .box na página HTML.


