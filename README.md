# ДЗ
```
ivanv@MSI MINGW64 ~
$pwd
/c/Users/ivanv
$mkdir homework
$cd homework
ivanv@MSI MINGW64 ~/homework
$ mkdir folder1 folder2 folder3

ivanv@MSI MINGW64 ~/homework
$ cd folder1

ivanv@MSI MINGW64 ~/homework/folder1
$ touch test1.txt test2.txt test3.txt

ivanv@MSI MINGW64 ~/homework/folder1
$ touch test3.json test4.json

ivanv@MSI MINGW64 ~/homework/folder1
$ mkdir folder4 folder5 folder6

ivanv@MSI MINGW64 ~/homework/folder1
$ ls -la
total 4
drwxr-xr-x 1 ivanv 197609 0 Apr 17 17:59 ./
drwxr-xr-x 1 ivanv 197609 0 Apr 17 17:51 ../
drwxr-xr-x 1 ivanv 197609 0 Apr 17 17:59 folder4/
drwxr-xr-x 1 ivanv 197609 0 Apr 17 17:59 folder5/
drwxr-xr-x 1 ivanv 197609 0 Apr 17 17:59 folder6/
-rw-r--r-- 1 ivanv 197609 0 Apr 17 17:55 test1.txt
-rw-r--r-- 1 ivanv 197609 0 Apr 17 17:55 test2.txt
-rw-r--r-- 1 ivanv 197609 0 Apr 17 17:56 test3.json
-rw-r--r-- 1 ivanv 197609 0 Apr 17 17:55 test3.txt
-rw-r--r-- 1 ivanv 197609 0 Apr 17 17:56 test4.json

ivanv@MSI MINGW64 ~/homework/folder1
$ vim test1.txt
i (write text)
esc-:wq

ivanv@MSI MINGW64 ~/homework/folder1
cd ..
ivanv@MSI MINGW64 ~/homework
```
_____

```
ivanv@MSI MINGW64 ~/homework
$ cd folder1

ivanv@MSI MINGW64 ~/homework/folder1
$ mv test2.txt test3.json \folder4

ivanv@MSI MINGW64 ~/homework/folder1
$ cp test3.txt test4.json \folder5

ivanv@MSI MINGW64 ~/homework/folder1
$ find . -name 'test3.json'
./folder4/test3.json

ivanv@MSI MINGW64 ~/homework/folder1
$ tail -f test1.txt

ivanv@MSI MINGW64 ~/homework/folder1
$ head -3 test1.txt

ivanv@MSI MINGW64 ~/homework/folder1
$ tail -4 test1.txt

ivanv@MSI MINGW64 ~/homework/folder1
$ less test1.txt
q(для выхода)

ivanv@MSI MINGW64 ~/homework/folder1
$ date
Mon Apr 17 18:44:59 RTZ 2023
```
___

# Задание *

ivanv@MSI MINGW64 ~/homework/folder1
$ curl http://162.55.220.72:5005/terminal-hw-request




