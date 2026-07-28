# Estrutura de Pastas - Front-end Web

Esta é a estrutura de pastas recomendada para a organização de projetos front-end web tradicionais, focando em manutenibilidade, separação de responsabilidades e reutilização de componentes.

## Visão Geral do Diretório

```text
meu-projeto/
│
├── index.html
├── sobre.html
│
└── assets/               <-- Tudo o que é estático/público fica aqui
    ├── css/
    │   ├── style.css     <-- Estilos globais/principais
    │   ├── components/   <-- Estilos de partes específicas
    │   │   ├── header.css
    │   │   └── footer.css
    │   └── vendor/       <-- CSS de terceiros (Bootstrap, Swiper, etc.)
    │
    ├── js/
    │   ├── main.js       <-- Scripts globais/principais
    │   ├── components/   <-- Scripts de componentes
    │   │   ├── header.js
    │   │   └── footer.js
    │   └── vendor/       <-- JS de terceiros
    │
    ├── images/           <-- Imagens e mídia
    │   ├── logo.svg
    │   ├── icons/        <-- Ícones em SVG ou PNG
    │   └── banners/      <-- Imagens grandes ou de fundo
    │
    └── includes/         <-- Trechos reutilizáveis (PHP ou template engines)
        ├── header.html (ou .php)
        └── footer.html (ou .php)
