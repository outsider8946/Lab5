# Lab5
Код по своей концепции по сути является наработкой прошлой лабы. Также создается html страница с моощью верстки в tabl.php. В самом начале заранее создается база данных
в mysql (точнее database, создал только подключение, подключиться в mysql  так и не получилось работал  в vs code). Далее, при ведении данных в  html странице 
и нажатию на кнопку переходим в файл Table_fill_data.php, где подключаемся к mysql  и по данным, указаныым в site.conf (пароль и контейнер). Тут из POST берем
введенные данные и заполянем ими базу данных, после возвращаемся в tabl.php с помощью header. В  результате подклчюаемся к гугтабличке из  прошлой лабы, как делали это 
там. Заранее созаем строку названий столбцов, тк не хрнаим ее в базезе данных  и пострчоно из баззы даных списываем данные(прошу прощения за тавтологию), преобразуем в
нужный вид (массив массивов), чтобы заполнить ими таблицу. 
Линк гугл таблицы(та же самая): https://docs.google.com/spreadsheets/d/1YTrDcTAZe7oJajvY1wrubGmBSWlu1RNP2InNxCGByMQ/edit#gid=0
