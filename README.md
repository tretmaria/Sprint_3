# Sprint_3
Описание: нужно протестировать API учебного сервиса Яндекс.Самокат. Его документация: qa-scooter.praktikum-services.ru/docs/.

Протестировать ручки:
Создание курьера
Проверить:
курьера можно создать;
нельзя создать двух одинаковых курьеров;
чтобы создать курьера, нужно передать в ручку все обязательные поля;
запрос возвращает правильный код ответа;
успешный запрос возвращает ok: true;
если одного из полей нет, запрос возвращает ошибку;
если создать пользователя с логином, который уже есть, возвращается ошибка.

Логин курьера
Проверить:
курьер может авторизоваться;
для авторизации нужно передать все обязательные поля;
система вернёт ошибку, если неправильно указать логин или пароль;
если какого-то поля нет, запрос возвращает ошибку;
если авторизоваться под несуществующим пользователем, запрос возвращает ошибку;
успешный запрос возвращает id.

Создание заказа
Проверить, что когда создаёшь заказ:
можно указать один из цветов — BLACK или GREY;
можно указать оба цвета;
можно совсем не указывать цвет;
тело ответа содержит track.
Чтобы протестировать создание заказа, нужно использовать параметризацию.

Список заказов
Проверить, что в тело ответа возвращается список заказов.

Сгенерировать отчёт Allure
