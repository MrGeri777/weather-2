В папке js присутствует date.pic.js это скачана с интернета маленькая библиотека которая формирует дату по заданному формату(думаю что это не критично).</br>
</br>
Данные об погоде берутся с сайта wunderground.com</br>
</br>
В index.html нужно задавать в ручную город и регион(страну)(из файла citys.txt), потому что API wunderground не предоставляет данные об доступных, города в выше упомянутом файле были взяты из форума.
</br>
Данные об выбранном городе храниться в LocalStorage.</br>
</br>
UPD:</br>
В папке dist лежат исходники всего кода.</br>
В папке public лежит версия с минимизированным кодом.</br>
</br>
Пофиксил запуск только через сервер.</br>
Добавил вкладки(today, tommorow, select date).</br>
