<div style="font-size: 16px; line-height: 1.5;">
[Скриншот 1.](screenshots/1.jpg) Створюємо репозиторій на GitHub.   
[Скриншот 2.](screenshots/2.jpg) Підключаємось до репозиторію.    
[Скриншот 3.](screenshots/3.jpg) Переходимо в необхідну папку і робимо клон репозиторію.    
[Скриншот 4.](screenshots/4.jpg) По потрібному шляху видно, що проект був клонований у потрібне місце.  <br>
[Скриншот 5.](screenshots/5.jpg) Переходимо в директорію клона і там створюємо папку Work. Потім входимо в неї і створюємо файл hello.html.  <br>
[Скриншот 6.](screenshots/6.jpg) Виходимо назад у папку і створюємо коміт для файлу Work/hello.html. <br>
[Скриншот 7.](screenshots/7.jpg) Перевіряємо статус гіта (в якій гілці ми знаходимося). Через те, що я трохи змінив підхід і створив репозиторій заздалегідь, у ньому є один коміт. <br>
[Скриншот 8.](screenshots/8.jpg) Додали нові зміни і бачимо, що файл тепер модифікований і статус змінено. <br>
[Скриншот 9.](screenshots/9.jpg) Команда `git commit` (ввімкнувся редактор коду для опису комміту). <br>
[Скриншот 10.](screenshots/10.jpg) Команда `git commit` (виконная та успішний статус). <br>
[Скриншот 11.](screenshots/11.jpg) Зроблено дві зміни: перше - додано тег <div> для <h1>, друге - змінено `title` документа з `document` на `Hello document!` <br>
[Скриншот 12.](screenshots/12.jpg) Після додавання деяких змін (тега `h2`), видно, що файл був змінений, але не закомічений. <br>
[Скриншот 13.](screenshots/13.jpg) З допомогою команди `git add .` можна одразу перевірити всі файли проєкту і додати їх до коміту. Після перевірки статусу видно, що зміни у файлі були прийняті. <br>
[Скриншот 14.](screenshots/14.jpg) За допомогою команди `git log` можна отримати всю історію проєкту. <br>
[Скриншот 15.](screenshots/15.jpg) Або, якщо в одній строчці, то командою `git log --pretty=oneline`. <br>
[Скриншот 16.](screenshots/16.jpg) Також інші варіанти перегляду історії. <br>
[Скриншот 17.](screenshots/17.jpg) Перемкнувся на перший коміт і видно, що було у файлі з самого початку. <br>
[Скриншот 18.](screenshots/18.jpg) Перемикаємося на основну гілку і бачимо, що тут зберігається вже справжній документ. <br>
[Скриншот 19.](screenshots/19.jpg) Створюємо тег версії. <br>
[Скриншот 20.](screenshots/20.jpg) Створюємо тег для попередньої версії. <br>
[Скриншот 21.](screenshots/21.jpg) Тепер перший коміт має тег `v1-beta`. <br>
[Скриншот 22.](screenshots/22.jpg) Перемикаємося по тегам. <br>
[Скриншот 23.](screenshots/23.jpg) Переглядаємо список усіх тегів. <br>
[Скриншот 24.](screenshots/24.jpg) Тут можна побачити в основній гілці всі логи і їхні теги. <br>
[Скриншот 25.](screenshots/25.jpg) Створення непотрібного коментаря і перевірка статусу репозиторія. <br>
[Скриншот 26.](screenshots/26.jpg) Перемикаємося на версію файлу в репозиторії. <br>
[Скриншот 27.](screenshots/27.jpg) Бачимо, що у файлі більше немає того коментаря, який був створений раніше. Непроіндексовані зміни були видалені. <br>
[Скриншот 28.](screenshots/28.jpg) Тепер скасовуємо проіндексацію змін. Створюємо коментар, зберігаємо файл і робимо індексацію перед комітом. <br>
[Скриншот 29.](screenshots/29.jpg) Прибираємо проіндексацію. <br>
[Скриншот 30.](screenshots/30.jpg) Після перемикання на версію коміту коментар був видалений з файлу. <br>
[Скриншот 31.](screenshots/31.jpg) Тепер спробуємо видалити коміт. Для цього створимо тестовий варіант з коментарем і зробимо коміт з назвою "Oops, we didn't want this commit". <br>
[Скриншот 32.](screenshots/32.jpg) Для скасування коміту використовуємо команду `git revert HEAD` і переходимо в редактор. Тут залишаємо все як є. <br>
[Скриншот 33.](screenshots/33.jpg) Переглядаємо логи і бачимо, що тут є скасований коміт (перший). Але в цьому випадку коміт все ще видно в логах, і це може бути "недобре". <br>
[Скриншот 34.](screenshots/34.jpg) На цьому скріншоті встановлюється тег для останнього коміту, а після цього з використанням команди `git reset --hard v1` ми видаляємо всі коміти до коміту з тегом `v1`. Таке може бути небажаним, оскільки в цьому випадку також було видалено коміт з створенням `h2`. Потрібно бути обережним при його використанні. <br>
[Скриншот 35.](screenshots/35.jpg) Видаляємо тег `oops` командою `git tag -d oops`. `-d` означає delete. <br>
[Скриншот 36.](screenshots/36.jpg) Внесення змін у коміти. Спочатку створимо коміт з частиною коду з Вікіпедії. <br>
[Скриншот 37.](screenshots/37.jpg) Трохи змінюємо і тепер за допомогою команди `git commit --amend -m <опис>` перезаписуємо останній коміт. У логах видно, що старий коміт замінився новим. <br>
[Скриншот 38.](screenshots/38.jpg) Створюємо нову гілку і автоматично перемикаємося на неї. <br>
[Скриншот 39.](screenshots/39.jpg) Додаємо файл стилів `style.css`. <br>
[Скриншот 40.](screenshots/40.jpg) Додаємо у гілку також і змінений HTML файл, створюючи новий коміт. <br>
[Скриншот 41.](screenshots/41.jpg) Тепер вивчаємо перемикання гілок. <br>
[Скриншот 42.](screenshots/42.jpg) Після перемикання на основну гілку за допомогою команди `git switch main` файл автоматично прибрав зміни з `hello.html` (зникла строка з підключенням файлу CSS). Тією ж командою можна перемикатися між гілками. <br>
[Скриншот 43.](screenshots/43.jpg) За допомогою команди `git show <tag>` можна переглянути зміни у файлі, які були внесені. <br>
[Скриншот 44.](screenshots/44.jpg) Після перейменування git вважає, що файл був видалений і створено новий. <br>
[Скриншот 45.](screenshots/45.jpg) Для виправлення ситуації необхідно проіндексувати його. <br>
[Скриншот 46.](screenshots/46.jpg) Для того щоб перейменувати або перенести файл безпечно, необхідно використовувати команду разом з git. Тоді вона гарантовано буде записана в git як переміщення. <br>
[Скриншот 47.](screenshots/47.jpg) Після цього, щоб переглянути логи переміщення і зміни назв файлів, необхідно вказати додатковий атрибут `--follow` у команді `git log --follow <шлях>`. <br>
[Скриншот 48.](screenshots/48.jpg) Перегляд логів усіх гілок здійснюється за допомогою опцій --all, яка надає результат усіх гілок, та --graph, що додає дерево комітів для зручності читання. <br>
[Скриншот 49.](screenshots/49.jpg) Для того щоб зробити злиття двох гілок використовується команда `git merge <назва гілки>`. Необхідною умовою є знаходження на тій гілці, яку потрібно злити з іншою гілкою. У цьому випадку гілка `style` зливається з гілкою `main`. <br>
[Скриншот 50.](screenshots/50.jpg) На цьому скріншоті відбувається перехід до основної гілки і зміна файлу `hello.html` конфліктуючими даними (зміна назви документа, видалення рядків). Після цього переглядаємо логи гілок і бачимо, що деякі гілки переплітаються і конфліктують одна з одною. <br>
[Скриншот 51.](screenshots/51.jpg) Після переходу на гілку Style і спроби злиття отримуємо помилку. Це нормально, бо git не зміг автоматично вирішити конфлікти і просить нашого ручного втручання. <br>
[Скриншот 52.](screenshots/52.jpg) Після відкриття файлу видно місця конфліктів. Останній тег <div> з втраченим (зміненим текстом) автоматично зміг побудуватися, але з рештою змін git не впорався. <br>
[Скриншот 53.](screenshots/53.jpg) Перед тим як виправляти конфлікти - скасовуємо злиття. <br>
[Скриншот 54.](screenshots/54.jpg) Після чого вирішуємо всі конфлікти. <br>
[Скриншот 55.](screenshots/55.jpg) І робимо коміт. Тепер конфліктів бути не повинно. <br>
[Скриншот 56.](screenshots/56.jpg) Для перевірки різниці між злиттям (`merge`) і перебазуванням (`rebase`) необхідно повернутися до моменту злиття в гілці `style`. <br>
[Скриншот 57.](screenshots/57.jpg) Пов'язано з минулим скрином <br>
[Скриншот 58.](screenshots/58.jpg) При спробі перебазувати (`rebase`) гілку конфлікти нікуди не зникли, але тепер конфлікти не в файлі `hello.html`, а в файлі `index.html`. Це сталося тому, що `rebase` знаходився в процесі зміни `style` поверх гілки `main`. <br>
[Скриншот 59.](screenshots/59.jpg) Після вирішення конфліктів і повторної індексації всі проблеми були вирішені, все добре перебазувалося, і тепер гілка комітів стала більш правильною і лінійною. <br>
[Скриншот 60.](screenshots/60.jpg) Здійснюємо злиття з основною гілкою `main` за допомогою `merge`. <br>
[Скриншот 61.](screenshots/61.jpg) Тепер створимо клон репозиторія в кореневій папці за допомогою команди `git clone <назва репозиторія> <назва папки для клону репозиторія>`. <br>
[Скриншот 62.](screenshots/62.jpg) Команда `git remote` показує ім'я за замовчуванням віддаленого репозиторія. Ім'я `origin` застосовується як ім'я первинного централізованого репозиторія. <br>
[Скриншот 63.](screenshots/63.jpg) В клону репозиторія можна також дізнатися про поточні гілки та отримати список віддалених гілок. <br>
[Скриншот 64.](screenshots/64.jpg) Змінюємо файл `README.md` в основному репозиторії і додаємо коміт. <br>
[Скриншот 65.](screenshots/65.jpg) У другому репозиторії (клоні) підтягуючи зміни у файлі `README.md`. <br>
[Скриншот 66.](screenshots/66.jpg) Скриншот для показу того, що файл був змінений. <br>
[Скриншот 67.](screenshots/67.jpg) За допомогою команди `git merge origin/main` виконуємо злиття підтягнутих змін в локальну гілку. Використовуючи команду `git pull`, яка швидко зливає зміни з віддаленої гілки в поточну за один виклик замість двох (1. `git fetch` 2. `git merge origin/main`). <br>
[Скриншот 68.](screenshots/68.jpg) Додаємо гілку, яка буде відстежувати віддалену гілку, за допомогою команди `git branch --track style origin/style`. Переглядаємо всі гілки командою `git branch -a`. <br>
[Скриншот 69.](screenshots/69.jpg) Для створення чистого репозиторія використовуємо команду `git clone --bare work work.git`. <br>
[Скриншот 70.](screenshots/70.jpg) Для того щоб додати чистий репозиторій як віддалений репозиторій до оригіналу, необхідно використовувати всередині основного репозиторія команду `git remote add shared ../work.git`. <br>
[Скриншот 71.](screenshots/71.jpg) Після внесення змін у файл `README.md` і створення коміту, відправляємо зміни в загальний репозиторій, створений на попередньому кроці. <br>
[Скриншот 72.](screenshots/72.jpg) За допомогою наступних команд підтягнемо в репозиторій `home` зміни, що були відправлені в загальний репозиторій: <br>
1. `git fetch shared` <br>
2. `git merge shared/main` <br>
[Скриншот 73.](screenshots/73.jpg) Щоб розмістити Git-репозиторій на GitHub, можна використовувати команду `git daemon --verbose --export-all --base-path=.` і посилання на папку з репозиторіями. Після цього перейти в іншому терміналі і виконати команди в тій же папці: <br>
1. `git clone git://localhost/work.git network_work` <br>
2. `cd network_work` <br>
3. `ls` <br>
Можна буде побачити копію проєкту.
</h3>
