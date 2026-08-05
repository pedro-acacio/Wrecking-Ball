# Wrecking Ball

Cena de física interativa feita com p5.js e a engine de física Matter.js. Um personagem "herói" fica pendurado por uma corda (constraint rígida) presa a um ponto fixo, balançando por gravidade em direção a um "monstro" e a uma pilha de caixas, todos simulados como corpos rígidos (círculos e retângulos) no mundo do Matter.js. O código presente no repositório monta a cena e a simulação física, mas não implementa entrada do jogador (mouse/teclado), pontuação ou condição de vitória/derrota — é essencialmente um protótipo/demo de física do tipo "bola de demolição".

## Tecnologias

- p5.js (renderização e loop de desenho)
- Matter.js (motor de física 2D: corpos, constraints/corda, colisões)
- Imagens PNG/JPG para os sprites (herói, monstro, fundos)

## Como rodar

Abrir `index.html` por meio de um servidor local (por exemplo `npx serve .` ou a extensão Live Server do VS Code). Abrir o arquivo diretamente com duplo clique (`file://`) pode falhar no carregamento das imagens pelo `preload()` do p5.js por causa de restrições de CORS do navegador.
