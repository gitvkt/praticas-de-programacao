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

```

## Descrição das Pastas

### `assets/`
Diretório principal que centraliza todos os arquivos estáticos e recursos públicos da aplicação.

* **`css/`**: Contém as folhas de estilo do sistema.
  * **`style.css`**: Estilos gerais, reset e variáveis globais.
  * **`components/`**: Estilos isolados para elementos específicos (ex: `header.css`, `footer.css`, `cards.css`).
  * **`vendor/`**: Bibliotecas de estilo externas sem modificação direta.
* **`js/`**: Contém scripts e lógica JavaScript.
  * **`main.js`**: Inicializações e scripts globais da aplicação.
  * **`components/`**: Módulos ou scripts específicos de cada componente.
  * **`vendor/`**: Bibliotecas externas de JS.
* **`images/`**: Armazena todas as mídias visuais do projeto.
  * **`icons/`**: Logotipos pequenos, ícones utilitários e favicons.
  * **`banners/`**: Imagens de fundo e artes de destaque.
* **`includes/`**: Trechos de código HTML ou PHP reaproveitáveis que formam o layout base (cabeçalhos, rodapés, sidebars).
