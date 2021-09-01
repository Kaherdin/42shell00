# 42shell00
ex00: OK 
ex01: OK 
ex02: KO 
ex03: OK 
ex04: OK 
ex05: OK 
ex06: OK 
ex07: OK 
ex08: KO 
ex09: KO

```
= Host-specific information ====================================================
$> hostname; uname -msr
c2r6s5.42lausanne.ch
Darwin 19.6.0 x86_64
$> date
Wed Sep  1 12:05:15 CEST 2021
$> gcc --version
Configured with: --prefix=/Applications/Xcode.app/Contents/Developer/usr --with-gxx-include-dir=/Library/Developer/CommandLineTools/SDKs/MacOSX10.15.sdk/usr/include/c++/4.2.1
Apple clang version 12.0.0 (clang-1200.0.32.28)
Target: x86_64-apple-darwin19.6.0
Thread model: posix
InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin
$> clang --version
Apple clang version 12.0.0 (clang-1200.0.32.28)
Target: x86_64-apple-darwin19.6.0
Thread model: posix
InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin

= User files collection ========================================================
Collecting user files from Vogsphere
Repository URL: git@vogsphere.42lausanne.ch:vogsphere/intra-uuid-9ae143db-b6c2-4431-900c-d80674281080-3757833

= Git history ==================================================================
$> git -C /tmp/tmpmxnnj8zo/user log --pretty='%H - %an, %ad : %s'
3f6d0cacdc09941a04b82c9e156b7ea14840f268 - Aurelien Borst, Wed Sep 1 00:07:15 2021 +0200 : ex09
7360cb3620655d11d700167ecc7788db528c6c80 - Aurelien Borst, Tue Aug 31 23:19:14 2021 +0200 : correction
ef9db483a568656f6eba93490de4ca6fa6d12660 - Aurelien Borst, Tue Aug 31 15:38:46 2021 +0200 : Correction
4f47d6893aee9218a1f231119ffee7b858218b2a - Aurelien Borst, Tue Aug 31 10:53:46 2021 +0200 : Cleaning2
fdd2487ff79e26a7306016bcbf4062ef8cd6056b - Aurelien Borst, Tue Aug 31 10:50:38 2021 +0200 : Cleaning
8db35fb0137e3e63d19cec6864019399bd08bf65 - Aurelien Borst, Mon Aug 30 21:17:36 2021 +0200 : add ex08 clean
c08cfccb50b38b8d4ea157497bd970c84dbe3245 - Aurelien Borst, Mon Aug 30 20:54:31 2021 +0200 : ex07 with all
acd7b8b725e8b5be4abd978714b5eb4cd0ad38fd - Aurelien Borst, Mon Aug 30 20:24:53 2021 +0200 : Better ex05 (git check-ignore **/*)
470b02d3320e4f63e51eb3eb3e32102922f2baf8 - Aurelien Borst, Mon Aug 30 20:14:04 2021 +0200 : Add git_ignore.sh
ecd5515c65d28b3f2b84d98bbb5180e5f200dfe8 - Aurelien Borst, Mon Aug 30 20:10:19 2021 +0200 : add ignore.txt
9e55e8a832046996cb4ecdbdd7acfcddd0935c76 - Aurelien Borst, Mon Aug 30 20:08:54 2021 +0200 : add gitignore
3f34d6e7af6888f3eebe98e6c77a0d0b3a9112e4 - Aurelien Borst, Mon Aug 30 19:54:09 2021 +0200 : cleaning
9c300964ae7f3e25c249d6711dbd7303fd0ec8c6 - Aurelien Borst, Mon Aug 30 19:49:21 2021 +0200 : remove coucou foldert
fad8195422355331a26cadd46c4f0b8aa92dea23 - Aurelien Borst, Mon Aug 30 19:48:19 2021 +0200 : parent folder commit
8c06b081942cb09eacdda0069bda611621921139 - Aurelien Borst, Mon Aug 30 18:45:43 2021 +0200 : 5 commit
5317b78f8d8d8ddc2e210fd28ee061a66c435413 - Aurelien Borst, Mon Aug 30 18:45:33 2021 +0200 : 4 commit
1a00c4f0e4b6683a136f996eb6accbe689175049 - Aurelien Borst, Mon Aug 30 18:45:23 2021 +0200 : 3 commit
6de77351a7022e4cd118b0535ebe5d98c641d175 - Aurelien Borst, Mon Aug 30 18:45:13 2021 +0200 : 2 commit
3c610b5104e11ee056bf7dd4e1e54da8826cb302 - Aurelien Borst, Mon Aug 30 18:44:48 2021 +0200 : 1er commit
 
= Collected files ==========================================
$> ls -lAR /tmp/tmpmxnnj8zo/user
total 24
-rw-r--r--  1 root  wheel    29 Sep  1 12:05 .gitignore
-rw-r--r--  1 root  wheel  6837 Sep  1 12:05 __GIT_HISTORY
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex00
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex01
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex02
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex03
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex04
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex05
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex06
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex07
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex08
drwxr-xr-x  3 root  wheel    96 Sep  1 12:05 ex09

/tmp/tmpmxnnj8zo/user/ex00:
total 8
-rw-r--r--  1 root  wheel  2 Sep  1 12:05 z

/tmp/tmpmxnnj8zo/user/ex01:
total 8
-rw-r--r--  1 root  wheel  2048 Sep  1 12:05 testShell00.tar

/tmp/tmpmxnnj8zo/user/ex02:
total 16
-rw-r--r--  1 root  wheel  6144 Sep  1 12:05 exo2.tar

/tmp/tmpmxnnj8zo/user/ex03:
total 8
-rw-r--r--  1 root  wheel  236 Sep  1 12:05 klist.txt

/tmp/tmpmxnnj8zo/user/ex04:
total 8
-rw-r--r--  1 root  wheel  9 Sep  1 12:05 midLS

/tmp/tmpmxnnj8zo/user/ex05:
total 8
-rw-r--r--  1 root  wheel  23 Sep  1 12:05 git_commit.sh

/tmp/tmpmxnnj8zo/user/ex06:
total 8
-rw-r--r--  1 root  wheel  43 Sep  1 12:05 git_ignore.sh

/tmp/tmpmxnnj8zo/user/ex07:
total 8
-rw-r--r--  1 root  wheel  538 Sep  1 12:05 b

/tmp/tmpmxnnj8zo/user/ex08:
total 8
-rw-r--r--  1 root  wheel  19 Sep  1 12:05 clean

/tmp/tmpmxnnj8zo/user/ex09:
total 8
-rw-r--r--  1 root  wheel  20 Sep  1 12:05 ft_magic
 
= ex00 =========================================================================
$> diff -U 3 z ref_output | cat -e


Diff OK :D
Grade: 5

= ex01 =========================================================================
total 8
-rw-r--r--  1 deepthought  deepthought  2048 Sep  1 10:05 testShell00.tar


-r--r-xr-x  1 deepthought  deepthought  40 Jun  1 21:42 testShell00


Grade: 5

= ex02 =========================================================================
total 16
-rw-r--r--  1 deepthought  deepthought  6144 Sep  1 10:05 exo2.tar



KO test0
Grade: 0

= ex03 =========================================================================
total 8
-rw-r--r--  1 deepthought  deepthought  236 Sep  1 10:05 klist.txt


        Principal: aborst@42LAUSANNE.CH


Grade: 10

= ex04 =========================================================================
total 16
-rw-r--r--  1 deepthought  deepthought    9 Sep  1 10:05 midLS
-rw-r--r--  1 deepthought  deepthought  536 Sep  1 10:05 test_midls.sh


$> sh ./test_midls.sh
< our file, > your file
ok


< our file, > your file
ok

Grade: 10

= ex05 =========================================================================
total 24
-rw-r--r--  1 deepthought  deepthought   23 Sep  1 10:05 git_commit.sh
-rw-r--r--  1 deepthought  deepthought  266 Sep  1 10:05 start.sh
-rw-r--r--  1 deepthought  deepthought   27 Sep  1 10:05 test_git_commit.sh


warning: templates not found in /usr/share/git-core/templates
Initialized empty Git repository in /tmp/qfph8b74/.git/

[master (root-commit) 205d37c] commit toto.dylib
 Committer: Deepthought <deepthought@c2r6s5.42lausanne.ch>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 toto.dylib
[master 31d9684] commit notice_me_senpai
 Committer: Deepthought <deepthought@c2r6s5.42lausanne.ch>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 notice_me_senpai

[master f9da7b9] commit top_secret
 Committer: Deepthought <deepthought@c2r6s5.42lausanne.ch>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 top_secret

[master 81cd79b] commit yoyo.test
 Committer: Deepthought <deepthought@c2r6s5.42lausanne.ch>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 yoyo.test
[master d6ae6a3] commit resultat_selection_piscine
 Committer: Deepthought <deepthought@c2r6s5.42lausanne.ch>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 resultat_selection_piscine

[master b4db319] commit test.test.test
 Committer: Deepthought <deepthought@c2r6s5.42lausanne.ch>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test.test.test


$> diff -U 3 user_output test_output | cat -e


Diff OK :D
OK
Grade: 10

= ex06 =========================================================================

total 24
-rw-r--r--  1 deepthought  deepthought   43 Sep  1 10:05 git_ignore.sh
-rw-r--r--  1 deepthought  deepthought  581 Sep  1 10:05 start.sh
-rw-r--r--  1 deepthought  deepthought   51 Sep  1 10:05 test_git_ignore.sh


warning: templates not found in /usr/share/git-core/templates
Initialized empty Git repository in /tmp/21zbkbat/.git/


$> diff -U 3 user_output test_output | cat -e


Diff OK :D
OK
Grade: 10

= ex07 =========================================================================
$> diff -U 3 b 42b | cat -e


Diff OK :D
Grade: 10

= ex08 =========================================================================
total 16
-rw-r--r--  1 deepthought  deepthought   19 Sep  1 10:05 clean
-rwxr-xr-x  1 deepthought  deepthought  859 Sep  1 10:05 test_clean.sh


$> sh ./test_clean.sh
find: *~: No such file or directory

KO


find: *~: No such file or directory
KO

Grade: 0

= ex09 =========================================================================
total 32
-rwxr-xr-x  1 deepthought  deepthought   21 Sep  1 10:05 correct_magic
-rw-r--r--  1 deepthought  deepthought   20 Sep  1 10:05 ft_magic
-rw-r--r--  1 deepthought  deepthought   46 Sep  1 10:05 test42
-rwxr-xr-x  1 deepthought  deepthought  711 Sep  1 10:05 test_magic.sh


$> sh ./test_magic.sh
-n testing ft_magic 1/2 ...
/usr/share/file/magic, 0: Warning: using regular magic file `correct_magic'
/usr/share/file/magic, 0: Warning: using regular magic file `./ft_magic'
< our file, > your file
1c1
< test42: 42 file$
---
> test42: ASCII text, with no line terminators$
[KO]


-n testing ft_magic 1/2 ...
/usr/share/file/magic, 0: Warning: using regular magic file `correct_magic'
/usr/share/file/magic, 0: Warning: using regular magic file `./ft_magic'
< our file, > your file
1c1
< test42: 42 file$
---
> test42: ASCII text, with no line terminators$
[KO]

Grade: 0

= Final grade: 10 ==============================================================
```
