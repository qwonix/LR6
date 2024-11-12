# Отчет по выполнению лабораторной работы №6

## Шаги выполнения

### 1. Создание аккаунта на GitHub
Создан аккаунт на сайте [GitHub](https://github.com).
![](screenshots/Screen-070.png)

### 2. Форк репозитория
Сделан форк репозитория [Kurtyanik/LR6](https://github.com/Kurtyanik/LR6) в личное хранилище.
![](screenshots/Screen-053.png)

### 3. Установка Git
Git уже установлен с официального сайта [git-scm.com](https://git-scm.com).
![](screenshots/Screen-047.png)

### 4. Настройка Git
Настроен клиент git:
```bash
git config --global user.name "В3441 Кулаков Р.С."
git config --global user.email "roman.qwonix@gmail.com"
```
![](screenshots/Screen-049.png)

### 5. Клонирование репозитория
Личный удалённый репозиторий клонирован на локальный компьютер:
```bash
git clone https://github.com/qwonix/LR6.git
```
![](screenshots/Screen-050.png)

### 6. Добавление файла через интерфейс GitHub
Файл добавлен через интерфейс GitHub. Изменения подтянуты в локальный репозиторий:
```bash
git pull
```
![](screenshots/Screen-055.png)
![](screenshots/Screen-054.png)
![](screenshots/Screen-056.png)

### 7. Получение истории операций
История операций для каждой ветки получена:
```bash
git log
```
![](screenshots/Screen-057.png)

### 8. Просмотр последних изменений
Просмотр последних изменений:
```bash
git diff
```
![](screenshots/Screen-057.png)

### 9. Слияние в ветку master
Слияние выполнено, конфликт разрешён:
```bash
git merge branch1
```
![](screenshots/Screen-059.png)
![](screenshots/Screen-060.png)
![](screenshots/Screen-061.png)
![](screenshots/Screen-062.png)
![](screenshots/Screen-063.png)

Конфликт разрешён с использованием редактора **nano**.

### 10. Удаление побочной ветки
Побочная ветка удалена:
```bash
git branch -d branch1
```
![](screenshots/Screen-065.png)

### 11. Фиксация изменений
Сделаны несколько изменений и зафиксированы с комментариями:
```bash
git add .
git commit -m "comment"
```
![](screenshots/Screen-068.png)

### 12. Откат коммита
Откат коммита выполнен:
```bash
git reset --hard HEAD~1
```
![](screenshots/Screen-069.png)

### 13. Создание ветки для отчёта
Создана новая ветка:
```bash
git checkout -b report
```

### 14. Оформление отчёта
Отчёт оформлен в файле `README.md` с использованием Markdown. 
Скриншоты помещены в папку `screenshots`.

---

## Лог команд

```bash
git clone https://github.com/qwonix/LR6.git
git pull
git log
git diff
git merge branch1
git branch -d branch1
git add .
git commit -m "comment"
git reset --hard HEAD~1
git checkout -b report
```