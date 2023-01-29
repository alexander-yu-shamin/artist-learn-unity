~~
# Глава 1

## Цели
- [ ] изучить Jira и принципы командной работы
  - [ ] выполнить первую поставленную задачу в Jira
- [ ] изучить основы Git
- [ ] форкнуть репозиторий, добавить изменения, создать пулл реквест на добавление в основной репозиторий, создать issue
- [ ] сделать merge, cherry-pick, squash

## Последовательность изучения

### Jira

- изучаем Jira:
  - изучаем общие вопросы [совместной работы над проектом](https://www.atlassian.com/ru/work-management/project-collaboration)
  - знакомимся с [общими подходами в управлении проектами](https://www.atlassian.com/ru/agile/manifesto)
  - находим свои задачи в группе [Jira: Artists learn Unity](/resources.md#jira)
  - выполняем задачу 'Chapter 1':
    - находим задачу которая назначена на нашего пользователя - и перемещаем ее в Board в In Progress состояние
    - заполняем поля: Start Date, Time tracking
    - упоминаем в комментариях ментора, добавляем его в ревьюверы (если его там нет)
    - переносим задачу в Review состояние
  - ожидаем проверку задачи (будет перемещена в Done статус)

### Git

- ознакамливаемся с курсом: [Основы работы с Git, GitHub и даже GitHub Actions | Udemy](https://www.udemy.com/course/russian-git/?start=0#overview) или [Основы Git, GitHub и GitHub Actions - YouTube](https://www.youtube.com/playlist?list=PLg5SS_4L6LYstwxTEOU05E0URTHnbtA0l)
- выбираем себе [курс](https://habr.com/ru/post/510126/) и бегло его просматриваем, самый лучший курс [документация по Git](https://git-scm.com/doc)
- для визуалов советую [Learn Git Branching](https://learngitbranching.js.org/) - чтобы видеть что происходит 
- начинаем эксперименты:
  - с помощью SourceTree и Github - форкаем текущий репозиторий ([Artist learn Unity](/resources.md#github))
  - клонируем форкнутый репозиторий к себе на машину
  - в директории students создаем свою директорию (например alexander-yu-shamin)
  - добавляем в эту директорию файл README.MD и добавляем своей краткое faq. Используем [Markdown](https://www.markdownguide.org/cheat-sheet/) - специальный язык разметки текста
  - создаем коммит с добавленной информацией, проверяем что добавили только необходимую информацию.
  - пушим добавленные изменения в свой форкнутрый репозиторий
  - заходим на свой форкнутый репозиторий на GitHub.com и создаем pull request в основной репозиторий.
  - отмечаемся в Issues 'Chapter 1'
- в [Learn Git Branching](https://learngitbranching.js.org/) пробуем сделать merge, cherry-pick, squash, reset - чтобы понять что это такое.


## Рефлексия
- Что такое commit? commit hash? 
- Зачем нужны ветки в git?
- Зачем нужен cherry-pick и squash?
- Разница в использовании reset --soft, --hard, --mixed?
- Зачем необходима система контроля задач выполняющему задачу? Как оформлять задачу в Jira?

## Примечания 

- проверить настройки на github и jira (для ментора)~~