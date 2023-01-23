# Введение

Проект будет планомерно дополняться информацией. Следите за обновлениями проекта.

По возможности проект будет вестись в билингва формате, но основным языком будет русский.

Общение будет происходить 

## Входные требования

### Unity

- [Unity Hub](https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.exe)
- Unity 2021.3.16f1 (install via the Unity Hub) with modules:
	- Microsoft Visual Studio Community 2022
	- Android Build Support: OpenJDK, Android SDK & NDK Tools
	- IOS Build Support
	- Windows Build Support (IL2CPP)
  

### Git

- [Git](https://git-scm.com/)
- [Git LFS](https://git-lfs.com/)
- [SourceTree](https://www.sourcetreeapp.com/)

### Image applications

> *Choose what you need…* *Use what you can…*

- [GIMP](https://www.gimp.org/) / [Photoshop](https://www.adobe.com/products/photoshop.html) / [Illustrator](https://www.adobe.com/products/illustrator.html)
- [Blender](https://www.blender.org/) / [3D Max](https://www.autodesk.com/products/3ds-max) / [Maya](https://www.autodesk.com/products/maya) / [Cinema 4D](https://www.maxon.net/en/cinema-4d) / [Houdini](https://www.sidefx.com/)
- [Spine](http://esotericsoftware.com/) / [Spriter](https://brashmonkey.com/) / [Creature](https://creature.kestrelmoon.com/)
- [Krita](https://krita.org/) / [Inkscape](https://inkscape.org/)
- [asepriTe](https://www.aseprite.org/) / [Pixen](https://pixenapp.com/)

### Accounts

- [Jira](https://www.atlassian.com/software/jira)
	- The Jira project is [Artists Learn Unity](https://artists-learn-unity.atlassian.net/jira/software/projects/ALU/boards/1)
- [GitHub](https://github.com/)
	- The GitHub project is [Artists learn Unity](https://github.com/alexander-yu-shamin/artists-learn-unity)


## Информация для развлечения

- [Базовая сертификация Unity | Unity](https://unity.com/ru/products/unity-certifications/associate-game-developer)
	- [Попробуй ответить на вопросы](https://images.response.unity3d.com/Web/Unity/%7B11623644-24d4-4eef-833c-b36112ca2f1f%7D_UC_3D_Artist_Exam_Objectives-2018-09-25_RU.pdf)
	- [Сертифицированный пользователь Unity: художник базового уровня | Unity](https://unity.com/ru/products/unity-certifications/associate-artist)
	- [Профессиональная сертификация для художников и дизайнеров игр | Unity](https://unity.com/ru/products/unity-certifications/professional-artist)
- [Инструменты для игровых художников | Инструменты Unity | Unity](https://unity.com/ru/solutions/artist-designers)
- [🎲 Разработка игр на Unity: с нуля до профессионала](https://proglib.io/p/razrabotka-igr-na-unity-s-nulya-do-professionala-2020-08-27)
- [Кто такой Технический художник (Tech artist)?](https://itanddigital.ru/techartist)
- [Арт-специальности в GameDev, какие бывают и что необходимо знать / Хабр](https://habr.com/ru/post/552768/)
- [Профессия игровой художник. Разбираемся как стать игровым художником. | GDJob.PRO](https://gdjob.pro/stati/soiskatelyam/professiya-igrovoy-khudozhnik-razbiraemsya-kak-stat-igrovym-khudozhnikom/)
- [Технический художник (gamedev) – редкая, а значит хорошо оплачиваемая профессия?](https://3dyuriki.com/2021/06/05/tehnicheskij-hudozhnik-gamedev-redkaya-a-znachit-horosho-oplachivaemaya-professiya/)
- [Unity с позиции художника при разработке кроссплатформенной игры / Хабр](https://habr.com/ru/post/308918/)

# Глава 0
**Цели главы:**
- [ ] установить необходимые приложения
- [ ] создать необходимые аккаунты
- [ ] получить доступ к ресурсам (Jira, GitHub)

**Последовательность действий:**
- устанавливаем приложения из разделов:
  - [Unity](#unity)
  - [Git](#git)
  - [Приложения для обработки изображений](#image-applications)
- создаем аккаунты на указанных [ресурсах](#accounts)
- связываемся с @alexander-yu-shamin и получаем доступ к 
  - Jira проект => [Artists Learn Unity](https://artists-learn-unity.atlassian.net/jira/software/projects/ALU)
  - GitHub проект => [Artists learn Unity](https://github.com/alexander-yu-shamin/artists-learn-unity)
- пока ждем доступ, можно ознакомится с [подборкой ресурсов](#информация-для-развлечения)

**Примечания для ментора:**
- при выдаче доступа, создать в [Jira](https://artists-learn-unity.atlassian.net/jira/software/projects/ALU/boards/1) набор задач для каждого пользователя.

# Глава 1

**Цели главы:**
- [ ] изучить Jira и принципы командной работы
  - [ ] выполнить первую поставленную задачу в Jira
- [ ] изучить основы Git
- [ ] форкнуть репозиторий, добавить изменения, создать пулл реквест на добавление в основной репозиторий, создать issue
- [ ] попробовать сделать merge, cherry-pick

**Последовательность действий:**
- изучаем Jira:
  - изучаем общие вопросы [совместной работы над проектом](https://www.atlassian.com/ru/work-management/project-collaboration)
  - знакомимся с [общими подходами в управлении проектами](https://www.atlassian.com/ru/agile/manifesto)
  - находим свои задачи в [Jira](https://artists-learn-unity.atlassian.net/jira/software/projects/ALU/boards/1)
  - выполняем задачу Chapter 1:
    - находим свою задачу - и перемещаем ее в Board в In Progress состояние
    - заполняем поля: Start Date, Time tracking
    - упоминаем в комментариях ментора, добавляем его в ревьюверы (если его там нет)
    - переносим задачу в Review состояние
  - ожидаем проверку задачи (будет перемещена в Done статус), переходим к следующей задаче
- ознакамливаемся с курсом: [Основы работы с Git, GitHub и даже GitHub Actions | Udemy](https://www.udemy.com/course/russian-git/?start=0#overview)
- выбираем себе [курс](https://habr.com/ru/post/510126/) и бегло его просматриваем, самый лучший курс [Git - Documentation](https://git-scm.com/doc)
- для визуалов советую [Learn Git Branching](https://learngitbranching.js.org/) - чтобы видеть что происходит 
- начинаем эксперименты:
  - с помощью SourceTree и Github - форкаем текущий репозиторий.
  - клонируем форкнутый репозиторий к себе на машину
  - в директории students создаем свою директорию (например alexander-yu-shamin)
  - добавляем в эту директорию файл README.MD и добавляем своей краткое faq. Используем [Markdown](https://www.markdownguide.org/cheat-sheet/) - специальный язык разметки текста
  - создаем коммит с добавленной информацией, проверяем что добавили только необходимую информацию.
  - пушим добавленные изменения в свой форкнутрый репозиторий!!!
  - переходим в основной [репозиторий](https://github.com/alexander-yu-shamin/artists-learn-unity) и создаем pull request.
  - отмечаемся в Issues 'Chapter 1'
- в [Learn Git Branching](https://learngitbranching.js.org/) пробуем сделать merge, cherry-pick, squash, reset - чтобы понять что это такое.

Переходим к следующей главе.

**Примечания для ментора:**
- проверить настройки на github и jira