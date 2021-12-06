# GIT Homework - repository JSON 
TXT
 1. Создать внешний репозиторий c названием TXT. `+ -> new repository -> заполнить поле "Repository name" -> чек бокс "Add a README file" -> кликнуть кнопку "create repository"`
 2. Клонировать репозиторий TXT на локальный компьютер. `git clone https://github.com/Pavlik1100/TXT.git`  
 3. Внутри локального TXT создать файл “new.txt”. `> new.txt`  
 4. Добавить файл под гит. `git add new.txt`  
 5. Закоммитить файл. `git commit -m "create file new.txt"`  
 6. Отправить файл на внешний GitHub репозиторий. `git push`  
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.  

`vim new.txt`
```sh  
FIO - SimonovPavelSergeevich  
age -28  
home_pets - 0  
salary - 1000  
```  
 8. Отправить изменения на внешний репозиторий.  
```sh  
git commit -am "update new.txt"  
git push  
```  
 9. Создать файл preferences.txt `> preference.txt`  
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.   
`vim preferences.txt`  
```sh  
favourite_film - Blade_runner  
favourite_serial - LOST  
favourite_food - fried_chiken    
favourite_time_of_the_year - summer  
next_visit_country - USA    
```  
  
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT  
```sh
> skills.txt  
vim sklls.txt 
```
```sh
skill_1 - why_QA    
skill_2 - when_QA    
skill_3 - where_QA    
```
 12. Сделать коммит в одну строку. `Так как файлы только созданы и небыли git add то добавление и коммит в одной строке не выйдет. Однако при следующем изменении добавить и закомитить можно будет одной строкой`
```sh  
 git add prefereces.txt skills.txt  
 git commit -m "added files preferences.txt skills.txt"  
```

 13. Отправить сразу 2 файла на внешний репозиторий. `git push`  
 14. На веб интерфейсе создать файл bug_report.txt. `add new file -> заполнить поле названия файла`   
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. `добавить commit в поле "commit changes" -> отметить чекбокс "commit directory to the main branch" -> нажать кнопку "commit changes"`
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT. `выбрать в дериктории файл для редактирования, кликнуть чтобы открыть -> нажать кнопку с карандашом "Edit this file" -> ввести данные в формате TXT`
```sh
Title - Button_'Home'_dont_click  
Steps - Open_web_and_click_button_'Home'  
Facual_result - When_button_click_nothing_is_happening  
Expected_result - When_button_click_we_back_home_page  
Severity - Medium   
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. `добавить commit в поле "commit changes" -> отметить чекбокс "commit directory to the main branch" -> нажать кнопку "commit changes"`  
 18. Синхронизировать внешний и локальный репозиторий TXT `git pull`
