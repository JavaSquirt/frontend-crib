# frontend-crib
Тут будет описание
<!DOCTYPE html>
<html lang="ru">
<head>
  <title>Frontend info. HTML, CSS, JavaScript and other...</title>
  <link rel="icon" type="image/png" href="img/favicon.png">
  <!-- <meta name="google-site-verification" content="Xr39MNyJOeeGSQ7QM-cfbKlRXS_6hdeDF4E37qe1HO4"> -->
  <!-- <meta name="yandex-verification" content="213a5e4fb918d3d0" /> -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <meta name="description" content="Топовые материалы по фронтенду, на русском языке.">
  <meta name="keywords" content="html, css, javascript, grid, fonts, svg, flexbox, бэм">
  <meta name="author" content="Vald3r">
  <!-- place for fonts -->
  <link href="https://fonts.googleapis.com/css?family=Play:400,700&amp;subset=cyrillic" rel="stylesheet">
  <link rel="stylesheet" href="css/normalize.css">
  <link rel="stylesheet" href="css/mobile-first.css">
  <!-- <script async src="js/google-analytics.js"></script> -->
  <!-- <script async src="js/yandex-metrika.js"></script> -->
</head>
<body>

  <!-- ========== HEADER ========== -->

  <header class="header">
    <div class="container">
      <nav class="header-nav">
        <ul>
          <li>
            <a href="index.html" target="_blank" class="active">Home</a>
          </li>
          <li>
            <a href="https://github.com/vald3r" target="_blank">Git</a>
          </li>
          <li>
            <a href="https://codepen.io/Vald3r/" target="_blank">Codepen</a>
          </li>
          <li>
            <a href="projects.html" target="_blank">Work</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- ========== Содержание ========== -->

  <div class="container">
    <h2><small>Краткое содержание:</small></h2>
    <ul class="list">
      <li>
        <a href="#start">
          С чего начать.
        </a>
      </li>
      <li>
        <a href="#articles">
          Статьи.
        </a>
      </li>
      <li>
        <a href="#flexbox">
          Flexbox
        </a>
      </li>
      <li>
        <a href="#grid">
          Grid Layout
        </a>
      </li>
      <li>
        <a href="#codeguides">
          Кодгайды
        </a>
      </li>
      <li>
        <a href="#progressive-enhancement">
          Прогрессивное улучшение
        </a>
      </li>
      <li>
        <a href="#fonts">
          Шрифты
        </a>
      </li>
      <li>
        <a href="#svg">
          SVG
        </a>
      </li>
      <li>
        <a href="#mobile-first">
          Mobile First
        </a>
      </li>
      <li>
        <a href="#media-queries">
          Медиа запросы
        </a>
      </li>
      <li>
        <a href="#bem">
          БЭМ
        </a>
      </li>
      <li>
        <a href="#git">
          Git
        </a>
      </li>
      <li>
        <a href="#podcasts">
          Подкасты
        </a>
      </li>
      <li>
        <a href="#books">
          Литература
        </a>
      </li>
      <li>
        <a href="#useful">
          Полезности
        </a>
      </li>
      <li>
        <a href="#gulp">
          Gulp
        </a>
      </li>
      <li>
        <a href="#webpack">
          Webpack
        </a>
      </li>
      <li>
        <a href="#minification">
          Минификация
        </a>
      </li>
      <li>
        <a href="#ide">
          IDE
        </a>
      </li>
    </ul>
  </div>

  <!-- ========== MAIN ========== -->

  <div class="container">
    <h2 id="start">С чего начать.<br> <small>Подробно. Структурировано. Актуально.</small></h2>
    <ul>
      <li>
        <a href="http://webmasters.teamdev.com" target="_blank" title="TeamDev">
          TeamDev
        </a>
        <p>
          <del>Предупреждение</del> <ins>пособие</ins> для тех, кому надо верстать.
        </p>
      </li>
      <li>
        <a href="http://krekotun.ru/ui-developer-skills" target="_blank" title="Что должен знать HTML-верстальщик?">
          Что должен знать HTML-верстальщик?
        </a>
        <p>
          В этой статье я перечислю все актуальные на сегодняшний момент знания и инструменты, которые позволят вам успешно работать в профессии и создадут базу для развития.
        </p>
      </li>
      <li>
        <a href="https://www.gitbook.com/book/melnik909/tutorial-for-beginner-front-end-developer/details" target="_blank" title="Методическое пособие по HTML-верстке для новичков">
          Методическое пособие по HTML-верстке для новичков.
        </a>
        <p>
          Данное методическое пособие содержит основополагающие знания, актуальные приемы, практические задачи и полезные советы для людей, которые только начинают делать первые шаги в HTML-верстке.
        </p>
      </li>
      <li>
        <a href="https://medium.com/russian/от-нуля-до-героя-front-enda-часть-1-f524d668f328" target="_blank" title="От нуля до героя фронтенда">
          От нуля до героя фронтенда.
        </a>
        <p>
          Часть первая.
        </p>
      </li>
      <li>
        <a href="http://blog.csssr.ru/2016/09/19/how-to-be-a-beginner-developer/" target="_blank" title="Как быть начинающим разработчиком и не сойти с ума">
          Как быть начинающим разработчиком и не сойти с ума.
        </a>
        <p>
          Узбагойтесь.
        </p>
      </li>
      <li>
        <a href="https://exit.sc/?url=https%3A%2F%2Fmedium.com%2Fp%2F865b640d5d18" target="_blank" title="Frontend Dev: хороший, плохой, злой">
          Frontend Dev: хороший, плохой, злой.
        </a>
        <p>
          Часть 1: Хороший путь
        </p>
      </li>
      <li>
        <a href="https://htmlacademy.ru" target="_blank" title="HTML Academy">
          HTML Academy
        </a>
        <p>
          Категорически рекомендую.
        </p>
      </li>
      <li>
        <a href="https://webref.ru" target="_blank" title="webref.ru">
          webref.ru
        </a>
        <p>
          Справочники и руководства.
        </p>
      </li>
      <li>
        <a href="https://codebra.ru" target="_blank" title="codebra.ru">
          codebra.ru
        </a>
        <p>
          Курсы по HTML, CSS, JavaScript, PHP, jQuery.
        </p>
      </li>
      <li>
        <a href="https://html5book.ru" target="_blank" title="html5book.ru">
          html5book.ru
        </a>
        <p>
          Весьма толковые справочники и уроки по HTML, CSS, JS и т.д.
        </p>
      </li>
      <li>
        <a href="http://ru.html.net" target="_blank" title="html.net">
          html.net
        </a>
        <p>
          Учебники по HTML, CSS, PHP.
        </p>
      </li>
      <li>
        <a href="http://htmlbook.ru" target="_blank" title="htmlbook.net">
          htmlbook.net
        </a>
        <p>
          Ходят слухи что лучший справочник всея-руси по HTML, CSS.
        </p>
      </li>
      <li>
        <a href="https://learn.javascript.ru" target="_blank" title="Библия ЖС на русском">
          learn.javascript.ru
        </a>
        <p>
          Лучший онлайн учебник по ЖС на русском.
        </p>
      </li>
      <li>
        <a href="https://pastebin.com/3VAYADCd" target="_blank" title="pastebin">
          Кошерная паста по теме
        </a>
        <p>
           Маст рид. Некоторые представленные в ней ресурсы уже не рабочие(мб когда-нибудь разгребу и составлю свой список <del>с игрищами и блудницами</del>).
        </p>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/netologyru/blog/327294/" target="_blank" title="Статья безумной женщины">
          Статья какой-то безумной женщины из Нетологии.
        </a>
        <p>
          Комменты доставляют, в них же и представлена более конструктивная инфа по теме.
        </p>
      </li>
      <li>
        <a href="https://exit.sc/?url=https%3A%2F%2Fmedium.com%2Fp%2F619289ce8bae" target="_blank" title="Хорошие и плохие CSS-практики для начинающих">
          Хорошие и плохие CSS-практики для начинающих.
        </a>
        <p></p>
      </li>
      <br>
      <li>
        <a href="https://exit.sc/?url=https%3A%2F%2Fmedium.com%2Fp%2Fa916de106283" target="_blank"  title="Собеседование">
          Собеседование.
        </a>
        <p>
          Что ожидать от собеседования на должность HMTL-Верстальщик/Junior frontend программист.
        </p>
      </li>
    </ul>

    <!-- ========== Articles ========== -->

    <h2 id="articles">Статьи</h2>
    <ul>
      <li>
        <a href="http://prgssr.ru/development/9-nedoocenivaemyh-vozmozhnostej-css.html" target="_blank" title="9 недооцененных возможностей CSS">
          9 недооцененных возможностей CSS.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles-css/impossible-pseudos.html" target="_blank" title="Псевдоэлементы, которых не может быть">
          Псевдоэлементы, которых не может быть.
        </a>
      </li>
      <br>
      <li>
        <a href="https://htmlacademy.ru/blog/115-always-use-a-label" target="_blank" title="Всегда используйте label">
          Всегда используйте label.
        </a>
      </li>
      <br>
      <li>
        <a href="https://ru.bem.info/forum/1130/" target="_blank" title="Минимизация классов в HTML">
          Минимизация классов в HTML.
        </a>
      </li>
      <br>
      <li>
        <a href="https://isqua.ru/blog/2017/05/21/artgorbunov-typography/" target="_blank" title="Статьи Артёма Горбунова про типографику и вёрстку">
          Статьи Артёма Горбунова про типографику и вёрстку.
        </a>
      </li>
      <br>
      <li>
        <a href="http://nicothin.pro/" target="_blank" title="Блог Николая Громова о веб-разработке и фотографии">
          Блог Николая Громова о веб-разработке и фотографии.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/312022/" target="_blank" title="Каково оно учить JavaScript в 2016">
          Каково оно учить JavaScript в 2016.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/312422/" target="_blank" title="Создавайте хорошие таблицы">
          Создавайте хорошие таблицы.
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/alternativnyj-tekst-dlya-izobrazhenij.html" target="_blank" title="Альтернативный текст для изображений">
          Альтернативный текст для изображений.
        </a>
      </li>
      <br>
      <li>
        <a href="http://kizu.ru/fun/conditions-for-css-variables/" target="_blank" title="Условия для CSS-переменных">
          Условия для CSS-переменных.
        </a>
      </li>
      <br>
      <li>
        <a href="https://htmlacademy.ru/blog/64-about-normalize-css" target="_blank" title="О normalize.css">
          О normalize.css
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/peremennye-osnova-arhitektury-css.html" target="_blank" title="Переменные как основа архитектуры CSS при работе с препроцессорами">
          Переменные как основа архитектуры CSS при работе с препроцессорами.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/275539/" target="_blank" title="Почему до сих пор повсеместно не используется HTTPS?">
          Почему до сих пор повсеместно не используется HTTPS?
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/about-native-css-variables.html" target="_blank" title="Почему я в восторге от «родных» CSS-переменных">
          Почему я в восторге от «родных» CSS-переменных.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/upravlenie-zagruzkoj-css-s-pomoshhyu-polzovatelskix-svojstv.html" target="_blank" title="Управление загрузкой CSS с помощью пользовательских свойств">
          Управление загрузкой CSS с помощью пользовательских свойств.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles-css/background-clip-use-cases.html" target="_blank" title="Свойство background-clip и его применения">
          Свойство background-clip и его применения.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/kratkij-obzor-object-fit-i-object-position.html" target="_blank" title="Краткий обзор «object-fit» и «object-position»">
          Краткий обзор «object-fit» и «object-position».
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/selectel/blog/278167/" target="_blank" title="HTTP/2: готовимся к переходу">
          HTTP/2: готовимся к переходу.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/278655/" target="_blank" title="Кризис ожирения сайтов">
          Кризис ожирения сайтов.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/lyubovnoe-pismo-k-jquery.html" target="_blank" title="Любовное письмо к jQuery">
          Любовное письмо к jQuery.
        </a>
      </li>
      <br>
      <li>
        <a href="http://simonenko.su/8725324958/for-what-i-love-coffeescript" target="_blank" title="За что я люблю CoffeeScript">
          За что я люблю CoffeeScript.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/na-osvoenie-react-mne-potrebovalas-vsego-nedelya-a-chem-vy-xuzhe.html" target="_blank" title="На освоение React мне потребовалась всего неделя, а чем вы хуже?">
          На освоение React мне потребовалась всего неделя, а чем вы хуже?
        </a>
      </li>
      <br>
      <li>
        <a href="https://frontender.info/estimating-a-front-end-web-dev-job/" target="_blank" title="Оценка задач фронтендера">
          Оценка задач фронтендера (сайт временно не доступен).
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/avtomatizaciya-regressionnogo-testirovaniya-css-2016.html" target="_blank" title="Автоматизация регрессионного тестирования CSS">
          Автоматизация регрессионного тестирования CSS.
        </a>
      </li>
      <br>
      <li>
        <a href="https://frontender.info/css-modules-part-1-need/" target="_blank" title="Что такое CSS-модули и зачем они нам?">
          Что такое CSS-модули и зачем они нам? (сайт временно не доступен)
        </a>
      </li>
      <br>
      <li>
        <a href="https://events.yandex.ru/lib/talks/1520/" target="_blank" title="Семантика или смерть">
          Семантика или смерть.
        </a>
      </li>
      <br>
      <li>
        <a href="https://webref.ru/layout/magic-of-css" target="_blank" title="Магия CSS">
          Магия CSS.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/otladka-css.html" target="_blank" title="Отладка CSS">
          Отладка CSS.
        </a>
      </li>
      <br>
      <li>
        <a href="https://frontender.info/whats-wrong-with-jquery-and-bootstrap/" target="_blank" title="jQuery и Bootstrap: расставляем точки над «i»">
          jQuery и Bootstrap: расставляем точки над «i». (сайт временно не доступен)
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/semanticheskij-css.html" target="_blank" title="Семантический CSS">
          Семантический CSS.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/ponimanie-semantiki.html" target="_blank" title="Понимание семантики">
          Понимание семантики.
        </a>
      </li>
      <br>
      <li>
        <a href="https://github.com/yoksel/common-words" target="_blank" title="Слова, часто используемые в CSS-классах">
          Слова, часто используемые в CSS-классах.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/vecssti-s-polej/modul-generiruemogo-kontenta-css3-obnovilsya-spustya-13-let.html" target="_blank" title="Модуль генерируемого контента CSS3 обновился спустя 13 лет">
          Модуль генерируемого контента CSS3 обновился спустя 13 лет.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/regressivnye-veb-prilozheniya.html" target="_blank" title="Регрессивные веб-приложения">
          Регрессивные веб-приложения.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/tinkoff/blog/303580/" target="_blank" title="Как мы разрабатываем новый фронтенд Tinkoff.ru">
          Как мы разрабатываем новый фронтенд Tinkoff.ru
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/303918/" target="_blank" title="Опрос: насколько строго вы следуете стандартам и лучшим практикам на фронтенде?">
          Опрос: насколько строго вы следуете стандартам и лучшим практикам на фронтенде?
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/vecssti-s-polej/html5-0-uxodit-v-proshloe.html" target="_blank" title="HTML5.0 уходит в прошлое">
          HTML5.0 уходит в прошлое.
        </a>
      </li>
      <br>
      <li>
        <a href="https://web-standards.ru/articles/path-of-tutor/" target="_blank" title="Путь наставника">
          Путь наставника.
        </a>
      </li>
      <br>
      <li>
        <a href="https://web-standards.ru/articles/check-it-before-you-wreck-it/" target="_blank" title="Не проверив HTML5-кода, не суйся в воду">
          Не проверив HTML5-кода, не суйся в воду — с Майком™ Смитом.
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/oformlenie-modalnyh-okon.html" target="_blank" title="Оформление модальных окон">
          Оформление модальных окон.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/css-izolyaciya.html" target="_blank" title="CSS-изоляция">
          CSS-изоляция.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/yandex/blog/307064/" target="_blank" title="Делать ли мобильную версию?">
          Делать ли мобильную версию?
        </a>
      </li>
      <br>
      <li>
        <a href="http://kizu.ru/issues/cursor-pointer/" target="_blank" title="Правильный курсор на активных элементах">
          Правильный курсор на активных элементах.
        </a>
      </li>
      <br>
      <li>
        <a href="http://tonsky.livejournal.com/307980.html" target="_blank" title="Сказка о потерянном времени">
          Сказка о потерянном времени.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/308308/" target="_blank" title="Пишите меньше кода">
          Пишите меньше кода, блин.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/309076/" target="_blank" title="Недоступный веб: как мы развели такой бардак">
          Недоступный веб: как мы развели такой бардак.
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/sposoby-smeny-poryadka-vyvoda-elementov-s-pomoshyu-css.html" target="_blank" title="Способы смены порядка вывода элементов с помощью CSS">
          Способы смены порядка вывода элементов с помощью CSS.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/mailru/blog/309212/" target="_blank" title="Frontend: Разработка и поддержка">
          Frontend: Разработка и поддержка.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/309318/" target="_blank" title="4 вида утечек памяти в JavaScript и как с ними бороться">
          4 вида утечек памяти в JavaScript и как с ними бороться.
        </a>
      </li>
      <br>
      <li>
        <a href="http://kizu.ru/blog/styling-inline-code/" target="_blank" title="Оформление строчных блоков кода">
          Оформление строчных блоков кода.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/vecssti-s-polej/novye-statusy-html5-1-i-svg2.html" target="_blank" title="Новые статусы HTML5.1 и SVG2">
          Новые статусы HTML5.1 и SVG2.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/google/blog/308498/" target="_blank" title="Air Berlin: реализация Progressive Web App">
          Air Berlin: реализация Progressive Web App.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/google/blog/310454/" target="_blank" title="Секреты Progressive Web Apps: часть первая">
          Секреты Progressive Web Apps: часть первая.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/311920/" target="_blank" title="Может, хватит уже поливать грязью CSS на конференциях разработчиков?">
          Может, хватит уже поливать грязью CSS на конференциях разработчиков?
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles-css/understanding-border-image.html" target="_blank" title="Еще раз про border-image">
          Еще раз про border-image.
        </a>
      </li>
      <br>
      <li>
        <a href="https://exit.sc/?url=https%3A%2F%2Fmedium.com%2Fp%2F28d8ab6ebd3d" target="_blank" title="Доступность сайтов для самых маленьких">
          Доступность сайтов для самых маленьких.
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/kak-otravit-polzovatelya-s-mobilnym.html" target="_blank" title="Как отравить мобильного пользователя">
          Как отравить мобильного пользователя.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/matematika-css-shlyuzov.html" target="_blank" title="Математика CSS-шлюзов">
          Математика CSS-шлюзов.
        </a>
      </li>
      <br>
      <li>
        <a href="http://tanalin.com/blog/2016/11/div-dl-dt-dd/" target="_blank" title="DIV официально разрешён внутри DL">
          DIV официально разрешён внутри DL.
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/grid-fleksboks-i-vyravnivanie-blokov-nasha-novaya-sistema-raskladki.html" target="_blank" title="Грид, флексбокс и выравнивание блоков">
          Грид, флексбокс и выравнивание блоков.
        </a>
      </li>
      <br>
      <li>
        <a href="https://exit.sc/?url=https%3A%2F%2Fmedium.com%2Fp%2F7b2ad80f0340" target="_blank" title="Улучшение формы комментариев">
          Улучшение формы комментариев.
        </a>
      </li>
      <br>
      <li>
        <a href="http://telegra.ph/AMP-Instant-Articles-Instant-View-whut-11-23" target="_blank" title="AMP, Instant Articles, Instant View, whut?">
          AMP, Instant Articles, Instant View, whut?
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/odnoklassniki/blog/313978/" target="_blank" title="Анимации на GPU: делаем это правильно">
          Анимации на GPU: делаем это правильно.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/edison/blog/316668/" target="_blank" title="Hype Driven Development">
          Hype Driven Development.
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/kratkaya-zapis-css-kak-antipattern.html" target="_blank" title="Краткая запись CSS как антипаттерн">
          Краткая запись CSS как антипаттерн.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles-css/pravilnye-kontrolnye-tochki-v-css.html" target="_blank" title="На 100% правильный способ делать контрольные точки в CSS">
          На 100% правильный способ делать контрольные точки в CSS.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.com/@ABatickaya" target="_blank" title="Переводы и статьи Алёны Батицкой на Medium">
          Переводы и статьи Алёны Батицкой на Medium.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/316978/" target="_blank" title="Dear JavaScript">
          Dear JavaScript.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css.yoksel.ru/a11y-for-logotypes/" target="_blank" title="Логотип не отвечает или временно недоступен">
          Логотип не отвечает или временно недоступен.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.com/web-standards/манифест-а-что-зачем-865e609f6f47" target="_blank" title="Манифест? А? Что? Зачем?">
          Манифест? А? Что? Зачем?
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/319664/" target="_blank" title="Что поправить в верстке перед выпуском в продакшн?">
          Что поправить в верстке перед выпуском в продакшн?
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/faq/displayflow-root-not-clearfix.html" target="_blank" title="Новый display:flow-root — не clearfix, но что это и зачем?">
          Новый display:flow-root — не clearfix, но что это и зачем?
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.com/high-technologies-center/кто-ты-такой-service-worker-9bce3b1201b6" target="_blank" title="Кто ты такой, Service Worker?">
          Кто ты такой, Service Worker?
        </a>
      </li>
      <br>
      <li>
        <a href="https://frontender.info/the-power-of-rgba/" target="_blank" title="Сила цветовой CSS-функции rgba">
          Сила цветовой CSS-функции rgba. (сайт временно недоступен)
        </a>
      </li>
      <br>
      <li>
        <a href="http://callbackhell.ru" target="_blank" title="Ад обратных вызовов">
          Ад обратных вызовов.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.com/@olgabaryshnikova/веб-дизайнеры-начните-верстать-c44fa28b6ad9" target="_blank" title="Веб-дизайнеры, начните верстать!">
          Веб-дизайнеры, начните верстать!
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/htmlacademy/blog/321498/" target="_blank" title="Как «прокачаться» дизайнеру: советы и полезные ссылки от российских экспертов">
          Как «прокачаться» дизайнеру: советы и полезные ссылки от российских экспертов.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.com/web-standards/обещание-бургерной-вечеринки-b0ed209809ab" target="_blank" title="Обещание бургерной вечеринки">
          Обещание бургерной вечеринки.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.com/high-technologies-center/кто-ты-такой-service-worker-9bce3b1201b6" target="_blank" title="Кто ты такой, Service Worker?">
          Кто ты такой, Service Worker?
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/tricks/tryuk-razdelnye-funkcii-css-transformacii.html" target="_blank" title="Трюк: раздельные функции CSS-трансформации">
          Трюк: раздельные функции CSS-трансформации.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/html5/nuzhen-li-nam-novyj-zagolovochnyj-element.html" target="_blank" title="Нужен ли нам новый заголовочный элемент? Мы не знаем">
          Нужен ли нам новый заголовочный элемент? Мы не знаем.
        </a>
      </li>
      <br>
      <li>
        <a href="http://zmeika.name/2017/03/02/custom-css-properties-basics.html" target="_blank" title="Пользовательские свойства CSS. Основы">
          Пользовательские свойства CSS. Основы.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/css/metriki-shrifta-line-height-vertical-align.html" target="_blank" title="Неизведанные глубины CSS: метрики шрифта, line-height и vertical-align">
          Неизведанные глубины CSS: метрики шрифта, line-height и vertical-align.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/html5/problema-vybora-struktury-dokumenta.html" target="_blank" title="Проблема выбора структуры документа">
          Проблема выбора структуры документа.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/323876/" target="_blank" title="Правила использования ARIA в HTML">
          Правила использования ARIA в HTML.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.com/web-standards/реализуем-пуш-уведомления-на-фронтенде-и-бэкенде-9fea70221028" target="_blank" title="Реализуем пуш-уведомления на фронтенде и бэкенде">
          Реализуем пуш-уведомления на фронтенде и бэкенде.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/323790/" target="_blank" title="Асинхронный JavaScript против отложенного">
          Асинхронный JavaScript против отложенного.
        </a>
      </li>
      <br>
      <li>
        <a href="https://pepelsbey.net/2012/08/stylish-switch/" target="_blank" title="Модный переключатель">
          Модный переключатель.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.com/devschacht/david-gilbertson-rems-and-ems-and-why-you-probably-dont-need-them-3b2b1e785787" target="_blank" title="Ремы, емы, и почему отказ от них — не проблема">
          Ремы, емы, и почему отказ от них — не проблема.
        </a>
      </li>
      <br>
      <li>
        <a href="http://nicothin.pro/page/css-solutions" target="_blank" title="Советы по написанию современного CSS">
          Советы по написанию современного CSS.
        </a>
      </li>
    </ul>

    <!-- ========== Flexbox ========== -->

    <h2 id="flexbox">Flexbox</h2>
    <ul>
      <li>
        <a href="https://habrahabr.ru/post/281254/" target="_blank" title="Почти полное руководство по flexbox (без самих flexbox)">
          Почти полное руководство по flexbox (без самих flexbox).
        </a>
      </li>
      <br>
      <li>
        <a href="http://progressivered.com/fla/?d=0&v=1&h=1&s=0&i=000&a=000" target="_blank" title="Flex Layout Attribute">
          Flex Layout Attribute.
        </a>
      </li>
      <br>
      <li>
        <a href="http://prgssr.ru/development/kak-rabotayut-v-fleksbokse-z-index-i-avtootstupy.html" target="_blank" title="Как работают в флексбоксе z-index и автоотступы">
          Как работают в флексбоксе z-index и автоотступы.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/otnosites-k-setkam-na-fleksboksax-proshhe.html" target="_blank" title="Относитесь к сеткам (на флексбоксах) проще">
          Относитесь к сеткам (на флексбоксах) проще.
        </a>
      </li>
      <br>
      <li>
        <a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/" target="_blank" title="A Complete Guide to Flexbox">
          A Complete Guide to Flexbox.
        </a>
      </li>
      <br>
      <li>
        <a href="http://yoksel.github.io/flex-cheatsheet/" target="_blank" title="Flexbox Cheatsheet">
          Flexbox Cheatsheet.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.freecodecamp.com/an-animated-guide-to-flexbox-d280cf6afc35" target="_blank" title="">
          How Flexbox works — explained with big, colorful, animated gifs.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles-css/grid-fleksboks-moshhnejshee-kombo-v-veb-raskladke.html" target="_blank" title="">
          Грид + флексбокс: мощнейшее комбо в веб-раскладке.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.freecodecamp.com/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af" target="_blank" title="">
          Understanding Flexbox: Everything you need to know.
        </a>
      </li>
      <br>
      <li>
        <a href="https://alialaa.github.io/css-grid-cheat-sheet/" target="_blank" title="">
          CSS Grid Cheat Sheet.
        </a>
      </li>
    </ul>

    <!-- ========== Grid Layout ========== -->

    <h2 id="grid">Grid Layout</h2>
    <ul>
    <li>
      <a href="http://css-live.ru/verstka/gryadut-gridy.html" target="_blank" title="Грядут гриды">
        Грядут гриды!
      </a>
    </li>
    <br>
    <li>
      <a href="http://css-live.ru/css/bolshaya-statya-pro-gridy-css-grid-layout.html" target="_blank" title="Большая статья про гриды">
        Большая статья про гриды.
      </a>
    </li>
    <br>
    <li>
      <a href="http://css-live.ru/articles/ot-butstrapa-k-css-gridam.html" target="_blank" title="От бутстрапа - к CSS-гридам">
        От бутстрапа - к CSS-гридам.
      </a>
    </li>
    <br>
    <li>
      <a href="https://habrahabr.ru/post/331316/" target="_blank" title="CSS: введение в единицу длины 'fr'">
        CSS: введение в единицу длины 'fr'.
      </a>
    </li>
    <br>
      <li>
        <a href="http://learncssgrid.com/" target="_blank" title="A guide to learning CSS grid">
        A guide to learning CSS grid.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/325760/" target="_blank" title="CSS Grid Layout. Быстрый старт">
          CSS Grid Layout. Быстрый старт.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/znakomstvo-s-css-grid-layout.html" target="_blank" title="Знакомство с CSS Grid Layout">
          Знакомство с CSS Grid Layout.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/podrobno-o-razmeshhenii-elementov-v-grid-raskladke-css-grid-layout.html" target="_blank" title="Подробно о размещении элементов в грид-раскладке (CSS Grid Layout)">
          Подробно о размещении элементов в грид-раскладке (CSS Grid Layout).
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/css/zolotaya-rybka-css3-grid-layout.html" target="_blank" title="Золотая рыбка CSS3 Grid Layout (часть 1)">
          Золотая рыбка CSS3 Grid Layout (часть 1).
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/zolotaya-rybka-css3-grid-layout-chast-2.html" target="_blank" title="Золотая рыбка CSS3 Grid Layout (часть 2)">
          Золотая рыбка CSS3 Grid Layout (часть 2).
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/zolotaya-rybka-css3-grid-layout-chast-3.html" target="_blank" title="Золотая рыбка CSS3 Grid Layout (часть 3)">
          Золотая рыбка CSS3 Grid Layout (часть 3).
        </a>
      </li>
      <br>
      <li>
        <a href="https://webformyself.com/vvedenie-v-maket-css-grid/" target="_blank" title="Введение в макет CSS Grid">
          Введение в макет CSS Grid.
        </a>
      </li>
      <br>
      <li>
        <a href="https://www.mozilla.org/en-US/developer/css-grid/" target="_blank" title="Mozilla css grid">
          Mozilla CSS Grid.
        </a>
      </li>
      <br>
      <li>
        <a href="https://github.com/sylvainpolletvillard/postcss-grid-kiss" target="_blank" title="Grid Kiss">
          Grid Kiss.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/css-gridy-prishli-nasovsem.html" target="_blank" title="CSS-гриды пришли насовсем">
          CSS-гриды пришли насовсем.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/izuchaem-css-gridy.html#comment-254677" target="_blank" title="Изучаем CSS-гриды">
          Изучаем CSS-гриды.
        </a>
      </li>
      <br>
      <li>
        <a href="https://tympanus.net/codrops/css_reference/grid/" target="_blank" title="Codrops CSS Reference: Grid">
          Codrops CSS Reference: Grid.
        </a>
      </li>
      <br>
      <li>
        <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout" target="_blank" title="Basic concepts of grid layout">
          Basic concepts of grid layout.
        </a>
      </li>
      <br>
      <li>
        <a href="https://gridbyexample.com/video/" target="_blank" title="Learn Grid Layout Video Series">
          Learn Grid Layout Video Series.
        </a>
      </li>
      <br>
      <li>
        <a href="https://cloudfour.com/thinks/first-css-grid-layout/" target="_blank" title="Case Study: My First Practical CSS Grid Layout">
          Case Study: My First Practical CSS Grid Layout.
        </a>
      </li>
      <br>
      <li>
        <a href="https://alistapart.com/article/practical-grid" target="_blank" title="Practical CSS Grid: Adding Grid to an Existing Design">
          Practical CSS Grid: Adding Grid to an Existing Design.
        </a>
      </li>
      <br>
      <li>
        <a href="https://tuhub.ru/frontend/css-grid-complete-guide/" target="_blank" title="Полное руководство по CSS Grid">
          Полное руководство по CSS Grid на русском.
        </a>
      </li>
    </ul>

    <!-- ========== CODEGUIDES ========== -->

    <h2 id="codeguides">Кодгайды</h2>
    <ul>
      <li>
        <a href="https://htmlacademy.github.io/codeguide" target="_blank" title="HTML Academy">
          HTML Academy
        </a>
      </li>
      <br>
      <li>
        <a href="http://sadcitizen.me/code-guide/" target="_blank" title="MDO">
          MDO
        </a>
      </li>
      <br>
      <li>
        <a href="https://google.github.io/styleguide/htmlcssguide.html" target="_blank" title="Google">
          Google
        </a>
      </li>
      <br>
      <li>
        <a href="https://github.com/necolas/idiomatic-css/tree/master/translations/ru-RU" target="_blank" title="Idiomatic CSS">
          Idiomatic CSS
        </a>
      </li>
    </ul>

    <!-- ========== Progressive Enhancement ========== -->

    <h2 id="progressive-enhancement">Прогрессивное улучшение (Progressive Enhancement)</h2>
    <ul>
      <li>
        <a href="https://habrahabr.ru/post/157115/" target="_blank" title="Progressive Enhancement или всё-таки Graceful Degradation">
          Progressive Enhancement или всё-таки Graceful Degradation.
        </a>
      </li>
      <br>
      <li>
        <a href="https://uwebdesign.ru/progressive-enhancement/" target="_blank" title="Progressive Enhancement vs Graceful Degradation">
          Progressive Enhancement vs Graceful Degradation.
        </a>
      </li>
      <br>
      <li>
        <a href="https://exit.sc/?url=https%3A%2F%2Fmedium.com%2Fp%2F7084fa62d967" target="_blank" title="Прогрессивное улучшение меня расстраивает">
          Прогрессивное улучшение меня расстраивает.
        </a>
      </li>
      <br>
      <li>
        <a href="https://htmlacademy.ru/blog/8-is-it-expensive-to-progressive-enhancement" target="_blank" title="Так ли дорого прогрессивное улучшение?">
          Так ли дорого прогрессивное улучшение?
        </a>
      </li>
      <br>
      <li>
        <a href="https://htmlacademy.ru/blog/6-graceful-degradation" target="_blank" title="Graceful Degradation">
          Graceful Degradation.
        </a>
      </li>
      <br>
      <li>
        <a href="https://htmlacademy.ru/demos/1#step1" target="_blank" title="Progressive enhancement на примере формы входа">
          Progressive enhancement на примере формы входа.
        </a>
      </li>
      <br>
      <li>
        <a href="https://events.yandex.ru/lib/talks/373/" target="_blank" title="Progressive Enhancement: практичный подход к современной кроссбраузерной разработке">
          Progressive Enhancement: практичный подход к современной кроссбраузерной разработке.
        </a>
      </li>
    </ul>

    <!-- ========== Fonts ========== -->

    <h2 id="fonts">Шрифты</h2>
    <ul>
      <li>
        <a href="https://habrahabr.ru/post/310044/" target="_blank" title="Шрифты в вебе, обзор от 2016 года">
          Шрифты в вебе, обзор от 2016 года.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/minimalno-neobxodimye-shrifty.html" target="_blank" title="Минимально необходимые шрифты">
          Минимально необходимые шрифты.
        </a>
      </li>
      <br>
      <li>
        <a href="https://store.artlebedev.ru/books/design/typography/osnovy-stilya-v-tipografike/" target="_blank" title="Основы стиля в типографике">
          Основы стиля в типографике.
        </a>
      </li>
      <br>
      <li>
        <a href="http://mdash.ru/" target="_blank" title="Типограф Муравьёва 3.5">
          Типограф Муравьёва 3.5
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/antipattern-dlya-veb-shriftov-data-uri.html" target="_blank" title="Антипаттерн для веб-шрифтов: Data URI">
          Антипаттерн для веб-шрифтов: Data URI.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/obzor-inlajnovyj-kontekst-formatirovaniya.html" target="_blank" title="Обзор: Инлайновый контекст форматирования">
          Обзор: Инлайновый контекст форматирования.
        </a>
      </li>
      <br>
      <li>
        <a href="https://web-standards.ru/articles/web-font-loading-patterns/" target="_blank" title="Паттерны загрузки веб-шрифтов">
          Паттерны загрузки веб-шрифтов.
        </a>
      </li>
      <br>
      <li>
        <a href="https://exit.sc/?url=https%3A%2F%2Fmedium.com%2Fp%2F9ba8a2998bcc" target="_blank" title="Как использовать кастомные шрифты в вебе и не сойти с ума">
          Как использовать кастомные шрифты в вебе и не сойти с ума.
        </a>
      </li>
      <br>
      <li>
        <a href="https://peredelka.wordpress.com/2013/10/29/о-верстке-вертикального-ритма/" target="_blank" title="О верстке вертикального ритма">
          О верстке вертикального ритма.
        </a>
      </li>
      <br>
      <li>
        <a href="http://pixelgene.ru/articles/vertical-rhythm.html" target="_blank" title="Создание вертикального ритма на сайте">
          Создание вертикального ритма на сайте.
        </a>
      </li>
      <br>
      <li>
        <a href="http://nicothin.pro/page/webfonts-min" target="_blank" title="Оптимизация шрифтов">
          Оптимизация шрифтов.
        </a>
      </li>
    </ul>

    <!-- ========== SVG ========== -->

    <h2 id="svg">SVG</h2>
    <ul>
      <li>
        <a href="https://htmlacademy.ru/courses/130" target="_blank" title="Знакомство с SVG">
          Знакомство с SVG.
        </a>
      </li>
      <br>
      <li>
        <a href="https://svgontheweb.com/ru/" target="_blank" title="SVG в вебе">
          SVG в вебе. Практическое руководство.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css.yoksel.ru/inline-styles-in-background/" target="_blank" title="Инлайновые стили в background-image">
          Инлайновые стили в background-image.
        </a>
      </li>
      <br>
      <li>
        <a href="http://yoksel.github.io/url-encoder/ru/" target="_blank" title="URL-encoder для SVG">
          URL-encoder для SVG.
        </a>
      </li>
      <br>
      <li>
        <a href="https://wsd.events/2014/06/28/pres/meet-svg/" target="_blank" title="Позвольте представить: SVG">
          Позвольте представить: SVG.
        </a>
      </li>
      <br>
      <li>
        <a href="https://wsd.events/2015/06/20/pres/text-alive/" target="_blank" title="Оживляем текст">
          Оживляем текст.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css.yoksel.ru/tags/#svg" target="_blank" title="Статьи Юли Бухваловой">
          Статьи Юли Бухваловой.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css.yoksel.ru/svg-gradients/" target="_blank" title="SVG-градиенты">
          SVG-градиенты.
        </a>
      </li>
      <br>
      <li>
        <a href="https://htmlacademy.ru/blog/127-a-guide-to-svg-on-web" target="_blank" title="Как проектировать, создавать и анимировать SVG">
          Как проектировать, создавать и анимировать SVG.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css.yoksel.ru/svg-patterns/" target="_blank" title="SVG-паттерны">
          SVG-паттерны.
        </a>
      </li>
    </ul>

    <!-- ========== MOBILE FIRST ========== -->

    <h2 id="mobile-first">Mobile First</h2>
    <ul>
      <li>
        <a href="https://habrahabr.ru/post/269419/" target="_blank" title="Почему Mobile First?">
          Почему Mobile First?
        </a>
      </li>
    </ul>

    <!-- ========== MEDIA QUERIES ========== -->

    <h2 id="media-queries">Медиа запросы (media queries)</h2>
    <ul>
      <li>
        <a href="https://html5book.ru/css3-mediazaprosy/" target="_blank" title="CSS3-медиазапросы">
          CSS3-медиазапросы.
        </a>
      </li>
      <br>
      <li>
        <a href="https://itchief.ru/lessons/html-and-css/css-media-queries" target="_blank" title="CSS - Медиа запросы">
          CSS - Медиа запросы.
        </a>
      </li>
    </ul>

    <!-- ========== БЭМ ========== -->

    <h2 id="bem">БЭМ</h2>
    <ul>
      <li>
        <a href="https://habrahabr.ru/company/yandex/blog/276035/" target="_blank" title="БЭМ-методология: с чего всё начиналось и зачем это всё нужно">
          БЭМ-методология: с чего всё начиналось и зачем это всё нужно.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/osmyslennyj-css-opisyvajte-stilyami-svoyu-logiku.html" target="_blank" title="Осмысленный CSS: описывайте стилями свою логику">
          Осмысленный CSS: описывайте стилями свою логику.
        </a>
      </li>
      <br>
      <li>
        <a href="http://css-live.ru/articles/bemantika-pishite-osmyslennye-stili-bez-povtorov.html" target="_blank" title="БЭМантика: пишите осмысленные стили без повторов">
          БЭМантика: пишите осмысленные стили без повторов.
        </a>
      </li>
      <br>
      <li>
        <a href="https://github.com/yoksel/html-tree" target="_blank" title="HTML-tree">
          HTML-tree.
        </a>
      </li>
      <br>
      <li>
        <a href="https://ru.bem.info/methodology/quick-start/" target="_blank" title="Документация">
          Документация.
        </a>
      </li>
    </ul>

    <!-- ========== Git ========== -->

    <h2 id="git">Git</h2>
    <ul>
      <li>
        <a href="https://githowto.com/ru" target="_blank" title="Git? Что это?">
          Git? Что это?
        </a>
      </li>
      <br>
      <li>
        <a href="https://github.com/web-standards-ru/dictionary/blob/master/git.md" target="_blank" title="Словарь терминов Git и GitHub">
          Словарь терминов Git и GitHub.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/174467/" target="_blank" title="Ежедневная работа с Git">
          Ежедневная работа с Git.
        </a>
      </li>
      <br>
      <li>
        <a href="http://frontiermag.ru/commit-message.html" target="_blank" title="Пиши коммиты правильно">
          Пиши коммиты правильно.
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/post/329992/" target="_blank" title="Лучшая практика создания Git Commit'ов от OpenStack">
          Лучшая практика создания Git Commit'ов от OpenStack.
        </a>
      </li>
    </ul>

    <!-- ========== PODCASTS ========== -->

    <h2 id="podcasts">Подкасты</h2>
    <ul>
      <li>
        <a href="https://soundcloud.com/web-standards" target="_blank" title="Веб-стандарты">
          Веб-стандарты
        </a>
      </li>
      <br>
      <li>
        <a href="https://soundcloud.com/frontend_u?utm_source=soundcloud&utm_campaign=share&utm_medium=twitter" target="_blank" title="Фронтенд Юность">
          Фронтенд Юность
        </a>
      </li>
      <br>
      <li>
        <a href="https://radiojs.ru/" target="_blank" title="RadioJS">
          RadioJS
        </a>
      </li>
      <br>
      <li>
        <a href="http://frontflip.me/" target="_blank" title="Frontflip">
          Frontflip
        </a>
      </li>
      <br>
      <li>
        <a href="http://5minreact.ru/" target="_blank" title="Пятиминутка React">
          Пятиминутка React
        </a>
      </li>
    </ul>

    <!-- ========== BOOKS ========== -->

    <h2 id="books">Литература</h2>
    <ul>
      <li>
        <a href="http://www.ozon.ru/context/detail/id/15708347/" target="_blank" data-hover="Сначала мобильные!" title="">
          Сначала мобильные!
        </a>
      </li>
      <br>
      <li>
        <a href="http://www.ozon.ru/context/detail/id/24493075/" target="_blank" data-hover="Новая большая книга CSS" title="">
          Новая большая книга CSS
        </a>
      </li>
      <br>
      <li>
        <a href="https://habrahabr.ru/company/piter/blog/307364/" target="_blank" data-hover="Секреты CSS. Идеальные решения ежедневных задач" title="">
          Секреты CSS. Идеальные решения ежедневных задач
        </a>
      </li>
      <br>
      <li>
        <a href="https://www.ozon.ru/context/detail/id/135656602/" target="_blank" data-hover="CSS. Карманный справочник" title="">
          CSS. Карманный справочник
        </a>
      </li>
      <br>
      <li>
        <a href="https://www.ozon.ru/context/detail/id/3881091/" target="_blank" data-hover="JavaScript. Подробное руководство" title="">
          JavaScript. Подробное руководство
        </a>
      </li>
      <br>
      <li>
        <a href="https://www.gitbook.com/book/karmazzin/eloquentjavascript_ru/details" target="_blank" data-hover="Выразительный Javascript" title="">
          Выразительный Javascript
        </a>
      </li>
    </ul>

    <!-- ========== Полезности ========== -->

    <h2 id="useful">Полезности</h2>
    <ul>
      <li>
        <a href="http://kangax.github.io/html-minifier/" target="_blank" title="HTML Minifier (v3.5.2)">
          HTML Minifier (v3.5.2)
        </a>
      </li>
      <br>
      <li>
        <a href="https://github.com/web-standards-ru/dictionary" target="_blank" title="Словари по фронтенду">
          Словари по фронтенду.
        </a>
      </li>
      <br>
      <li>
        <a href="http://cssreference.io/" target="_blank" title="Справочник по CSS">
          Справочник по CSS.
        </a>
      </li>
      <br>
      <li>
        <a href="http://htmlreference.io/" target="_blank" title="Справочник по HTML">
          Справочник по HTML.
        </a>
      </li>
      <br>
      <li>
        <a href="https://csspeeper.com/" target="_blank" title="CSS Peeper">
          CSS Peeper.
        </a>
      </li>
    </ul>

    <!-- ========== Gulp ========== -->

    <h2 id="gulp">Gulp</h2>
    <ul>
      <li>
        <a href="https://learn.javascript.ru/screencast/gulp" target="_blank" title="Скринкаст по Gulp">
          Скринкаст по Gulp.
        </a>
      </li>
    </ul>

    <!-- ========== Webpack ========== -->

    <h2 id="webpack">Webpack</h2>
    <ul>
      <li>
        <a href="https://learn.javascript.ru/screencast/webpack" target="_blank" title="Скринкаст по Webpack">
          Скринкаст по Webpack
        </a>
      </li>
    </ul>

    <!-- ========== MINIFICATION ========== -->

    <h2 id="minification">Минификация</h2>
    <ul>
      <li>
        <a href="https://css.github.io/csso/csso.html" target="_blank" title="CSS">
          CSS
        </a>
      </li>
      <br>
      <li>
        <a href="https://marijnhaverbeke.nl/uglifyjs" target="_blank" title="JavaScript">
          JavaScript
        </a>
      </li>
    </ul>
  </div>

    <!-- ========== IDE ========== -->

    <h2 id="ide">IDE</h2>
    <ul>
      <li>
        <a href="https://habrahabr.ru/post/276825/" target="_blank" title="Используем VS Code для Веб-разработки">
          Используем VS Code для Веб-разработки.
        </a>
      </li>
      <br>
      <li>
        <a href="https://medium.freecodecamp.com/atom-treasures-82a64ac391c" target="_blank" title="Плагины для Atom">
          Плагины для Atom.
        </a>
      </li>
    </ul>
  </div>

  <!-- Foot3r -->

  <footer>
    <!-- Where footer maaaan?! -->
    <p>Copyright &copy;2017 Vladimir Marakhovich</p>
    <p>ilove.github@gmail.com</p>
  </footer>
</body>
</html>
