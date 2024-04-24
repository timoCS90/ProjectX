
49157@DESKTOP-483GV34 MINGW64 ~
$ mkdir ~/Desktop/ProjectX

49157@DESKTOP-483GV34 MINGW64 ~
$ mkdir -p ~/Desktop/ProjectX/docs

49157@DESKTOP-483GV34 MINGW64 ~
$ mkdir -p ~/Desktop/ProjectX/docs/reports

49157@DESKTOP-483GV34 MINGW64 ~
$ mkdir -p ~/Desktop/ProjectX/docs/images

49157@DESKTOP-483GV34 MINGW64 ~
$ mkdir -p ~/Desktop/ProjectX/src/html

49157@DESKTOP-483GV34 MINGW64 ~
$ mkdir -p ~/Desktop/ProjectX/src/css

49157@DESKTOP-483GV34 MINGW64 ~
$ mkdir -p ~/Desktop/ProjectX/src/js

49157@DESKTOP-483GV34 MINGW64 ~
$ mkdir -p ~/Desktop/ProjectX/data

49157@DESKTOP-483GV34 MINGW64 ~
$ touch ~/Desktop/ProjectX/docs/reports/report_one.txt

49157@DESKTOP-483GV34 MINGW64 ~
$ touch ~/Desktop/ProjectX/docs/reports/report_two.txt

49157@DESKTOP-483GV34 MINGW64 ~
$ touch ~/Desktop/ProjectX/src/html/index.html

49157@DESKTOP-483GV34 MINGW64 ~
$ touch ~/Desktop/ProjectX/src/css/style.css

49157@DESKTOP-483GV34 MINGW64 ~
$ touch ~/Desktop/ProjectX/src/js/script.js

49157@DESKTOP-483GV34 MINGW64 ~
$ touch ~/Desktop/ProjectX/data/data.txt

49157@DESKTOP-483GV34 MINGW64 ~
$ echo "Hello Data" > ~/Desktop/ProjectX/data/data.txt

49157@DESKTOP-483GV34 MINGW64 ~
$ cd ~/Desktop/ProjectX

49157@DESKTOP-483GV34 MINGW64 ~/Desktop/ProjectX
$ git init
Initialized empty Git repository in C:/Users/49157/Desktop/ProjectX/.git/

49157@DESKTOP-483GV34 MINGW64 ~/Desktop/ProjectX (master)
$ git add .
warning: in the working copy of 'data/data.txt', LF will be replaced by CRLF the next time Git touches it

49157@DESKTOP-483GV34 MINGW64 ~/Desktop/ProjectX (master)
$ git commit -m "initial setup"
[master (root-commit) 44e87b0] initial setup
 6 files changed, 1 insertion(+)
 create mode 100644 data/data.txt
 create mode 100644 docs/reports/report_one.txt
 create mode 100644 docs/reports/report_two.txt
 create mode 100644 src/css/style.css
 create mode 100644 src/html/index.html
 create mode 100644 src/js/script.js

49157@DESKTOP-483GV34 MINGW64 ~/Desktop/ProjectX (master)
$ touch ~/Desktop/ProjectX/docs/images/.gitkeep

49157@DESKTOP-483GV34 MINGW64 ~/Desktop/ProjectX (master)
$ git remote add origin https://github.com/timoCS90/ProjectX

49157@DESKTOP-483GV34 MINGW64 ~/Desktop/ProjectX (master)
$ git push -u origin master
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (11/11), 675 bytes | 675.00 KiB/s, done.
Total 11 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/timoCS90/ProjectX/pull/new/master
remote:
To https://github.com/timoCS90/ProjectX
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

49157@DESKTOP-483GV34 MINGW64 ~/Desktop/ProjectX (master)
$ git checkout -b feature/add-content
Switched to a new branch 'feature/add-content'

49157@DESKTOP-483GV34 MINGW64 ~/Desktop/ProjectX (feature/add-content)
$ code .
