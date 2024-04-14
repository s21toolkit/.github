# Инструменты для студентов школы 21

Прикладные программы:

- [s21lint](https://github.com/s21toolkit/s21lint) - Статический анализатор для проверки кода на C/C++ на соответствие школьным требованиям
  - [s21lint-vscode](https://github.com/s21toolkit/s21lint-vscode) - Интеграция s21lint в VSCode
- [s21cli](https://github.com/s21toolkit/s21cli) - Консольный интерфейс для работы с платформой

Браузерные скрипты:

> [!IMPORTANT]  
> Необходим [Tampermonkey](https://www.tampermonkey.net) или любой другой совместимый скрипт менеджер

- [s21gravatar.user.js](https://update.greasyfork.org/scripts/482418/s21gravatar.user.js) - Отображение граватаров со школьной почты (будут видеть все, у кого стоит скрипт)
- [s21sale-bar-remover.user.js](https://greasyfork.org/scripts/457634-s21-salebarremover/code/S21%20SaleBarRemover.user.js) - Удаление полосок распродаж
- [s21review-slug.user.js](https://gist.github.com/EnergoStalin/87da333846b831083ed7bb96adcee01a/raw/s21ReviewSlug.user.js) - Кнопка для копирования информации о проверке в календаре
- [s21particles-remover.user.js](https://gist.github.com/EnergoStalin/2ba9d4d4379a47303a06900f5bd42405/raw/s21ParticlesRemover.user.js) - Удаление партиклов (новогодних)
- [s21cultured-avatars.user.js](https://greasyfork.org/scripts/458785-s21-culturedavatars/code/S21%20CulturedAvatars.user.js) - Замена пустых аватарок кошкожёнами
- [s21disable-deadline-redirect.user.js](https://gist.github.com/EnergoStalin/333d2167626fe96c500a7797103c69b8/raw/s21DisableDeadlineRedirect.user.js) - Обход заставки просроченного дедлайна

Инструменты:

- [s21introspector](https://github.com/s21toolkit/s21introspector) - Инструмент для интроспекции GQL API платформы
- [s21auto](https://github.com/s21toolkit/s21auto) - Многофункциональный инструмент для вывода схем GQL API платформы из логов запросов, генерации клиентских библиотек и документации.

Автогенерируемые библиотеки (в связке с s21auto):

> [!NOTE]
> Данный набор инструментов создан для работы в связке с s21auto.
> Они позволяют обходить запрет интроспекции и генерировать библиотеки на основе образцов коммуникации с платформой.
> Если есть возможность использовать интроспекцию - лучше использовать (см. [s21introspector](https://github.com/s21toolkit/s21introspector)), а библиотеки оставить для авторизации.

- [s21client](https://github.com/s21toolkit/s21client) - Клиент для работы со внутренним API платформы на Go
- [s21client-ts](https://github.com/s21toolkit/s21client-ts) - Клиент для работы со внутренним API платформы на Bun/TypeScript
- [s21adapter](https://github.com/s21toolkit/s21adapter) - Контейнеризированные сервис-адаптер для работы со внутренним API платформы, обеспечивает возможность генерации спецификации Swagger и клиентов по ней
  - [s21adapter-example](https://github.com/s21toolkit/s21adapter-example) - Пример сервиса, использующего s21adapter для генерации клиента и общения с платформой

Организация:

- [s21schema](https://github.com/s21toolkit/s21schema) - Репозиторий для хранения и отслеживания схем API платформы
- [s21docs](https://github.com/s21toolkit/s21docs) - Общий репозиторий документации

> [!TIP]
> Запросы на обновление/добавление схем для клиентских библиотек нужно заводить в ишью [s21schema](https://github.com/s21toolkit/s21schema).
