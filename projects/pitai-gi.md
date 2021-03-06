# Проект "Питай ги"

Портал за изпращане на електронни заявления за достъп до обществена информация (по ЗДОИ), базиран на платформа с отворен код, която се използва в над дузина държави. Отговорите на институциите могат да бъдат направени публични и да се търси в тях.

Сайт: [pitaigi.bg](https://pitaigi.obshtestvo.bg/)

## Описание

Според ЗДОИ всеки български гражданин има право да изпраща запитвания за определен тип информация до голям набор учреждения и администрации (Парламент, Министерски съвет, общините и други – над 500 такива обекта). Проектът се бори да популяризира това право, да улесни хората да правят запитвания, да улесни институциите, като направи публично достъпни и индексирани отговорите им, както и да приложи натиск над институциите да отговарят на запитвания. По проекта си партнираме с Програма за достъп до информация. Заедно с тях ще откриваме и изследваме какви промени да предложим на законодателя, за да се регламентират по-добре въпросните заявления по електронен път, които в момента са в сива зона.

## Основни дейности

Текущи:

- Интеграция на дизайна, направен от хърватските ни партньори
- Разработка на специфични за българското законодателство функции
- Инсталация, конфигурация и поддръжка на работещо копие (практически готово)

Предстоящи:

- Комуникация с партньорските организации и медии за популяризиране на портала
- Комуникация с институции, за да започнат да ползват портала и да отговарят там
- Организация на срещи и събития за популяризиране на ЗДОИ, платформата и ползите от двете
- Маркетинг задачи

## Участници

За въпроси се обръщайте към координатора на проекта.

- [Антон Стойчев](mailto:antitoxic@gmail.com), координатор на проекта
- [Валентин Ейткен](https://github.com/bostko), разработчик (frontend и backend)
- Валентин Ласков, преводач
- [Димитър Димитров](mailto:me@ddimitrov.name), разработчик (frontend и backend) и координатор на проекта
- [Йордан Щерев](https://github.com/shterev), разработчик (frontend)
- Славка Цанкова, разработчик (frontend)
- [Станислав Гатев](https://github.com/s2gatev), разработчик (backend)

И други.

## Технически особености

Проектът е fork на [Alaveteli](http://alaveteli.org), написан от английската
civic hacking организация [MySociety](https://www.mysociety.org/). Направени са
малки промени за напасване към българското законодателство.

В основната си част, проектът е уебсайт, плюс интеграция с пощенски сървър за
автоматично прихващане на входящи писма.

- Ruby on Rails (Rails 3.2.x, Ruby 2.x)
- PostgreSQL
- Memcached
- Xapian
- Postfix (имейл сървър) със собствени правила за прихващане на входяща поща

Хранилища в GitHub:

- Кодът на сайта е тук: https://github.com/obshtestvo/alaveteli-bulgaria
- Темата се намира тук: https://github.com/obshtestvo/alavetelitheme

Повече информация има в
[Wiki-то на нашия fork](https://github.com/obshtestvo/alaveteli-bulgaria/wiki).

## Организация

Организираме се основно в:

- Групов Skype чат. При желание да се включите в проекта, ще ви добавим.
- [Facebook група](https://www.facebook.com/groups/pitaigi.bg/).
- [Asana проект](https://app.asana.com/0/19564721227789/19564721227789).

## Партньори

-   [Фондация "Програма за достъп до информация" (ПДИ)](http://aip-bg.org).
    Това е точно техният ресор и са много запалени по проекта. Те предоставиха
    текущия списък с 500+ организации, до които да могат да се отправят
    заявления по ЗДОИ.
-   Rational International от Хърватска, чието дело е дизайна и с които ще
    споделяме общ codebase.
