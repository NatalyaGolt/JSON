# JSON
### 1. Создать внешний публичный репозиторий c названием JSON
- Перейти в [профиль github](https://github.com/NatalyaGolt, "NatalyaGolt github profile")
  
- Перейти на вкладку репозиториев
  
  <img src="https://1.downloader.disk.yandex.ru/preview/9f50482d806f9d83a6cd1f87fad35f86239759470050468d77144f55ae49990e/inf/CUDKqTwaJe4hf9dMTxVsfE8qzhPSJypVPykKtg9OjXySsw9wVa9prnVU6EhyoU_mFA2nWtP0yjC5pxyJhyhfIA%3D%3D?uid=40883143&filename=Repositories.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=40883143&tknv=v2&size=1318x628" alt="Repositories" align=center>
  
- Создать новый репозиторий
  
  <img src="New.png" alt="New" align=center>
  
- Ввести имя репозитория
  
  <img src="Repository name.png" alt="Repository name" align=center>
  
- Добавить Readme.md файл
- 
  <img src="Add readme.png" alt="Add readme" align=center>
- Создать репозиторий
  
    <img src="Create repository.png" alt="Create repository" align=center>
### 2. Клонировать репозиторий JSON на локальный компьютер
    git clone https://github.com/NatalyaGolt/JSON.git
### 3. Внутри локального JSON создать файл “new.json”
    git clone https://github.com/NatalyaGolt/JSON.git
### 4. Добавить файл под гит
    cd JSON
    git add new.json
### 5. Закоммитить файл
    git commit -m "add new.json"
### 6. Отправить файл на внешний GitHub репозиторий
    git push
### 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON
    cat >> new.json
    {
    "name":"Natalya",
    "age":"30",
    "pets":"0",
    "salary":"2000$"
    }

    ctrl+C - для выхода из режима редактирования

### 8. Отправить изменения на внешний репозиторий
    git add new.json && git commit -m "change new.json" && git push   
### 9. Создать файл preferences.json
    touch preferences.json
### 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON
    cat >> preferences.json
    {
    "movie":"The prestige",
    "series":"Friends",
    "food":"borsh",
    "season":"summer",
    "country":"Iceland"
    }

    ctrl+C - для выхода из режима редактирования
### 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
    vim skills.json

    i - для редактирования файла

    {
            "skill1":"Linux Terminal/gitbash",
            "skill2":"JavaScript",
            "skill3":"Autotests in Postman"
    }

    esc - выход из режима реадактирования

    :wq - возврат к командной строке
### 12. Отправить сразу 2 файла на внешний репозиторий
    git add . && git commit -m "add two files" && git push
### 13. На веб интерфейсе создать файл bug_report.json
Находясь во внешнем репозитории JSON
- Нажать на кнопку Добавить файл
  
  <img src="Add file.png" alt="Add file" align=center>
- Нажать Создать новый файл
  
  <img src="Create new file.png" alt="Create new file" align=center>
- Ввести имя и расширение файла
  
  <img src="File name.png" alt="File name" align=center>
### 14. Сделать Commit на веб интерфейсе
Нажать кнопку Закоммитить новый файл

<img src="Commit new file.png" alt="Commit new file" align=center>

### 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
- На внешнем репозитории выбрать файл bug_report.json 
  
<img src="File bug_report.json.png" alt="File bug_report.json" align=center>

- Нажать кнопку редактирования файла

<img src="Edit this file.png" alt="Edit this file" align=center>

- Написать баг репорт в формате json

<img src="Bug report.png" alt="Bug report" align=center>

### 16.  Сделать Commit changes (сохранить) изменения на веб интерфейсе
Нажать кнопку Закоммитить изменения

<img src="Commit changes.png" alt="Commit changes" align=center>

### 17. Синхронизировать внешний и локальный репозиторий JSON
    git pull