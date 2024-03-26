1. Створіть в своєму середовищі новий каталог з назвою "new-project".

```sh
mkdir "new-project"
```

2. Перейдіть до каталогу "new-project".

```sh
cd "new-project"
```

3. Ініціалізуйте новий публічний Git-репозиторій всередині каталогу "new-project".

```sh
git init
```

4. Створіть новий файл з назвою "README.md" і додайте до нього початковий текст.

```sh
touch "README.md"
```

5. Підготуйте файл "README.md" до коміту.

```sh
git add "README.md"
```

6. Закомітьте зміни у репозиторій з коміт повідомленням “init”.

```sh
git commit -m "init"
```

7. Створіть нову гілку з назвою "development" і перейдіть до неї.

```sh
git checkout -b development
```

8. Додайте інструкцію до файлу "README.md" і підготуйте їх до коміту.

```sh
###
git add "README.md"
```

9. Закомітьте зміни у гілці "development" з повідомленням про коміт.

```sh
git commit -m "Added instructions."
```

10. Об'єднайте зміни з гілки "development" у гілку "main".

```sh
git checkout main
git merge development
```

11. Перевірте статус, переконайтеся, що все актуально.

```sh
git status
```

12. Закомітьте зміни

```sh
git commit -m "Merged development to main."
```
