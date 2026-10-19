# 🐾 VetCare — Hospital Veterinário e Centro Diagnóstico

O **VetCare** é uma aplicação web desenvolvida para apresentar a estrutura, corpo clínico e serviços de uma clínica veterinária e centro diagnóstico 24h. O projeto foca em oferecer uma experiência fluida aos tutores de pets, aplicando conceitos modernos de desenvolvimento front-end, arquitetura limpa, acessibilidade e responsividade.

---

## 🎯 Visão Geral e Objetivo

Este projeto simula o desenvolvimento front-end em ambiente profissional. O objetivo principal é disponibilizar uma interface intuitiva e acessível para que os usuários conheçam os serviços prestados, consultem especialidades, conheçam o corpo clínico, tirem dúvidas frequentes e entrem em contato direto para atendimentos e emergências.

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **HTML5 Semântico:** Estruturação da página focada em acessibilidade,SEO e boas práticas, utilizando elementos como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<details>`, `<summary>` e `<footer>`.
- **CSS3 Avançado:**
  - **Variáveis Globais (CSS Custom Properties):** Padronização de tokens de cores, tipografia e sombras.
  - **Layout Flexbox:** Utilizado para alinhamento e distribuição fluida de componentes.
  - **Unidades Relativas (`rem`, `%`, `vh`, `vw`):** Escala tipográfica baseada no elemento raiz e layout responsivo adaptável.
  - **Posicionamento Fixo (`position: fixed`):** Utilizado no menu lateral, no rodapé e no botão flutuante.
  - **Transições e Microinterações:** Efeitos de `:hover`, elevação com `box-shadow` e transformações suaves para melhorar a UX.
- **Metodologia BEM (Block Element Modifier):** Nomenclatura organizada de classes no HTML e CSS para evitar acoplamento e facilitar a manutenção.
- **Tipografia Externa:** Importação da fonte *Poppins* (pesos 400, 500, 600 e 700) via Google Fonts.
- **Integração com API Externa:** Link direto para o WhatsApp oficial via protocolo URL dinâmico.

---

## 📂 Organização da Arquitetura de Arquivos

A estrutura do projeto segue o princípio de separação de responsabilidades (RNF04):

```text
├── assets/
│   ├── css/
│   │   ├── variables.css      # Variáveis globais e Design System
│   │   ├── global.css         # Reset de CSS e estilos base
│   │   ├── components.css     # Estilos de cards, botões e elementos BEM
│   │   └── layout.css         # Estilização das seções, sidebar e rodapé
│   └── images/                # Imagens e recursos visuais locais
├── index.html                 # Estrutura HTML5 da aplicação
└── README.md                  # Documentação completa do projeto
