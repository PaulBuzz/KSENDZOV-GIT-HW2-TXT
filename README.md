# TXT
**TXT Rep for HW2 @ Ksendzov Course**

1. Создайте текстоовый файл как в первом ДЗ по Terminal.
2. Сценарий перенесите в этот файл.
3. Напротив каждого действия - напишите команду в GitBash.
```
Command: cd /Users/macintosh/Desktop/CODING/KSENDZOV/HW2
Перемещаемся в папку, куда будем клонировать репозиторий, который мы только что создали.
```
4. Создать внешний репозиторий c названием TXT.
- <img width="1002" alt="JSON01" src="https://user-images.githubusercontent.com/84155505/144830991-461a9823-dce9-4b15-938b-8e4ec39926ac.png">
- <img width="744" alt="TXT01" src="https://user-images.githubusercontent.com/84155505/144832980-66ea8677-4296-4666-976a-f869683a52d4.png">
5. Клонировать репозиторий TXT на локальный компьютер.
```
Command: git clone https://github.com/PaulBuzz/TXT
Клонирование в «TXT»…
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Получение объектов: 100% (3/3), готово.
```
6. Внутри локального TXT создать файл “new.txt”.
```
Command: cd TXT
Command: touch new.txt
```
7. Добавить файл под гит.
```
Command: git add "new.txt"
```
8. Закоммитить файл.
```
Command: git commit -m "commiting TXT file to our rep"
```
9. Отправить файл на внешний GitHub репозиторий.
```
Command: git push
```
10. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```
Command: vim new.txt
NSF
name Pavel
surname Buzin
father_name Aleksandr
age 29
pets 0
desired_salary 6000
```
11. Отправить изменения на внешний репозиторий.
```
Command: git push
Result: Перечисление объектов: 5, готово.
Подсчет объектов: 100% (5/5), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (3/3), готово.
Запись объектов: 100% (3/3), 394 байта | 394.00 КиБ/с, готово. Всего 3 (изменений 0), повторно использовано пакетов 0
To https://github.com/PaulBuzz/TXT
```
12. Создать файл preferences.txt.
```
Command: touch preferences.txt
```
13. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```
Command: vim preferences.txt
fav_movie 25th_hour
fav_TVSHOW Scrubs
fav_food Kebab
fav_season Autumn
country_to_visit Denmark
```
14. Создать файл skills.txt и добавить информацию о скиллах, которые будут изучены на курсе в формате TXT.
```
Command: touch skills.txt
Command: vim skill.txt
skill_1 HTTP
skill_2 GIT
skill_3 VPN
skill_4 SQL
skill_5 Postman
skill_6 Charles
skill_7 Fiddler
skill_8 Android_Studio
skill_9 XCODE
skill_10 QA_Theory
```
15. Сделать коммит в одну строку.
```
Command: git add -A && git commit -m "adding multiple files to the repository"
```
16. Отправить сразу 2 файла на внешний репозиторий.
```
Command: git push 
Добавляет все файлы
```
17. На веб интерфейсе создать файл bug_report.txt.
- <img width="1438" alt="TXT03" src="https://user-images.githubusercontent.com/84155505/144840004-f0a15ae4-ee0b-4507-8e07-5dd2c1c70648.png">
- <img width="1403" alt="TXT02" src="https://user-images.githubusercontent.com/84155505/144839947-1cb3e8c2-5563-484c-9a47-1356deb6b0c5.png">
18. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- <img width="1408" alt="TXT04" src="https://user-images.githubusercontent.com/84155505/144840120-c268aad6-120c-4580-b6f1-5d5c9e1fa496.png">
19. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
- <img width="1421" alt="TXT05" src="https://user-images.githubusercontent.com/84155505/144841261-44fa603c-55ed-4be8-ae80-c851f37f6013.png">
20. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- <img width="1411" alt="TXT06" src="https://user-images.githubusercontent.com/84155505/144841374-bb468a04-a412-41e2-ad59-8191b778ee31.png">
21. Синхронизировать внешний и локальный репозиторий XML.
```
Command: git pull
```
