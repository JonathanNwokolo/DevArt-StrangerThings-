# 🎬 DevArt - Stranger Things Experience

Landing page interativa inspirada na série Stranger Things, desenvolvida com animações avançadas utilizando GSAP (GreenSock Animation Platform).

![Stranger Things](imagens/pagina-full.jpg)

## 📋 Sobre o Projeto

Este projeto é uma experiência imersiva que simula uma página promocional para "The Experience - Stranger Things". A página apresenta animações fluidas de scroll, efeitos de parallax e transições cinematográficas que capturam a atmosfera da série.

## ✨ Funcionalidades

- **Preloader Animado**: Logo de Stranger Things com efeito de desenho SVG
- **Scroll Suave**: Navegação fluida com ScrollSmoother
- **Animações de Texto**: Efeitos de fade-in e split text nas seções
- **Parallax**: Elementos com movimento em diferentes velocidades
- **Design Responsivo**: Adaptação para dispositivos móveis
- **Cards Interativos**: Seção de escolha de cidade com efeitos de blur
- **Depoimentos**: Seção com citações sobre a experiência
- **Footer Animado**: Efeito de texto infinito deslizante

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização avançada com variáveis e responsividade
- **JavaScript**: Lógica de animações
- **GSAP 3.14.1**: Biblioteca de animações
  - ScrollTrigger: Animações baseadas em scroll
  - ScrollSmoother: Scroll suavizado
  - SplitText: Animações de texto caractere por caractere
- **Google Fonts**: Tipografia Poppins
- **Fonte Customizada**: Benguiat (fonte oficial de Stranger Things)

## 📁 Estrutura de Arquivos

```
DevArt StrangerThings/
│
├── index.html          # Estrutura HTML principal
├── style.css           # Estilos e responsividade
├── script.js           # Animações e interações
│
├── fontes/
│   └── Benguiat Bold.ttf
│
└── imagens/
    ├── bg-1.webp
    ├── bg-1-mobile.webp
    ├── bg-2.webp
    ├── bg-2-mobile.webp
    ├── bg-sec2.webp
    ├── bg-footer.webp
    ├── card1.webp
    ├── card2.webp
    ├── card3.webp
    ├── netflix-logo.svg
    ├── fever-logo.svg
    ├── clio-logo.svg
    └── ... (outros assets)
```

## 🎨 Seções da Página

1. **Header**: Logo e navegação
2. **Hero Section**: Seção principal com parallax
3. **Escolha sua Cidade**: Cards interativos com cidades disponíveis
4. **Depoimentos**: Citações sobre a experiência
5. **Agradecimentos**: Lista de cidades participantes
6. **Footer**: Informações institucionais e redes sociais

## 🎯 Animações Implementadas

### Preloader
- Animação de traçado SVG (stroke-dasharray)
- Transição de cor ao finalizar
- Fade out ao completar

### Hero Section
- Fade in na entrada
- Parallax vertical em camadas
- Animação de texto split

### Cards
- Fade in com blur progressivo
- Stagger (escalonamento) entre cards
- Ativação por scroll

### Texto Animado
- Split text (divisão em caracteres)
- Fade in + movimento vertical
- Sincronização com scroll

### Footer
- Movimento vertical de entrada
- Texto infinito deslizante



3. **Acesse no navegador**
   - Direto: `file:///caminho/para/index.html`
   - Local: `http://localhost:8000`

## 📱 Responsividade

O projeto utiliza media queries e imagens otimizadas para diferentes tamanhos de tela:

- **Desktop**: Layout completo com todas as animações
- **Mobile**: Imagens redimensionadas e layout adaptado
- **Breakpoint**: 600px

## 🎨 Paleta de Cores

- **Background**: `#0c0102` (Preto avermelhado)
- **Primária**: `#E92A2D` (Vermelho Stranger Things)
- **Texto**: `rgba(255, 255, 255, 0.9)` (Branco translúcido)
- **Destaques**: `rgb(168, 19, 19)` (Vermelho escuro)


## 🌐 Navegadores Compatíveis

- ✅ Chrome (versão 90+)
- ✅ Firefox (versão 88+)
- ✅ Safari (versão 14+)
- ✅ Edge (versão 90+)
- ⚠️ Internet Explorer: Não suportado


## 🎓 Aprendizados do Projeto

- Implementação avançada de GSAP Timeline
- Uso eficiente de ScrollTrigger para animações baseadas em scroll
- Técnicas de parallax com data-speed
- Otimização de performance com lazy loading implícito
- Estruturação de código para animações complexas



## 📄 Licença

Este é um projeto educacional/portfólio. O conteúdo e marcas relacionadas a Stranger Things são propriedade da Netflix.

