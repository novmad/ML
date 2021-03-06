# Определение перспективного тарифа для телеком компании

В компании оператора сотовой связи клиентам предлагается два тарифных плана: «Смарт» и «Ультра». Требуется определить, какой тариф выгоднее. Доступны данные 500 пользователей за 2018 год.

## 1. Описание тарифов

**Тариф «Смарт»**
* Ежемесячная плата: 550 рублей
* Включено 500 минут разговора, 50 сообщений и 15 Гб интернет-трафика
* Стоимость услуг сверх тарифного пакета:
* Минута разговора: 3 рубля
* Сообщение: 3 рубля
* 1 Гб интернет-трафика: 200 рублей

**Тариф «Ультра»**
* Ежемесячная плата: 1950 рублей
* Включено 3000 минут разговора, 1000 сообщений и 30 Гб интернет-трафика
* Стоимость услуг сверх тарифного пакета:
* Минута разговора: 1 рубль
* Сообщение: 1 рубль
* 1 Гб интернет-трафика: 150 рублей

*Замечаие.* Компания всегда округляет вверх значения минут и мегабайтов (разговор, длительностью 1 секунда, засчитывается как 1 минута).

## 2. Описание данных

**Информация о пользователях**
* _user_id_ — уникальный идентификатор пользователя
* _first_name_ — имя пользователя
* _last_name_ — фамилия пользователя
* _age_ — возраст пользователя (годы)
* _reg_date_ — дата подключения тарифа (день, месяц, год)
* _churn_date_ — дата прекращения пользования тарифом (если значение пропущено, то тариф ещё действовал на момент выгрузки данных)
* _city_ — город проживания пользователя

