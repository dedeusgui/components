# Exemplo de Accordion (Acordeão)

Este repositório contém um exemplo simples de um componente **Accordion**, com HTML, CSS e JavaScript puros. O objetivo é mostrar como criar um efeito de abrir/fechar seções de conteúdo ao clicar em títulos.

---

## 📌 O que é um Accordion?

O **Accordion (ou Acordeão)** é um padrão de interface onde o usuário clica em um título para revelar ou esconder o conteúdo relacionado. É muito usado para economizar espaço na tela e melhorar a organização de informações, como em FAQs (Perguntas Frequentes), menus e listas.

---

## 💻 Exemplo de Código

### HTML

```html
<div class="accordion">
  <div class="accordion-item">
    <button class="accordion-header">Seção 1</button>
    <div class="accordion-content">
      <p>Conteúdo da seção 1...</p>
    </div>
  </div>

  <div class="accordion-item">
    <button class="accordion-header">Seção 2</button>
    <div class="accordion-content">
      <p>Conteúdo da seção 2...</p>
    </div>
  </div>
</div>
