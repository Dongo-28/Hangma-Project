# 🎯 Hangma-Project

<p align="center">
  <strong>Um jogo clássico da forca, desenvolvido com HTML, CSS e JavaScript.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

---

## 📌 Sobre o Projeto

**Hangma-Project** é uma implementação digital do clássico jogo da forca, desenvolvida com HTML, CSS e JavaScript. O objetivo é descobrir uma palavra secreta, letra por letra, antes que o desenho da forca seja completado.

O projeto apresenta uma interface simples, intuitiva e responsiva, proporcionando uma experiência de jogo agradável, com feedback visual, atualização dinâmica das imagens e um popup para apresentar o resultado de cada partida.

## ✨ Funcionalidades

- 🔤 **Palavras aleatórias:** seleção automática de palavras a partir de uma lista predefinida.
- 🖼️ **Forca dinâmica:** atualização da imagem a cada tentativa incorreta.
- ✅ **Letras corretas:** identificação e apresentação das letras acertadas.
- ❌ **Letras incorretas:** apresentação das letras que não pertencem à palavra secreta.
- ⚠️ **Prevenção de repetições:** aviso visual ao tentar inserir uma letra já utilizada.
- 📱 **Design responsivo:** interface adaptável a diferentes tamanhos de ecrã.
- 🏆 **Sistema de resultados:** identificação automática de vitória ou derrota através de um popup.
- 🔁 **Reiniciar partida:** possibilidade de começar um novo jogo após o término da partida.

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
|---|---|
| HTML5 | Estrutura e organização da interface. |
| CSS3 | Estilização, layout responsivo e animações visuais. |
| JavaScript | Lógica do jogo, manipulação do DOM e gestão dos eventos. |

## 🚀 Como Executar o Projeto

Não é necessário instalar dependências nem configurar um servidor. Basta seguir os passos:

**1. Clonar o repositório**

```bash
git clone https://github.com/Dongo-28/Hangma-Project.git
```

**2. Aceder à pasta do projeto**

```bash
cd Hangma-Project
```

**3. Executar o jogo**

Abre o ficheiro `forca.html` diretamente no teu navegador preferido, como Google Chrome, Mozilla Firefox ou Microsoft Edge.

> 📦 Não são necessárias dependências externas!

## 🎮 Como Jogar

1. Abre o jogo no navegador.
2. Observa os espaços em branco que representam a palavra secreta.
3. Pressiona uma letra no teclado para tentar adivinhar a palavra.
4. Acompanha as letras corretas, as tentativas incorretas e a evolução do desenho da forca.

### 📜 Regras do Jogo

| Situação | Resultado |
|---|---|
| ✅ Letra correta | Aparece na posição correspondente da palavra. |
| ❌ Letra incorreta | É adicionada à lista de erros e atualiza a imagem da forca. |
| ⚠️ Letra repetida | É apresentado um aviso visual. |
| 🏆 Vitória | Todas as letras da palavra são descobertas. |
| 💀 Derrota | A forca é completada após 6 erros. |

Quando a partida termina, um popup apresenta o resultado e disponibiliza a opção **«Jogar Novamente»**.

## 📁 Estrutura do Projeto

```text
Hangma-Project/
│
├── forca.html          # Estrutura principal do jogo
│
├── style.css           # Estilos e design da interface
│
├── script.js           # Lógica e funcionalidades do jogo
│
└── img/
    ├── forca1.png      # Estado inicial
    ├── forca2.png      # Primeiro erro
    ├── forca3.png      # Segundo erro
    ├── forca4.png      # Terceiro erro
    ├── forca5.png      # Quarto erro
    └── forca6.png      # Estado final
```

## 🐞 Problemas Conhecidos

Existem alguns pontos que podem beneficiar de melhorias na implementação atual:

- **Sincronização das imagens:** a função `desenharForca()` poderá apresentar problemas caso o número de erros não esteja devidamente sincronizado com o array de imagens.
- **Verificação de vitória:** a comparação `palavraSecreta === container.innerText` poderá falhar devido à presença de elementos HTML. Recomenda-se utilizar uma comparação direta entre as letras descobertas e a palavra secreta.

## 🔮 Melhorias Futuras

Algumas funcionalidades que poderão ser implementadas em versões futuras:

- 🔊 Adicionar efeitos sonoros para acertos, erros e fim de jogo.
- 🎯 Implementar diferentes níveis de dificuldade.
- 🥇 Criar um sistema de pontuação e recordes.
- ♿ Melhorar a acessibilidade através de navegação por teclado e atributos ARIA.
- 💡 Adicionar um sistema de dicas para ajudar os jogadores.
- 🌍 Expandir a lista de palavras e adicionar diferentes categorias.

## 🤝 Contribuições

As contribuições são bem-vindas!

Se quiseres contribuir para o desenvolvimento do **Hangma-Project**, segue estes passos:

1. Faz um Fork do repositório.
2. Cria uma nova branch (`git checkout -b feature/nova-funcionalidade`).
3. Implementa as tuas alterações.
4. Efetua o commit (`git commit -m "Adiciona nova funcionalidade"`).
5. Envia as alterações (`git push origin feature/nova-funcionalidade`).
6. Abre um Pull Request.

Por favor, mantém o código organizado, segue o estilo de desenvolvimento do projeto e documenta as alterações relevantes.

---

<p align="center">
  Desenvolvido com ❤️ utilizando HTML, CSS e JavaScript.
</p>

<p align="center">
  <strong>🎯 Hangma-Project — Testa a tua capacidade de adivinhar!</strong>
</p>
