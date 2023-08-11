# Проект для Git
## Project for Git

1. Создать новый проект и подключить в него Git через терминал: git init
2. В проекте проигнорировать все файлы с расширением .sass и папки: bin, admin, config:
в корневой папке создаем файл .gitignore и прописываем:
1 *.sass
2 bin
3 admin
4 config 
3. Выполните следующие задачи:
добавить все файлы в локальное хранилище, в терминале прописать:
git add */*
git status
git commit -m "first version"
создайть новую ветку и перейти в неё, в терминале прописать:
git status
git branch blog
git checkout blog 
git status 
в новой ветке создайть папку blog с файлами: index.js, index.html:
создаем папку с файлами в редакторе
в терминале прописываем:
git add .
git status
git commit -m "add blog"
git checkout master
git merge blog 
загрузить на удаленный репозиторий лишь основную ветку вашего проекта:
регистрация на Github 
в Github создаем новый репозиторий через "New"
в терминале прописываем:
git remote add origin (из Github копируем)
git push -u origin master (из Github копируем) 
устанавливаем двухфакторную аутентификацию 
создаем новый файл README.md
в терминале прописываем:
git add .
git status
git commit -m "Add Readme file"
git push -u origin master 