# I can has frontend skillz: fat FAQ

Платиновая шапка платинового треда.

## Содержание:

1. [Интро](#Интро)
2. [Верстка](#Верстка)
3. [JavaScript](#javascript)
4. [Основы](#Основы)
5. [Продолжение](#Продолжение)
6. [Advanced](#advanced)
7. [Заключение](#Заключение)

## Интро

Этот FAQ посвящен вкату во фронтенд-разработку — создание веб-приложений на HTML, CSS и JavaScript. Сейчас эта область на этапе взрывного роста: современные браузеры позволяют создавать очень сложные и функциональные сайты-приложения, такие как Google Docs, Gmail, VK и Facebook.

Разработка таких приложений состоит из двух частей:
1. Простой — верстка на HTML и CSS компонентов и целых страниц приложения — они должны правильно отображались на разных устройствах и разрешениях и иметь нужные размеры, цвета и шрифты.
2. И сложной — «оживление» с помощью JS чтобы оно могло получать данные с сервера, отправлять их туда и реагировать на действия пользователя.

Соотношение частей растет в пользу второй по мере увеличения сложности проекта — на обычном лендинге может быть много верстки и лишь пара скриптов, которые меняют картинки в слайдере, а код большой энтерпрайз-CRM практически полностью состоит из JS.

Вакансии на чистых верстальщиков периодически мелькают в ДС и ДС2, но даже там в требованиях обычно указывают как минимум jQuery. Умение в респонсив, сборщики, препроцессоры и прочие ништяки — это само собой. В мусохрансках вакансии на верстал — нонсенс, хотя в треде иногда отчитываются аноны, которые таки СМОГЛИ устроиться верстальщиком. Но расчитывать на это не стоит.

В 2017 фронтенд-разработчик это продвинутый формошлеп, который, в основном, копается в JS. Это не значит, что изучать верстку не обязательно — даже если на работе верстать не будете, на собеседовании обязательно спросят какую-нибудь фигню.

Что нужно знать на позицию фронтенд-разработчика начально-среднего уровня:
  * HTML + CSS
  * JS с ES6-синтаксисом
  * Фреймворк. Нет, jQuery не считается. Лучший выбор для новичка - Реакт. Если генетика одарила вас железобетонной силой воли — Angular 2.

Учится попутно:
  * Инструменты сборки: gulp или webpack
  * Окружение разработчика: npm, git, командная строка

Все теоретические навыки обязательно подкрепляются практикой. Это может быть калькулятор, крестики-нолики, сверстанный статик-сайтец или даже полноценная приложуха на фреймворке.

### Ответы на вопросы для самых маленьких

> Можно ли вкатиться в `age` лет?

Можно.

> Можно ли вкатиться без знаний программирования, матана, функционирования гипертекст протоколов и т.д.?

Можно.

> Можно ли вкатиться без высшего образования или с дипломом заборостроительного ВУЗа?

Можно.

> Есть ли работа?

Да. В обозримые `n` лет была, есть и будет. В России это чуть ли не единственный рынок на котором сейчас растут зарплаты.

> Мой друг Ваня-копирайтер сказал, что кризис, работу вайти не найти, джуниоров не берут и вообще лучше выпилиться. Это правда?

И да, и нет. На рынке катастрофическая нехватка *грамотных* специалистов. Конторы разной степени говнистости готовы судиться за любого миддла, появление где-нибудь на hh открытого резюме сениора вызывает жуткий резонанс, начинается охота, интриги, драмы, эйчары прыгают из окон. В тоже время рынок перенасыщен дебилами-выпускниками гикбрейнс-гоайти и прочих итвднов, которые ничего не умеют, а на работу хотят, бегают, размахивают своими сертификатами курсов. Ну вы понели, да?

_TL;DR_: если вы осилите нечто большее, чем прикручивание плагинов и верстку на бутстрапе, сможете показать, что вы владеете актуальным стеком технологий — работа сама вас найдет даже без реального опыта.

> Кто-то уже приходил к успеху/расскажите кулстори/кто-то уже работает/кто-то съехал от мамки

Да, и не один а двое, азазаза.

Ладно. Да приходили, и да, вряд-ли кто-то тут получает удовольствие от повторения одних и тех же слов в тысячный раз. Пожалуйста, избавь нас от этой головной боли.

> Сколько времени займет обучение?

Примерно 1000 часов до программиста, которому не страшно доверить коммерческий проект без постоянного присмотра. На работу можно пытаться устраиваться после 500 часов.

> Могу ли учить верстку/JS после работы по 2 часа?

Можете, но это вряд ли будет эффективно. Умножаем время на 1,3.

> Слышал что для устройства на работу нужно портфолио

Да, портфолио программиста это его гитхаб и ссылка на него должа стоять в резюме. Кроме того, все проекты, которые можно «потрогать» должны быть опубликованы на Github pages.

> Почему фронтенд вообще существует? Есть же CMS/конструкторы-сайтов.

Жизнь сложнее конструктора.

## Верстка

### Основы

#### Что нужно знать:
  * HTML:
    *  Структура документа
    *  Разметка
    *  Тэги
    *  Атрибуты
  * CSS:
    *  Основные селекторы (без фанатизма)
    *  Основные свойства (отступы, размеры, цвет, шрифты и прочее)
    *  Наследование свойств, каскад, вложенность
    *  Основы сетки: блочная модель, флоаты, инлайн-блоки
    *  Свойства position
  * Все вместе:
    *  Типовая разметка текста
    *  Картиночки, ссылочки
    *  Таблички, списочки
    *  Формы, инпуты, лэйблы

#### Итого

Умение сверстать простенькую статику, без новомодных фич, без семантики, модульности, бэмов, шмэмов, респонсивности и прочего.

#### Где учить, что читать?

  *  Старт: интерактивные курсы хтмл академии: https://htmlacademy.ru/program бесплатных вполне хватит, но можно и оплатить подписку (лучше не надо). Можно спросить в треде скриншоты теории продвинутых интерактивов: их регулярно трут отовсюду, кроме меги, поэтому приходится перезаливать.
  *  http://htmlbook.ru/
  *  https://webref.ru/
  *  Базовый интенсив все той же академии (брать на торрентах)

Не стоит увлекаться просмотром сотен тысяч курсов, вебинаров, туториалов и прочему. Как правило хтмл академии + хтмлбука более, чем достаточно для усвоения азов верстки.

### Верстка advanced

#### Что нужно знать:
  * HTML5:
    *  "Новые" тэги
    *  "Новые" атрибуты
    *  Формы и инпуты
    *  {Что-нибудь еще}
  * CSS:
    *  Продвинутые селекторы (опять же без фанатизма, но знать полезно)
    *  Градиенты, трансформации, анимации, переходы и прочие приколюхи
    *  Флекс Бокс (значение знаеш?)
    *  Респонсив ("адаптивность")
    *  {Что-нибудь еще}
  * О дивный новый мир:
    *  Автоматизация (галп, нпм / йарн + скрипты)
    *  Организация структуры проекта
    *  Препроцессоры (любой на выбор)
    *  {Что-нибудь еще}
  * Не помешает:
    * Умение самостоятельно размечать и реализовывать динамические штуки (слайдер, например)
    * Примерное понимание как работает js || jq

#### Итого получаем:

Готовую личинку верстальщика, которая сможет заверстать статику любой сложности по данному макету.

#### Где учить, что читать?

  *  Продолжаем: интерактивные курсы хтмл академии https://htmlacademy.ru/program читаем про флексы, препроцессоры и т.п. Материалы платных интерактивов можно спросить в тредике
  *  http://htmlbook.ru/
  *  https://webref.ru/
  *  Продвинутый интенсив академии (брать на торрентах)
  *  Верстка по БЭМ на примерах: http://habrahabr.ru/post/203440/
  *  http://ru.bem.info/ - документация БЭМ от Яндекса
  *  http://getbootstrap.com/ - Бутстрап. Полезная штука, кто бы что ни говорил.   
  *  http://habrahabr.ru/post/114256/ - чеклист верстки. Несколько устарел, но, в целом, актуален.
  *  http://habrahabr.ru/hub/webdev/ - тематический хаб, иногда проскальзывают полезные публикации.
  *  Документация препроцессоров: http://sass-lang.com/ http://lesscss.org/ http://stylus-lang.com/

__Дополнительные ресурсы, которые могут быть полезными на данном этапе:__

  *  http://tympanus.net/codrops/ - еженедельная подборка новостей
  *  http://www.smashingmagazine.com/ - многое отсюда так или иначе переведено на русский, ресурс полезный для развития
  *  http://css-tricks.com/ - много готовых шаблонов для решения часто встречающихся задач  
  *  http://codepen.io/ - ресурс с кучей интересных примеров кода
  *  http://www.html5rocks.com/en/ - туториалы от гугла
  *  http://frontender.info - неплохой ресурс, но редко обновляется
  *  http://www.sitepoint.com/html-css/, https://medium.com/tag/css, http://css-live.ru/ выборка статей по теме.
  *  Уютный бложик Никотина: http://nicothin.pro/ (есть полезные статейки)
  *  Материалы интенсивов академии: https://github.com/tsergeytovarov/htmlacademy-basic-additional-material
  *  Материалы от teamtreehouse, любезно слитые аноном (англ): https://mega.nz/#!PgRiXJLK!Ske0xNBPaC9Rm_3mV9c5Zoz6rD5Yna-V7pI-yzJOB_A

> __А книги, книги то будут? Хочу книжку!__

Книги надо выбирать индивидуально. Если по HTML/CSS, то желательно, чтобы книга была не старше 2012 года, ну или хотя бы переиздана. Читай все что интересно. В любом случае это будет полезно.

* http://frontendbookshelf.ru/ - список полезных книг. Большинство актуальны, можно выбрать по языку, технологии и конкретному уровню знаний. Первооочередную литературу желательно брать оттуда.
* http://scanlibs.com/ что-то типа хранилища айти книг. Скачать книги можно бесплатно. Там есть дохуя всего. Если в свободном доступе не найдете, попробуйте поискать там.

#### Что верстать?
  *  Макеты для верстки, тоже от академии. Все из их рассылки, поэтому лучше бы тебе на нее подписаться. https://mega.nz/#!CtYGSCbB!3Y6fDxxL_N_LstGFPGjHrhXbIoNqk4BzmNjjEmk2jPc
  *  Вполне годные макеты можно найти здесь: http://freebiesbug.com/psd-freebies/
  *  Moose - http://yadi.sk/d/g74XxFDUPyrob  - корпоративный сайт
  *  Hotel - http://yadi.sk/d/5VEeZriDPyroK  - туристический сайт
  *  Seabird - http://yadi.sk/d/XVt_w-TrPyrp4  - корпоративный сайт
  *  Appmo - https://yadi.sk/d/Ofaah1ZsTNrLf  - лендинг приложения
  *  Cleanwhite - https://yadi.sk/d/b05MLaKITNrLy  - корпоративный сайт
  *  Shoes - https://yadi.sk/d/Cp7qki0yTNrM4  - интернет-магазин обуви.
  *  Крупный пак с псдшками для практики - https://mega.nz/#!CtYGSCbB!3Y6fDxxL_N_LstGFPGjHrhXbIoNqk4BzmNjjEmk2jPc
  *  http://dbfreebies.co/templates  http://freebiesbug.com/psd-freebies/website-template/ - cайты с макетами.
  *  http://www.html5rocks.com/ru/tutorials/internals/howbrowserswork/  как работают браузеры.

#### В чем работать?

Вопрос личных предпочтений. Сейчас многие любители саблаймов и брэкетсов перешли на Visual Studio Code, говорят годнота. Никто не мешает писать в Атоме, Вебшторме или даже каком-нибудь Нетбинсе. Главное не слушать прожженных хардкорщиков и не бросаться "учить" vi и прочие emacs - напрасная трата времени.

#### Что делать дальше?
Сверстать пару макетов для закрепления и переходить к JS. Не помешает сразу зацепить гит, основные команды в терминале, поколупать какую-нибудь бубунту на виртуалке. Само собой использование галпа / вебпака, отсутствие боязни терминала, понимание того, как браузер рендерит страничку, как лучше подключать шрифты/стили/скрипты и т.п.

#### Гайд от анона по гитхабу:

>http://randomfederation.github.io/

## JavaScript

Мир верстки был довольно дружелюбным и понятным. Мир JS - это особый мир особого программирования, где любая задача может иметь десятки решений, где существуют сотни и тысячи инструментов, библиотек и подводных камней. Добро пожаловать в ад.

![alt text](http://i.imgur.com/lKnOgq7.png "welcome to hell")

Шутка. На самом деле, все довольно хорошо. ES6 прекрасен, вебпак прекрасен, а среди фреймворков осталось ровно два стула: React+Redux vs Angular2. Но обо всем по порядку.

## Основы

*  Учебник JavaScript http://learn.javascript.ru/ Ультраплатиновая ультрагоднота. Лучше просто нет, не осиливаете Кантора - повод задуматься о смене сферы интересов. Серьезно. На что обращать внимание в первую очередь (в порядке разделов учебника):
*  Основы - типы данных, функции, операторы
*  Структуры данных - массивы, объекты, их свойства, встроенные методы
*  Область видимости - что такое глобальный объект, как вызываются функции, как работают замыкания
*  Методы объектов и контекст вызова - здесь нужно осилить все

На этом можно притормозить и отдышаться. Что-то не получается? Не вычисляются фибоначчи? Рекурсия не рекурсирует? Отвлекитесь, отдохните, перечитайте теорию, попробуйте снова. Составьте алгоритм псевдокодом или вовсе своими словами.

Пример:

      `Создаем [пустой массив]. Берем число, проверяем его на нужное условие. Для этого нужно сделать то-то и то-то.`

Кантора нужно разнообразить:
*  https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw Очень годный канал (англ). Есть и основы ES5, и ES6 и, конечно, React + Redux + MobX.
*  Неплохой курс на коудкадеми(англ): https://www.codecademy.com/ru/learn/javascript
*  http://bonsaiden.github.io/JavaScript-Garden/ru/ - хорошая вещь. Как для тех, кто уже разбирается, так и для тех, кто только начинает и запутался.
*   __Справочник Mozilla Developer Network, без него никуда__ http://developer.mozilla.org/en/docs/Web/JavaScript

Опять же: все теоретические навыки обязательно подкрепляются практикой. Решайте задачки Кантора, ищите примеры реализации на youtube / codepen / stackoverflow. Можно уже попробывать написать что-нибудь рабочее, пусть даже код будет похож на императивную простыню: главное, чтобы работало.

## Продолжение

Lorem ipsum dolor amet

## Advanced

Lorem ipsum dolor amet

## Заключение

Lorem ipsum dolor amet

> Placeholder
*  http://learn.javascript.ru/
*  http://shamansir.github.io/JavaScript-Garden/
*  https://www.youtube.com/user/ArtSorax
*  https://www.youtube.com/channel/UCY10FZglXJ8RL3xB04VpykQ Тоже очень клевый канал, ЕС6, немного реакта, редакса и ангуляра
*  https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw Лучший туториал по реакту, вместе с оф.доками этого достаточно для уверенного освоения. Нишмагли? Добро пожаловать на завод, хаха.
*  https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w Годнота от парня с забавным акцентом.
*  https://egghead.io/courses Ультрагоднота на английском, есть все, много бесплатного, в том числе подробнейший скринкаст по редаксу от создателя редакса
*  https://www.coursera.org/ Неплохой ресурс, но почти все платно
*  http://codeschool.com/ Аналогично
*  Материалы от teamtreehouse, любезно слитые аноном (JavaScript Angular/Node/D3/Gulp/NPM/OOJS/Ajax/Ember, англ): https://mega.nz/#!C0ZmhIhJ!PoCGxIVvExoTa0rAjrDoXp-tjQ2kc3k5UasFu8lRB_4
