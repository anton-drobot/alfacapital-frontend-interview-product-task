# Задача по вёрстке для собеседования на позицию фронтенд-разработчика в компанию Альфа-Капитал

Нужно сверстать карточку товара по макету.

При вёрстке важно учесть, чтобы кнопка имела тег `button`, которая теоретически бы открывала модальное окно с формой регистрации.

### Дизайн:

![Дизайн](https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/design.png)

### Дизайн с указанием размеров:

![Дизайн с указанием размеров](https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/design_sizes.png)

#### Размеры:

- Размер картинки продукта: `374x228px`
- Размер картинки эмитента: `34x34px`
- Ширина блока с текстом: `415px`
- Высота кнопки: `52px`
- Скругление карточки: `16px`
- Скругление картинки: `8px`
- Скругление кнопки: `8px`

#### Шрифты

- Размер основного текста: `14px`
- Интерлиньяж основного текста: `20px`
- Размер заголовка и доходности: `22px`
- Интерлиньяж заголовка и доходности: `28px`
- Размер кнопки: `17px`

#### Цвета

- Фон карточки: `#fff`
- Основной цвет текста: `#19191a`
- Цвет текста описания продукта: `#8e9299`
- Цвет доходности: `#3ba659`
- Цвет рамки у кнопки: `#e52f22`
- Цвет фона у кнопки при наведении: `rgba(199, 45, 32, 0.1)`

#### Изображения

- Продукт: `https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/src/product.png`
- Лукоил: `https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/src/e_lukoil.png`
- Газпром: `https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/src/e_gazprom.png`
- Сбер: `https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/src/e_sber.jpg`

#### SVG-иконка

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
    <path d="M12.41 15.285a.5.5 0 01-.821 0L7.347 9.163a.5.5 0 01.411-.785h8.483a.5.5 0 01.411.785l-4.241 6.122z"/>
</svg>
```

## Шаблон для ноутбука

```html
<div id="write-here">

</div>

<div id="task-description">
    <p>Нужно сверстать карточку товара по макету.</p>
    <p>При вёрстке важно учесть, чтобы кнопка имела тег <code>button</code>, которая теоретически бы открывала модальное окно с формой регистрации.</p>

    <h3>Дизайн:</h3>
    <p>
        <img src="https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/design.png">
    </p>

    <h3>Дизайн с указанием размеров:</h3>
    <p>
        <img src="https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/design_sizes.png">
    </p>

    <h4>Размеры:</h4>
    <ul>
        <li>Размер картинки продукта: <code>374x228px</code></li>
        <li>Размер картинки эмитента: <code>34x34px</code></li>
        <li>Ширина блока с текстом: <code>415px</code></li>
        <li>Высота кнопки: <code>52px</code></li>
        <li>Скругление карточки: <code>16px</code></li>
        <li>Скругление картинки: <code>8px</code></li>
        <li>Скругление кнопки: <code>8px</code></li>
    </ul>

    <h4>Шрифты</h4>
    <ul>
        <li>Размер основного текста: <code>14px</code></li>
        <li>Интерлиньяж основного текста: <code>20px</code></li>
        <li>Размер заголовка и доходности: <code>22px</code></li>
        <li>Интерлиньяж заголовка и доходности: <code>28px</code></li>
        <li>Размер кнопки: <code>17px</code></li>
    </ul>

    <h4>Цвета</h4>
    <ul>
        <li>Фон карточки: <code>#fff</code></li>
        <li>Основной цвет текста: <code>#19191a</code></li>
        <li>Цвет текста описания продукта: <code>#8e9299</code></li>
        <li>Цвет доходности: <code>#3ba659</code></li>
        <li>Цвет рамки у кнопки: <code>#e52f22</code></li>
        <li>Цвет фона у кнопки при наведении: <code>rgba(199, 45, 32, 0.1)</code></li>
    </ul>

    <h4>Изображения</h4>
    <ul>
        <li>Продукт: <code>https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/src/product.png</code></li>
        <li>Лукоил: <code>https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/src/e_lukoil.png</code></li>
        <li>Газпром: <code>https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/src/e_gazprom.png</code></li>
        <li>Сбер: <code>https://raw.githubusercontent.com/anton-drobot/alfacapital-frontend-interview-product-task/master/src/e_sber.jpg</code></li>
    </ul>

    <h4>SVG-иконка</h4>
    <pre>&lt;svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"&gt;
    &lt;path d="M12.41 15.285a.5.5 0 01-.821 0L7.347 9.163a.5.5 0 01.411-.785h8.483a.5.5 0 01.411.785l-4.241 6.122z"/&gt;
&lt;/svg&gt;</pre>
</div>

<style>
    #task-description {
        font-family: Arial;
    }

    #task-description h3,
    #task-description h4 {
        margin: 2em 0 1em 0;
    }

    #task-description pre,
    #task-description code {
        padding: 2px;
        border-radius: 4px;
        background-color: #efefef;
    }
</style>
```
