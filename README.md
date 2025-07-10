# 🧙‍♂️ Projeto de Cartas - Magick IA (Dev em Dobro)

Este projeto foi desenvolvido durante o evento **Magick IA**, promovido pela [Dev em Dobro](https://www.devemdobro.com/). Trata-se de uma página de catálogo de cartas fictícias com sistema de filtro por categoria e preço.

## 📋 Funcionalidades

- Visualização de cartas com nome, categoria, imagem e preço.
- Filtro de cartas por:
  - Categoria (Comum, Rara, Épica);
  - Preço máximo.
- Botão de compra com redirecionamento para o WhatsApp (simulação).

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3** (Flexbox, `calc()`, media queries, etc.)
- **JavaScript** (para a lógica dos filtros)
- **Imagens fornecidas pelo evento**
- **Google Fonts** (Roboto)

## 🎨 Diferenças em relação ao projeto original

Apesar de ter sido inspirado e iniciado a partir do conteúdo apresentado no evento, este projeto contém **adaptações pessoais**:

- 🔧 **Correções visuais no layout**:
  - Utilização de `width: calc(33.333% - 32px)` para organizar melhor as cartas em **3 colunas** no desktop;
  - Uso de `width: calc(50% - 16px)` no responsivo para manter a proporção em **2 colunas** no tablet.

- 🟥 **Estilo visual personalizado**:
  - Alteração da cor de fundo da `.container` para **vermelho/laranja intenso** (`orangered`) para destacar o conteúdo.

- 🛠️ **Ajustes e testes manuais**:
  - Pequenos ajustes foram feitos para corrigir imperfeições e tornar o layout mais próximo da proposta visual ideal — mesmo que de forma diferente da solução oficial.

## 📁 Estrutura de pastas

```bash
magick-ia/
├── src/ 
│   ├── css/
│   │   ├── reset.css
│   │   ├── estilos.css
│   │   └── responsivo.css
│   ├── imagens/
│   │   ├── carta-arkanon.png 
│   │   ├── carta-drahven.png
│   │   ├── carta-kaelthar.png
│   │   ├── carta-lymara.png
│   │   ├── carta-maldrik.png
│   │   ├── carta-nyxsombra.png
│   │   ├── logo.png
│   │   ├── lord-demon.png
│   │   ├── rei-gelado.png
│   │   ├── seta-para-baixo.png
│   │   └── yog-sothoth.png
│   └── js/       
│       ├── index-refatorada.js
│       └── index.js
├── index.html
└── README.md

## 🔗 Link do Projeto
