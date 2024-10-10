<p align="center">
  <img src="screenshots/1.jpg" alt="Описание изображения 2"/>
</p>
Створюємо репозиторій на GitHub.    <br> <br>

<p align="center">
  <img src="screenshots/2.jpg" alt="Описание изображения 2"/>
</p>
Підключаємось до репозиторію.     <br> <br>

<p align="center">
  <img src="screenshots/3.jpg" alt="Описание изображения 2"/>
</p>
Переходимо в необхідну папку і робимо клон репозиторію.     <br> <br>

<p align="center">
  <img src="screenshots/4.jpg" alt="Описание изображения 2"/>
</p>
По потрібному шляху видно, що проект був клонований у потрібне місце.  <br> <br>

<p align="center">
  <img src="screenshots/5.jpg" alt="Описание изображения 2"/>
</p>
Переходимо в директорію клона і там створюємо папку Work. Потім входимо в неї і створюємо файл hello.html.  <br> <br>

<p align="center">
  <img src="screenshots/6.jpg" alt="Описание изображения 2"/>
</p>
Виходимо назад у папку і створюємо коміт для файлу Work/hello.html. <br> <br>

<p align="center">
  <img src="screenshots/7.jpg" alt="Описание изображения 2"/>
</p>
Перевіряємо статус гіта (в якій гілці ми знаходимося). Через те, що я трохи змінив підхід і створив репозиторій заздалегідь, у ньому є один коміт. <br> <br>

<p align="center">
  <img src="screenshots/8.jpg" alt="Описание изображения 2"/>
</p>
Додали нові зміни і бачимо, що файл тепер модифікований і статус змінено. <br> <br>

<p align="center">
  <img src="screenshots/9.jpg" alt="Описание изображения 2"/>
</p>
Команда `git commit` (ввімкнувся редактор коду для опису комміту). <br> <br>

<p align="center">
  <img src="screenshots/10.jpg" alt="Описание изображения 2"/>
</p>
Команда `git commit` (виконная та успішний статус). <br> <br>

<p align="center">
  <img src="screenshots/11.jpg" alt="Описание изображения 11"/>
</p> Зроблено дві зміни: перше - додано тег `<div>` для `<h1>`, друге - змінено `title` документа з `document` на `Hello document!` <br> <br>

<p align="center">
  <img src="screenshots/12.jpg" alt="Описание изображения 12"/>
</p> Після додавання деяких змін (тега `h2`), видно, що файл був змінений, але не закомічений. <br> <br>

<p align="center">
  <img src="screenshots/13.jpg" alt="Описание изображения 13"/>
</p> З допомогою команди `git add .` можна одразу перевірити всі файли проєкту і додати їх до коміту. Після перевірки статусу видно, що зміни у файлі були прийняті. <br> <br>

<p align="center">
  <img src="screenshots/14.jpg" alt="Описание изображения 14"/>
</p> За допомогою команди `git log` можна отримати всю історію проєкту. <br> <br>

<p align="center">
  <img src="screenshots/15.jpg" alt="Описание изображения 15"/>
</p> Або, якщо в одній строчці, то командою `git log --pretty=oneline`. <br> <br>

<p align="center">
  <img src="screenshots/16.jpg" alt="Описание изображения 16"/>
</p> Також інші варіанти перегляду історії. <br> <br>

<p align="center">
  <img src="screenshots/17.jpg" alt="Описание изображения 17"/>
</p> Перемкнувся на перший коміт і видно, що було у файлі з самого початку. <br> <br>

<p align="center">
  <img src="screenshots/18.jpg" alt="Описание изображения 18"/>
</p> Перемикаємося на основну гілку і бачимо, що тут зберігається вже справжній документ. <br> <br>

<p align="center">
  <img src="screenshots/19.jpg" alt="Описание изображения 19"/>
</p> Створюємо тег версії. <br> <br>

<p align="center">
  <img src="screenshots/20.jpg" alt="Описание изображения 20"/>
</p> Створюємо тег для попередньої версії. <br> <br>

<p align="center">
  <img src="screenshots/21.jpg" alt="Описание изображения 21"/>
</p> Тепер перший коміт має тег `v1-beta`. <br> <br>

<p align="center">
  <img src="screenshots/22.jpg" alt="Описание изображения 22"/>
