1.Створення нового каталогу "new-project" і перехід до нього:
- mkdir new-project
- cd new-project

2.Ініціалізація нового публічного Git-репозиторію всередині каталогу "new-project":
- git init
- 
3.Створення нового файлу "README.md" і додавання до нього початкового тексту:
- echo "# New Project" > README.md

4.Підготовка файлу "README.md" до коміту:
- git add README.md

5.Коміт змін у репозиторій з коміт-повідомленням "init":
- git commit -m "init"

6.Створення нової гілки "development" і перехід до неї:
- git branch development
- git checkout development

7.Додавання інструкцій до файлу "README.md" і підготовка їх до коміту:
- echo "Instructions: ..." >> README.md
- git add README.md

8.Коміт змін у гілці "development" з повідомленням про коміт:
- git commit -m "Addded instructions to README"

9.Об'єднання змін з гілки "development" у гілку "main":
- git checkout main
- git merge development

10.Перевірка статусу, переконайтеся, що все актуально:
- git status

11.Коміт змін:
- git commit -m "Final changes"
