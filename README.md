# [GIT TUTORIAL](https://try.github.io/levels/1/challenges/1)

### 1. Got 15 minutes and want to learn Git?

[view on github] (https://try.github.io/levels/1/challenges/1)

- it allows groups of people to work on the same documents (often code) at the same time, and without stepping on each other's toes. It's a distributed version control system.Our terminal prompt below is currently in a directory we decided to name "octobox". To initialize a Git repository here, type the following command:

`git init`

- Это позволяет группам людей работать на одних и тех же документов (часто кода) в то же время, и не наступая на пятки друг другу. Это распределенная управления версиями system.Our подсказка терминала ниже в настоящее время в каталоге мы решили назвать "octobox".

### 1.2 Checking the Status

[view on github] (https://try.github.io/levels/1/challenges/2)

- Good job! As Git just told us, our "octobox" directory now has an empty repository in /.git/. The repository is a hidden directory where Git operates.To save your progress as you go through this tutorial -- and earn a badge when you successfully complete it -- head over to create a free Code School account. We'll wait for you here.Next up, let's type the git status command to see what the current state of our project is:

`git status`

### 1.3 Adding & Committing

[view on github] (https://try.github.io/levels/1/challenges/3)

### 1.4 Adding Changes

[view on github] (https://try.github.io/levels/1/challenges/4)

- Good, it looks like our Git repository is working properly. Notice how Git says octocat.txt is "untracked"? That means Git sees that octocat.txt is a new file.To tell Git to start tracking changes made to octocat.txt, we first need to add it to the staging area by using git add.

`git add octocat.txt`

- Хорошо, это выглядит как наш репозиторий Git работает должным образом. Обратите внимание, как Git говорит octocat.txt это "несопровождаемый"? Это означает, что Git видит, что octocat.txt новый файл.Чтобы сказать Git, чтобы начать отслеживать изменения, сделанные в octocat.txt, нам сначала нужно добавить его в область размещения с помощью Git добавить.

### 1.5 Checking for Changes

[view on github] (https://try.github.io/levels/1/challenges/5)

- Good job! Git is now tracking our octocat.txt file. Let's run git status again to see where we stand:

`git status`

### 1.6 Committing

[view on github] (https://try.github.io/levels/1/challenges/6)

- Notice how Git says changes to be committed? The files listed here are in the Staging Area, and they are not in our repository yet. We could add or remove files from the stage before we store them in the repository.To store our staged changes we run the commit command with a message describing what we've changed. Let's do that now by typing:

`git commit -m "Add cute octocat story"`

- Обратите внимание, как Git говорит изменения должны быть совершены? Файлы, перечисленные здесь, находятся в промежуточной области, и они не находятся в нашем хранилище пока нет. Мы могли бы добавить или удалить файлы из стадии, прежде чем мы хранить их в хранилище.Для того, чтобы сохранить наши постановочные изменения, которые мы выполнить команду совершить с сообщением, описывающей то, что мы изменили. Давайте сделаем это сейчас.

### 1.7 Adding All Changes

[view on github] (https://try.github.io/levels/1/challenges/7)

- Great! You also can use wildcards if you want to add many files of the same type. Notice that I've added a bunch of .txt files into your directory below.I put some in a directory named "octofamily" and some others ended up in the root of our "octobox" directory. Luckily, we can add all the new files using a wildcard with git add. Don't forget the quotes!

`git add "*.txt"`

- Большой! Вы можете также использовать групповые символы, если вы хотите добавить много файлов одного и того же типа. Обратите внимание, что я добавил кучу файлов .txt в каталог ниже.Я положил некоторые в папку с именем "octofamily" и некоторые другие оказались в корне нашего каталога "octobox". К счастью, мы можем добавить все новые файлы, используя символ подстановки с ГИТ доп. Не забудьте кавычки!

### 1.8 Committing All Changes

[view on github] (https://try.github.io/levels/1/challenges/8)

`git commit -m "Add all the cotocat txt files"`

### 1.9 History

[view on github] (https://try.github.io/levels/1/challenges/9)

- So we've made a few commits. Now let's browse them to see what we changed.Fortunately for us, there's git log. Think of Git's log as a journal that remembers all the changes we've committed so far, in the order we committed them. Try running it now:

`git log`

- Таким образом, мы сделали несколько фиксаций. Теперь давайте просматривать их, чтобы увидеть, что мы изменили. К счастью для нас, есть журнал мерзавец. Подумайте о журнале Git в качестве журнала, который запоминает все изменения, которые мы совершенные до сих пор, в том порядке, мы их совершивших. Попробуйте запустить его прямо сейчас:

