# Шпаргалка по Git

## Создание локального репозитория Git:

* Инициализация нового репозитория:
```git init```

* Добавление файлов к коммиту:
```git add <файл1> <файл2>```

* Создание коммита:
```git commit -m "Ваш комментарий"```
<br>


## Работа с удаленным репозиторием (GitHub):

* Добавление удаленного репозитория:
```git remote add origin <URL_репозитория_GitHub>```

* Отправка изменений на GitHub:
```git push -u origin master```

* Получение изменений с GitHub:
```git pull origin master```
<br>


## Ветвление:

* Создание новой ветки:
```git branch <название_ветки>```

* Переключение на другую ветку:
```git checkout <название_ветки>```

* Объединение веток:
```git merge <название_ветки>```
<br>


## Регистрация на GitHub:

* Создание аккаунта на GitHub:

Перейдите по [ссылке](https://github.com/ "github") и следуйте инструкциям.

* Добавление SSH-ключа:

[Генерация SSH-ключа](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent "Жми, да?")


[Генерация SSH-ключа](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account Добавление SSH-ключа на GitHub "А не хочешь, не жми")