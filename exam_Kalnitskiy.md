# 1. Установка и настройка Git:
* Скачайте и установите Git с официального сайта
* Запустите установщик и следуйте инструкциям по установке
* После установки настройте основные параметры Git, такие как имя пользователя и адрес электронной почты:
<br>
#### $ git config --global user.name "Ваше имя"
#### $ git config --global user.email "ваша почта"
<br><br>

# 2. Создание репозитория
* Создайте новую директорию для проекта на вашем компьютере
* В командной строке перейдите в эту директорию
* Инициализируйте новый локальный репозиторий с помощью команды:
#### $ git init
<br><br>

# 3. Добавление файлов в репозиторий
* Поместите файлы проекта в директорию репозитория
* Добавьте файлы в индекс Git с помощью команды:
#### $ git add .
* Примечание: '.' добавляет все файлы из текущей директории в индекс. Можно также указать конкретные файлы или папки.
<br><br>

# 4. Фиксация изменений
* Фиксируйте изменения в репозитории с помощью команды:
#### $ git commit -m "Описание изменений"
* Здесь "Описание изменений" должно ясно описывать внесенные изменения.
<br><br>

# 5. Работа с удаленными репозиториями
* Создайте удаленный репозиторий на хостинг-платформе Git, такой как GitHub, GitLab или Bitbucket.
* Свяжите локальный репозиторий с удаленным репозиторием с помощью команды:
#### $ git remote add name <URL_удаленного_репозитория>
<br><br>

# 6. Отправка изменений в удаленный репозиторий
* Загрузите все локальные коммиты в удаленный репозиторий с помощью команды:
#### $ git push -u origin <ветка>
* <ветка> - это имя ветки, которую вы хотите отправить в удаленный репозиторий
* После первой отправки можно будет использовать просто git push, чтобы отправить изменения в последующий раз.
<br><br>


# 7. Получение изменений из удаленного репозитория
* Получите изменения из удаленного репозитория в локальный репозиторий с помощью команды:
#### $ git pull origin <ветка>

# 8. Ветвление и слияние изменений
* Создайте новую ветку с помощью команды:
#### $ git branch <имя_ветки>
* Переключитесь на новую ветку с помощью команды:
#### $ git checkout <имя_ветки>
* Внесите изменения в этой ветке
* Переключитесь обратно на основнуюветку (обычно "master") и выполните слияние изменений из ветки с помощью команды:
#### $ git merge <имя_ветки>
<br><br>

# 9. Отслеживание состояния репозитория
* Проверьте текущее состояние вашего репозитория с помощью команды:
#### $ git status
* Git покажет информацию о неотслеживаемых файлах, измененных файлах, ветке и другую полезную информацию.

# 10. Отправка ветки с изменениями на GitHub
* Перейдите на страницу репозитория, в котором вы хотите внести изменения
* Нажмите кнопку Fork. Это создаст копию репозитория в вашем аккаунте.
* Клонируйте репозиторий
* Создайте новую ветку
* Внесите изменения
* Создайте новый коммит
* Введите следующую команду, чтобы отправить вашу ветку с изменениями на GitHub:
#### $ git push origin <имя ветки>
* После необходимо перейти на страницу вашего форка и создать pull request


