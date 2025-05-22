Hangma-Project

Visão Geral

O Hangma-Project é um jogo da forca simples implementado usando HTML, CSS e JavaScript. O jogo desafia os jogadores a adivinhar uma palavra secreta inserindo letras pelo teclado. Os jogadores têm um número limitado de palpites errados antes de perder o jogo. O projeto apresenta um design responsivo, feedback visual para palpites corretos e incorretos e um popup para indicar os resultados do jogo.
Funcionalidades

Seleciona aleatoriamente uma palavra de uma lista predefinida.
Exibe a imagem da forca que é atualizada a cada palpite errado.
Mostra as letras corretas na palavra e as letras erradas separadamente.
Alerta o jogador quando uma letra repetida é inserida.
Design responsivo com layout centralizado e um popup para os resultados do jogo.
Opção para reiniciar o jogo após vencer ou perder.

Tecnologias Utilizadas

HTML: Estrutura da interface do jogo.
CSS: Estilização da interface, incluindo cor de fundo, contêineres centralizados e um popup para resultados.
JavaScript: Lógica do jogo, incluindo tratamento de entradas do teclado, atualização do estado do jogo e gerenciamento das condições de vitória/derrota.

Configuração
Para executar o jogo localmente, siga estas etapas:

Clonar o Repositório:git clone https://github.com/Dongo-28/Hangma-Project

Navegar até o Diretório do Projeto:cd Hangma-Project


Abrir o Jogo:Abra o arquivo forca.html em um navegador web (como Chrome ou Firefox) para começar a jogar. Não são necessárias dependências adicionais ou configuração de servidor.

Como Jogar

Abra o jogo em um navegador web.
Uma palavra secreta é selecionada aleatoriamente, exibida como sublinhados (_) para cada letra.
Pressione qualquer tecla de letra (A-Z) no teclado para adivinhar uma letra.
Se a letra estiver na palavra, ela aparece na(s) posição(ões) correta(s).
Se a letra não estiver na palavra, ela é adicionada à lista de "Letras Erradas", e a imagem da forca é atualizada.


Se você tentar uma letra já usada, uma mensagem de aviso temporária aparece.
O jogo termina quando:
Você adivinha a palavra corretamente (Vitória).
Você faz 6 palpites errados, completando a forca (Derrota).


Um popup exibe o resultado com a opção de "Jogar Novamente", que recarrega o jogo.

Estrutura de Arquivos

forca.html: Arquivo HTML principal com a estrutura do jogo.
style.css: Arquivo CSS para estilizar a interface do jogo.
script.js: Arquivo JavaScript com a lógica do jogo e manipulação de eventos.
img/: Diretório contendo as imagens da forca (forca1.png a forca6.png).

Problemas Conhecidos

A lógica de atualização da imagem da forca em desenharForca() pode não funcionar como esperado devido a uma discrepância entre o número de palpites errados e o array de imagens. Certifique-se de que as imagens estejam corretamente mapeadas para o número de palpites errados.
A verificação da condição de vitória (palavraSecreta === container.innerText) pode não ser confiável, pois compara a palavra secreta com o texto do contêiner, que inclui tags HTML. Considere revisar para comparar diretamente com as letras adivinhadas.

Melhorias Futuras

Adicionar efeitos sonoros para palpites corretos/incorretos e resultados do jogo.
Implementar um sistema de pontuação ou níveis de dificuldade.
Melhorar a acessibilidade com atributos ARIA e navegação por teclado.
Adicionar uma funcionalidade de dica para fornecer pistas sobre a palavra secreta.

Contribuindo
Contribuições são bem-vindas! Faça um fork do repositório, realize suas alterações e envie um pull request. Certifique-se de que seu código siga o estilo existente e inclua comentários apropriados.
Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.
Agradecimentos

Inspirado em jogos clássicos da forca.
Construído com JavaScript puro, HTML e CSS para uma experiência leve e acessível.