</p> Перемикаємося по тегам. <br> <br>

<p align="center">
  <img src="screenshots/23.jpg" alt="Описание изображения 23"/>
</p> Переглядаємо список усіх тегів. <br> <br>

<p align="center">
  <img src="screenshots/24.jpg" alt="Описание изображения 24"/>
</p> Тут можна побачити в основній гілці всі логи і їхні теги. <br> <br>

<p align="center">
  <img src="screenshots/25.jpg" alt="Описание изображения 25"/>
</p> Створення непотрібного коментаря і перевірка статусу репозиторія. <br> <br>

<p align="center">
  <img src="screenshots/26.jpg" alt="Описание изображения 26"/>
</p> Перемикаємося на версію файлу в репозиторії. <br> <br>

<p align="center">
  <img src="screenshots/27.jpg" alt="Описание изображения 27"/>
</p> Бачимо, що у файлі більше немає того коментаря, який був створений раніше. Непроіндексовані зміни були видалені. <br> <br>

<p align="center">
  <img src="screenshots/28.jpg" alt="Описание изображения 28"/>
</p> Тепер скасовуємо проіндексацію змін. Створюємо коментар, зберігаємо файл і робимо індексацію перед комітом. <br> <br>

<p align="center">
  <img src="screenshots/29.jpg" alt="Описание изображения 29"/>
</p> Прибираємо проіндексацію. <br> <br>

<p align="center">
  <img src="screenshots/30.jpg" alt="Описание изображения 30"/>
</p> Після перемикання на версію коміту коментар був видалений з файлу. <br> <br>
<p align="center">
  <img src="screenshots/31.jpg" alt="Описание изображения 31"/>
</p> Тепер спробуємо видалити коміт. Для цього створимо тестовий варіант з коментарем і зробимо коміт з назвою "Oops, we didn't want this commit". <br> <br>

<p align="center">
  <img src="screenshots/32.jpg" alt="Описание изображения 32"/>
</p> Для скасування коміту використовуємо команду `git revert HEAD` і переходимо в редактор. Тут залишаємо все як є. <br> <br>

<p align="center">
  <img src="screenshots/33.jpg" alt="Описание изображения 33"/>
</p> Переглядаємо логи і бачимо, що тут є скасований коміт (перший). Але в цьому випадку коміт все ще видно в логах, і це може бути "недобре". <br> <br>

<p align="center">
  <img src="screenshots/34.jpg" alt="Описание изображения 34"/>
</p> На цьому скріншоті встановлюється тег для останнього коміту, а після цього з використанням команди `git reset --hard v1` ми видаляємо всі коміти до коміту з тегом `v1`. Таке може бути небажаним, оскільки в цьому випадку також було видалено коміт з створенням `h2`. Потрібно бути обережним при його використанні. <br> <br>

<p align="center">
  <img src="screenshots/35.jpg" alt="Описание изображения 35"/>
</p> Видаляємо тег `oops` командою `git tag -d oops`. `-d` означає delete. <br> <br>

<p align="center">
  <img src="screenshots/36.jpg" alt="Описание изображения 36"/>
</p> Внесення змін у коміти. Спочатку створимо коміт з частиною коду з Вікіпедії. <br> <br>

<p align="center">
  <img src="screenshots/37.jpg" alt="Описание изображения 37"/>
</p> Трохи змінюємо і тепер за допомогою команди `git commit --amend -m <опис>` перезаписуємо останній коміт. У логах видно, що старий коміт замінився новим. <br> <br>

<p align="center">
  <img src="screenshots/38.jpg" alt="Описание изображения 38"/>
</p> Створюємо нову гілку і автоматично перемикаємося на неї. <br> <br>

<p align="center">
  <img src="screenshots/39.jpg" alt="Описание изображения 39"/>
</p> Додаємо файл стилів `style.css`. <br> <br>

<p align="center">
  <img src="screenshots/40.jpg" alt="Описание изображения 40"/>
</p> Додаємо у гілку також і змінений HTML файл, створюючи новий коміт. <br> <br>

<p align="center">
  <img src="screenshots/41.jpg" alt="Описание изображения 41"/>
</p> Тепер вивчаємо перемикання гілок. <br> <br>

