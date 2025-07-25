# 📘 Lista de Exercícios 3 – Desenvolvimento Web Básico

Este repositório contém uma série de exercícios práticos para reforçar os conhecimentos iniciais em HTML e CSS.

---

## 🧱 1. Estrutura Semântica – `index.html`

Crie um arquivo `index.html` com a seguinte estrutura utilizando **tags semânticas**:

- `<header>` contendo:
  - Um `<h1>` com o título da página.
  - Um `<p>` com um parágrafo introdutório.

- `<main>` dividido em duas seções:
  - Seção **Missão** com `<h2>` e `<p>`.
  - Seção **Visão** com `<h2>` e `<p>`.

- `<footer>` contendo um `<p>` com os direitos autorais (copyright).

---

## 📋 2. Listas e Navegação – `listas.html`

Crie um arquivo `listas.html` com os seguintes elementos:

- Uma **lista não ordenada** (`<ul>`) com **cinco hobbies pessoais**, cada um em um `<li>`.
- Uma **lista ordenada** (`<ol>`) com o passo a passo de uma **receita simples**, cada passo em um `<li>`.
- Ao final, adicione uma seção de **navegação** (`<nav>`) com **três links externos**, usando a sintaxe:  
  ```html
  <a href="URL_DO_SITE" target="_blank">Nome do Site</a>
  ```

---

## 📝 3. Formulário de Feedback – `feedback.html`

Crie um formulário contendo os seguintes campos:

- Nome  
- E-mail  
- Endereço completo  
- Tipo de feedback (pode ser um `<select>` ou `<input type="radio">`)  
- Campo para escrever o feedback  
- Botão de envio

---

## 🎨 4. CSS Básico e Box Model – `styles.css`

Crie e vincule um arquivo `styles.css` ao `index.html`. Nele:

- Defina `background-color` e `color` para as tags: `<header>`, `<main>` e `<footer>`.
- Aplique `margin`, `padding` e `border` em cada uma dessas seções para evidenciar seus contornos.

---

## 🎯 5. Seletores e Propriedades – `styles.css`

Ainda no mesmo `styles.css`, adicione:

- Estilo para **todas as tags `<h2>`**:
  - `font-size` aumentada
  - `text-decoration: underline`

- Uma classe `.destaque`:
  - `font-style: italic`
  - `background-color` suave

- Um ID `#importante`:
  - Adiciona uma `border-top` mais espessa em um parágrafo específico

---

## 🖼️ 6. Grid e Flexbox – Galeria Responsiva

Crie uma **galeria com 8 imagens** e respectivas **legendas**, organizadas assim:

- Use **CSS Grid** para dispor as imagens.
- Envolva a galeria em um **container com Flexbox** para centralização e quebra automática de linha em telas menores.
- Utilize **media queries** para ajustar o número de colunas conforme o tamanho da tela.

---

## 🍔 7. Menu Hamburger Responsivo

Implemente um **menu “hamburger”** que:

- Aparece **somente** em telas com **largura ≤ 600px**
- **Oculta** o menu padrão
- Permite **abrir/fechar** o menu ao ser clicado
