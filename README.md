# bcomp-parser
Парсер команд БЭВМ. Переводит код команды в мнемонику и наименование (а еще адресацию выводит). 

Скрипт написан **для проверки**. Не нужно на 100% полагаться на него.

_А ещё числа в мнемонике написаны по-разному, но все в шестнадцатеричной системе. В презентациях по-разному, поэтому я не знаю, как лучше оставить. Исправляйте, кому как больше нравится._

**Добавлена поддержка команд для 4 лабы**

6.04.2020: теперь парсер не ломается на некорректных кодах, а просто сообщает, что это переменная/константа. Однако он до сих пор по умолчанию распознает все коды как команды.

Команды ввода-вывода, прерывание не поддерживаются.

Как использовать:
1. В файл input.txt внести построчно коды (без адресов ячеек)
2. Запустить (python main.py в командной строке или запустить start.bat в Windows)

TODO: 
1. Все остальное для следующих лаб.
2. Экспорт в какой-нибудь табличный формат, чтобы удобно было в отчет вставлять
3. Запускалки для мака и линукса (я сам без понятия, как там это работает)
