
#Electronic-school
##1. Скачивание
   Чтобы скачать проект, запустите команду `git clone https://github.com/UtelkhanAzamat/Electronic-school.git` в консоли, в удобной вам директории.
##2. Настройка
   После скачивания, нужно настроить несколько вещей перед запуском приложения.
###2.1  Настройка базы данных.
   В файле *application.properties* нужно прописать ващи настройки базы данных.\
      Открываем файл конфигурации application.properties\
         1. Измените название базы данных(если у вас другой порт,указажите его).\
         2. Измените имя пользователя, с которым вы входите в базу данных.\
         3. Измените пароль от базы данных.\
         4. Чтобы инициализировать или повторно извлечь тестовые данные, установите значение на true (после первого запуска можно установить на false).\
         <img src="C:\Users\Myskill.PC\Downloads\тестовое задание\ElectronicSchool\server\e-school\db.png"/>
###2.2  Настройка клиентской части приложения.
  Перейдите в каталог с клиентской стороны приложения.\
      Установка необходимых модулей:\
         1. Откройте командную строку.\
         2. И затем выполните команду ``npm install``, которая установит все необходимые модули.
##3. Запуск
   Запускаем server и client по отдельности:\
      1. Запустите команду `npm start` на клиентской сторонe приложения.\
      2. Запустите джава приложение.