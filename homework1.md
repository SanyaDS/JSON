Homework 1 JSON

> Перед началом выполнения работы предварительно создаем папку например "GitHub" на локальном компьютере и в ней работаем через Terminal или GitBash.

1. Создать внешний репозиторий c названием JSON.  
`https://github.com/SanyaDS/JSON`
2. Клонировать репозиторий JSON на локальный компьютер.  
`$ git clone git@github.com:SanyaDS/JSON.git`
3. Внутри локального JSON создать файл new.json.  
`$ cd json`  
`$ touch new.json`
4. Добавить файл под гит.  
`$ git status`  
`$ git add new.json`
5. Закоммитить файл.  
`$ git commit -m "New file json"`
6. Отправить файл на внешний GitHub репозиторий.  
`$ git push`
7. Отредактировать содержание файла new.json - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
`$ vim new.json`  
`i # добавляем информацию.`  
`Esc`  
`:x`  
`Enter # выходим из редактора vim.`
8. Отправить изменения на внешний репозиторий.  
`$ git status`  
`$ git add new.json`  
`$ git commit -m "Update file json"`  
`$ gut push`
9. Создать файл preferences.json.  
`$ touch preferences.json`
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
`$ vim preferences.json`  
`i # добавляем информацию.`  
`Esc`  
`:x`  
`Enter # выходим из редактора vim.`
11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.  
`$ touch skills.json`  
`$ vim skills.json`  
`i # добавляем информацию.`  
`Esc`  
`:x`  
`Enter # выходим из редактора vim.`
12. Отправить сразу 2 файла на внешний репозиторий.  
`$ git status`  
`$ git add .`  
`$ git commit -m "New file json"`  
`$ gut push`
13. На веб интерфейсе создать файл bug_report.json.  
`# Создали файл bug_report.json.`
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`# Сохранили файл bug_report.json.`
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
`# Открыли файл bug_report.json и модифицировали.`
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`# Сохранили файл bug_report.json.`
17. Синхронизировать внешний и локальный репозиторий JSON.  
`$ git pull`
