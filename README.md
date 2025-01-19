# Sorteador de Amigo Secreto Simples

Este projeto é um sorteador de amigo secreto minimalista, desenvolvido utilizando HTML, CSS e JavaScript puros. Ele permite que você realize um sorteio rápido e fácil para a sua troca de presentes.

## Como Funciona

O projeto consiste em uma página web com um único botão, que ao ser clicado, realiza o sorteio.

### Código-fonte

O botão de sorteio é implementado da seguinte forma em HTML:

```html
<div class="button-container">
    <button class="button-draw" onclick="sortearAmigo()" aria-label="Sortear amigo secreto">
        <img src="assets/play_circle_outline.png" alt="Ícone para sortear">
        Sortear amigo
    </button>
</div>
content_copy
download
Use code with caution.
Markdown

O botão possui:

class="button-draw": Para estilização via CSS.

onclick="sortearAmigo()": Uma função Javascript, que deve ser implementada, que dispara o processo de sorteio.

aria-label="Sortear amigo secreto": Atributo que melhora a acessibilidade, fornecendo uma descrição do botão para leitores de tela.

img src="assets/play_circle_outline.png": Uma imagem de um ícone para dar melhor clareza.

Sortear amigo: Label do botão visível para os usuários.

O JavaScript associado a este botão, responsável pela lógica do sorteio, deve ser implementado no arquivo script.js ou similar, e não foi incluído neste trecho.

Como Usar

Clone o repositório:

git clone https://github.com/assismayko/jogo-do-numero-secreto
content_copy
download
Use code with caution.
Bash

Abra o arquivo index.html em seu navegador.

Clique no botão "Sortear amigo" para realizar o sorteio.

Contribuições são bem-vindas! Se você tiver alguma sugestão de melhoria, correção de bugs ou novas funcionalidades, sinta-se à vontade para abrir uma issue ou um pull request.
