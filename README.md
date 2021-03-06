# Проект React.js + Node.js - Slim mom

Фронтенд часть проекта. Это веб-приложение имеет мобильную, планшетную и
десктопную версии. В приложении можно зарегистрироваться, повторно логиниться
(через уникальный никнейм и пароль). Суть - помочь женщинам похудеть.
На стартовой транице приложения женщина/девушка может просчитать свою суточную норму каллорий. После зарегистрировшись/залогинившись в приложение может вносить употребляемые продукты и по средствам отправки асинхронных запросов на бэкенд будет приходить совпадения по продуктам и предлагаться в выпадающем списке. На бэкенде и в базе данных уже задана каллорийность каждого продукта. Также женщина/девушка наблюдать свой прогресс на графике, сколько каллорий в день она потребляет по сравнению с рекоммендуемой нормой рассчитанной ранее, также можно пересчитать потребляемую норму калларий в день с помощью калькулятора.

## Рабочая ссылка проекта:

### https://slim-moms.goit.co.ua/

## Материалы проекта:

1. [Макеты (мобилка, планшет, десктоп)](https://drive.google.com/drive/folders/1xUOd4qJ0TbT3Qxa-DC2rdxnXDTqsx-dD)
2. [Репозиторий бэкенда](https://github.com/goitProjects/slim_mom_backend)
3. [Документация бэкенда](https://slim-moms.goit.co.ua/doc/)
4. [Бэклог проекта](https://docs.google.com/spreadsheets/d/14PhdIxsff_NA45-MJf6cxfRblR29VLJWoKbgXnANfcA/edit#gid=1609911290)
5. [Ссылка приглашение к доске в trello](https://trello.com/invite/b/66YeriQ0/63cb4440d31d9eb205221f74eeaf24a3/health-project-frontend)
6. [Доска в trello](https://trello.com/b/66YeriQ0/health-project-frontend)
7. [Ссылка на инструкцию по работе с github](https://docs.google.com/document/d/1y-nMdpPIIP83rbqPYt6kM_KXMC83UPbkbxKqgaHlnfI/edit)
8. [Реализацию redux store смотреть в redux devtools готового проекта, они в продакшене не отключены](https://slim-moms.goit.co.ua/)
9. [Схема фронтенда, разбиение на компоненты и страницы](http://joxi.net/ZrJ9dxBcw5pONA)
10. [Репозиторий фронтенда](https://github.com/goitProjects/slim_mom_frontend)
11. [Данные для Базы данных](https://drive.google.com/file/d/1bmA7WnJKNrwCMkdq531vJDQ6KzikUQkF/view)
12. [Requerements](https://docs.google.com/document/d/1v2eUnm3U2yKDUeowwwXHcsiK3CLzEegCSgTkqelMyzY/edit)

## Дополнительная информация:

Ветка master самая актуальная и базовая в проекте, build сделанный из нее лежит
и работает на сервере.

Формула для просчета дневной нормы каллорий для женщин : 10*текущий вес+6,25*рост-5*текущий возраст-161-10*(текущий вес-желаемый вес) . Например, для роста 178, веса 90 кг, возрасте 40 лет при желаемом весе 60 кг необходимо есть 10*90+6.25*178-5*40-161-10*60 = 1051.5 калл в день

[Оригинал репозитория и автор данного фронтенд в оригинале Павел Пастушенко и команда группы Bootcamp12 из GO IT. Ветка - feature/achievement](https://github.com/Sinas66/SlimMom-FrontEnd/tree/feature/achievement)

[Ментором фронтенд части был Андрей Слободянюк, ссылка на его репозиторий, актуальная ветка - dev (тут только не реализован график, более актуальная версия в данном репозитории или и в репозитории Павла Пастушенко)](https://github.com/AndrewSlobodianiuk/SlimMom)
