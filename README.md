# RichPresence
RichPresence with Assets, timestamps, party, state, details...

# LICENSE
Данный репозиторий выложен под лицезнией `MIT`, не стесняйтесь брать из него части кода или форкать его, если вы думаете что можете помочь улучшить данный гит, то отправляйте нам `PULL REQUEST'S`, мы расмотрим их, так-же вы можете работать с нами в нашей организации.
# Установка
## Первый этап
* Для установки в Windows и MacOS X заходим на сайт https://nodejs.org и скачиваем последню весию (последнюю не обязательно, но желательно. Также лучше новичкам устанавливать LTS версию)
* Для установки в Linux нам надо добавить репозиторий.
Для этого заходим в терминал и пишем:
$ sudo apt-add-repository ppa:chris-lea/node.js
Если не получилось, написал ошибку, тогда пишем вместо этой команды эту:
$ sudo add-apt-repository ppa:chris-lea/node.js
Далее пишем (все):
$ sudo apt-get update
или
$ sudo apt update
Теперь пишем команду:
$ sudo apt-get install nodejs
Готово!
## Второй этап
Второй этап установки уже ничем не отличается от установленной ОС, будь это Windows, MacOs X или Linux, кроме некоторых моментов.
Отправляемся в командную строку, есть 2 варианта:
1 вариант:
В Linux жмём правой кнопкой мышки в любое свободное пространство файлового менеджера (при этом вы должны находиться в директории со скриптом + не все файловые менеджеры оснащены этим функционалом) и жмёте `открыть в терминале`.
В Windows также, но с зажатой клавишей Shiht и там функция называется `Открыть в командной строке`
В MacOS X скоро будет...
2 вариант:
В Linux е и Windows заходим в командную строку и пишем:
$ cd ваша_директория/
В MacOS X тоже пока неизвестно...

Теперь пишем:
$ npm i discord.js
Готово!
# Запуск
В командной строке пишем:
$ node .
