# Аннотация теста
Название проекта | Автосервис
:---:|---:
Рабочая версия | 1.0
Имя тестирующего| Светлаков Кирилл
Имя тестирующего |15.02.2021
 
## Тестовый пример #1:
Тестовый пример | TestCase_DeleteProduct_x
---|---
Приоритет тестирования | Средний
Заголовок/название теста | Удаление сервиса,не имеющего продаж и картинок из таблицы service 
Краткое изложение теста |   Сервис должен без ошибок удалиться из таблицы service
Этапы теста |    1.Найти услугу с названием "Светлаков Кирилл" <br> 2.Если она есть удалить из таблицы оказанных услуг (ClientService) и из таблицы услуг (service) <br> 3. Добавить тестовую услугу "Оррифшоев Бахтиёр" в таблицу service <br> 4. Вызвать метод удаления услуги <br> 5. Проверить наличие тестовой услуги в таблице service 
Тестовые данные | 
