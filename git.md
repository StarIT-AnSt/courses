# Как работать с Git

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/playlist?list=PLBXnHSmq7po9YlkHrpFq6xL9TrHQzSx8s) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/plst/256633)

Курс с открытыми занятиями по `git`.

## Занятие 1.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/fAvdrZ9GwbI) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/8d5601e91b3420fde7957efd2072c44d/)

Попробовали создать локальный репозиторий, добавили файл, зафиксировали изменения.

***

## Занятие 2.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/OtJv9sVBxow) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/36dfad8f3d1f9dfee6ce9778269d87ad/)

Подключили к локальному репозиторию внешний репозиторий, склонировали его, запушили коммиты и сделали вытягивание изменений с удалённого репозитория. Подключали внешний(удалённый) репозиторий с [GitHub](https://github.com/) и [GitFlic](https://gitflic.ru/).

***

## Занятие 3.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/vH15qmNEISA) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/19b7caf5de425daf1d96d8a594ad5cf9/)

Создали в локальном репозитории ветки. Сделали слияние веток (merge). Удалили ветку. Создали ветку из определённого коммита.

***

## Занятие 4.

Командная работа с репозиториями.

### Часть 1.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/FaCGV3RojDo) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/00b835d961beea7d668536c3e54496b1/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/StarIT-AnSt/test_command_work_1.git)

Создали [общий репозиторий](https://github.com/StarIT-AnSt/test_command_work_1.git), подключили к нему другого разработчика, поработали с ветками, поработали с запросами на слияние (pull request).

[Правила полета на Git](https://github.com/k88hudson/git-flight-rules/blob/master/README_ru.md) - https://github.com/k88hudson/git-flight-rules/blob/master/README_ru.md

### Часть 2.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/IWcNOU40Mi4) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/b4d99c8b8e165c7f1a2e14a415f9432e/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/StarIT-AnSt/test_command_work_2.git)

Создали [общий репозиторий](https://github.com/StarIT-AnSt/test_command_work_2.git), сделали форк репозитория, создали запрос на слияние из форка. Обсудили какие бывают [варианты командной работы](https://www.atlassian.com/git/tutorials/comparing-workflows)

### Часть 3.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/nL28gSsoyfU) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/4aab926793f049353c90c9ae02afa484/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/StarIT-AnSt/test_command_work_3.git)

Создали [общий репозиторий](https://github.com/StarIT-AnSt/test_command_work_3.git), инициализировали репозиторий с git flow, поработали с ветками (фичи и релиза), создали релиз.

Материалы по работе с git flow:
- https://www.atlassian.com/ru/git/tutorials/comparing-workflows/gitflow-workflow
- https://danielkummer.github.io/git-flow-cheatsheet/index.ru_RU.html

***

## Занятие 5.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/Cf6q53n80Kw) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/35b5a41020a69da5e1f443783063bc98/)

Создали репозиторий. Понаделали коммитов, попробовали отменить коммит через `git reset --hard`. Потом попробовали отменить отмену коммита (восстановить отменённый коммит) через создание новой ветки из отменённого коммита. Попробовали использовать `git revert` для сохранения историй отмены.

Материалы:
- https://ru.stackoverflow.com/questions/431520/Как-вернуться-откатиться-к-более-раннему-коммиту
- https://www.atlassian.com/ru/git/tutorials/undoing-changes
- https://habr.com/ru/company/skillbox/blog/534972/
- https://github.com/k88hudson/git-flight-rules/blob/master/README_ru.md#Я-случайно-сделал-жесткий-сброс---hard-и-теперь-хочу-вернуть-свои-изменения

***

## Занятие 6.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/wdao44tnfUI) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/e832ef5b2b2a8a1afc9e0b138354acce/)

Создали репозиторий. Разобрали немного теории git hooks, попробовали сделать простейший хук.

Материалы:
- https://git-scm.com/book/ru/v2/Настройка-Git-Хуки-в-Git
- https://www.atlassian.com/ru/git/tutorials/git-hooks
- https://habr.com/ru/companies/dins/articles/584562/
- https://xakep.ru/2016/02/11/git-hook-magic/

***

## Занятие 7.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/z3A4J_vu7fM) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/13452e1510853cc688d7260abfd31fbf/)

Разобрали зачем нужны `.gitattributes` и `.gitignore`

Материалы:
- https://www.youtube.com/watch?v=V3z80lCvHJo
- https://radioprog.ru/post/1401

Репозитории с шаблонными файлами:
- https://github.com/alexkaratarakis/gitattributes
- https://github.com/github/gitignore

Сервисы для создания .gitattributes и .gitignore:
- https://www.richie-bendall.ml/gitattributes-generator/
- https://gitattributes.io/
- https://www.toptal.com/developers/gitignore

***

## Занятие 8.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/Mef9MY717Jk) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/a7c389afea447ffdfbae666498065152/)

Установили и немного поработали с некоторыми  GUI git-клиентами: [GitHub Desktop](https://desktop.github.com/), [SourceTree](https://www.sourcetreeapp.com/), [GitKraken](https://www.gitkraken.com/).

Материалы:
- https://git-scm.com/download/gui/windows

***

## Занятие 9.

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/Z0z1Vi2_B0s) [![RuTube](https://img.shields.io/badge/RuTube-000000?style=for-the-badge&logo=rutube&logoColor=white)](https://rutube.ru/video/8e2fc7eed448e6c5645fa10732349ab2/)

Разобрали как исправлять конфликты при слиянии. Также рассмотрели различные сценарии когда конфликты могут возникать и как их можно избежать.

***
