## Инструменты для студентов школы 21

Документация:
- [s21docs](https://github.com/s21toolkit/s21docs) - Общий репозиторий документации

Работа с платформой:

- [s21cli](https://github.com/s21toolkit/s21cli) - Консольный интерфейс для работы с платформой

- [s21docs](https://github.com/s21toolkit/s21docs) - Документация внутреннего API платформы
- [s21schema](https://github.com/s21toolkit/s21schema) - Репозиторий для хранения и отслеживания схем API платформы
- [s21client](https://github.com/s21toolkit/s21client) - Клиент для работы со внутренним API платформы на Go
- [s21client-ts](https://github.com/s21toolkit/s21client-ts) - Клиент для работы со внутренним API платформы на Bun/TypeScript
- [s21adapter](https://github.com/s21toolkit/s21adapter) - Контейнеризированный сервер-адаптер для работы со внутренним API платформы, обеспечивает возможность генерации спецификации Swagger и клиентов по ней
  - [s21adapter-example](https://github.com/s21toolkit/s21adapter-example) - Пример сервиса, использующего s21adapter для генерации клиента и общения с платформой
 
> [!TIP]
> Запросы на обновление/добавление схем нужно заводить в ишью [s21schema](https://github.com/s21toolkit/s21schema).

Внутренние инструменты:

- [s21auto](https://github.com/s21toolkit/s21auto) - Многофункциональная утилита для разработки инструментов, в основном используется как генератор кода и документации.

Юзерскипты:
> [!IMPORTANT]  
> Необходим [Tampermonkey](https://www.tampermonkey.net) или любой другой совместимый скрипт мнеджер

- [s21DisableDeadlineRedirect.user.js](https://gist.github.com/EnergoStalin/333d2167626fe96c500a7797103c69b8/raw/9bf3e264647ced988bef36c985b19ac6f32c9931/s21DisableDeadlineRedirect.user.js) - Обход заставки просроченного дедлайна
- [s21ReviewSlug.user.js](https://gist.github.com/EnergoStalin/87da333846b831083ed7bb96adcee01a/raw/5295f54eaebbbee33f4a7766161fcedec00cbb3d/s21ReviewSlug.user.js) - Кнопка для копирования информации о проверке в календаре
- [s21gravatar.user.js](https://update.greasyfork.org/scripts/482418/s21gravatar.user.js) - Отображение граватаров со школьной почты

- [S21 CulturedAvatars.user.js](https://greasyfork.org/scripts/458785-s21-culturedavatars/code/S21%20CulturedAvatars.user.js) - Замена пустых аватарок кошкожёнами
- [S21 SaleBarRemover.user.js](https://greasyfork.org/scripts/457634-s21-salebarremover/code/S21%20SaleBarRemover.user.js) - Удаление полосок распродаж
