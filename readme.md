# Oleksandr Vrahaliev — CV & Portfolio

Учебный сайт WEB1 на HTML и CSS. Главные страницы: About Me, CV и Portfolio. Учебные работы взяты из разделов 01, 02 и 03 курса.

## Как открыть проект в VS Code

1. Распакуй `oleksandr-portfolio.zip` через **Извлечь всё / Extract All**.
2. Открой **VS Code → File → Open Folder**.
3. Выбери папку `oleksandr-portfolio`, в которой лежит главный `index.html`.
4. Установи расширение **Live Server** от Ritwick Dey, если его ещё нет.
5. Открой главный `index.html` и нажми **Alt+L, затем Alt+O**. Это последовательность двух сочетаний, а не четыре клавиши одновременно. Либо нажми правой кнопкой по HTML → **Open with Live Server**.
6. Нажми **Ctrl+S** после изменения: Live Server обновит страницу.

Live Server открывает браузер по умолчанию. Чтобы открывался Chrome, в настройках VS Code найди `Live Server Custom Browser` и выбери `chrome`.

Без расширения можно дважды нажать на `index.html` в Проводнике Windows. После сохранения кода обновляй страницу браузера через **Ctrl+R**.

## Где что лежит

| Файл / папка | Назначение |
| --- | --- |
| `index.html` | About Me, фотография и интересы |
| `cv.html` | Образование, работа, навыки, языки |
| `portfolio.html` | Шесть карточек учебных работ и ссылки на все упражнения |
| `css/styles.css` | Общее оформление трёх главных страниц |
| `css/exercises.css` | Простое оформление каталогов упражнений |
| `projects/01-html/` | HTML без CSS: Star Pizza, личный сайт, схема веб-запроса |
| `projects/02-css/` | Личный сайт с CSS, box sizing, единицы размеров, навигация, Zen Garden |
| `projects/03-layout/` | EcoBottle, Flexbox, Grid, наложение элементов, breakpoints, адаптивный личный сайт |
| `images/` | Твоя фотография, значок сайта и изображения карточек |
| `images/exercises/` | Изображения из учебных заданий |
| `code-guide.md` | Разбор кода простыми словами с примерами |
| `course-checklist.md` | Соответствие упражнениям курса и действия перед сдачей |

Начальные страницы специально простые. CSS упражнений лежит рядом с их HTML, отдельно от оформления основного портфолио. Изменение CSS Star Pizza не требуется: это упражнение только на HTML.

## Что осталось вписать из личных данных

- В футерах трёх учебных личных сайтов замени `https://github.com/` на адрес **своего профиля**. Логин пока не указан, поэтому здесь стоит ссылка на главную GitHub. Можно поставить свою другую соцсеть.
- В CV уровни уже указаны: английский **B2**, датский **примерно A2–B1**, продолжаешь учить. Работа в Hotel Marselis указана как текущая, без выдуманной даты начала.
- Если появятся сертификаты или волонтёрский опыт, добавь их в соответствующие разделы `cv.html`.

## Как загрузить только этот проект на GitHub

Другие задания из папок на твоём компьютере загружать не нужно. Для сайта достаточно содержимого папки `oleksandr-portfolio`.

1. Войди на [github.com](https://github.com/) и нажми **+ → New repository**.
2. Назови репозиторий `web1-portfolio`, выбери **Public** и нажми **Create repository**.
3. В пустом репозитории нажми **uploading an existing file**. Если файлы уже есть: **Add file → Upload files**.
4. Открой папку `oleksandr-portfolio` в Проводнике. Перетащи её **содержимое**, включая подпапки, на страницу GitHub.
5. Проверь, что главный `index.html` находится в корне репозитория, рядом с `cv.html`, `portfolio.html`, `css`, `images` и `projects`.
6. Нажми **Commit changes** и сохрани в ветку `main`.

ZIP вместо распакованных файлов загружать не нужно. Учебные страницы внутри `projects` открываются по ссылкам с портфолио.

## Как включить GitHub Pages

1. Открой репозиторий → **Settings → Pages**.
2. В **Build and deployment** выбери **Source → Deploy from a branch**.
3. Выбери **main**, затем **/(root)** и нажми **Save**.
4. Дождись завершения публикации. На странице Pages появится адрес сайта.
5. Открой адрес и проверь главные страницы и ссылки на упражнения.
6. Отправь ссылку в слот задания на itslearning.

Адрес будет примерно таким:

```text
https://YOUR-USERNAME.github.io/web1-portfolio/
```

Если обновляешь существующий репозиторий, загрузи новые файлы поверх старых. Старые страницы `nordic-roast.html`, `aarhus-tap.html`, `study-week.html`, `java-study-notes.html`, прежний `projects/star-pizza.html` и `css/projects.css` больше не используются — их можно удалить из репозитория. Star Pizza теперь находится в `projects/01-html/star-pizza.html`.

## Проверка перед сдачей

1. В главных страницах проверь ширины **375px, 768px, 1024px**: **F12 → Ctrl+Shift+M** в Chrome/Edge и поле ширины.
2. Проверь HTML через [W3C HTML Validator](https://validator.w3.org/nu/), CSS через [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).
3. Замени ссылку на личный профиль в учебных футерах.
4. Пройди игры и работу с DevTools из `course-checklist.md`, если преподаватель ждёт выполнения этих действий.

Исходный HTML Zen Garden сохранён без изменений. Его ссылки вида `/pages/...` относятся к оригинальному сайту и при просмотре локальной копии могут вести не туда. Оригинальные ресурсы открывай на [csszengarden.com](https://csszengarden.com/). Оформление локальной версии находится в `projects/02-css/zen-garden/style.css`.

Локальная проверка актуальным Nu HTML Checker выполнена для всех 34 HTML-страниц и 15 CSS-файлов: ошибок нет. Предварительные макеты главных страниц просмотрены при ширинах 375px, 768px и 1024px. Перед сдачей проверь опубликованный сайт в Chrome.

## Источники

- [01 — The Web & HTML](https://kasperknop.github.io/WEB1/01-the-web-and-html/)
- [02 — CSS](https://kasperknop.github.io/WEB1/02-css/)
- [03 — Layout](https://kasperknop.github.io/WEB1/03-layout/)
- [Hotel Marselis](https://hotelmarselis.com/)
- [GitHub Pages: выбор ветки для публикации](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Live Server: официальная страница расширения](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

Фотографии меню, EcoBottle и Pasta Primavera взяты из материалов курса. HTML CSS Zen Garden — исходный учебный документ Dave Shea; ссылки и указание лицензии сохранены. Новый CSS для Zen Garden распространяется на условиях CC BY-NC-SA 3.0, как требует исходная страница.
