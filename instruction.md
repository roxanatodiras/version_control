# Инструкция по языку MarkDown

Новая строка - это олна пустая строка

**Полужирный текст**

*Курсив текст*

## Цитирование
> Первый уровень
>> Второй уровень

## Списки
### Ненумерованные списки
* Лист 1
* Лист 2
### Нумерованные списки
1. Лист 1
2. Лист 2
3. Лист 3

## WEB ссылки
Текст [пример ссылки](http.example.com "Всплывающая подсказка")

## Работа с таблицами

Буква | Цифра | Символ
------ | ------|----------
a      | 4     | $
x      | 365    | (
b      |       | ^  

Буква|Цифра|Символ
---|---|---
a|4|$
 |365|(
b| |^  

Column | Column
------ | ------
\| Cell \|| \| Cell \|  


Column | Column | Column
:----- | :----: | -----:
Left   | Center | Right
align  | align  | align

## Картинки

### Это яблоко

![apple](apple.jpg)

### Это апельсин

![orange](orange.png)

## Working with remotes

### Showing Your Remotes
To see which remote servers you have configured, you can run the:
```sh
 git remote
```
 command. It lists the shortnames of each remote handle you’ve specified. If you’ve cloned your repository, you should at least see origin
 ### Adding Remote Repositories
 To add a new remote Git repository as a shortname you can reference easily, run:
 ```sh
 git remote add [shortname] [url]
```

### Pushing to Your Remotes
When you have your project at a point that you want to share, you have to push it upstream. The command for this is simple:
```sh
 git push [remote-name] [branch-name]
```
### Pulling from Your Remotes
you can use the:
```sh
git pull
```
command to automatically fetch and then merge a remote branch into your current branch.

*Running git pull generally fetches data from the server you originally cloned from and automatically tries to merge it into the code you’re currently working on.*