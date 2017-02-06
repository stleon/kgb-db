# kgb-db
Дело-ориентированная БД

Основная кодировка данной БД - **Косыгин-8**. Доступна на пользовательской операционной системе **Маркс ОС**, а также на серверной - **Энгельс ОС** (запускаемой в виртуальной машине **ЗИЛ**).

В состав бд входят:

- Lenin CI
- Дзержинский Антивирус
- Горбачев-коллектор (gc)

Это первая система, полностью поддерживающая **Хрущев Procedure Call** (оборачивание сообщений в кукурузу) и **iOSталин**.

БД содержит **партийные ячейки** (таблицы), **звенья** (колонки). У каждой таблицы есть **вожатый** (owner). Простейший индекс - целина.

Каждый инстанс **kgb-db** можно запустить в контейнере - **республике**. Синхронизация между республиками происходит через **Собрания КПСС**.

В качестве генератора рандомных чисел используется **спорт-лото**, а 1917 год - как начало эпохи.

Предустановлен мощный firewall - **Занавес**. На данный момент существует только один внешний драйвер - **Fidel**.

Главный процесс, контролирующий работу всей системы, - **ГенСек**, напрямую связан с ядром.

## Ядро

**kgb-db** благодаря своему ядру **Лубянка** может выдержать до 1 000 000 000 доносов в секунду (реализация очередей и талонов).

В ядре **Лубянка** не может сущестовать никаких importов, подключаемых модулей и плагинов. 

Однако допускается использование расширений для работы с ядром. Главным каналом распросранения таких пакетов является package-index **Ералаш** (веселые пакеты).

**БАМ** используется в качестве шины, с помощью которой решается теорема **CAP**.

Главные компоненты дело-ориентированной базы данных - это **товарищи** и **доносы** на товарищей.

## Товарищ

Товарищ (рабочий) - это абстрактный базовый класс, от которого наследуются другие классы:
- резидент
- коммунист
- партийный
- беспартийный
- спорстмен

Ниже приведен код проверки товарища:

```
если не товарищ
  верни тамбовский волк --- враг народа
```

У товарища есть следующие абстрактные методы:
- `__расстрел__`
- `__go_to_гуллаг__`
- `__создать_донос__`
- `__собрание__` (партийное)

Для того, чтобы взаимодейстовать с **kgb-db**, товарищу необходим партийный билет (auth token).

Воронок может доставить до 3х товарищей на stack (**карцер**).

## Донос

Доносы пишутся на **Донос Query Language**:

```
выбрать всех товарищей, где донос - истина, иначе расстрел
```

Существует механизм ускорения **ДQL** - 5-летки.

Также реализован язык допросов. 

Товарищ может выдержать только 1 одновременный допрос.

## Установка

Чтобы скачать последние обновления **kgb-db** на **Маркс ОС** достаточно использовать **Gagarin Version Control**:

```
yura pull kgb-db
```

Или 

```
yura push
```

Для публикации изменений.

## Тестирование

Для написания своих тестов используют следущие объекты:
- белка
- стрелка

Их необходимо *mock*ать, также существует соглашение о наименовании их - `белок` и `уголек`, так как 

> Они сгорели

Для тестирования товарищей обычно применяют **гулаги**.

## Сообщество

Проводятся митапы - **October Fest**, где происходит встреча пользователей с евангелистами и core-разработчиками **kgb-db**.

Для огромного кол-ва ~~говна~~ поделий, производимых сообществом, был создан специальный зоопарк фреймворков - **Артек**. 

На основе **kgb-db** написана социальная сеть **Пионерская Зорька**.

**Pioner.js**, разработанный сообществом, позволяет на порядок увеличить кол-во доносов, которое может выдержать **kgb-db**, включен в официальную поставку.
