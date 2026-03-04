# PawLux — Landing Page para Pet Shop

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

**Landing page moderna, responsiva e de alta fidelidade visual para o nicho de pet shop.**

[Tecnologias](#-tecnologias) · [Como usar](#-como-usar) · [Estrutura](#-estrutura-do-projeto)

</div>

---

## Sobre o projeto

Este projeto foi desenvolvido para atender a requisição de um cliente que buscava uma **base de design moderna e reproduzível** voltada para o segmento de pet shop. O objetivo principal era entregar um template profissional que pudesse ser facilmente adaptado por qualquer profissional ou equipe de desenvolvimento para diferentes marcas e negócios do nicho pet.

A proposta era clara: fugir de layouts genéricos e criar algo com identidade visual forte, tipografia refinada, interações fluidas e uma arquitetura de código limpa o suficiente para servir como ponto de partida real em projetos comerciais.

## Objetivos da entrega

- Construir uma landing page completa e funcional em um **único arquivo HTML**, sem dependências externas de build.
- Aplicar uma paleta de cores definida pelo cliente: **amarelo dourado, marrom, branco e preto**.
- Utilizar exclusivamente **ícones SVG inline e imagens** — nenhum emoji no projeto.
- Garantir **responsividade total** para desktop, tablet e mobile.
- Priorizar **performance e acessibilidade**, com carregamento leve e navegação acessível.
- Produzir um código organizado e bem comentado que sirva de **template reutilizável**.

## Preview

O layout segue uma estrutura de seções comum em landing pages de alta conversão:

| Seção | Descrição |
|---|---|
| **Navbar** | Menu fixo com efeito glassmorphism ao rolar |
| **Hero** | Headline de impacto, CTA duplo, estatísticas e imagem com cards flutuantes animados |
| **Parceiros** | Barra de logos de marcas parceiras |
| **Serviços** | Grid de 4 cards com ícones, descrição e preço inicial |
| **Sobre** | Seção institucional com galeria, badge de experiência e features |
| **Produtos** | Vitrine de 4 produtos com badges, favoritos e carrinho |
| **Depoimentos** | 3 cards de testimonial com estrelas e avatar |
| **CTA** | Caixa de conversão com formulário de e-mail |
| **Footer** | Informações de contato, links, redes sociais e créditos |

## Tecnologias

O projeto foi desenvolvido propositalmente com tecnologias vanilla para garantir máxima portabilidade:

- **HTML5** — estrutura semântica
- **CSS3** — variáveis customizadas, grid, flexbox, animações, transições e media queries
- **JavaScript** — scroll reveal, navbar dinâmica, interações de UI
- **Google Fonts** — Playfair Display + DM Sans
- **SVG inline** — ícones vetoriais nativos sem dependência de bibliotecas de ícones
- **Unsplash** — imagens de alta qualidade via URL direta

Nenhum framework, bundler ou pré-processador é necessário.

## Como usar

### Visualização rápida

Basta abrir o arquivo `petshop-landing-page.html` em qualquer navegador moderno. Não há etapa de build.

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/pawlux-landing.git

# Acesse a pasta
cd pawlux-landing

# Abra no navegador (macOS)
open petshop-landing-page.html

# Ou no Linux
xdg-open petshop-landing-page.html
```

### Personalização

As variáveis de design estão centralizadas no bloco `:root` do CSS, facilitando a customização completa:

```css
:root {
    --gold: #D4A017;         /* Cor principal / Accent */
    --brown-dark: #3E2723;   /* Textos e seções escuras */
    --brown: #5D4037;        /* Textos secundários */
    --white: #FFFFFF;        /* Backgrounds claros */
    --black: #1A1A1A;        /* Footer e contraste */

    --font-display: 'Playfair Display', Georgia, serif;
    --font-body: 'DM Sans', system-ui, sans-serif;
}
```

Para adaptar a uma marca diferente, basta alterar as variáveis de cor e tipografia — todo o layout responde automaticamente.

## Estrutura do projeto

```
pawlux-landing/
├── petshop-landing-page.html   # Arquivo único com HTML + CSS + JS
└── README.md                   # Documentação do projeto
```

Toda a lógica, estilização e marcação está contida em um único arquivo `.html`, incluindo:

- CSS embarcado com variáveis, animações e responsividade
- SVGs inline para todos os ícones
- JavaScript vanilla para interações e scroll reveal
- Imagens servidas via CDN (Unsplash)

## Destaques técnicos

**Design System embutido** — paleta, tipografia, espaçamentos, sombras e raios de borda definidos em variáveis CSS, criando consistência visual em toda a página.

**Animações performáticas** — scroll reveal via Intersection Observer, hover states com GPU-accelerated transforms, cards flutuantes com keyframes e navbar com backdrop-filter.

**Responsividade** — breakpoints em 1024px e 768px com reorganização completa do grid, menu mobile funcional e ajustes de tipografia via clamp().

**Acessibilidade** — atributos aria-label em botões de ícone, estrutura semântica com nav/section/footer, contraste adequado e navegação por teclado nos links.

**Zero dependências de build** — sem Node.js, sem npm, sem webpack. Abre direto no navegador.

## Licença

Este projeto é de uso livre para fins educacionais e comerciais. Ao utilizar como base para projetos de clientes, recomenda-se substituir as imagens do Unsplash por fotos próprias e ajustar os textos para o contexto real do negócio.

---

<div align="center">

Desenvolvido como solução de design para o nicho pet shop.

</div>