<p align="center">
  <img src="screenshots/42.jpg" alt="Описание изображения 42"/>
</p> Після перемикання на основну гілку за допомогою команди `git switch main` файл автоматично прибрав зміни з `hello.html` (зникла строка з підключенням файлу CSS). Тією ж командою можна перемикатися між гілками. <br> <br>

<p align="center">
  <img src="screenshots/43.jpg" alt="Описание изображения 43"/>
</p> За допомогою команди `git show <tag>` можна переглянути зміни у файлі, які були внесені. <br> <br>

<p align="center">
  <img src="screenshots/44.jpg" alt="Описание изображения 44"/>
</p> Після перейменування git вважає, що файл був видалений і створено новий. <br> <br>

<p align="center">
  <img src="screenshots/45.jpg" alt="Описание изображения 45"/>
</p> Для виправлення ситуації необхідно проіндексувати його. <br> <br>

<p align="center">
  <img src="screenshots/46.jpg" alt="Описание изображения 46"/>
</p> Для того щоб перейменувати або перенести файл безпечно, необхідно використовувати команду разом з git. Тоді вона гарантовано буде записана в git як переміщення. <br> <br>

<p align="center">
  <img src="screenshots/47.jpg" alt="Описание изображения 47"/>
</p> Після цього, щоб переглянути логи переміщення і зміни назв файлів, необхідно вказати додатковий атрибут `--follow` у команді `git log --follow <шлях>`. <br> <br>

<p align="center">
  <img src="screenshots/48.jpg" alt="Описание изображения 48"/>
</p> Перегляд логів усіх гілок здійснюється за допомогою опцій --all, яка надає результат усіх гілок, та --graph, що додає дерево комітів для зручності читання. <br> <br>

<p align="center">
  <img src="screenshots/49.jpg" alt="Описание изображения 49"/>
</p> Для того щоб зробити злиття двох гілок використовується команда `git merge <назва гілки>`. Необхідною умовою є знаходження на тій гілці, яку потрібно злити з іншою гілкою. У цьому випадку гілка `style` зливається з гілкою `main`. <br> <br>

<p align="center">
  <img src="screenshots/50.jpg" alt="Описание изображения 50"/>
</p> На цьому скріншоті відбувається перехід до основної гілки і зміна файлу `hello.html` конфліктуючими даними (зміна назви документа, видалення рядків). Після цього переглядаємо логи гілок і бачимо, що деякі гілки переплітаються і конфліктують одна з одною. <br> <br>
<p align="center">
  <img src="screenshots/51.jpg" alt="Описание изображения 51"/>
</p> Після переходу на гілку Style і спроби злиття отримуємо помилку. Це нормально, бо git не зміг автоматично вирішити конфлікти і просить нашого ручного втручання. <br> <br>

<p align="center">
  <img src="screenshots/52.jpg" alt="Описание изображения 52"/>
</p> Після відкриття файлу видно місця конфліктів. Останній тег <div> з втраченим (зміненим текстом) автоматично зміг побудуватися, але з рештою змін git не впорався. <br> <br>

<p align="center">
  <img src="screenshots/53.jpg" alt="Описание изображения 53"/>
</p> Перед тим як виправляти конфлікти - скасовуємо злиття. <br> <br>

<p align="center">
  <img src="screenshots/54.jpg" alt="Описание изображения 54"/>
</p> Після чого вирішуємо всі конфлікти. <br> <br>

<p align="center">
  <img src="screenshots/55.jpg" alt="Описание изображения 55"/>
</p> І робимо коміт. Тепер конфліктів бути не повинно. <br> <br>

<p align="center">
  <img src="screenshots/56.jpg" alt="Описание изображения 56"/>
</p> Для перевірки різниці між злиттям (`merge`) і перебазуванням (`rebase`) необхідно повернутися до моменту злиття в гілці `style`. <br> <br>

<p align="center">
  <img src="screenshots/57.jpg" alt="Описание изображения 57"/>
</p> Пов'язано з минулим скрином <br> <br>

<p align="center">
  <img src="screenshots/58.jpg" alt="Описание изображения 58"/>
