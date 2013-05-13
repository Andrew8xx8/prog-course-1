
# Задание 9

Продолжаем заниматься ресторанным бизнесом. Новое задание основывается на коде, который уже написан в рамках предыдущего задания.

С помощью PaaS-проекта [Parse](https://www.parse.com/docs/js_guide) (Platform as a Service) необходимо сделать так, чтобы при перезагрузке страницы пользователем данные из ресторанов оставались в том же состоянии, что и до перезагрузки. Это потребует общения с сервером Parse при загрузке страницы, и сохранение объектов (моделей ресторанов, моделей посетителей) при их изменении.

В проекте Parse есть два уровня API. Один — уровня JavaScript библиотек. Другой — чистый REST. Можно использовать любой, но, в идеале, надо будет попробовать оба.

Подключение REST-серверной функциональности к моделям, сделанным в предыдущем задании, нужно делать в районе метода `.save()` модели.
