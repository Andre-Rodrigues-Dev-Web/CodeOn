# Projeto Angular Car

# Pré requisitos de ambiente de desenvolvimento

* [X] Editor de código Vscode
* [X] Navegador atualizado (uso de Chrome)
* [X] NodeJS
* [X] Terminal

# Pré requisitos de conhecimento

* [X] HTML
* [X] CSS
* [X] JavaScript
* [X] TypeScript
* [X] Sass, Scss

## Um pouco sobre o SCSS e metodologias CSS

O SCSS (Sassy CSS) é uma linguagem de pré-processamento CSS que adiciona recursos e funcionalidades ao CSS padrão. Ele permite que você escreva estilos mais complexos e reutilizáveis para suas páginas da web, economizando tempo e aumentando a eficiência.

A estrutura básica do SCSS é semelhante ao CSS padrão, mas possui algumas diferenças importantes. Uma das principais diferenças é que o SCSS usa sintaxe de bloco, o que significa que os blocos de código são delimitados por chaves {} e terminados com ponto e vírgula ;.

Outra diferença significativa é que o SCSS permite o uso de variáveis, o que significa que você pode definir um valor uma vez e reutilizá-lo em todo o seu código. Isso torna o processo de estilização mais fácil e eficiente.

O SCSS também suporta aninhamento, que permite aninhar seletores dentro de outros seletores. Isso facilita a escrita e a leitura do código, além de torná-lo mais organizado e fácil de manter.

Além disso, o SCSS permite a criação de mixins, que são blocos de código que podem ser reutilizados em todo o seu código. Isso significa que você pode escrever um bloco de código uma vez e usá-lo em várias partes do seu projeto.

Por fim, o SCSS é compilado em CSS padrão, o que significa que, embora seja escrito em uma linguagem diferente, o resultado final é um arquivo CSS que pode ser interpretado pelos navegadores da web.

### Introdução a BEM

BEM é uma metodologia de nomenclatura de classes CSS que foi desenvolvida para ajudar a tornar o processo de desenvolvimento web mais organizado, escalável e fácil de manter. BEM significa "Block, Element, Modifier" (Bloco, Elemento, Modificador) e divide os componentes de uma página da web em blocos, elementos e modificadores.

Um bloco é um componente independente e reutilizável que pode ser usado em diferentes partes da página da web. Um bloco pode ser um botão, um formulário, uma caixa de diálogo, entre outros.

Um elemento é uma parte de um bloco que desempenha uma função específica. Por exemplo, em um botão, um elemento pode ser o ícone, o texto ou o contorno.

Um modificador é uma variação de um bloco ou elemento que muda seu estilo, estado ou comportamento. Por exemplo, um modificador pode ser usado para mudar a cor de um botão quando ele é clicado ou para adicionar uma animação a um formulário quando um usuário envia seus dados.

A metodologia BEM segue uma convenção de nomenclatura específica que usa classes CSS para identificar blocos, elementos e modificadores. A convenção de nomenclatura é simples: um bloco é identificado por um nome único, um elemento é identificado pelo nome do bloco seguido de dois traços e o nome do elemento e um modificador é identificado pelo nome do bloco ou elemento seguido de dois traços e o nome do modificador.

## Startando nossa aplicação

### Instalação Angular modo CLI

```
npm i -g @angular/cli
```

### Iniciando um projeto com angular

```
ng new meu-projeto
```

### Criação de componente

No terminal dentro da pasta do componente digite o seguinte comando:

```shell
ng generate component meu-componente
```

Observação: após feito o comando, basta apenas adicionar o componente no lugar desejado dentro do arquivo html, o import no arquivo TypeScript já é automático.