</p> При спробі перебазувати (`rebase`) гілку конфлікти нікуди не зникли, але тепер конфлікти не в файлі `hello.html`, а в файлі `index.html`. Це сталося тому, що `rebase` знаходився в процесі зміни `style` поверх гілки `main`. <br> <br>

<p align="center">
  <img src="screenshots/59.jpg" alt="Описание изображения 59"/>
</p> Після вирішення конфліктів і повторної індексації всі проблеми були вирішені, все добре перебазувалося, і тепер гілка комітів стала більш правильною і лінійною. <br> <br>

<p align="center">
  <img src="screenshots/60.jpg" alt="Описание изображения 60"/>
</p> Здійснюємо злиття з основною гілкою `main` за допомогою `merge`. <br> <br>

<p align="center">
  <img src="screenshots/61.jpg" alt="Описание изображения 61"/>
</p> Тепер створимо клон репозиторія в кореневій папці за допомогою команди `git clone <назва репозиторія> <назва папки для клону репозиторія>`. <br> <br>

<p align="center">
  <img src="screenshots/62.jpg" alt="Описание изображения 62"/>
</p> Команда `git remote` показує ім'я за замовчуванням віддаленого репозиторія. Ім'я `origin` застосовується як ім'я первинного централізованого репозиторія. <br> <br>

<p align="center">
  <img src="screenshots/63.jpg" alt="Описание изображения 63"/>
</p> В клону репозиторія можна також дізнатися про поточні гілки та отримати список віддалених гілок. <br> <br>

<p align="center">
  <img src="screenshots/64.jpg" alt="Описание изображения 64"/>
</p> Змінюємо файл `README.md` в основному репозиторії і додаємо коміт. <br> <br>

<p align="center">
  <img src="screenshots/65.jpg" alt="Описание изображения 65"/>
</p> У другому репозиторії (клоні) підтягуючи зміни у файлі `README.md`. <br> <br>

<p align="center">
  <img src="screenshots/66.jpg" alt="Описание изображения 66"/>
</p> Скриншот для показу того, що файл був змінений. <br> <br>

<p align="center">
  <img src="screenshots/67.jpg" alt="Описание изображения 67"/>
</p> За допомогою команди `git merge origin/main` виконуємо злиття підтягнутих змін в локальну гілку. Використовуючи команду `git pull`, яка швидко зливає зміни з віддаленої гілки в поточну за один виклик замість двох (1. `git fetch` 2. `git merge origin/main`). <br> <br>

<p align="center">
  <img src="screenshots/68.jpg" alt="Описание изображения 68"/>
</p> Додаємо гілку, яка буде відстежувати віддалену гілку, за допомогою команди `git branch --track style origin/style`. Переглядаємо всі гілки командою `git branch -a`. <br> <br>

<p align="center">
  <img src="screenshots/69.jpg" alt="Описание изображения 69"/>
</p> Для створення чистого репозиторія використовуємо команду `git clone --bare work work.git`. <br> <br>

<p align="center">
  <img src="screenshots/70.jpg" alt="Описание изображения 70"/>
</p> Для того щоб додати чистий репозиторій як віддалений репозиторій до оригіналу, необхідно використовувати всередині основного репозиторія команду `git remote add shared ../work.git`. <br> <br>

<p align="center">
  <img src="screenshots/71.jpg" alt="Описание изображения 71"/>
</p> Після внесення змін у файл `README.md` і створення коміту, відправляємо зміни в загальний репозиторій, створений на попередньому кроці. <br> <br>

<p align="center">
  <img src="screenshots/72.jpg" alt="Описание изображения 72"/>
</p> За допомогою наступних команд підтягнемо в репозиторій `home` зміни, що були відправлені в загальний репозиторій: <br> 
<code>git fetch shared</code> <br>
<code>git merge shared/main</code> <br> <br>

<p align="center">
  <img src="screenshots/73.jpg" alt="Описание изображения 73"/>
</p> Щоб розмістити Git-репозиторій на GitHub, можна використовувати команду <code>git daemon --verbose --export-all --base-path=.</code> і посилання на папку з репозиторіями. Після цього перейти в іншому терміналі і виконати команди в тій же папці: <br> 
<code>git clone git://localhost/work.git network_work</code> <br> 
<code>cd network_work</code> <br>
<code>ls</code> <br>
Можна буде побачити копію проєкту.

