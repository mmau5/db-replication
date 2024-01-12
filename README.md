# «Репликация и масштабирование. Часть 1» - Зябликова Анастасия

# Задание 1

В конфигурации мастер-слейв изменения данных мастера распространяются на слейв сервер. Изменения слейв сервера не будут отображаться в мастере. Таким образом мастер отвечает за изменения данных, а слейв за чтение.


В конфигурации мастер-мастер плюсом является то, что можно обеспечить удаленным пользователям одинаково быструю возможность записывать изменения в базу. Но недостаток такого варианта в том, что если пользователи одновременно внесли изменения в те же данные, непонятно чьи изменения считать окончательными и т.д. Здесь любой из серверов может использоваться как для чтения так и для записи.

# Задание 2

![1](https://github.com/mmau5/db-replication2/blob/master/Screenshot%20from%202024-01-12%2015-29-04.png)

![2](https://github.com/mmau5/db-replication2/blob/master/Screenshot%20from%202024-01-12%2015-28-33.png)

![3](https://github.com/mmau5/db-replication2/blob/master/Screenshot%20from%202024-01-12%2015-28-41.png)

![4](https://github.com/mmau5/db-replication2/blob/master/Screenshot%20from%202024-01-12%2016-07-16.png)

![5](https://github.com/mmau5/db-replication2/blob/master/Screenshot%20from%202024-01-12%2016-06-54.png)

![6](https://github.com/mmau5/db-replication2/blob/master/Screenshot%20from%202024-01-12%2017-10-09.png)

![7](https://github.com/mmau5/db-replication2/blob/master/Screenshot%20from%202024-01-12%2017-10-28.png)


