
<div align="center">

  # ⚔️ God of War - Ragnarök Landing Page


  ![God of War Banner](img/logo.jpg)
  
  **Uma landing page épica e imersiva para o lançamento de God of War Ragnarök. Design moderno com animações fluidas, carousel interativo de personagens e seção de trailer integrada.**
  
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
  [![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
  [![Swiper](https://img.shields.io/badge/Swiper-6332F6?style=for-the-badge&logo=swiper&logoColor=white)](https://swiperjs.com/)
  
</div>

## 🚀 Demo Online

<div align="center">

### 🌐 <a href="https://god-of-war-ragnarok.mklly.com.br/" target="_blank" rel="noopener noreferrer">**VER PROJETO AO VIVO**</a>

<a href="https://god-of-war-ragnarok.mklly.com.br/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/>
</a>

</div>

## 📸 Screenshots

<div align="center">

  <img src="./img/screen-shot-hero.png" alt="Seção Hero" width="600"/>

</div>

## ✨ Funcionalidades

- � **Player de Trailer**: Botão interativo para reprodução do trailer oficial
- 🎠 **Carousel de Personagens**: Slider responsivo com os principais personagens
- 🎨 **Design Imersivo**: Interface que captura a essência visual do jogo
- 📱 **Layout Responsivo**: Adaptação perfeita para todos os dispositivos
- ⚡ **Animações Fluidas**: Transições suaves e efeitos visuais envolventes
- 🎯 **Seção de Pré-venda**: Call-to-action estratégico para compras
- 📋 **Informações Técnicas**: Detalhes sobre compatibilidade e recursos do jogo
- 🏷️ **Classificação Etária**: Informações oficiais sobre faixa etária

## 🎯 Destaques do Design

- **Hero Section**: Banner principal com informações de lançamento e preço
- **Seção Storyline**: Narrativa envolvente sobre a jornada de Kratos e Atreus
- **Galeria de Personagens**: Cards interativos com os principais protagonistas
- **Informações Técnicas**: Ícones e detalhes sobre recursos do PlayStation
- **Branding Oficial**: Logos e elementos visuais oficiais da Sony/Santa Monica

## 📁 Estrutura do Projeto

```
📦 god-of-war-landing
├── 📄 index.html              # Página principal
├── 📄 README.md
├── 📁 css/
│   └── 📄 main.css           # Estilos compilados
├── 📁 scss/
│   ├── 📄 _reset.scss        # Reset de estilos
│   ├── 📄 _grid.scss         # Sistema de grid
│   ├── 📄 _header.scss       # Estilos do cabeçalho
│   ├── � _home.scss         # Estilos das seções principais
│   ├── 📄 _patterns.scss     # Padrões reutilizáveis
│   └── 📄 main.scss          # Arquivo principal SCSS
├── 📁 js/
│   └── 📄 main.js            # Configuração do Swiper
└── 📁 img/
    ├── 📄 *.jpg              # Imagens dos personagens
    ├── 📄 *.png              # Ícones e logos
    └── 📄 *.svg              # Vetores e ícones
```

## 💻 Como Executar

1. **Clone o repositório**
```bash
git clone https://github.com/marquesmaycon/god-of-war-ragnarok.git
```

2. **Navegue até a pasta**
```bash
cd god-of-war-ragnarok
```

3. **Abra o projeto**
   - Abra o arquivo `index.html` no seu navegador
   - Ou use um servidor local como Live Server (VS Code)

## 🛠️ Principais Implementações

### Carousel Responsivo com Swiper.js
```javascript
var swiper = new Swiper(".slide-characters", {
   slidesPerView: 3.5,
   spaceBetween: 19,
   freeMode: true,
   breakpoints: {
      320: { slidesPerView: 1.1 },
      768: { slidesPerView: 2.2 },
      991: { slidesPerView: 2.8 },
      1200: { slidesPerView: 3.5 }
   }
});
```

### Arquitetura SCSS Modular
- **Componentização**: Estilos organizados por seções
- **Mixins e Variáveis**: Reutilização eficiente de código
- **Sistema de Grid**: Layout flexível e responsivo
- **Reset Customizado**: Base sólida para estilos

### Design System
- **Tipografia**: Fonte Archivo para legibilidade
- **Paleta de Cores**: Tons escuros que remetem ao universo do jogo
- **Breakpoints**: Design mobile-first com 4 pontos de quebra
- **Animações**: Transições CSS suaves e naturais

## 🎨 Destaques Técnicos

- **CSS Grid & Flexbox**: Layout moderno e flexível
- **SCSS**: Pré-processamento para código mais limpo
- **Swiper.js**: Biblioteca robusta para carousels
- **Mobile-First**: Abordagem responsiva moderna
- **Semantic HTML**: Estrutura acessível e SEO-friendly
- **Performance**: Otimização de imagens e assets

## ⚔️ Personagens Incluídos

**Kratos** - Deus da Guerra, protagonista principal
**Atreus** - Filho de Kratos, co-protagonista  
**Mímir** - Conselheiro e aliado leal
**Freya** - Mãe de Baldur, personagem complexa
**Thor** - Deus do Trovão, antagonista poderoso
**Týr** - Deus da Guerra Nórdico, aliado misterioso

## 👨‍💻 Autor

<div align="center">
  <img src="https://github.com/marquesmaycon.png" width="100px" style="border-radius: 50%"/>
  <br/>
  <strong>Maycon Marques</strong>
  <br/>
  <br/>
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayconhenrique/)
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/marquesmaycon)
  [![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mayconmarquesh@gmail.com)

  ### Feito com ❤️ e muita 🎵
</div>