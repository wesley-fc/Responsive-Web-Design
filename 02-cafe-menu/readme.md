# Aprendizados de CSS — Projeto CafeMenu (FreeCodeCamp) ☕

Este documento contém os principais conceitos e práticas de CSS que aprendi durante a construção de um menu de café, baseado nos exercícios do FreeCodeCamp.
---

## 🧠 O que é CSS?

CSS (Cascading Style Sheets) informa ao navegador como exibir os elementos da página HTML. Podemos usar CSS para definir:

- Cores
- Fontes
- Tamanhos
- Layouts
- Alinhamentos
- Imagens de fundo
- E muito mais!

---

## ✅ Etapas do Aprendizado

### 🟩 Etapa 1: CSS Interno com `<style>`
```html
<style>
  h1 {
    text-align: center;
  }
</style>
```

### 🟩 Etapa 2: Seletor de Tipo
```css
h1 {
  color: brown;
}

h1, p {
  text-align: center;
}
```

### 🟩 Etapa 3: CSS Externo com `styles.css`
**Vantagens**:
- Organização e Manutenção
- Reutilização em várias páginas
- Melhora no desempenho via cache
- Facilidade para colaboração
- Escalabilidade

### 🟩 Etapa 4: Vinculando CSS Externo
```html
<link rel="stylesheet" href="styles.css">
```

### 🟩 Etapa 5: Responsividade
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### 🟩 Etapa 6: `<div>` para Layout

### 🟩 Etapa 7: Controlando Largura com `width`
```css
#menu {
  width: 80%;
}
```

### 🟩 Etapa 8: Comentários em CSS
```css
/* Este comentário explica o código */
```

### 🟩 Etapa 9: Tamanhos Relativos com `%`

### 🟩 Etapa 10: Centralização com `margin: auto`
```css
#menu {
  margin-left: auto;
  margin-right: auto;
}
```

### 🟩 Etapa 11: Seletor de Classe
```css
.menu {
  background-color: #fff;
}
```

```html
<div class="menu"></div>
```

### 🟩 Etapa 12: Imagem de Fundo
```css
body {
  background-image: url("cafe.jpg");
}
```

### 🟩 Etapa 13: Exibindo `<p>` na Mesma Linha
```css
p {
  display: inline-block;
}
```

### 🟩 Etapa 14: Seletores Aninhados
```css
.item p {
  display: inline-block;
}
```

### 🟩 Etapa 15: Espaçamento com `padding`
```css
.menu {
  padding: 20px;
}
```

### 🟩 Etapa 16: Largura Máxima com `max-width`
```css
.menu {
  max-width: 600px;
}
```

### 🟩 Etapa 17: Fontes com `font-family`
```css
body {
  font-family: Arial, sans-serif;
}
```

### 🟩 Etapa 18: Estilo de Fonte com `font-style`
```css
p {
  font-style: italic;
}
```

### 🟩 Etapa 19: Tamanho da Fonte com `font-size`
```css
h1 {
  font-size: 32px;
}
```

### 🟩 Etapa 20: Divisores com `<hr>`
```css
hr {
  height: 3px;
  background-color: brown;
}
```

### 🟩 Etapa 21: Bordas com `border`
```css
.box {
  border: 2px solid red;
}

.box {
  border-top: 1px dashed blue;
  border-bottom-width: 4px;
}
```

### 🟩 Etapa 22: Estilizando Links
```css
a {
  color: green;
}

a:visited {
  color: purple;
}

a:hover {
  text-decoration: underline;
}

a:active {
  color: red;
}
```

---

## 📁 Estrutura Recomendada do Projeto

```
/projeto-menu-cafe
│
├── index.html
├── styles.css
```

---

## 🚀 Conclusão

Esses fundamentos de CSS me permitiram criar um menu bonito, limpo e funcional. Essa base é essencial para qualquer pessoa desenvolvedora web que deseja construir interfaces estilosas e acessíveis.

---
