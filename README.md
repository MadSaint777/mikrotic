block port scanners  -  Создает правила блокирующее ip адрес любителей сканировать порты.

-----------------------------------------------------------------------------------------
Create backup to email  -  Создает бэкап и отправляет на почту

:local smtpserv [:resolve "smtp.gmail.com"]; -указываем smtp сервер
:local Eaccount "from@gmail.com"; -указываем почту от кого отправляем бэкап
:local Eaccount2 "to@gmail.com"; -указываем почту кто получает бэкап
:local pass "P@$$WORD"; -указываем пароль от почты

-----------------------------------------------------------------------------------------
ping knocking to winbox  -  Создает возможность добавить с помощью пинга ваш ip в список разрешенных Winbox_Wan

нужно пропинговать двумя пакетами размером по 10, а после этого двумя пакетами по 20. После этой операции появится доступ Winbox на один час к устройству.

8.8.8.8 для примера!
Через командную строку windows.
ping 8.8.8.8 -n 2 -l 10
ping 8.8.8.8 -n 2 -l 20

----------------------------------------------------------------------------------------
telegram bot for RouterOS  -  Управление RouterOS с помощью бота Telegram


В скрипте надо указать ваш botID и myChatID

:global botID "bot5******7:AAG***********************aIpo";
:global myChatID "-10*************00";
