## Админ панель Cerberus
Данная админ панель разработана для работы с restapi бота Cerberus.

Для её локального запуска, сборки редактирования подготовлены 3 bash скрипта, а точнее:

 - install.sh
 - build.sh
 - start.sh

Разберём их по порядку:

**install.sh** нам понадобится для установки всего окружения, а точнее для подгрузки node modules, установки js обфускатора (для продакшина) , итд. Нам нужен установленный npm для запуска данного скрипта!!! Ибо весь проект построен на nodejs !!!

**build.sh** сборка продакшин билда и его обфускация. Билд складывается в директорию /build

**start.sh** запуск npm сервера с панелью на localhost:3000 !


Все вопросы знаете куда задавать и писать по поводу панели. Если что-то меняете, то проверьте 10 раз, а потом ток в master делайте коммит))




This admin panel is designed to work with Cerberus restapi bot.

To run it locally, edit assembly, 3 bash scripts have been prepared, to be exact:

    install.sh
    build.sh
    start.sh

Let's take them in order:

we need install.sh to install the entire environment, or rather, to load node modules, install the js obfuscator (for production), etc. We need npm installed to run this script!!! For the whole project is built on nodejs !!!

build.sh assembly of the production build and its obfuscation. The build is added to the /build directory

start.sh start npm server with panel on localhost:3000 !

All questions know where to ask and write about the panel. If you change something, then check it 10 times, and then make a commit in master))
