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
    └── includes/         <-- Trechos de HTML reutilizáveis (quando usa PHP ou similar)
        ├── header.html (ou .php)
        └── footer.html (ou .php)
