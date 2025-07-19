# Secret_Authentication
The project aims to train the autontefication of the user

## Project start
* Для запуска:
`npm i` и
`nodemon index.js`
* Cоздать базу sql, для этого можно открыть файлы queries.sql, затем добавить столбец solution-queries.sql
* Для аутентификации через google нужно в профиле google создать проект. Оттуда добавить в файл GOOGLE_CLIENT_ID и GOOGLE_CLIENT_SECRET
* Создать файл расширения и добавить:
<h6>GOOGLE_CLIENT_ID="from gmail google"<h6>
<h6>GOOGLE_CLIENT_SECRET="from gmail google"<h6>
<h6>SESSION_SECRET="text"<h6>
<h6>PG_USER="user from sql"<h6>
<h6>PG_HOST="host from sql"<h6>
<h6>PG_DATABASE="name from sql"<h6>
<h6>PG_PASSWORD="yours password"<h6>
<h6>PG_PORT="yours port"<h6>


## Useful links
* Про криптография и хеширования [cryptii](https://cryptii.com/pipes/caesar-cipher) и [encode](https://encode-decode.com/aes256-encrypt-online/)
* Проверка утечки данных по почте [haveibeenpwned](https://haveibeenpwned.com/)
* Про популярные пароли [wikipedia](https://en.wikipedia.org/wiki/List_of_the_most_common_passwords)
* Эмуляция хакера [hackertyper](https://hackertyper.net/)
* Очень нужная документация [passportjs](https://www.passportjs.org/docs/)

* Для dotenv [npmjs](https://www.npmjs.com/package/dotenv)
* gitignor for nodejs [gitignore](https://github.com/github/gitignore/blob/main/Node.gitignore)
