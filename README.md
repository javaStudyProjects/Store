# Store


Описание: Магазин является сервисом, предоставляющим услуги продажи компакт-дисков. Содержит 3 страницы:

"Main" (содержит статическую информацию)

"Catalogue" (содержит список компакт-дисков для продажи)

"Shopping Cart" (содержит список выбранных для покупки пользователем компакт-дисков)

Header и Меню статические. Перегружается только основной контент. Выбранное меню остается выделенным. Под описанием выводится последние 5 новинок компакт-дисков (по одному из каждого жанра).

Страница "Catalogue" содержит список компакт-дисков. Блок фильтрации: Блок фильтрации содержит 2 связанных combobox (select), в первом содержатся Типы дисков, во втором – Жанры, соответствующие выбранному Типу.

Жанры заполняються без перезагрузки страницы. Фильтры в таблице: По типу – выпадающий список. По жанру – выпадающий список. Название – по введенному значению Кроме того, состояние фильтров сохраняеться после осуществления поиска.

Список дисков содержит таблицу, содержащую список дисков из базы данных. Каждой строке соответсвует checkbox. Выбранные диски можно "положить в корзину" (сохранить в сессии).

Цвет фона изменяется с помощью выпадающего списка и выбранный цвет сохраняется при переходе на другую страницу.

Страница "Shopping Cart" содержит список компакт-дисков, положенных в корзину.Также есть возможность удаления определенного компакт-диска.
