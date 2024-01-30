# STD23019
Login:

loging as : pouloulou
pouloulou@warchall.net's password:
Welcome to Ubuntu 22.04.3 LTS (GNU/Linux 5.4.0 x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/pro
Last login: Mon Jan 29 20:00:12 2024 from 154.126.10.139
pouloulou@warchall:~$

LEVEL0:

pour trouver la solution0 :

pouloulou@warchall:~$ cd /home/level/
pouloulou@warchall:/home/level$ ls
ca affiche les contenues dedans 
pouloulou@warchall:/home/level$ cd 00_welcome
pouloulou@warchall:/home/level/00_welcome$
pouloulou@warchall:/home/level/00_welcome$ ls
README.md
pouloulou@warchall:/home/level/00_welcome$ cat README.md
solution level0 is "bitwarrior"

LEVEL1:

pour trouver la solution1 :

pouloulou@warchall:/home/level$ cd 01_choice_tree
pouloulou@warchall:/home/level/01_choice_tree$ cd blue
pouloulou@warchall:/home/level/01_choice_tree/blue$ cd hats
pouloulou@warchall:/home/level/01_choice_tree/blue/hats$ ls 
black grey white
pouloulou@warchall:/home/level/01_choice_tree/blue/hats$ cd grey
pouloulou@warchall:/home/level/01_choice_tree/blue/hats/grey$ ls
solution
pouloulou@warchall:/home/level/01_choice_tree/blue/hats/grey$ cd solution
pouloulou@warchall:/home/level/01_choice_tree/blue/hats/grey/solution$ ls
patience
pouloulou@warchall:/home/level/01_choice_tree/blue/hats/grey/solution/patirnce$ ls
SOLUTION.txt
pouloulou@warchall:/home/level/01_choice_tree/blue/hats/grey/solution/patience$ cat SOLUTION.txt
This was just a little warmup.
The solution to level 1 is "patience" without the quotes

LEVEL2:

pour trouver la solution2 :
pouloulou@warchall:/home/level$ cd 02
pouloulou@warchall:/home/level/02$ ls -a
. .. .porb documents photos
pouloulou@warchall:/home/level/02$ cd .porb
pouloulou@warchall:/home/level/02/.porb$ ls -al
total 12
drwxr-xr-x 2 root level02 4096 Jan 11 2023 .
drwxr-xr-x 5 root level02 4096 Jan 11 2023 ..
-rw-r--r-- 1 root root      32 Jan 11 2023 .solution
pouloulou@warchall:/home/level/02/.porb$ cat .solution
The solution is HiddenIsConfig

LEVEL3 :

pour trouver la solution3 :
pouloulou@warchall:/home/level$ cd 03
pouloulou@warchall:/home/level/03$ ls -al
total 16
drwxrwxr-x  3 root    level03 4096 Jan 11  2023 .
drwxr-xr-x 19 root    root    4096 Feb 11  2023 ..
-rw-r--r--  1 level03 level03  122 Jan 11  2023 .bash_history
drwxr-xr-x  3 level03 level03 4096 Jan 11  2023 .local
pouloulou@warchall:/home/level/03$ cat .bash_history
The solution to SSH3 is: RepeatingHistory
ls
whoami
exit
ls
ls -asl
nano .bash_history
ls -asl
cat .bash_history
ls -asl
pouloulou@warchall:/home/level/03$

LEVEL4 :

pour trouver la solution4 :
pouloulou@warchall:/$ cd /home/user/pouloulou/level
pouloulou@warchall:~/level$ ls
04_kwisatz
pouloulou@warchall:~/level$ cd 04_kwisatz/
pouloulou@warchall:~/level/04_kwisatz$ ls
README.txt  README2.md
pouloulou@warchall:~/level/04_kwisatz$ cat README2.md
-bash: cat: README2.md/: Permission denied
pouloulou@warchall:~/level/04_kwisatz$ ls -l README2.md
-rwx------ 1 pouloulou pouloulou 248 Jan 23 19:16 README2.md
pouloulou@warchall:~/level/04_kwisatz$ chmod 700 README2.md
pouloulou@warchall:~/level/04_kwisatz$ cat README2.md
# Congratulations!

Dear Challenger,

WarChall got erased once,
hence, the original message is lost.

I think kwisatz wanted to say:

Hey there, welcome to wechall!

 - kwisatz


## Flag

Your flag is: "AndOfCourseIDoKnowChown" without the quotes.
