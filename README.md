# socket-server
Лабораторная работа. Университетское задание.

Задание 1: Разработать программу клиента, которая должна:
- запрашивать у пользователя адрес программы-сервера;
- устанавливать соединение с сервером;
- передавать на сервер имя выбранного каталога;
- принимать ответ от сервера и выводить его на экран;
- закрывать соединение с сервером.

Задание 2: Разработать программу сервера, которая должна:
- ожидать запрос от программ клиентов на соединение; 
- устанавливать соединение с клиентами, при установлении соединения передавать список логических устройств клиенту; 
- принимать от клиента данные:
- если это имя каталога, передавать клиенту структуру каталога (имена файлов и подкаталогов); 
- если это имя текстового файла, передавать клиенту содержимое файла.
- закрывать соединение с клиентом при получении уведомления.
