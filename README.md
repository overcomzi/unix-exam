# Установка
Вся информация по развёртыванию и установке находится в диретокрии doc в виде pdf-файлов

# Технические требования к реализаци 
Ваша задача продемонстрировать установку  систем с помощью Docker и их успешную интеграцию друг с другом.

Система управления задачами: [taiga](https://taiga.io/)

Система управления репозиториями: [gogs](https://gogs.io/)

Система непрерывной интеграции: [jenkins](https://www.jenkins.io/)


Вы должны предоставить репозиторий, включающий в себя следующие элементы:
В корне должен располагаться файл docker-compose.yml, с помощью которого необходимо осуществлять настройку системы.
Для каждого используемого средства необходимо создать каталог. В каждом из каталогов должны быть:
Dockerfile для формирования образа данного средства.
Дополнительные файлы, которые нужны для формирования образа средства.
1. Эти каталоги не должны содержать конфигурации, связанной с развёртыванием, а только со сборкой образа.
2. В корне проекта должен располагаться каталог doc, содержащий документацию о проекте.
3. В корне проекта может располагаться каталог config, в котором могут располагаться файлы конфигурации, связанные с конкретным развёртыванием системы.
4. Dockerfile могут быть написаны вами или взяты с hub.docker.com. В любом случае их структура должна быть задокументирована.
