🏁 Pole Position — Corrida Virtual

Mini-game de corrida em HTML5 Canvas, com tema de Fórmula 1.

Este jogo foi desenvolvido como um recurso complementar do site Corrida Lendária, com o objetivo de tornar o aprendizado sobre Fórmula 1 mais interativo e divertido para o público leigo.

📖 Sobre

No Pole Position, o jogador assume o volante de um carro de F1 e precisa sobreviver 60 segundos em uma pista de 5 faixas, desviando de obstáculos e coletando combustível ao longo do caminho. Quanto mais tempo o jogador sobrevive, maior a distância percorrida — e maior a pontuação final.

🎮 Como jogar
Ação	Controle
Mover para a esquerda	Seta ← ou tecla A
Mover para a direita	Seta → ou tecla D
Em dispositivos móveis	Toque no lado esquerdo/direito da tela, ou use os botões ◀ ▶

Como perder:

💥 Colidir com um cone ou carro acidentado na pista
⛽ Ficar sem combustível

Como vencer:

🏁 Sobreviver aos 60 segundos com combustível restante

Ao final da partida, é exibida a distância total percorrida (em metros) e uma mensagem de acordo com o desempenho.

✨ Funcionalidades
Movimento suave entre 5 faixas de pista
Geração progressiva de obstáculos e itens de combustível, com dificuldade crescente conforme a distância aumenta
Sistema de partículas (fumaça do escapamento, explosão ao colidir, brilho ao coletar combustível)
Efeito de tremor de tela (screen shake) ao bater
Linhas de velocidade que aumentam de intensidade conforme o carro acelera
HUD com distância, tempo restante e velocidade
Suporte a controles de teclado, toque e botões na tela (mobile)
Totalmente responsivo, sem dependências externas
🛠️ Tecnologias
HTML5 — estrutura da página
CSS3 — estilização (tema escuro inspirado na identidade visual da F1)
JavaScript puro (Vanilla JS) — toda a lógica do jogo
Canvas 2D API — renderização gráfica (sem sprites, sem bibliotecas de jogos)

Não há dependências externas além da fonte do Google Fonts (Barlow / Barlow Condensed).

🚀 Como rodar

Por ser um único arquivo HTML autocontido, basta:

Baixar o arquivo .html
Abrir diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari)

Não é necessário servidor, instalação ou build — o jogo funciona 100% no lado do cliente.

📁 Estrutura do arquivo

O jogo está organizado em um único arquivo, dividido em três blocos:

index.html
├── <style>   → identidade visual, HUD, overlay de início/fim, controles mobile
└── <script>  → lógica do jogo:
    ├── Estado do jogo (posição, velocidade, combustível, tempo, itens na pista)
    ├── Game loop (requestAnimationFrame)
    ├── Funções de desenho (carro, obstáculos, barreiras, linhas de velocidade)
    ├── Sistema de partículas
    └── Controles (teclado, toque, botões mobile)

Documentação técnica mais detalhada disponível em JOGO.md.

🎓 Contexto

Este jogo foi criado como parte de uma atividade acadêmica sobre Fórmula 1, com o objetivo de unir aprendizado e entretenimento, tornando a experiência do site mais imersiva para um público que não necessariamente já é fã do esporte.

📄 Licença

Este projeto está sob a licença MIT.
