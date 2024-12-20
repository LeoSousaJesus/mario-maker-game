# Aprendendo a programar o jogo do Super Mário Bros


## Este é um projeto para recriar o jogo **Super Mário Bros** como parte de um aprendizado em desenvolvimento web e programação de jogos.

---

## Estrutura do Projeto

Abaixo está a organização das pastas e arquivos do projeto:

### **Diretórios Principais**
- **`css/`**: Arquivos de estilo CSS.
  - `reset.css`: Define um estilo base para o projeto.
  - `style.css`: Contém os estilos personalizados do jogo.

- **`fonts/`**: Fontes utilizadas no jogo.
  - `SuperMario256.ttf`: Fonte personalizada do Super Mário.

- **`images/`**: Recursos gráficos do jogo, como sprites e ícones.
  - Exemplos:
    - `bg.png`: Imagem de fundo do jogo.
    - `coin.png`: Sprite da moeda.
    - `mario-sprites.png`: Sprites do personagem Mário.

- **`js/`**: Scripts JavaScript que implementam a lógica do jogo.
  - **`levelEditor/`**: Scripts para criar e editar níveis.
    - `CreatedLevels.js`: Gerenciamento de níveis criados.
    - `Editor.js`: Funcionalidades do editor de níveis.
    - `Storage.js`: Armazenamento local dos níveis.
  - **`mainGame/`**: Scripts para a mecânica principal do jogo.
    - `GameUI.js`: Interface do usuário no jogo.
    - `MarioMaker.js`: Configuração e execução do jogo.
    - `Preloader.js`: Pré-carregamento de recursos.
    - `View.js`: Gerenciamento da visão no jogo.

- **`sounds/`**: Arquivos de áudio usados no jogo.
  - Exemplos:
    - `bullet.wav`: Som do disparo.
    - `coin.wav`: Som ao coletar moedas.
    - `jump.wav`: Som do pulo do Mário.

---

### **Arquivos Principais**
- **`index.html`**: Arquivo principal para execução do jogo.
- **`README.md`**: Documentação do projeto.

---

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

