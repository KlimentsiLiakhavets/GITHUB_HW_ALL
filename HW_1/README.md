```
1) Посмотреть где я					pwd			"/d/QA"
2) Создать папку					mkdir task_1
3) Зайти в папку					cd task_1
4) Создать 3 папки					mkdir -p {a_1,a_2,a_3}
5) Зайти в любоую папку					cd a_1
6) Создать 5 файлов (3 txt, 2 json)			touch {1.txt,2.txt,3.txt,4.json,5.json}
7) Создать 3 папки					mkdir -p {b_1,b_2,b_3}
8. Вывести список содержимого папки			ls -la         		"можно ls -f  или ls -a"
drwxr-xr-x 1 wolf 197121 0 Jan  5 21:19 ./
drwxr-xr-x 1 wolf 197121 0 Jan  5 21:08 ../
-rw-r--r-- 1 wolf 197121 0 Jan  5 21:15 1.txt
-rw-r--r-- 1 wolf 197121 0 Jan  5 21:15 2.txt
-rw-r--r-- 1 wolf 197121 0 Jan  5 21:15 3.txt
-rw-r--r-- 1 wolf 197121 0 Jan  5 21:15 4.json
-rw-r--r-- 1 wolf 197121 0 Jan  5 21:15 5.json
drwxr-xr-x 1 wolf 197121 0 Jan  5 21:19 b_1/
drwxr-xr-x 1 wolf 197121 0 Jan  5 21:19 b_2/
drwxr-xr-x 1 wolf 197121 0 Jan  5 21:19 b_3/
9) + Открыть любой txt файл  				vim 1.txt
10) + написать туда что-нибудь, любой текст		i
	Человеку надо мало
	Чтоб искал и находил.
	Чтоб имелись для начала
	Друг - один
	И враг - один.
	Человеку надо мало
	Чтоб тропинка вдаль вела.
	Чтоб жила на свете мама
	Сколько нужно ей - жила
11) + сохранить и выйти.				Esc :wq
12) Выйти из папки на уровень выше			cd ..
13) переместить любые 2 файла, которые вы создали,
 в любую другую папку.					mv /d/QA/task_1/a_1/1.txt /d/QA/task_1/a_2/1.txt
							mv /d/QA/task_1/a_1/2.txt /d/QA/task_1/a_2/2.txt
						или
							mv a_1/{1.txt,2.txt} a_2

14) скопировать любые 2 файла, которые вы создали, 
в любую другую папку.					cp /d/QA/task_1/a_1/4.json /d/QA/task_1/a_2/4.json
							cp /d/QA/task_1/a_1/5.json /d/QA/task_1/a_2/5.json
						или
							cp a_1/{4.json,5.json} a_2

15) Найти файл по имени					find -name 1.txt
16) просмотреть содержимое в реальном времени.		tail -f /d/QA/task_1/a_2/1.txt
17) вывести несколько первых строк из 
текстового файла					head -3 /d/QA/task_1/a_2/1.txt
18) вывести несколько последних строк из 
текстового файла					tail -3 /d/QA/task_1/a_2/1.txt
19) просмотреть содержимое длинного файла.		less /d/QA/task_1/a_2/1.txt
20) вывести дату и время				date
