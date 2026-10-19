# 🐾 VetCare — Hospital Veterinário e Centro Diagnóstico

O **VetCare** é uma aplicação web desenvolvida para apresentar a estrutura, corpo clínico e serviços de uma clínica veterinária e centro diagnóstico 24h[cite: 3, 6]. O projeto foca em oferecer uma experiência fluida aos tutores de pets[cite: 3], aplicando conceitos modernos de desenvolvimento front-end, arquitetura limpa, acessibilidade e responsividade[cite: 1].

---

## 🎯 Visão Geral e Objetivo

Este projeto simula o desenvolvimento front-end em ambiente profissional[cite: 1]. O objetivo principal é disponibilizar uma interface intuitiva e acessível para que os usuários conheçam os serviços prestados, consultem especialidades[cite: 4], conheçam o corpo clínico[cite: 4, 7], tirem dúvidas frequentes[cite: 4, 7] e entrem em contato direto para atendimentos e emergências[cite: 4, 7, 8].

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **HTML5 Semântico:** Estruturação da página focada em acessibilidade,SEO e boas práticas, utilizando elementos como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<details>`, `<summary>` e `<footer>`[cite: 1, 4].
- **CSS3 Avançado:**
  - **Variáveis Globais (CSS Custom Properties):** Padronização de tokens de cores, tipografia e sombras[cite: 3, 5].
  - **Layout Flexbox:** Utilizado para alinhamento e distribuição fluida de componentes.
  - **Unidades Relativas (`rem`, `%`, `vh`, `vw`):** Escala tipográfica baseada no elemento raiz e layout responsivo adaptável.
  - **Posicionamento Fixo (`position: fixed`):** Utilizado no menu lateral, no rodapé e no botão flutuante[cite: 3, 4, 5].
  - **Transições e Microinterações:** Efeitos de `:hover`, elevação com `box-shadow` e transformações suaves para melhorar a UX[cite: 4, 5].
- **Metodologia BEM (Block Element Modifier):** Nomenclatura organizada de classes no HTML e CSS para evitar acoplamento e facilitar a manutenção.
- **Tipografia Externa:** Importação da fonte *Poppins* (pesos 400, 500, 600 e 700) via Google Fonts[cite: 6].
- **Integração com API Externa:** Link direto para o WhatsApp oficial via protocolo URL dinâmico[cite: 4].

---

## 📂 Organização da Arquitetura de Arquivos

A estrutura do projeto segue o princípio de separação de responsabilidades (RNF04)[cite: 2]:

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
