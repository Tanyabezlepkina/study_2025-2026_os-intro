---
lang: ru-RU
title: Доклад по теме "Trustworthy Computing Initiative"
subtitle: Архитектура компьютеров
author:
  - Безлепкина Т.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 06 марта 2026

## Fonts for PDF (кириллица)
mainfont: Liberation Serif
sansfont: Liberation Sans
monofont: Liberation Mono

## Formatting pdf
toc: false
slide_level: 0
aspectratio: 169
section-titles: true
---

# Информация

## Докладчик

- Безлепкина Татьяна Игоревна
- Студентка НКАбд-01-25
- Российский университет дружбы народов
- [1032253539@rudn.ru](mailto:1032253539@rudn.ru)

# 1. Вводная часть

## 1.1 Актуальность темы

- До 2002 года безопасность Windows не была приоритетом — важнее были новые функции
- Массовые атаки червей Code Red, Nimda, Klez, Slammer нанесли ущерб по всему миру
- Крупные клиенты (государства, банки) потеряли доверие к Microsoft
- Проблема: как перейти от «гонки функций» к безопасной разработке?

## 1.2 Объект и предмет исследования

### 1.2.1 Объект

- Инициатива Microsoft Trustworthy Computing (TwC)

### 1.2.2 Предмет

- Изменения в процессах разработки ПО, вызванные TwC, и их влияние на индустрию

## 1.3 Новизна

Системный анализ TwC как точки смены парадигмы: от гонки функций к безопасности как приоритету.

# 2. Цель

Рассмотреть инициативу Trustworthy Computing (TwC) как точку смены парадигмы в разработке ПО

# 3. Гипотеза

TwC не просто улучшила безопасность Microsoft, а создала отраслевой стандарт (SDL), который изменил индустрию в целом

# 4. Задачи исследования

- Выявить предпосылки создания TwC
- Описать 4 ключевых столпа инициативы
- Проанализировать изменения в процессах разработки Microsoft
- Оценить результаты, критику и наследие TwC

# 5. Материалы и методы исследования

## 5.1 Материалы

- Меморандум Билла Гейтса (2002)
- Документация Microsoft по SDL
- Аналитические обзоры Gartner, Forbes
- Публикации о TwC Next и Secure Future Initiative

## 5.2 Методы

- Анализ исторических источников
- Сравнительный анализ процессов разработки

# 6. Содержание исследования

## 6.1 Кризис доверия

Кто потерял доверие:
- Государственные учреждения
- Банки и финансовые компании
- Крупные корпоративные клиенты

Цитата (Джон Пескаторе, Gartner):
«Гейтс был главной причиной проблем с безопасностью. Он говорил, что потребители хотят удобства, а не безопасности»

## 6.2 Что было ДО TwC?

| Год | Событие | Кто | Значение |
|:---:|:---|:---|:---|
| 1999 | Доклад «Trust in Cyberspace» | Национальный исследовательский совет США | Первый сигнал тревоги о ненадёжности систем |
| 2000 | Вирусные атаки нарастают | Code Red, Nimda, Klez | Microsoft игнорирует проблему |
| 2002 | Меморандум Билла Гейтса | Microsoft | Старт инициативы Trustworthy Computing |

## 6.3 Четыре столпа TwC

| Столп | Суть |
|:---|:---|
| Безопасность | Защита от атак и вредоносного кода |
| Конфиденциальность | Контроль пользователя над личными данными |
| Надёжность | Стабильная работа без сбоев |
| Честность бизнеса | Прозрачность и открытость перед клиентами |

## 6.4 Как менялась разработка

Февраль 2002 — «Security Push»

| Действие | Что произошло |
|:---|:---|
| Остановка кода | Тысячи разработчиков прекратили писать новый код |
| Массовая проверка | Весь месяц проверяли существующий код на уязвимости |
| Обучение | Разработчики проходили обязательные курсы безопасности |
| Затронутые продукты | Windows, Office, Visual Studio |

Цитата (Халид Карк, Forrester Research):
«Гейтс задал видение, которое привело к фундаментальным изменениям в Microsoft»

## 6.5 Шесть этапов SDL

- Требования — обучение, стандарты безопасности
- Проектирование — моделирование угроз (STRIDE)
- Реализация — безопасные функции, статический анализ кода
- Верификация — динамическое тестирование, фаззинг, пентесты
- Релиз — постепенный выпуск по «кольцевой» системе
- Реагирование — мониторинг и выпуск обновлений

## 6.6 Новые вызовы

- Облачные сервисы (Azure, Office 365) — новые модели угроз
- Мобильные устройства — рост числа атак
- Кибершпионаж (Advanced Persistent Threats) — целевые атаки
- Большие данные — новые цели для злоумышленников

Цитата (Скотт Чарни, корп. вице-президент Microsoft, 2012):
«Мы находимся на очередной переломной точке. Ожидания лучшей безопасности растут в геометрической прогрессии»

# 7. Анализ и практическая значимость

## 7.1 Результаты и критика TwC

| Положительные | Критика |
|:---|:---|
| Эпидемии вирусов прекратились | Уязвимости остались даже после SDL |
| SDL стал отраслевым стандартом | Безопасность — «прикрученное» дополнение |
| Качество Windows значительно выросло | Изменение восприятия заняло годы |

# 8. Заключение и выводы

Trustworthy Computing — это не просто набор правил, а фундаментальная смена парадигмы.

- Безопасность перестала быть «галочкой» в конце разработки
- Стала встроенным свойством ПО на всех этапах
- SDL остаётся отраслевым стандартом спустя более 20 лет
- Современные инициативы Microsoft (SFI) продолжают ту же философию

# 9. Список литературы

1. ITPro Today. Complete text of the Bill Gates "Trustworthy Computing" Memo (2002). 
   https://www.itprotoday.com/it-management/complete-text-of-the-bill-gates-trustworthy-computing-memo

2. Wikipedia. Trustworthy computing. 
   https://en.wikipedia.org/wiki/Trustworthy_computing

3. Microsoft Learn. The Trustworthy Computing Security Development Lifecycle (2005). 
   https://learn.microsoft.com/en-us/archive/technet-wiki/7100.the-security-development-lifecycle

4. InfoQ. Bryan Sullivan on Security Development Lifecycle (2010). 
   https://www.infoq.com/articles/sullivan-sdl/

5. InformationWeek. Microsoft Launches Security Initiative (2001). 
   https://www.informationweek.com/cyber-resilience/microsoft-launches-security-initiative

6. Computerworld. Microsoft Launches Security Initiative (2001). 
   https://www.computerworld.com/article/1354646/microsoft-launches-security-initiative.html

7. Forbes. The Business World Owes A Lot To Microsoft Trustworthy Computing (2014). 
   https://www.forbes.com/sites/tonybradley/2014/03/05/the-business-world-owes-a-lot-to-microsoft-trustworthy-computing/

8. Microsoft Press. The Security Development Lifecycle (Howard, Lipner, 2006). 
   https://www.microsoftpressstore.com/store/security-development-lifecycle-sdl-a-process-for-developing-9780735622142

9. Microsoft Learn. SD3+C концепция. 
   https://learn.microsoft.com/zh-tw/previous-versions/msdn10/cc895318(v=msdn.10)
