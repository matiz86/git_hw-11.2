
Домашнее задание к занятию 11.2. «Кеширование Redis/memcached» - "Skopkin Ilya"

Задание 1. Кеширование
Приведите примеры проблем, которые может решить кеширование.

Приведите ответ в свободной форме.

Кэширование - это перемещение части данных в оперативную память, делается это для того, чтобы "за минимальные деньги" получить максимум производительности. В кэш могут помещаться данные которые чаще всего запрашивают из системы (это может быть например очень тяжелый запрос к базе данных), мы можем отправлять пользователям закэшированные данные т.к. это в разы быстрее чем постоянно обращаться к БД. + Если множество пользователей запрашивают одни и те же данные - мы можем отправлять пользователям одни и те-же данные тем самым мы уменьшаем нагрузку на базу данных.

Задание 2. Memcached
Установите и запустите memcached.

Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.

![alt text](https://github.com/matiz86/git_hw-11.2/blob/main/Screenshot_2.png

Задание 3. Удаление по TTL в Memcached
Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.

![alt text](https://github.com/matiz86/git_hw-11.2/blob/main/Screenshot_1.jpg

Задание 4. Запись данных в Redis
Запишите в Redis несколько ключей с любыми именами и значениями.

Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.

![alt text](https://github.com/matiz86/git_hw-11.2/blob/main/Screenshot_3.jpg
