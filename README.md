## Git командууд :+1:
git командуудын тайлбар, тусламжийн репо.

### Live server тохируулах

Visual studio code - Live server >> install

### Github хэрэгэгчийг солих

Windows Search хэсэгт -> Credential manager - Git хэрэглэгчийг солих

### Командуудын жагсаалт

`git add *` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add .` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add -A` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add [index.html]` **index.html файлыг стэйжилнэ**

`git version` **Version харах**

`git clone [https://github.com/Munkhsoyoldavaa/testorigin.git]` **Репо буюу үүсгэсэн Project-г хувилах**

`git status` **Өөрчлөгдсөн файлуудыг харуулна**

`git log` **Өмнөх өөрчлөгдсөн түүхийг харуулна**

`q` **Log файлаас гарах**

`git commit -m ["хийсэн зүйлийнхээ тайлбар"]` **Тайлбар бичиж илгээнэ**

`git config -l` **Үндсэн тохиргоог харах**

`git config --global user.email [noyonmc.mine@gmail.com]` **Мэйл хаяг тохируулах**

`git config --global user.name [Munkhsoyoldavaa]` **Нэр тохируулах**

`git remote -v` **Git тэй холбоотой эсэхийг шалгах**

`git init` **Тухайн Folder - дотроо .git файл үүсгэх**

`git remote add origin [https://github.com/Munkhsoyoldavaa/mcgo.git]` **Github дотор репо үүсгэх. Үүсгэсэн rebo link хуулж тавих**

`git push origin master` **Push хийх**

`git push -u origin [branch name]` **Branch push хийх**

`git push` **Push хийх**

`git restore --staged [index.html]` **Өөрчлөгдсөн болон устгагдсан файлыг буцаах**

`git commit --help` **Дэлгэрэнгүй комманд**

`git checkout [shal id number]` **Тухайн push хийсэн хэсэгт буцаана**

`git merge [branch name]` **Merge хийх**

`git merge --abort` **Merge хийхээ болиулах**

`git fetch` **Github репо дээр байгаа файлыг локал репо руу хуулна**

`git pull` **Github репо дээр байгаа файлыг ажлын хавтас руу автоматаар merge хийнэ хуулна**

`git remote show origin` **репо -ныхоо дэлгэрэнгүй мэдээлэл харна**

`git remote prune [remote_name]` **Локал дээрх remote -г цэвэрлэнэ**

`git push --all` **Бүх бранчийн бүх мэдээллийг push хийнэ**

`git show-ref [branch name]` **локал болон git репо дээрх мэдээллийг харах**

`git reflog` **work file, stage area, local repo дээрх бүх log харах**

`git reset -hard [number]` **тухайн commit -г сэргээх**

### Branch commands

`git branch` **Үүсгэсэн бүх branch харах**

`git branch [name]` **Branch үүсгэх**

`git checkout -b [branch name]` **Шинээр branch үүсгэнэ**

`git switch -C [branch name]` **Шинээр branch үүсгэнэ**

`git branch -m [branch name, change name]` **branch нэр өөрчлөх**

`git checkout [branch name]` **branch буюу төслийн хувилбар луу шилжих**

`git branch -d [branch name]` **branch устгах.**

`git branch -D [branch name]` **branch бүр мөсөн устгах**

`git checkout -b [branch name] origin/[branch name]` **Tracking branch**

`git checkout --track origin/[branch name]` **Tracking branch**

`git branch -vv` **Tracking branch харах**

### Хэрэгтэй холбоос болон программууд

1. sourcetreeapp.com
2. GithubDesktop
