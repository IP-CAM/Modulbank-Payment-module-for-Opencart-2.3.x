Платежный модуль для Opencart 2.3
=================================


### Установка на сервер


1. Перейдите в раздел "Модули/Расширения", подраздел "Установка расширений"
2. Нажмите на кнопку "Загрузить файл", выберите файл с расширением
3. Нажмите на кнопку "Продолжить". Если загрузка завершится ошибкой, то будет необходимо загрузить файлы модуля самостоятельно. Инструкция для этого ниже.
![Раздел "Установка расширений"](https://fpayments.github.io/screenshots/opencart23/extension-upload.png)
4. Зайдите в панель администратора, в раздел "Модули / Расширения", подменю также "Модули / Расширения"
5. Выберите тип расширения: "Оплата"
6. Найдите модуль с названием "Оплата через Модульбанк", и нажмите на кнопку "+" рядом с ним.
![Раздел "Активация расширения"](https://fpayments.github.io/screenshots/opencart23/extension-activate.png)

### Настройка

После установки необходимо установить основные настройки модуля:

  * Введите ID магазина и секретный ключ, которые можно узнать в личном кабинете Модульбанка
  * При необходимости включите или отключите тестовый режим
  * Убедитесь, что в настройках указана правильная ставка НДС для вашего магазина.
![Раздел "Настройки"](https://fpayments.github.io/screenshots/opencart23/settings.png)

### Ручная загрузка файлов модуля

В случае, если загрузка стандартным способом завершается ошибкой, файлы модуля можно загрузить вручную, для этого:

1. Подключитесь к серверу любым удобным способом (FTP, SFTP, и т.д.)
2. Откройте директорию на сервере, в которой у вас установлен интернет-магазин.
3. Откройте файл с модулем на локальном компьютере (это zip-архив).
4. Скопируйте содержимое папки upload в архиве модуля в корень сайта.

Дальнейшая настройка выполняется тем же способом, что при обычной установке модуля.


### Видеодемонстрация установки
![Раздел "Установка расширения Модульбанк"](https://fpayments.github.io/screenshots/opencart23/screencast.gif)
