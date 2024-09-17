# Лабораторная работа 1

Сдалал: `Ахмедов Бахадыр`

## Шаг 1
* Для того чтобы модифицировать файл `script.bash` открываем файл используя любой текстовый редактор, в моем случае это `vim`

<img width="500" src="./images/img_1.png"/>

* Содержимое файла `script.bash`:

<img width="500" src="./images/img_2.png"/>

## Шаг 2
* Заменяем строку `echo "Welcome to ITMO University"` на `"Welcome, $*"` где специальная переменная `$*"` выведит список всех позиционных аргументов, для того чтобы изменить строку в `vim` нажимаем  `I` для чтобы перейти в `Insert mode` 

<img width="500" src="./images/img_3.png"/>

 * Затем нажимаем `Esc` для того чтобы перейти в `Normal mode`

<img width="500" src="./images/img_4.png"/>

 * Зажимае `Shift + :` прописываем `wq` для того чтобы сохранить изменения и выйти из файла, нажимаем `Enter`

<img width="500" src="./images/img_5.png"/>

## Шаг 3
* Проверяем `script.bash` на работоспособность передаем два аргумента `Vasya Pupkin`

<img width="500" src="./images/img_6.png"/>

* Вводим большее количество аргументов `Benedict Timothy Carlton Cumberbatch`

<img width="600" src="./images/img_7.png"/>
