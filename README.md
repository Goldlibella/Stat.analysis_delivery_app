# Приложение доставки
Команда внедрила в приложение умную систему рекомендации товаров – предполагается, что такая система поможет пользователям эффективнее работать с приложением и лучше находить необходимые товары.

# Задача: 
чтобы проверить эффективность системы рекомендаций, был проведен АБ-тест. В группе 1 оказались пользователи с новой системой рекомендаций, в группе 0 пользователи со старой версией приложения, где нет рекомендации товаров. Необходимо оценить, смогла ли новая система рекомендаций принести пользу бизнесу и пользователям приложения, и определить, стоит ли включать новую систему рекомендаций на всех пользователей.

# Данные:
ab_users_data – история заказов пользователей, в этой таблице есть информация о том, какие заказы создавали и отменяли пользователи
ab_orders – подробная информация о составе заказа, тут для каждого заказа есть список id тех продуктов, которые были включены в заказ
ab_products – подробная информация о продуктах, их название и стоимость

# Процесс расписан в файле Delivery_app.ipynb.

# Выводы: 
исходя из того, что в группе с новой системой рекомендаций количество заказов значительно возросло, среднее количество заказываемых товаров увеличилось на 6 единиц, а суммарная стоимость заказов увеличилась более чем на 600 единиц, рекомендуем включить новую систему рекомендаций на всех пользователей.
