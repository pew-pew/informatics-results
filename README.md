### Установка
##### Способ первый
- Установить расширение для пользовательских скриптов из "магазина" расширений для нужного браузера:
- - для [оперы - Tampermonkey](https://addons.opera.com/ru/extensions/details/tampermonkey-beta/)
- - для [хрома - Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
- - для [файрфокса - Greasemonkey](https://addons.mozilla.org/ru/firefox/addon/greasemonkey/)
- Тык сюда -> [results.user.js](https://github.com/pew-pew/informatics-results/raw/master/results.user.js)
- Нажать "установить" (или "install")

##### Способ второй (опера и хром)
- Добавить как распакованное расширение папку "extension" из этого репозитория через менеджер расширений с функциями разработчика

### Что делает
Расставляет в таблицу результатов на сайте informatics баллы.
Берётся максимальный (по последним 5000 посылкам) балл за задачу.

Если посылки были, но ни в одной из них нет количества баллов, то результатом будет "???".