# Portfólio Pessoal e Linktree

Este é um projeto de site de portfólio pessoal que funciona como um cartão de visita digital. Ele foi projetado para ser totalmente responsivo, transformando-se em uma página no estilo "Linktree" em dispositivos móveis.

**[Veja a demonstração ao vivo](https://portfolio-linktree-eight.vercel.app/#contact)**

---

## 📸 Sobre o Projeto

O objetivo deste projeto é apresentar minhas habilidades, projetos e informações de contato de uma forma limpa, moderna e acessível. O site possui um layout de desktop que destaca os projetos visualmente e um layout para acesso rápido aos links mais importantes.

![alt text](assets/images/banner.png)

### ✨ Funcionalidades

- **Layout Responsivo:** Design adaptável que se ajusta a telas de desktop e móveis.
- **Versão Linktree:** Em telas menores, o site se transforma em uma lista de links de acesso rápido, ideal para redes sociais.
- **Animações de Scroll:** Utiliza a biblioteca [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) para animar elementos à medida que eles entram na tela.
- **Navegação Suave:** Rolagem suave entre as seções.
- **Componentização CSS:** O CSS é organizado usando arquitetura BEM, dividido em base, componentes, layout e seções.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3:**
  - Flexbox e Grid Layout
  - Media Queries para responsividade
  - Arquitetura de CSS modular
- **JavaScript (ES6+):**
- **[AOS (Animate On Scroll)](https://michalsnik.github.io/aos/):** Biblioteca para animações de scroll.

---

## 🚀 Como Executar o Projeto

Como este é um projeto front-end estático, você pode executá-lo abrindo o arquivo `index.html` em seu navegador.

1. Clone o repositório:
   ```bash
   git clone https://github.com/lcsqueiroz/portfolio-linktree.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd portfolio-linktree
   ```
3. Abra o arquivo `index.html` no seu navegador de preferência.

---

## 📂 Estrutura de Arquivos

O projeto está organizado da seguinte forma:

```
.
├── assets/         # Ícones e imagens
├── documents/      # Arquivos como o CV em PDF
├── js/
│   └── main.js     # Script principal
├── style/
│   ├── base/       # Estilos base (reset, variáveis, etc.)
│   ├── components/ # Componentes reutilizáveis (botões, cards)
│   ├── layout/     # Estilos de layout (header, footer, responsividade)
│   └── sections/   # Estilos para seções específicas (hero, projetos)
├── index.html      # Estrutura principal da página
└── README.md       # Esta documentação
```

---

Feito por Lucas Queiroz.
