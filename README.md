ELKA 02@DESKTOP-I3GM46A MINGW64 ~ (master)
$ mkdir git-basic

ELKA 02@DESKTOP-I3GM46A MINGW64 ~ (master)
$ cd git-basic

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ touch first.txt

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git init .
Initialized empty Git repository in C:/Users/ELKA 02/git-basic/.git/

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git add .

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git commit -m "adding first.txt"
[master (root-commit) f239f4e] adding first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 first.txt

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git log
commit f239f4e00dcc5b7de35adbc2f3715a643870ce7e (HEAD -> master)
Author: Anyman-28 <hilmanarifinilham28@gmail.com>
Date:   Thu Jul 28 08:02:55 2022 +0700

    adding first.txt

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ touch second.txt

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git add second.txt

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git commit -m "adding second.txt"
[master 60eed34] adding second.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 second.txt

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ rm first.txt

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git add .

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git commit -m "removing first.txt"
[master cf53edb] removing first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 first.txt

ELKA 02@DESKTOP-I3GM46A MINGW64 ~/git-basic (master)
$ git log
commit cf53edbbed5ecc776f8c56d2d7e6cb810f5294e4 (HEAD -> master)
Author: Anyman-28 <hilmanarifinilham28@gmail.com>
Date:   Thu Jul 28 08:07:00 2022 +0700

    removing first.txt

commit 60eed34dd46e59e73cb98a3a455f2a954c278d20
Author: Anyman-28 <hilmanarifinilham28@gmail.com>
Date:   Thu Jul 28 08:05:25 2022 +0700

    adding second.txt

commit f239f4e00dcc5b7de35adbc2f3715a643870ce7e
Author: Anyman-28 <hilmanarifinilham28@gmail.com>
Date:   Thu Jul 28 08:02:55 2022 +0700

    adding first.txt
