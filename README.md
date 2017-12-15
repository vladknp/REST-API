## Install and setup
### Install MongoDB for Windows
- Скачать `mongodb` с сайта https://www.mongodb.com
- Добавить путь к `bin` mongodb в `Переменные среды`, к примеру `C:\mongodb\bin`. 
- Создать файл `mongod.cfg` в корне пути, пример `C:\mongodb\mongod.cfg`.
- В файл `mongod.cfg` добавить путь к файлу логирования `logpath=C:\mongodb\log\mongo.log` и путь к каталогу с базами данных `dbpath=C:\databases`.
- Запустить коммандой `mongod.exe`. По умолчанию испольузется `port 27017`
- Создать базу данных `use keepnotes`. Если база существует подключится к ней иначе создать с именем `keepnotes`.

### Install dev/dependencies and run project
- `git clone https://github.com/vladknp/REST-API.git` 
- `cd REST-API
- `npm install` or `yarn`
- `npm run dev` or `yarn dev`
