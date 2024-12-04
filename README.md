# Лабораторная работа №5. Хранение данных. Настройки и внешние файлы.
* Выполнила: Зинченко Анна
* Язык программирования: Java

# Что делает приложение?
Этот проект демонстрирует простой пример хранения данных, настройку и внешние файлы в Android-приложении. 
Чтобы запустить проект можно прочитать ["Как запустить"](#как-запустить)

# Функциональность:
* MainActivity:
    При запуске приложения у пользователя появляется инструкция с выбором "Больше не показывать".
  <div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024-12-04-10-29-58-111_com.example.laba5.jpg" width="200" />
</div>
    На этом экране находятся кнопки "Загрузить", "Смотреть", "Удалить".
<div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024-12-04-10-30-07-227_com.example.laba5.jpg" width="200" />
</div>
   После успешной загрузки файла отображается уведомление о завершении загрузки, а кнопки "Смотреть" и "Удалить" становятся активными.
<div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024-12-04-10-33-12-901_com.example.laba5.jpg" width="200" />
</div>
   Проверка успешной загрузки файла в файловом менеджере.
<div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024_12_04_10_33_51_736_com_mi_android_globalFileexplorer.jpg" width="200" />
</div>
   Нажатие на кнопку "Смотреть" открывает файл в установленном на устройстве PDF-просмотрщике.
<div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024-12-04-10-33-28-120_com.mi.globalbrowser.jpg" width="200" />
</div>
   Нажатие на кнопку "Удалить" отображает подтверждение удаления, после чего файл удаляется.
<div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024-12-04-10-34-03-760_com.example.laba5.jpg" width="200" />
</div>
<div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024_12_04_10_34_08_239_com_mi_android_globalFileexplorer.jpg" width="200" />
</div>
  Если файл не найден на сервере, приложение выводит соответствующее уведомление.
<div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024-12-04-10-34-16-005_com.example.laba5.jpg" width="200" />
</div>
При отсутствии интернет-подключения приложение отображает уведомление об отсутствии соединения.
<div align="left">
  <img src="https://github.com/domosedochka/Laba5/blob/main/Screenshot_2024-12-04-10-34-43-193_com.example.laba5.jpg" width="200" />
</div>

# Как запустить
1. Загрузка или клонирование репозитория:
* Скачайте файлы проекта (ZIP-архив) и разархивируйте их в удобную папку или клонируйте репозиторий с помощью команды git clone [URL репозитория].

2. Открытие проекта в Android Studio:
* Откройте Android Studio.
* В главном окне выберите "Open an existing Android Studio project".
* Найдите папку, в которую вы скачали или клонировали проект, и выберите файл build.gradle.

3. Запуск приложения:
* В Android Studio, нажмите кнопку "Run" (зеленый треугольник) на панели инструментов.
* Выберите эмулятор или подключенное Android-устройство, на котором вы хотите запустить приложение.
* Дождитесь завершения сборки и запуска приложения.
