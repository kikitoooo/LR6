# Лабораторная работа №6
## Цель работы
Изучение базовых возможностей системы
управления версиями, опыт работы с Git Api, опыт работы с локальным и
удаленным репозиторием.
## Ход работы
### 1. Создание форка репозитория
### 2. Настройка клиента
```
git config user.name "4218 Puchok Nikita Sergeevich"
git config user.email nik.puchok@gmail.com
```
### 3. Клонирование удаленного репозитория
```
git clone https://github.com/Kurtyanik/LR6
```
### 4. Добавление test.txt через интерфейс GitHub. Подтяжка изменений в локальный репозиторий. ([См. рис. 1](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-commit.png))
```
cat > test.txt
<INFORMATION>
git add test.txt
git commit -m "Add text file"
```
### 5. Получение истории операций для каждой из веток. ([См. рис. 2](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-log.png))
```
git log - ветка master
git log origin/branch1 - ветка branch1
```
### 6. Просмотр последних изменений. ([См. рис. 3](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-branch%20-v.png))
```
git branch -v
```
### 7. Слияние в ветку master. ([См. рис. 4](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-merge.png))
```
git merge branch1
```
### 8. Удаление побочной ветки после слияния. ([См. рис. 5](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-branch%20-d.png))
```
git branch -d branch1
```
### 8. Сохдание нескольких изменений с коммитами. ([См. рис. 5](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-commit.png))
```
git add .
git commit -m "<comment>"
```
### 9. Откат последнего коммита ([См. рис. 6](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-reset%20--hard.png))
```
git reset --hard @~
```
### 10. Создание ветки для отчёта
```
git branch Otchet
```
### 11. Оформление отчета в файле README.md
### 12. Получение истории операций в форматированном виде. ([См. рис. 7](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-log%20-v.png))


## <b>Лог команд:</b>
1. git status - просмотр статуса файлов <br>
   ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-status.png?raw=true)
2. git add - добавление файлов в индекс 
3. git commit - создание коммита <br>
   ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-commit.png?raw=true)
4. git branch - просмотр веток <br>
   ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-branch.png?raw=true)
5. git checkout - переход к указаной ветка <br>
   ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-checkout.png?raw=true)
6. git config user.name - указание имени пользователя 
7. git config user.email - указание почты пользователя
8.  git log - просморт изменений проекта <br>
    ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-log.png?raw=true)
9.  git merge - обьединение веток <br>
    ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-merge.png?raw=true)
10. git branch -d - удаление ветки <br>
    ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-branch%20-d.png?raw=true)
11. git reset --hard - откат коммита <br>
    ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-reset%20--hard.png?raw=true)
12. git log -v - просмотр автора и времени изменений <br>
    ![](https://github.com/kikitoooo/LR6/blob/Otchet/photo/git-log%20-v.png?raw=true)

## Вывод
В ходе работы были изучены базовые возможности системы
управления версиями, опыт работы с Git Api, опыт работы с локальным и
удаленным репозиторием.