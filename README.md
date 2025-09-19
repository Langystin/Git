Тюлев Лев
11.24.2
TyulevLO23@spb.ithub.ru
## Инструкция по созданию репозитория

1) **Заходим на сайт github**

<img width="1418" height="1034" alt="image" src="https://github.com/user-attachments/assets/8132d305-7218-48a5-8571-371e702f5f35" />

2) **Нажимаем на кнопку New чтобы создать репозиторий**

<img width="1395" height="1034" alt="image" src="https://github.com/user-attachments/assets/a5b35a10-23f4-4985-8b31-d656b622819d" />

3) **Задаем имя репозиторию и делаем его публичным**

<img width="1406" height="1034" alt="image" src="https://github.com/user-attachments/assets/edbad46c-79b5-4101-891a-7cae493c17f9" />

4) **Cоздаем репозиторий с новым файл** (creating a new file) **или загружаем существующий** (uploading an existing file)

<img width="1404" height="1045" alt="image" src="https://github.com/user-attachments/assets/8bee38d8-ba90-45de-8ac2-0d93e2e98f8c" />

5) **Закидываем или создаем файл и нажимаем** "commit changes"

<img width="1406" height="1036" alt="image" src="https://github.com/user-attachments/assets/0e65cd3b-9f82-4fce-a003-9ca4652baef7" />

6) **Создаем репозиторий и нажимаем на файл** (в моем случае) git.txt.txt

<img width="1422" height="1043" alt="image" src="https://github.com/user-attachments/assets/1e277846-ae73-4d48-9efb-df203697af99" />

7) **Нажимаем на карандаш и пишем в файле то что нужно**

<img width="1410" height="1033" alt="image" src="https://github.com/user-attachments/assets/b83b1cc0-c203-4285-883b-81bc6bcf4dd7" />

8) **Нажимаем на** "commit changes"

<img width="1397" height="1043" alt="image" src="https://github.com/user-attachments/assets/4fdeb7b1-b71e-4d7e-abb7-b292da14e2f0" />

9) **Итог:** Создания репозитория.

<img width="1600" height="42" alt="image" src="https://github.com/user-attachments/assets/290bda1a-a0d4-4912-ad48-93b8ea5d9aa6" />


## Инструкция по клонированию репозитория

Для того чтобы клонировать репозиторий с GitHub'a нужно сделать следующие действия

1) **Открыть терминал**. (Сделать это можно в терминале в VS Code)
2) **Перейти в папку куда будет сохраняться проект** с помощью **команды** `cd` с указанием пути файла.
```bash
cd Documents/Project
```
3) **Скопировать URL репозитория на GitHub**
3.1) Зайти на страницу репозитория
3.2) Найти и нажать на кнопку **"<> Code"**.
3.3) Скопировать предложенный URL
4) **Выполнить команду** `git clone`, вставив скопированный URL:
```bash
git clone <URL>
```
5) **Итог:** Выполнения команды в выбранной папке и появления копий всех файлов репозитория.

## Инструкция по загрузке коммита

1) **Переходим в папку репозитория с помощью команды** `cd`
```bash
cd <имя репозитория>
```
2) **Добавляем изменные файлы в индекс** с помощью команды `git add` указывая конкретный файл
```bash
git add README.md
```
3) **Создаем коммит с комментарием который опизывается изменение**.
```bash
git commit -m "Инструкция по загрузке коммита"
```
4) **Загружаем коммит на Github** с помощью команды `git push`
```bash
git push origin main/master (если основная ветка не main, а master)
```
