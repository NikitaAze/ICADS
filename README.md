Acva Duty - дежурный Iris Chat Manager

УСТАНОВКА
Для установки мы будем использовать сайт pythonanywhere.com

1.Переходим , заполняем форму и нажимаем Register

(Под словами "вкладка X" далее по тексту, имеются в виду ссылки на этой панели)

2.Открываем вкладку Web
Кликаем на Add a new web app
В появившемся окошке next -> Flask -> Python3.8
В путь вводим /home/имя аккаунта/ICAD/start.py

3.Тыкаем на вкладку Files. В строке ниже слова Files вводим hello.py и нажимаем New file.

4.Вставляем в открывшийся редактор следующий текст и тыкаем на кнопку Run
импорт операционной системы

os.system('rm -rf ICAD') 
os.system('git clone https://github.com/elchinchel/ICAD')

5.Далее переходим во вкладку Web и нажимаем на кнопку Reload имя аккаунта.eu.pythonanywhere.com

Переходим по ссылке имяаккаунта.eu.pythonanywhere.com (ссылка над кнопкой перезагрузки)
6.Вводим данные, нажимаем Установить.

Проверяем ЛС Ириса. Если ирис ответил :
✅ Callback API сигналы успешно привязаны к вашей анкете 

Поздравляю, у тебя теперь есть дежурный. Подключиться к нужному чату можно, написав в нем команду +api

ВНИМАНИЕ! Через три месяца на бесплатном тарифе сайт отключается!
Чтобы этого не произошло, нужно как минимум раз в три месяца заходить в аккаунт и нажимать на эту кнопку (на вкладке Web под кнопкой перезагрузки)

КАК ОБНОВИТЬ
".c обновить"

Если дежурный не работает, открываем Files и создаём в любом месте файл upd.py. Вставляем в него следующий текст и тыкаем кнопочку Run:

Импорт операционной системы
os.system('cd ~/ICAD; git fetch --all; git reset --hard origin / master-beta')
