# Lista de Exercícios 3 - Desenvolvimento Web Básico

Este repositório contém os exercícios da Lista de Exercícios 3 do curso de Desenvolvimento Web Básico, parte do programa Full Stack + Prati.

## Estrutura do Projeto

O projeto está organizado nas seguintes pastas, correspondendo aos exercícios:

* **Exercicio1**: Contém os arquivos `index.html` e `styles.css`.
* **Exercicio2**: Contém o arquivo `listas.html`.
* **Exercicio3**: Contém o arquivo `feedback.html`.

## Conteúdo dos Exercícios

### `index.html` - Página Principal com Estilos e Menu Hamburguer

O arquivo `index.html` implementa a estrutura principal do site, utilizando tags semânticas como `<header>`, `<main>`, `<section>` e `<footer>`.

Características principais:
* **Estrutura Semântica (Exercício 1)**: Inclui um cabeçalho (`<header>`) com um título (`<h1>`) e um parágrafo (`<p>`) introdutório, um conteúdo principal (`<main>`) dividido em seções "Missão" e "Visão" (cada uma com `<h2>` e `<p>`), e um rodapé (`<footer>`) com um parágrafo de copyright.
* **Galeria de Imagens (Exercício 6)**: Contém uma galeria com oito imagens e legendas, organizada com Grid e envolta por um contêiner Flexbox para centralização e quebra de linha.
* **Menu Hamburguer Responsivo (Exercício 7)**: Implementa um menu "hamburger" que aparece apenas em telas com largura de até 600px, ocultando a navegação padrão e abrindo/fechando ao ser clicado.

### `listas.html` - Listas e Navegação

O arquivo `listas.html` demonstra o uso de diferentes tipos de listas e um bloco de navegação.

Características principais:
* **Lista Não Ordenada (Exercício 2)**: Contém uma lista não ordenada (`<ul>`) com cinco hobbies.
* **Lista Ordenada (Exercício 2)**: Inclui uma lista ordenada (`<ol>`) descrevendo os passos para preparar uma receita simples de pão caseiro.
* **Links Externos (Exercício 2)**: Possui um bloco de navegação (`<nav>`) com três links externos (`<a>`) para sites úteis.

### `feedback.html` - Formulário de Feedback

O arquivo `feedback.html` apresenta um formulário de feedback completo.

Características principais:
* **Campos de Informação Pessoal (Exercício 3)**: Inclui campos para "Nome", "E-mail" e "Endereço Completo".
* **Tipo de Feedback (Exercício 3)**: Oferece um campo de seleção (`<select>`) para o "Tipo de feedback" (Sugestão, Elogio, Reclamação, Dúvida, Outro).
* **Campo de Mensagem (Exercício 3)**: Dispõe de um campo de texto (`<textarea>`) para o feedback propriamente dito.
* **Botão de Envio (Exercício 3)**: Contém um botão de envio (`<button type="submit">`) para submeter o formulário.

### `styles.css` - Estilos CSS

O arquivo `styles.css` está vinculado a `index.html` e aplica estilos visuais abrangendo diversas funcionalidades.

Características principais:
* **CSS Básico e Box Model (Exercício 4)**: Define cores de fundo (`background-color`) e de texto (`color`), além de `margin`, `padding` e `border` para as tags `<header>`, `<main>` e `<footer>`, evidenciando seus contornos.
* **Seletores e Propriedades (Exercício 5)**:
    * Aplica estilo a todas as tags `<h2>` aumentando o `font-size` e adicionando `text-decoration: underline`.
    * Define uma classe `.destaque` que torna o texto em itálico (`font-style: italic`) e aplica um `background-color` suave.
    * Cria um ID `#importante` que adiciona uma `border-top` mais espessa em um parágrafo específico.
* **Grid e Flexbox na Galeria (Exercício 6)**: Utiliza Flexbox no `.galeria-container` para centralizar o conjunto de imagens e `flex-wrap` para quebra de linha. O `.galeria-grid` usa Grid para organizar as imagens em colunas. Ajusta o número de colunas da galeria (`.galeria-grid`) para telas menores por meio de media queries.
* **Menu Hamburguer (Exercício 7)**: Controla a visibilidade e o comportamento do menu hamburger em telas com largura de até 600px, ocultando a navegação padrão e revelando o menu responsivo ao clique.
