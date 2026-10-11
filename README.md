# 🎱 Duelo de Taco

Sinuca online em 3D para dois jogadores, feita em um único arquivo `index.html`. Sem instalação e sem servidor próprio: abra o arquivo, crie uma sala e mande o link para um amigo. Também dá para treinar sozinho contra um bot.

**Criado por Bruno Nunes da Silva.**

## Recursos

- **Multiplayer pela internet:** crie uma sala, compartilhe o código de 5 letras ou o link e jogue em tempo real (conexão direta entre os jogadores via PeerJS).
- **Modo treino:** botão na página inicial para jogar contra um bot, sem criar sala.
- **Gráficos 3D:** mesa, bolas e tacos renderizados com three.js, com iluminação, brilhos e sombras.
- **Mesa inspirada em mesas clássicas de bar:** feltro vermelho, almofadas vinho, moldura escura com medalhões e cantos prateados ornamentados.
- **Física realista:** deslizamento seguido de rolamento, atrito, colisões entre bolas, rebote nas tabelas e caçapas com animação de queda.
- **Efeito na bola branca:** escolha o ponto de contato (topo, retrocesso e efeito lateral) em um seletor circular.
- **Tacos e pontas:** vários temas de taco (madeira, carbono, metal, neon e outros) e cinco formatos de ponta. Cada combinação altera precisão, potência e efeito.
- **Regras de sinuca:** grupos de bolas lisas e listradas, faltas, bola 8 e revanche.
- **Chat, emojis e animações engraçadas:** galinha apressada, chuva de bananas, foguete, tomatada e mais.
- **Funciona no celular:** layout próprio para a horizontal e controles por toque.

## Como jogar

1. Na página inicial, digite seu nome e clique em **Criar sala** (ou use **Entrar em uma sala** com o código recebido).
2. Na sua vez, **arraste para trás** a partir da mesa e **solte** para dar a tacada. Quanto mais longe, mais forte.
3. Use o seletor circular no canto da mesa para dar efeito na bola branca.
4. Troque o taco no botão 🎨 e use 💬 para abrir o chat, os emojis e as animações.

## Como executar

Não há build nem dependências para instalar.

- **Localmente:** abra o `index.html` no navegador. O modo treino funciona assim.
- **Online:** publique o arquivo em qualquer hospedagem estática, como o GitHub Pages, para jogar com outra pessoa pelo link da sala.

## Tecnologias

- HTML, CSS e JavaScript puro, tudo em um único arquivo
- [three.js](https://threejs.org/) (r128) para o 3D
- [PeerJS](https://peerjs.com/) (1.5.4) para a conexão entre jogadores
- Web Audio API para os efeitos sonoros, sem arquivos de áudio

## Autor

Bruno Nunes da Silva
