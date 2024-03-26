Створення нового каталогу "new-project" і перехід до нього:
- mkdir new-project
- cd new-project
Ініціалізація нового публічного Git-репозиторію всередині каталогу "new-project":
- git init
Створення нового файлу "README.md" і додавання до нього початкового тексту:
- echo "# New Project" > README.md
Підготовка файлу "README.md" до коміту:
- git add README.md
Закомітьте зміни у репозиторій з коміт-повідомленням "init":
- git commit -m "init"
Створення нової гілки "development" і перехід до неї:
- git branch development
- git checkout development
Додавання інструкцій до файлу "README.md" і підготовка їх до коміту:
- echo "Instructions: ..." >> README.md
- git add README.md
Коміт змін у гілці "development" з повідомленням про коміт:
- git commit -m "Addded instructions to README"
Об'єднання змін з гілки "development" у гілку "main":
- git checkout main
- git merge development
Перевірка статусу, переконайтеся, що все актуально:
- git status
Коміт змін:
- git commit -m "Final changes"
