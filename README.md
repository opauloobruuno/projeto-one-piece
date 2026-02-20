# 🏴‍☠️ One Piece - Projeto Interativo

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📖 Descrição do Projeto

Este é um projeto web interativo dedicado aos **Piratas do Chapéu de Palha** da série One Piece. O site apresenta uma galeria visual dos principais membros da tripulação, permitindo que os usuários naveguem entre diferentes personagens através de uma interface intuitiva e responsiva.

O objetivo do projeto é criar uma experiência imersiva onde os fãs podem explorar informações sobre seus personagens favoritos, visualizando imagens em alta qualidade e lendo descrições detalhadas sobre cada membro da tripulação. O design foi pensado para ser moderno, elegante e totalmente adaptável a diferentes tamanhos de tela.

## ✨ Funcionalidades

- 🎯 **Galeria Interativa de Personagens**: Visualize os principais membros dos Piratas do Chapéu de Palha
- 🖱️ **Navegação por Botões**: Selecione personagens através de botões laterais com imagens dos tripulantes
- 📱 **Design Responsivo**: Interface adaptável para desktop, tablet e dispositivos móveis
- 🎨 **Efeitos Visuais**: Transições suaves e efeitos de seleção ao trocar entre personagens
- 📝 **Informações Detalhadas**: Descrições completas sobre cada personagem da tripulação
- 🖼️ **Imagens em Alta Qualidade**: Visualização de personagens com imagens otimizadas

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação semântica do conteúdo
- **CSS3**: Estilização avançada com gradientes, flexbox e animações
- **JavaScript (Vanilla)**: Interatividade e manipulação do DOM
- **Google Fonts**: 
  - [Secular One](https://fonts.google.com/specimen/Secular+One) - Fonte para títulos dos personagens
  - [Rubik](https://fonts.google.com/specimen/Rubik) - Fonte para descrições e textos

## 📁 Estrutura de Arquivos

```
projeto-one-piece/
│
├── index.html                 # Página principal do projeto
│
└── src/
    ├── css/
    │   ├── reset.css          # Reset CSS para normalização entre navegadores
    │   ├── estilos.css        # Estilos principais da aplicação
    │   └── responsivo.css     # Media queries para design responsivo
    │
    ├── js/
    │   └── index.js           # Lógica JavaScript para interatividade
    │
    └── imagens/
        ├── one-piece-logo.png # Logo do One Piece
        ├── personagem-*.png   # Imagens dos personagens (7 arquivos)
        └── tripulacao-*.png   # Ícones dos botões de navegação (7 arquivos)
```

## 🚀 Como Executar Localmente

### Opção 1: Abrir diretamente no navegador

1. **Clone ou baixe** este repositório para sua máquina local
   ```bash
   git clone <url-do-repositorio>
   ```
   Ou baixe o arquivo ZIP e extraia em uma pasta

2. **Navegue até a pasta** do projeto
   ```bash
   cd projeto-one-piece
   ```

3. **Abra o arquivo `index.html`** diretamente no seu navegador
   - Clique duas vezes no arquivo `index.html`
   - Ou clique com o botão direito → "Abrir com" → Selecione seu navegador preferido

### Opção 2: Usando um servidor local (recomendado)

#### Com Live Server (VS Code)
1. Instale a extensão **Live Server** no VS Code
2. Abra a pasta do projeto no VS Code
3. Clique com o botão direito no arquivo `index.html`
4. Selecione **"Open with Live Server"**

#### Com Python (se instalado)
```bash
# Python 3.x
python -m http.server 8000

# Depois acesse: http://localhost:8000
```

#### Com Node.js (http-server)
```bash
# Instale globalmente (se necessário)
npm install -g http-server

# Execute na pasta do projeto
http-server

# Acesse o endereço mostrado no terminal (geralmente http://localhost:8080)
```

### Opção 3: Com PHP (se instalado)
```bash
php -S localhost:8000
```

---

## 📝 Notas

- O projeto utiliza apenas tecnologias web nativas (HTML, CSS e JavaScript puro)
- Não são necessárias dependências externas ou instalação de pacotes
- Todas as imagens estão incluídas na pasta `src/imagens/`
- O projeto é totalmente funcional offline após o download

