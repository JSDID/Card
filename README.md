# Card 

## Описание

Этот проект демонстрирует реализацию карточки с использованием методологии БЭМ, семантической разметки и flexbox. В проекте нет сторонних библиотек, только чистый HTML и CSS.

## Структура файлов

- `card.html` — основной HTML-файл с примером карточки
- `styles.css` — стили для карточки, включая reset и flexbox

## Особенности

- **БЭМ**: Все классы оформлены по методологии БЭМ (`product-card`, `product-card__image`, `product-card__overlay` и т.д.)
- **Семантика**: Используются `<main>`, `<section>`, `<article>`, заголовки по смыслу
- **Flexbox**: Для выравнивания карточек и внутренних элементов
- **Reset-стили**: Убраны все стандартные отступы и бордеры

## Как использовать

1. Откройте файл `card.html` в браузере.
2. При необходимости продублируйте блок `<article class="product-card">...</article>` для отображения нескольких карточек.
3. Для изменения содержимого карточки — отредактируйте текст и изображения в HTML.

## Cтруктура карточки

```html
<main class="product-cards">
  <section class="product-cards__list">
    <article class="product-card">
      <div class="product-card__image-wrapper">
        <img class="product-card__image" src="https://picsum.photos/300" alt="Пример товара">
        <div class="product-card__overlay">
          <h1 class="product-card__title">Название товара</h1>
          <p class="product-card__short-desc">Краткое описание товара...</p>
        </div>
      </div>
    </article>
  </section>
</main>
```

## Лицензия

Свободно для использования в учебных и демонстрационных целях.
