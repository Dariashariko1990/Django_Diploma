# Дипломный проект по курсу «Django: создание функциональных веб-приложений»

Прототип сайта интернет-магазина: клиентская часть сервиса и интерфейс администрирования.


## Описание клиентской части


Реализовано:

* Главная страница со статьями о подборке товаров (отсортированы по дате создания статьи)
  и перечислением этих товаров.
* Страница категории и подкатегории товара со списком товаров с пагинацией.
* Страница товара с подробным описанием.
    
Меню:

* Ссылка на главную страницу.
* Ссылки на разделы (разделы могут иметь иерархию).
* Ссылка на корзину.
* Кнопка входа/выхода в зависимости от статуса авторизации. 
* Для входа используется аутентификация по email'у. Используется расширение backend'a авторизации.

Еще не реализовано:

* Просмотр товара и добавление в корзину (рядом с каждым товаром должна быть кнопка добавления в корзину).
* Корзина со списком выбранных товаров, привязанных к пользователю.
* Кнопка заказа должна создавать заказ и очищать корзину.


## Интерфейс администратора

Реализовано:

* Редактирование разделов.
* Редактирование товаров.
* Редактирование статей на главной странице и привязывание к ним товаров,
  которые должны отображаться после нее.

Еще не реализовано:
* Просмотр списка заказов пользователей, отсортированных по дате создания,
    с указанием пользователя и количества товаров.
* Страница детализации заказа с просмотром списка заказанных товаров.


* [Главная страница](./resources/index.html).
* [Страница раздела](./resources/smartphones.html).
* [Страница незаполненного раздела](./resources/empty_section.html).
* [Страница товара](./resources/phone.html).
* [Страница корзины](./resources/cart.html).
* [Страница входа](./resources/login.html).

