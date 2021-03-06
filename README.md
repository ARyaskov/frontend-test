# Установка проекта

P.S. - весь рабочий процесс происходит в директории `client`.

``` bash
## Установка зависимостей
npm install

## Запуск сервера с hot reload на localhost:8080
npm run dev

```

# Техническое задание

## Верстка

1. Необходимо сверстать блоки `product-preview` и `product-story`.
[PSD макет](https://goo.gl/OesXm3). Название блоков указано как название группы 
слоев в psd. Превью целевых блоков можно увидеть в директории `blocks-preview`.

2. Переделать верстку, чтобы страница была "резиновая".

   Максимальная ширина контента - `1280px`
   Минимальная ширина контента - `1024px`

   Фоны тянутся на всю ширину страницы.

   Изображения в блоке `product-social` не переносятся, а пропорционально
   уменьшаются. Превью данного блока можно увидеть в директории `blocks-preview`.

3. Необходимо сверстать корзину [PSD макет](https://goo.gl/RgvJGo).

## JavaScript

1. Необходимо сделать шаринги страницы в социальные сети.

2. Реализовать валидацию формы подтверждения в корзине 

   ##### Обязательные поля:
   * First name
   * Second name
   * Address
   * Postcode
   * City
   * Email
   * Phone
   * Terms of use and privacy

   Delivery mode изначально предустановлен

3. Реализовать подсчет стоимости заказа в корзине

   При уменьшении количества товара до 0 - выводить диалоговое окно, в котором
   уведомлять о удалении товара из корзины. Если пользователь согласен - удаляем,
   иначе оставляем товар без изменений.
   При изменении количества товаров происходит пересчет subtotal.

### Поддержка браузерами

- IE9+
- Edge 12+
- Chrome 52+
- Chrome Mobile 52+
- Mozilla Firefox 50+
- Safari 9+
- iOS Safari 9+
- Opera 42+

### Примечания

1. При верстке необходимо придерживаться структуры проекта

2. Использовать стек технологий проекта

## Рабочий процесс

Для начала выполнения тестового задания необходимо сделать fork репозитория.

Каждый пункт разделов "Верстка" и "Javascript" необходимо выполнять в новой
ветке в следующем формате `feature/task-name`.

После выполнения задания необходимо создать Pull/merge request для последующей
проверки. При создании Pull request'а в качестве base указать ветку,
соответствующую вашему имени пользователя github. 

[Гайд по оформлению commit'ов](https://gist.github.com/stephenparish/9941e89d80e2bc58a153#format-of-the-commit-message)

## Обратная связь

В случае, если возникли проблемы со сборщиком проекта - пишите описание проблем
в Issue репозитория.
