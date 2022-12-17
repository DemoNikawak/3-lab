# Л.Р. - 3-4
# Сайт - 5 элемент

Test-case №1
Добавление товара по акции в корзину.

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. Нажать на ссылку "Акции" в навигационном меню
3. Проскролить до заголовка "Скидки и промокоды"
4. Нажать на "Скидки"
5. Найти пылесос Deerma DX700S Plus (c 2-мя фильтрами)
6. Нажать на кнопку "В корзину"
7. Во всплывающем окне нажать на кнопку "Вернуться к покупкам"

Ожидаемый результат: Появление единички возле иконки корзины в правом верхнем углу


Test-case №2
Добавление популярного телевизора в избранное.
Входные данные: пользователь зарегистрирован

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. Нажать на ссылку "Телевизоры и видео" в навигационном меню
3. Проскролить до заголовка "Популярные товары"
4. Найти телевизор LG OLED55C24LA
6. Нажать на иконку "сердце" (лайк)
7. Во всплывающем окне нажать на кнопку "Вернуться к покупкам"

Ожидаемый результат: Появление единички возле иконки лайка в правом вехнем углу


Test-case №3
Отправить запрос на получение оповещения о снижении цены на телефон.
Входные данные: пользователь зарегистрирован, в личном кабинете заполнен E-mail, товар находится в избранном

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. Нажать на ссылку "Акции" в навигационном меню
3. Проскролить до заголовка "Скидки и промокоды"
4. Нажать на "Скидки"
5. Найти пылесос Deerma DX700S Plus (c 2-мя фильтрами)
6. Нажать на иконку "колокольчик"

Ожидаемый результат: во всплывающем окне увидеть сообщение "Мы отправим Вам на E-mail сообщение, когда цена на этот товар снизится"

Тест-кейс №4
Удалить телевизор из избранного
Входные данные: товар находится в избранном

1. В правом верхнем угле найти иконку сердце с надписью "Избранное" и нажать на неё
2. Нажать на кнопку "Перейти в избранное"
3. Найти блок с "Телевизором LG OLED55C24LA"
4. Нажать на кнопку "Удалить" в нижнем левом углу

Ожидаемый результат: блок с товаром исчез и число рядом с иконкой "Избранное" в правом верхнем углу уменьшилось на единицу

Тест-кейс №5
Удалить пылесос из корзины
Входные данные: товар находится в корзине

1. В правом верхнем угле найти иконку корзины и нажать на неё
2. Найти заголовок "Моя корзина"
3. Найти "Пылесос Deerma DX700S Plus (с 2-мя фильтрами)"
4. Нажать на кнопку "Удалить"
5. Найти блок с "Телевизором LG OLED55C24LA"
6. Нажать на кнопку "Удалить" в нижнем левом углу

Ожидаемый результат: блок с товаром исчез и число рядом с иконкой "Корзина" в правом верхнем угле уменьшилось на единицу


Test-case №6
Добавление телефона в сравнение.

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. Нажать на ссылку "Смартфоны и гаджеты" в навигационном меню
3. Проскролить до заголовка "Популярные товары"
4. Найти смартфон Xiaomi Redmi 9C 2GB/32GB Aurora Green EU
6. Нажать на иконку "Сравнение"

Ожидаемый результат: Увеличение числа на единицу возле иконки "Сравнение" в правом верхнем углу

Test-case №7 
Добавление телефона в сравнение из вкладки сравнение

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. Нажать на иконку "Сравнение" в правом верхнем углу
3. Во всплывающем окне нажать "Перейти в сравнение"
4. Выбрать категорию "Смартфоны"
5. Найти заголовок "Сравнение товаров в категории "Радиотелефоны DECT""
6. Нажать на ссылку "Добавить товары" в меню слева
7. Найти блок со "Смартфон Xiaomi POCO C40 4GB/64GB Yellow EU"
8. Нажать на иконку "Сравнение"

Ожидаемый результат: Увеличение числа на единицу возле иконки "Сравнение" в правом верхнем углу

Test-case №8 
Удалить все товары из сравнения
Входные данные: в "Сравнении" есть товары

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. Нажать на иконку "Сравнение" в правом верхнем углу
3. Во всплывающем окне нажать "Перейти в сравнение"
4. Найти заголовок "Сравнение товаров в категории "Радиотелефоны DECT""
5. В левом меню найти кнопку "Очистить список"

Ожидаемый результат: Возле иконки "Сравнения" в правом верхнем углу нет числа

Test-case №9
Добавить телефон в избранное, используя поиск
Входные данные: пользователь зарегистрирован

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. Нажать на поле ввода "Поиск товара"
3. Ввести "Samsung Galaxy M32"
4. Найти "Смартфон Samsung Galaxy M32 6GB/128GB (белый)" 
5. Нажать на иконку "сердце" (лайк)
6. Во всплывающем окне нажать на кнопку "Вернуться к покупкам"

Ожидаемый результат: Появление единички возле иконки лайка в правом вехнем углу

Ожидаемый результат: Возле иконки "Избранное" в правом верхнем углу число увеличилось на 1


Test-case №10
Сделать прездаказ на смартфон
Входные данные: пользователь зарегистрирован

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. На главной странице скролим до заголовка предзаказы
3. Находим "Смартфон Huawei nova 10 (NCO-LX1) Starry Silver"
4. Нажимаем на кнопку "Оформить предзаказ"
5. Проверяем данные, показанные во всплывшем окне
6. Нажимаем кнопку оформить

Ожидаемый результат: получение сообщения "Предзаказ успешно оформлен"


Test-case №11
Подписаться на рассылку
Входные данные: пользователь зарегистрирован

Шаги тест-кейса:
1. Перейти на сайт https://5element.by/
2. На главной странице футера сайта
3. Находим "Подписаться на новости и акции"
4. Кликнуть на текстовое поле "Электронная почта"
5. Ввести электронную почту
6. Поставить галочку в чекбоксе "Даю согласие ..."
7. Нажать на кнопку подписаться

Ожидаемый результат: получение сообщения "Ваша подписка успешно создана"



