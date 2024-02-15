# Solar System Animation

Este é um código HTML e CSS que cria uma animação simples do sistema solar, com o Sol, a Terra e a Lua orbitando em torno do Sol. Abaixo está uma descrição do código:

## Estrutura do Projeto

- **index.html:** O arquivo principal que contém a estrutura HTML do projeto.
- **style.css:** O arquivo de estilo que define a aparência e a animação dos elementos.

## Elementos Principais

### Sol (`<div class="sun"></div>`)

- Posicionado no centro (`top: 15em; left: 15em;`) da área de exibição.
- Tem uma cor amarela (`background-color: yellow;`) para representar o Sol.
- Possui um efeito de sombra simulando o brilho (`box-shadow: 0 0 3em white;`).

### Terra (`<div class="earth">...</div>`)

- Orbita ao redor do Sol com uma animação de órbita (`@keyframes orbit`).
- Possui uma cor azul (`background-color: aqua;`) para representar a Terra.
- Inclui uma lua (`<div class="moon"></div>`) que também orbita ao redor da Terra.

### Lua (`<div class="moon"></div>`)

- Orbita ao redor da Terra com uma animação de órbita separada.
- Tem uma cor prateada (`background-color: silver;`).

## Estilo Adicional

- O contêiner principal (`<div class="container">`) tem um tamanho fixo (`width: 40em; height: 40em;`) e é posicionado centralmente na tela.
- A animação de órbita é definida pela regra `@keyframes orbit`.

## Comentários

- Existem comentários (comentados) no código original que foram deixados deliberadamente desativados. Se desejar, você pode remover os comentários no arquivo CSS para ver o código comentado.

## Ícone do Favicon

- Um ícone do favicon foi incluído, mas o link parece estar incorreto. Certifique-se de corrigir o URL para o ícone do favicon.

Este é um projeto simples, mas você pode expandi-lo e personalizá-lo conforme necessário para criar animações mais complexas e realistas do sistema solar. Divirta-se explorando e aprendendo mais sobre animações em HTML e CSS!
