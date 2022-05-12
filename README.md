# JSON
### 1. Создать внешний публичный репозиторий c названием JSON
- Перейти в [профиль github](https://github.com/NatalyaGolt, "NatalyaGolt github profile")
  
- Перейти на вкладку репозиториев 

  |Repositories|
  |------------|
  
- Создать новый репозиторий
  
  |New|
  |---|
  
- Ввести имя репозитория
  
 
  |JSON :white_check_mark:|
  |-----------------------|
  
- Добавить Readme.md файл

  |:ballot_box_with_check: Add README file|
  |---------------------------------------|
- Создать репозиторий
  
  |Create repository|
  |-----------------|
### 2. Клонировать репозиторий JSON на локальный компьютер
    git clone https://github.com/NatalyaGolt/JSON.git
### 3. Внутри локального JSON создать файл “new.json”
    touch XML/new.json
### 4. Добавить файл под гит
    cd JSON && git add new.json
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

    esc - выход из режима редактирования

    :wq - возврат к командной строке
### 12. Отправить сразу 2 файла на внешний репозиторий
    git add . && git commit -m "add two files" && git push
### 13. На веб интерфейсе создать файл bug_report.json
Находясь во внешнем репозитории JSON
- Нажать на кнопку Добавить файл
  
  |Add file|
  |--------|
- Нажать Создать новый файл
  
  |Create new file|
  |---------------|
- Ввести имя и расширение файла
  
  |JSON/bug_report.json|
  |--------------------|
### 14. Сделать Commit на веб интерфейсе
Нажать кнопку Закоммитить новый файл

  |Commit new file|
  |---------------|

### 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
- На внешнем репозитории выбрать файл bug_report.json 
  
  |bug_report.json|
  |---------------|

- Нажать кнопку редактирования файла

  |:pencil2:|
  |---------|

- Написать баг репорт в формате json

   {
    "id":"001",
    "summary":"Can't send the email. Button 'send' is inactive",
    "environment":"PC Windows 10, Google Chrome v 101.0.4951.41",
    "precondisions":"autorisation in email",
    "steps":
    [
      "1. Push button 'write'",
      "2. Insert receiver email in 'whom' field",
      "3. Write the message",
      "4. Push button 'send'"
    ],
    "expected result":
    [
      "1. Letter window is opened",
      "2. Can add an adress",
      "3. Can write the message",
      "4. The letter sent sucsessfully. Window shows the message 'sent'"
    ],
    "actual result":
     [
      "1. Letter window is opened",
      "2. Can add an adress",
      "3. Can write the message",
      "4. Can't send the email. Button 'send' is inactive"
     ],
    "priority":"P1",
    "severity":"S1",
    "assign":"Email developer"
  }

### 16.  Сделать Commit changes (сохранить) изменения на веб интерфейсе
Нажать кнопку Закоммитить изменения

|Commit changes|
|--------------|

### 17. Синхронизировать внешний и локальный репозиторий JSON
    git pull
