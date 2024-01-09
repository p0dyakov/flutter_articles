<p align="center">
  <a href="https://raw.githubusercontent.com/p-zahar/flutter_articles">
    <img alt="logo" src="https://raw.githubusercontent.com/p-zahar/flutter_articles/main/logo.png">
  </a>
</p>

В данном репозитории собраны русскоязычные статьи по мобильной разработке на flutter. Выражаю огромную благодарность авторам этих материалов. Пулл реквесты приветствуются  
Другое: [flutter_interview](https://github.com/p0dyakov/flutter_interview), [flutter_roadmap](https://github.com/p0dyakov/flutter_roadmap)
<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [Фреймворк и язык](#--)
   * [Асинхронность](#)
   * [Списки  ](#-1)
   * [Под капотом](#-)
   * [Шейдеры](#-2)
   * [Другое](#-3)
- [Архитектура и управление состоянием](#---)
- [Чистый код](#--1)
- [Паттерны проектирования](#--2)
- [Базы данных](#--3)
- [Навигация](#-4)
- [Производительность ](#-5)
- [Тестирование](#-6)
- [CI / CD](#ci--cd)
- [Dependency Injection](#dependency-injection)
- [Пакеты, плагины и интеграции](#----1)
- [Безопасность](#-7)
- [Натив](#-8)
- [Собеседования](#-9)
- [Советы](#-10)
- [Ускорение разработки](#--4)
- [Кейсы](#-11)
- [Версии](#-12)
   * [Flutter](#flutter)
   * [Dart](#dart)
   * [Будущее](#-13)
- [Преимущества и недостатки Flutter](#---flutter)
- [Другое](#-14)

<!-- TOC end -->
# Фреймворк и язык
## Асинхронность
[Работа с асинхронностью в Dart](https://habr.com/ru/company/surfstudio/blog/539362/)  
[Flutter: простыми словами про ассинхронность и параллельность](https://habr.com/ru/post/654047/)  
[Dart 2. Асинхронное программирование: futures](https://habr.com/ru/post/442282/)  
[Dart: Асинхронность](https://habr.com/ru/post/720352/)  
[Магия асинхронных операций: взгляд изнутри. Future](https://habr.com/ru/companies/ligastavok/articles/539782/)  
[1.0 Асинхронность. Event Loop, MicroTask и Event в Dart](https://habr.com/ru/articles/754194/)  
[2.0 Асинхронность. Future](https://habr.com/ru/articles/754268/)  
[3.0 Асинхронность. async и await](https://habr.com/ru/articles/754280/)  
[4.0 Асинхронность. Isolates, потоки, процессы](https://habr.com/ru/articles/756404/)  

## Списки  
[Актуализация данных в списках Flutter-приложения](https://habr.com/ru/articles/656297/)  
[Работа со списками во Flutter-приложениях (часть 2)](https://habr.com/ru/articles/688864/)  
[Sliver во Flutter, или как работает скролл](https://habr.com/ru/company/surfstudio/blog/657215/)  

## Под капотом
[Сборка мусора во Flutter](https://habr.com/ru/company/rshb/blog/668600/)  
[Как работает Flutter](https://habr.com/ru/post/476018/)  
[Flutter под капотом ч.1](https://habr.com/ru/company/surfstudio/blog/501862/)  
[Flutter под капотом: Binding ч.2](https://habr.com/ru/company/surfstudio/blog/512326/)  
[Flutter под капотом: Owners ч.3](https://habr.com/ru/company/surfstudio/blog/533210/)  
[Метод setState() во Flutter может работать не так, как вы это представляете](https://habr.com/ru/articles/745726/)  

## Шейдеры
[Использование шейдеров во Flutter. Часть 1](https://habr.com/ru/company/friflex/blog/713298/)  
[Использование шейдеров во Flutter. Часть 2](https://habr.com/ru/company/friflex/blog/714956/)  
[Flutter jank shaders — история проблемы и пути решения](https://habr.com/ru/companies/rshb/articles/680586/)  

## Другое
[Flutter, руководство для начинающих](https://habr.com/ru/company/oleg-bunin/blog/460743/)  
[Про Flutter, кратко: Основы](https://habr.com/ru/post/430918/)  
[Dart. Всё, что надо знать про константы](https://habr.com/ru/post/501804/)  
[Null safety в Dart](https://habr.com/ru/post/513466/)  
[Правила компоновки во Flutter, которые должен знать каждый](https://habr.com/ru/post/500210/)  
[Flutter. RenderObject — замеряй и властвуй](https://habr.com/ru/company/surfstudio/blog/513070/)  
[InheritedWidget во Flutter](https://habr.com/ru/company/otus/blog/521032/)  
[Flutter для React/React Native разработчика](https://habr.com/ru/post/526362/)  
[Зоны в Dart: операция на открытом сердце для окружения](https://habr.com/ru/company/wrike/blog/510270/)  
[Все о фабричном конструкторе в Dart](https://habr.com/ru/articles/731298/)  
[Как не «сломать» вёрстку Flutter-приложения из-за textScaleFactor](https://habr.com/ru/companies/surfstudio/articles/720098/)  

# Архитектура и управление состоянием
[Flutter + чистая архитектура: разбираем на примере](https://habr.com/ru/post/522640/)  
[Model-Widget-WidgetModel, или какой архитектурой пользуется Flutter-команда в Surf](https://habr.com/ru/company/surfstudio/blog/510308/)  
[Основы архитектуры приложений на Flutter: Vanilla, Scoped Model, BLoC](https://habr.com/ru/post/438574/)  
[Структура Flutter-приложения: feature-first или layer-first](https://habr.com/ru/articles/772802/)  
[Flutter. MVVM. Начало](https://habr.com/ru/company/digdes/blog/660411/)  
[Архитектура MVVM в мобильных приложениях на Flutter](https://habr.com/ru/post/427327/)  
[Flutter.dev: Простое управление состоянием приложения](https://habr.com/ru/company/otus/blog/518156/)  
[Управление состоянием в приложениях на Flutter](https://habr.com/ru/post/424765/)  
[Состояние Flutter на изолятах](https://habr.com/ru/post/532862/)  
[Управление состоянием приложения в Flutter](https://habr.com/ru/post/435780/)  
[Простой, но масштабируемый State Management для Flutter](https://habr.com/ru/articles/773980/)    
[Пишем приложение на Flutter в связке с Redux](https://habr.com/ru/post/481624/)  
[Flutter. BlOC, Provider, async – архитектура «по полочкам»](https://habr.com/ru/post/489512/)  
[BLoC паттерн на простом примере](https://habr.com/ru/post/475404/)  
[Flutter. Как прокачать ваш BLoC](https://habr.com/ru/post/516764/)  
[Flutter BloC паттерн + Provider + тесты + запоминаем состояние](https://habr.com/ru/post/485002/)  
[Elementary: новый взгляд на архитектуру Flutter-приложений](https://habr.com/ru/company/surfstudio/blog/595619/)  
[Как устроен Elementary](https://habr.com/ru/company/surfstudio/blog/597167/)  
[Как подружить Elementary и BLoC](https://habr.com/ru/company/surfstudio/blog/667272/)  
[Проектируем flutter-приложение «чистым» способом используя bloc](https://habr.com/ru/articles/733960/)  
[Event Bus: пишем шину событий во Flutter-приложении](https://habr.com/ru/companies/friflex/articles/768060/)  

# Чистый код
[Сохраняем код чистым в приложении на Flutter](https://habr.com/ru/company/otus/blog/661609/)  
[Повышаем качество кода с Dart Code Metrics](https://habr.com/ru/company/wrike/blog/552012/)  
[Правильное понимание Single Responsibility Principle (SRP) в Dart/Flutter](https://habr.com/ru/articles/784528/)  

# Паттерны проектирования
[Паттерны проектирования в Dart](https://habr.com/ru/company/otus/blog/678714/)  
[Паттерны проектирования в Dart. Часть 2](https://habr.com/ru/company/otus/blog/681328/)  
[Паттерны проектирования в Dart. Часть 3](https://habr.com/ru/company/otus/blog/681954/)  
[Паттерны проектирования на Dart с примерами кода. Часть 1](https://habr.com/ru/articles/736364/)  
[Паттерны проектирования на Dart с примерами кода. Часть 2](https://habr.com/ru/articles/737038/)  

# Базы данных
[Hive — быстрая локальная база для Flutter, Dart](https://habr.com/ru/post/498070/)  
[Flutter. Локальная база данных](https://habr.com/ru/companies/digdes/articles/770950/)  
[SharedPreferences отличное хранилище для вашего flutter-приложения. Но есть нюансы…](https://habr.com/ru/articles/724706/)  

# Навигация
[Flutter: как мы выбирали навигацию для мобильного приложения?](https://habr.com/ru/company/rshb/blog/584348/)   
[Управляем навигацией во Flutter с помощью библиотеки auto_route. Часть 1](https://habr.com/ru/companies/friflex/articles/772234/)  
[Deeplinks и Flutter](https://habr.com/ru/post/692930/)   
[Все, что вам нужно знать о маршрутизации между страницами Flutter](https://habr.com/ru/company/otus/blog/539190/)  
[Навигация во flutter](https://habr.com/ru/post/512072/)  

# Производительность 
[Тестирование производительности Flutter приложений](https://habr.com/ru/post/451840/)  
[Как улучшить производительность вашего Flutter приложения](https://habr.com/ru/post/502882/)  
[Советы по оптимизации производительности растрового потока](https://habr.com/ru/company/otus/blog/581742/)  
[Ускоряем Dart. Нативно, недорого](https://habr.com/ru/post/547946/)  
[Разговор с разработчиками о производительности на Flutter](https://habr.com/ru/company/rshb/blog/674508/)  
[«Разгоняем» HashSet, HashMap и циклы на примере Dart](https://habr.com/ru/articles/772462/)  
[Flutter DevTools: анализируем и улучшаем Flutter-приложения на примере «Росбанк Инвест»](https://habr.com/ru/companies/rosbank/articles/753252/)  

# Тестирование
[Тестирование Flutter-приложений: инструменты, преимущества, проблемы](https://habr.com/ru/company/surfstudio/blog/517574/)  
[Тестирование Flutter-приложений. Начало](https://habr.com/ru/company/surfstudio/blog/468631/)  
[Тестирование Flutter-приложений: гайд по разработке тестов на Flutter](https://habr.com/ru/company/friflex/blog/666578/)  
[Тестирование мобильных приложений на Flutter с использованием Python + Appium](https://habr.com/ru/company/otus/blog/706394/)  
[Тестирование Flutter-приложений c помощью Appium](https://habr.com/ru/articles/758764/)  
[Flutter: автоматизация UI тестирования](https://habr.com/ru/company/talenttech/blog/591915/)   
[UI-тесты и лучшие практики разработки Flutter-проектов: митап Luxoft TechFest Mobile](https://habr.com/ru/company/jugru/blog/595505/)  
[Автоматизированное тестирование событий аналитики в мобильном приложении: насколько это реально и оправдано](https://habr.com/ru/companies/surfstudio/articles/782162/)  

# CI / CD
[Используем бесплатные возможности Github Actions для CI/CD на Flutter-проекте](https://habr.com/ru/company/surfstudio/blog/520506/)    
[Анализ кода в Flutter-приложениях и настройка сборочной линии Gitlab CI для анализа](https://habr.com/ru/post/717708/)  
[Инструкция: как быстро настроить GitLab CI/CD на Flutter-проекте](https://habr.com/ru/companies/agima/articles/779028/)  

# Dependency Injection
[Flutter: Мощь DI и Injectable](https://habr.com/ru/post/654119/)  
[Современные DI-тренды во Flutter-разработке](https://habr.com/ru/company/sezinnopolis/blog/588068/)  
[GetX во Flutter: Строим Unidirectional Data Flow с Rx-переменными](https://habr.com/ru/post/665676/)     
[GetX for Flutter. Dependency Injection для частных случаев](https://habr.com/ru/post/568488/)   
[jugger – внедрение зависимостей как в Android](https://habr.com/ru/post/664926/)   
[Внедрение зависимостей (Dependency Injection) с GetIt во Flutter](https://habr.com/ru/company/rshb/blog/564158/)   

# Пакеты, плагины и интеграции
[Пакеты Flutter, которые я использую в каждом проекте](https://habr.com/ru/company/otus/blog/600013/)  
[Как написать и опубликовать идеальный пакет для Flutter](https://habr.com/ru/post/548594/)  
[RxDart для самых маленьких… проектов](https://habr.com/ru/post/474968/)  
[RxVMS — практичная архитектура для Flutter-приложений ч.1](https://habr.com/ru/post/448776/)  
[Основы Dart Streams ч.2](https://habr.com/ru/post/450950/)  
[RxDart: магические трансформации потоков ч.3](https://habr.com/ru/post/451292/)  
[Основы RxVMS: RxCommand и GetIt ч.4](https://habr.com/ru/post/449872/)  
[Subject объекты в RxDart и чем они полезны Flutter-разработчику](https://habr.com/ru/companies/surfstudio/articles/773164/)  
[Подробно о пакете Provider для Flutter](https://habr.com/ru/company/piter/blog/503074/)  
[Организация Flavors во Flutter](https://habr.com/ru/company/surfstudio/blog/503864/)   
[Один плагин, чтоб править всеми. Как разработать сканер на Flutter для 3 платформ и ускорить ввод данных в 2 раза](https://habr.com/ru/company/simbirsoft/blog/719664/)  
[Flutter Yandex Mapkit: как внедрить основные инструменты Яндекс Карт в проект на Flutter. Часть 1](https://habr.com/ru/companies/friflex/articles/769662/)  
[Flutter Yandex Mapkit: как внедрить основные инструменты Яндекс Карт в проект на Flutter. Часть 2](https://habr.com/ru/companies/friflex/articles/770200/)  
[Шесть открытых библиотек от Mad Brains, которые упростят жизнь Flutter-разработчика](https://habr.com/ru/articles/724236/)  
[OpenStreetMap в Flutter-проекте: что такое flutter_map, как его внедрить и чем дополнить](https://habr.com/ru/companies/friflex/articles/776002/)    
[Как использовать нативный платежный сервис SberPay в кроссплатформенном приложении на Flutter](https://habr.com/ru/companies/friflex/articles/771354/)  
[Как быстро интегрировать Систему быстрых платежей (СБП) в приложение на Flutter](https://habr.com/ru/companies/friflex/articles/768610/)  
[Как сделать авторизацию блокчейне TON на DART с помощью кошелька через TON Connect](https://habr.com/ru/articles/742036/)  
[3D-объекты во Flutter. Расширяем Flame](https://habr.com/ru/company/otus/blog/677844/)  
[Дружим Flutter с С# и С++](https://habr.com/ru/articles/742860/)  
[Управляйте своим Flutter приложением на лету с помощью Firebase Remote Config](https://habr.com/ru/articles/733376/)  
[Как подключить локализацию L10n c Riverpod без ошибок с HTTP Requests](https://habr.com/ru/articles/729102/)  
[Один плагин, чтоб править всеми. Как разработать сканер на Flutter для 3 платформ и ускорить ввод данных в 2 раза](https://habr.com/ru/companies/simbirsoft/articles/719664/)  
[Зачем Clojure Flutter](https://habr.com/ru/articles/705448/)  
[Маркеры на Google Maps во Flutter: от простого к сложному](https://habr.com/ru/articles/680092/)  
[Создаем federated plugin для Flutter-проекта](https://habr.com/ru/companies/friflex/articles/780956/)  

# Безопасность
[Flutter: обзор алгоритмов хэширования на основе плагина crypto](https://habr.com/ru/post/661409/)  
[Flutter: Все способы защиты данных](https://habr.com/ru/post/659999/)  
[Поговорим про безопасность в Dart и Flutter](https://habr.com/ru/company/otus/blog/676138/)  

# Натив
[Flutter и настольные приложения](https://habr.com/ru/company/ruvds/blog/508128/)  
[Flutter и десктоп разработка](https://habr.com/ru/post/505546/)  
[Наводим мосты между Flutter и нативными библиотеками](https://habr.com/ru/company/otus/blog/692530/)  
[Flutter и работа с нативным кодом на примере библиотеки для работы с NFC](https://habr.com/ru/articles/770842/)  
[Flutter Web умер. Да здравствует Flutter Web](https://habr.com/ru/companies/pyrobyte/articles/779226/)  

# Собеседования
[10 популярных вопросов, которые нужно знать, чтобы пройти собеседование на позицию Flutter-разработчика](https://habr.com/ru/post/708692/)  
[Мой опыт flutter собеседований](https://habr.com/ru/post/678560/)  

# Советы
[11 вещей, о которых вы должны помнить перед стартом нового проекта на Flutter](https://habr.com/ru/post/667424/)  
[13 подвохов мобильного приложения, о которых лучше знать до старта разработки](https://habr.com/ru/post/549642/)    
[Стелем мягкую соломку на жёсткий Flutter: как подготовиться к первому проекту, чтобы не провалить его ](https://habr.com/ru/company/surfstudio/blog/661441/)  
[Секреты запуска Flutter в production. Создаем IT-верфи](https://habr.com/ru/company/atisu/blog/597709/)  
[Как не «сломать» вёрстку Flutter-приложения из-за textScaleFactor](https://habr.com/ru/company/surfstudio/blog/720098/)  
[12 методик, которые помогут создавать приложения на Flutter легко и просто](https://habr.com/ru/post/713702/)  

# Ускорение разработки
[Создание инициализатора Flutter-проектов. Чисто и SOLIDно](https://habr.com/ru/company/surfstudio/blog/680480/)  
[Flutter: Ускоряем работу с помощью VS Code Tasks](https://habr.com/ru/post/654293/)   
[Полезные плагины VS Code для разработки кроссплатформенных приложений с использованием React Native и Flutter](https://habr.com/ru/company/skillbox/blog/696128/)  
[Полезные Snippets для Flutter-разработчика](https://habr.com/ru/articles/736444/)  
[Генерация кода API клиента приложения на основе пакета dart openapi generator](https://habr.com/ru/companies/simbirsoft/articles/695528/)  
[Ускоряем разработку за счет пакета Mason на Flutter](https://habr.com/ru/articles/705798/)  
[Кодогенерация Dart](https://habr.com/ru/articles/724184/)  

# Кейсы
[Новое приложение «Медузы». Почему Flutter?](https://habr.com/ru/company/meduza/blog/501786/)  
[Как мы сделали мобильное приложение для курьеров «ВкусВилл» за 9 дней](https://habr.com/ru/company/automacon/blog/551436/)  
[Как я делал desktop-приложение на Flutter (+ bonus)](https://habr.com/ru/post/470251/)  
[Быстрее нативной разработки: опыт внедрения Flutter в крупной компании](https://habr.com/ru/company/rshb/blog/533848/)  
[1 год с Flutter в продакшне](https://habr.com/ru/post/542382/)  
[История разработки SDK для приема платежей в мобильном приложении на Flutter](https://habr.com/ru/company/tinkoff/blog/544080/)   
[Разработка мультиплеерной игры на Dart+Flutter](https://habr.com/ru/articles/753402/)  
[Разработка мультиплеерной игры на Dart+Flutter. Часть 2](https://habr.com/ru/articles/753636/)  
[Пример клиент-серверного приложения на Flutter](https://habr.com/ru/post/435688/)  
[Разработка приложения на Flutter с нуля до релиза: Идея + Базовая инфраструктура ч.1](https://habr.com/ru/post/594963/)     
[Разработка приложения на Flutter с нуля до релиза. ч.2](https://habr.com/ru/post/597605/)  
[Создаем клон Instagram при помощи Flutter и Feeds. Часть 1](https://habr.com/ru/articles/727794/)  
[Создаем клон Instagram при помощи Flutter и Feeds. Часть 2](https://habr.com/ru/articles/730104/)  
[Создаем клон Instagram при помощи Flutter и Feeds. Часть 3](https://habr.com/ru/articles/733748/)  
[Как мы стриминг пилили, или 5 неочевидных палок в колеса от Flutter](https://habr.com/ru/companies/surfstudio/articles/730340/)  
[Приложение для инженеров на Flutter](https://habr.com/ru/articles/728782/)  

# Версии
## Flutter
[Анонс Flutter **1.20**](https://habr.com/ru/company/surfstudio/blog/515042/)  
[Анонс Flutter **1.22**](https://habr.com/ru/company/surfstudio/blog/522244/)  
[Flutter **1.7** — что нового в релизе от 10 июля 2019 года](https://habr.com/ru/post/460513/)  
[Flutter **2**: что нового](https://habr.com/ru/company/surfstudio/blog/546224/)  
[Flutter: Что нового в версии **2.10**](https://habr.com/ru/post/661621/)  
[Flutter **2.8**: что нового](https://habr.com/ru/company/surfstudio/blog/596405/)  
[Flutter **3**: что нового](https://habr.com/ru/company/surfstudio/blog/666448/)  
[Flutter **3.3**: что нового](https://habr.com/ru/company/surfstudio/blog/688194/)  
[Flutter **3.7** — Что нового во Flutter](https://habr.com/ru/post/712894/)    
[Обновление Flutter **3.7**: перевод официального релиза и комментарии](https://habr.com/ru/companies/friflex/articles/713218/)  
[Что нового во Flutter **3.10**, ч.1](https://habr.com/ru/articles/739256/)  
[Что нового во Flutter **3.10**, ч.2](https://habr.com/ru/articles/739878/)  
[Нововведения фреймворка Flutter **3.13**. Часть 1](https://habr.com/ru/articles/759716/)  
[Нововведения фреймворка Flutter **3.13**.Часть 2](https://habr.com/ru/articles/760178/)  
[Flutter **3.13**. Что нового?](https://habr.com/ru/companies/surfstudio/articles/756472/)  
[Flutter **3.16**: обзор обновления фреймворка с комментариями разработчиков Surf](https://habr.com/ru/companies/surfstudio/articles/775714/)  
[Flutter **3.16**: что нового](https://habr.com/ru/companies/friflex/articles/774594/)  
[Flutter **3.3**: что нового](https://habr.com/ru/companies/surfstudio/articles/688194/)  

## Dart
[Анонс Dart **2.0**: Оптимизированный для клиентской разработки](https://habr.com/ru/company/wrike/blog/349790/)  
[Релиз Dart **2.10**: на шаг ближе к null-safety](https://habr.com/ru/company/wrike/blog/522794/)  
[Dart **2.12**: Sound null safety и Dart FFI отправлены на стабильный канал](https://habr.com/ru/company/surfstudio/blog/548460/)  
[Dart **2.17**: Продуктивность и интеграция](https://habr.com/ru/company/surfstudio/blog/667990/)  
[Анонсирован Dart **2.2**: более производительный машинный код, поддержка Set литералов](https://habr.com/ru/post/442014/)  
[Анонсирован Dart **2.3**: оптимизирован для разработки пользовательских интерфейсов](https://habr.com/ru/post/451318/)  
[Анонс Dart **3**](https://habr.com/ru/articles/734396/)  
[Анонсируем Dart **3**](https://habr.com/ru/articles/745000/)  
[Dart **3** на практике: что принесёт нам мажорное обновление языка](https://habr.com/ru/companies/surfstudio/articles/733532/)  
[Модификаторы классов в Dart **3.0**](https://habr.com/ru/articles/765736/)  
[Анонс Dart **3.2**](https://habr.com/ru/articles/774902/)  
[Новый линт в Dart **3.2**](https://habr.com/ru/articles/774744/)  

## Будущее
[Что ждёт Flutter в будущем](https://habr.com/ru/companies/surfstudio/articles/718500/)  
[Будущее iOS-разработки на Flutter](https://habr.com/ru/articles/750818/)  
[Перспективы развития Flutter](https://habr.com/ru/articles/726836/)  

# Преимущества и недостатки Flutter
[Flutter vs Native: почему мы переходим с первого на второй](https://habr.com/ru/company/ozontech/blog/648671/)  
[Сравнение React Native и Flutter с точки зрения их применения в реальных проектах](https://habr.com/ru/company/ruvds/blog/478322/)  
[Пять причин проникнуться симпатией к Flutter](https://habr.com/ru/company/ruvds/blog/349622/)  
[Flutter. Плюсы и минусы](https://habr.com/ru/company/simbirsoft/blog/441766/)  
[Flutter — новый взгляд на кроссплатформенную разработку](https://habr.com/ru/company/google/blog/426701/)  
[Flutter: Почему использует язык Dart](https://habr.com/ru/post/662135/)  
[8 плюсов Flutter по сравнению с React Native](https://habr.com/ru/post/491832/)  
[Как стать Flutter-разработчиком, или Почему кроссплатформа сейчас — это лучший выбор](https://habr.com/ru/post/695568/)
[Переходим на Flutter: за и против](https://habr.com/ru/articles/722466/)  
[Выбираем между кросс-платформенной и нативной разработкой](https://habr.com/ru/companies/agima/articles/736984/)  
[Flutter: почему он стал таким популярным и нужно ли изучать его прямо сейчас](https://habr.com/ru/companies/friflex/articles/779810/)  
[Болевые точки Dart и Flutter](https://habr.com/ru/articles/724538/)  
[Flutter: заказывать или не заказывать? Откровения разработчика](https://habr.com/ru/articles/766826/)  

# Другое
[Flutter: Настройка тем приложения](https://habr.com/ru/post/690572/)  
[Flutter на ОС Аврора](https://habr.com/ru/articles/761176/)  
[Полное руководство по использованию FVM (Flutter Version Management) – жонглируйте версиями Flutter sdk в своих проектах](https://habr.com/ru/articles/758212/)  
[Flutter-разработчикам: показываем, как шарить код через DartPad](https://habr.com/ru/companies/surfstudio/articles/754058/)    
[Свое мобильное приложение: от идеи до разработки, продвижения и развития](https://habr.com/ru/articles/726516/)  
[Как я стал Google Developer Expert по Flutter](https://habr.com/ru/articles/778328/)  
