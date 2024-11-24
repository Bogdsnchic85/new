# Операционная система Windows 10
# IDE: Visual Studio Code
# Установка PostgreSQL: Docker контейнер
# Основные команды:
- Клонирование репозитория: git clone <URL-репозитория>
- Проверка статуса:git status
- Добавление изменений в индекс:
git add <файл>  ( для добавления конкретного файла )
git add .       ( для добавления всех изменений )
- Фиксация изменений:git commit -m "Сообщение о коммите"
- Отправка изменений в удаленный репозиторий: git push origin <ветка>
- Получение изменений из удаленного репозитория: git pull origin <ветка>
- Создание новой ветки: git checkout -b <имя-ветки>
- Переключение на существующую ветку: git checkout <имя-ветки>
- Слияние веток
- Слияние изменений из одной ветки в текущую: git merge <имя-ветки>
- Удаление ветки :
-  Локальная ветка: git branch -d <имя-ветки>
- Удаление удаленной ветки: git push origin --delete <имя-ветки>
