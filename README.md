# Luxury Motors — Projeto CSS

Landing page de uma concessionária fictícia de carros de luxo, desenvolvida com **HTML5** e **CSS3 puro (Vanilla CSS)**, sem frameworks. O projeto foi feito para a disciplina **Frameworks Front-end** (SENAI), na aula de Frameworks CSS, como a versão "Vanilla" da atividade. A versão com framework está no repositório [projeto-tailwind](https://github.com/pietrosantos15/projeto-tailwind).

## 👤 Autor

**Pietro Freire Rezende dos Santos**

---

## 🖥️ Seções da Página

| Seção | Conteúdo |
|-------|----------|
| **Menu** | Cabeçalho fixo com logo e links de navegação por âncora |
| **Início (Hero)** | Título de destaque, descrição, botões e imagem com animação flutuante |
| **Carros** | Cards da coleção: Ferrari Purosangue, Lamborghini Aventador e Porsche 911 Turbo S |
| **Destaque** | Bloco em destaque da Ferrari Purosangue |
| **Sobre** | Apresentação da Luxury Motors |
| **Contato** | Chamada para entrar em contato |
| **Rodapé** | Direitos reservados |

---

## 🚀 Tecnologias

- **HTML5:** estrutura semântica (`header`, `nav`, `section`, `footer`)
- **CSS3:** estilização em arquivo externo (`style.css`) ligado pela tag `<link>`

---

## 🎨 Recursos de CSS Utilizados

- **Box Model:** controle de `margin`, `padding`, `border` e `box-sizing: border-box`
- **Flexbox:** organização do menu, dos botões e das informações dos cards
- **CSS Grid:** layout do hero, da seção de destaque e da grade de cards (`grid-template-columns`)
- **Responsividade:** `@media` queries para telas de até `800px` e `500px`, transformando as grades em uma coluna
- **Efeitos visuais:** `linear-gradient`, `backdrop-filter: blur()` no menu e sombras
- **Interações:** efeitos de `:hover` em links, botões, cards e imagens com `transition`
- **Animação:** `@keyframes flutuar` aplicada à imagem principal
- **Classes reutilizáveis:** botões (`.botao`, `.vermelho`, `.transparente`, `.preto`) e marcas dos cards

---

## 📁 Estrutura do Projeto

```
projetocss/
├── index.html   # Estrutura da página
└── style.css    # Estilos (CSS externo)
```

---

## ⚙️ Como Executar

O projeto não precisa de instalação nem de servidor.

```bash
# 1. Clonar o repositório
git clone https://github.com/pietrosantos15/projetocss.git

# 2. Entrar na pasta
cd projetocss
```

3. Abrir o arquivo `index.html` no navegador (ou usar a extensão **Live Server** do VS Code).

---

## 📌 Versões

| Versão | Descrição |
|--------|-----------|
| Inicial | Primeira versão do site |
| `2.0.0` | Refatoração completa do site (layout Luxury Motors) |

---

## 📷 Créditos das Imagens

As imagens dos carros são carregadas do [Unsplash](https://unsplash.com/).
