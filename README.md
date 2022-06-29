# Testing demo_qa_guru pages

# Установка

Создайте отдельную директорию на локальном компьютере
Скачайте все файлы которые расположены в директории
git clone https://github.com/yavv951/ui_test.git
Откройте проект
Установите все пакеты, которые указаны в файле requirements.txt
pip install -r /path/to/requirements.txt

# Описание проекта

- Разработан автотест на заполнение и отправку формы по адресу https://demoqa.com/automation-practice-form 
включающий шаги: 
1. Заполнить форму регистрации;
2. Проверить,что заполненные поля отобразились в форме регистрациию;
3. Редактируем все поля во второй строке;
4. Проверяем, что поля отредактированы;
5. Удаляем третье поле.

- Реализован автотест на таблицу по адресу https://demoqa.com/webtables включающий шаги: 
1. добавить новую четвертую строку; 
2. отредактировать все поля во второй строке; 
3. удалить третью строку.