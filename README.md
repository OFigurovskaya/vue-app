# vue-app
Пэт-проект интернет-магазин на Vue 2

Деплой:
https://ofigurovskaya.github.io/vue-app/index.html#/

Функционал
1. Каталог
При загрузке страницы уходит запрос на сервер за каталогом товаров.
В карточках можно фильтровать товары по:
- цене (от и до)
- категории
- цвету
Страниы листаются, кнопки "применить" и "сбросить" рабочие
При переходе на ктовар открывается страница с описанием товара.
2. Страница товара
Необходимое количество товара можно добавлять в корзину.
Реализовано меню "хлебные крошки".
Товар добавляется в корзину с задержкой, в иконке корзины обновляется количество.
Пока товар добавляется кнопка "в корзину" не активна во избежание многократного нажимания пользователем.
При клике на иконку корзины осуществляется переход в корзину
3. Корзина
Содержимое корзины сохраняется в LocalStorage
В корзине можно редактировать количество товаров, удалять товары. Сумма соответственно пересчитывается.
При клике на кнопку "оформить заказ" осуществляется переход на страницу заказа.
4. Страница оформления заказа
Содержит форму для заполнения пользователем.
Можно выбрать вариант доставки, сумма пересчитывается с учетов выбранного варианта.
При отправке формы запускается прелоадер и осуществляется проверка корректностим внесенных данных.
Если данные не внесены или внесены некорректно - выводится сообщение.
Если в корзине нет товаров - выводится сообщение об этоь

При попытке перехода на несуществующую страницу выводится сообщение о том, что страница не найдена.
