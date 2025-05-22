🎯 Hangma-Project

📌 Visão Geral

Hangma-Project é um jogo da forca simples e intuitivo, desenvolvido com HTML, CSS e JavaScript. O objetivo é adivinhar uma palavra secreta, letra por letra, antes que a forca se complete. O jogo conta com feedback visual, popup de resultado e um design responsivo.

⚙️ Funcionalidades
🔤 Seleção aleatória de palavras de uma lista predefinida.

🖼️ Atualização dinâmica da imagem da forca a cada erro.

✅ Exibição separada de letras corretas e incorretas.

⚠️ Aviso visual ao tentar inserir letras repetidas.

📱 Layout centralizado e responsivo.

🔁 Botão para reiniciar o jogo após vencer ou perder.

🛠️ Tecnologias Utilizadas
HTML: Estrutura da interface do jogo.

CSS: Estilização da UI, com foco em responsividade e popups.

JavaScript: Lógica do jogo, manipulação de eventos e regras de vitória/derrota.

🧩 Como Executar Localmente
# 1. Clone o repositório
git clone https://github.com/seu-usuario/Hangma-Project.git

# 2. Acesse o diretório
cd Hangma-Project

🔍 Agora, abra o arquivo forca.html em qualquer navegador (como Chrome ou Firefox).

📦 Nenhuma dependência externa ou servidor é necessário!

🎮 Como Jogar
Abra o jogo no navegador.

Uma palavra secreta será exibida como sublinhados (_).

Pressione letras no teclado para tentar adivinhar.

Regras:
✔️ Letras corretas aparecem nas posições certas.

❌ Letras erradas são listadas e a imagem da forca é atualizada.

⚠️ Letras repetidas geram um aviso.

🏆 Vitória: Adivinhe todas as letras.

💀 Derrota: 6 erros completam a forca.

🪧 Ao terminar, um popup exibirá o resultado com a opção de "Jogar Novamente".

📁 Estrutura de Arquivos
Hangma-Project/

├── forca.html        # Estrutura principal

├── style.css         # Estilização visual

├── script.js         # Lógica e interatividade

└── img/              # Imagens da forca (forca1.png a forca6.png)

🐞 Problemas Conhecidos
🔄 A função desenharForca() pode não atualizar corretamente a imagem, caso o número de erros e o array de imagens não estejam sincronizados.

🔎 A verificação palavraSecreta === container.innerText pode falhar devido à presença de HTML. Recomendado usar uma abordagem com comparação direta de letras adivinhadas.

🚀 Melhorias Futuras
🔊 Efeitos sonoros para acertos, erros e fim de jogo.

🎯 Níveis de dificuldade e sistema de pontuação.

♿ Acessibilidade com navegação por teclado e ARIA.

💡 Funcionalidade de dica para ajudar o jogador.

🤝 Contribuindo
Contribuições são bem-vindas!
Basta fazer um fork, criar uma branch, aplicar as mudanças e enviar um pull request.
Por favor, siga o estilo do projeto e comente seu código.
