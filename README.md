# LR6
Лабораторная работа №6
## Цель лабораторной работы: 
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  

## Ход работы

### Операции
746f8ec - 2023-11-16 - 4217 Матренина Е.А: Отчет 2  
24f580a - 2023-11-16 - 4217 Матренина Е.А: Отчет 1  
1028f35 - 2023-11-16 - 4217 Матренина Е.А: Файл изменен  
8aa4fe9 - 2023-11-16 - 4217 Матренина Е.А: Конфликт разрешен  
51252c9 - 2023-11-16 - liza: commit 1  
921f53b - 2020-11-21 - Kurtyanik: Обновление информации  
0f9f50d - 2020-11-21 - Kurtyanik: Заполнил файл  
c08a654 - 2020-11-21 - Kurtyanik: Файл создан пустым  
3c6e913 - 2020-11-21 - Kurtyanik: Initial commit  

### Лог команд 
cd c:  
cd labs  
git clone https://github.com/24kaa/LR6  
cd LR6  
git pull  
git log  --all  
git log -n 1  
git merge origin/branch1  
git status  
cat mergefile.txt  
git add .  
git commit -m "Конфликт разрешен"  
git push origin -d branch1  
git add .  
git commit -m "Файл изменен"  
git add .  
git commit -m "Файл изменен второй раз" 
git reset --hard HEAD^  
git checkout -b vetochka  
git add .  
git commit -m "Отчет 1"  
git add .  
git commit -m "Отчет 2"  
git log --pretty=format:"%h - %ad - %an: %s" --date=short  
git add .  
git commit -m "Отчет 3"  
git push origin vetochka  

### Изображения
Изображение консоли  
![Первый скриншот](https://github.com/24kaa/LR6/blob/vetochka/screenshots/s1.jpg)  

Изображения консоли  
![Второй скриншот](https://github.com/24kaa/LR6/blob/vetochka/screenshots/s2.jpg)  

Изображения консоли  
![Третий скриншот](https://github.com/24kaa/LR6/blob/vetochka/screenshots/s3.jpg)  

Изображение консоли  
![Четвертый скриншот](https://github.com/24kaa/LR6/blob/vetochka/screenshots/s4.jpg)  

Изображение консоли  
![Пятый скриншот](https://github.com/24kaa/LR6/blob/vetochka/screenshots/s5.jpg)  

## Вывод: 
Я изучила базовые возможности системы управления версиями, получила опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.  
