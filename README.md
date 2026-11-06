# Google Search Forms

[English](#english) · [Русский](#russian) · [עברית](#hebrew)

<a name="english"></a>

## English

Two versions of a search form that sends the query to Google, and a small hub page to choose between them. A Full Stack course lesson on HTML forms.

**Live demo:** https://dubnovalexey.github.io/L_09_Google/

### Try it

Compare Standard Version and Animated Version. Enter a search query, submit it to Google, then return with Back to check the local interface and loader reset.

### What is inside

- **Standard version** — a plain HTML form with hand-written CSS.
- **Animated version** — the same form with Tailwind CSS: a glowing animated border and soft background blobs.
- Both forms use `action="https://www.google.com/search"`, `method="get"` and the field `name="q"` — the browser builds the search URL by itself, no JavaScript needed.
- Fit a phone screen.

- The animated loader resets after Back navigation; reduced-motion settings stop decorative animations.

### Tech stack

HTML5 forms · CSS3 animations · JavaScript · Tailwind CSS (CDN) · GitHub Pages

### Run locally

Open `index.html` in a browser.

### Demo scope

Search leaves this project for Google. The project does not implement a search engine; the animated version also needs its Tailwind CDN connection.

### Further development

Proposals below are planned work, not existing features.

- Visual: keep contrast and keyboard focus consistent across both versions; add a neutral magnifying-glass favicon.
- Engineering: build Tailwind locally instead of loading its runtime CDN script, and add a navigation/Back smoke check.
- Features: offer optional local search history with an explicit clear action; leave external search visibly separate from the local project.

---

<a name="russian"></a>

## Русский

**Формы поиска Google**

Две версии формы поиска, которая отправляет запрос в Google, и маленькая страница-«хаб» для выбора. Урок курса Full Stack по HTML-формам.

**Демо:** https://dubnovalexey.github.io/L_09_Google/

### Попробовать

Сравните Standard Version и Animated Version. Введите запрос, перейдите к результатам Google, затем вернитесь кнопкой «Назад» и проверьте восстановление формы.

### Что внутри

- **Стандартная версия** — простая HTML-форма со своим CSS.
- **Анимированная версия** — та же форма на Tailwind CSS: светящаяся бегущая рамка и мягкие размытые пятна на фоне.
- Обе формы используют `action="https://www.google.com/search"`, `method="get"` и поле `name="q"` — браузер сам собирает адрес поиска, JavaScript не нужен.
- Помещаются на экране телефона.

- После возврата кнопкой «Назад» индикатор загрузки сбрасывается; reduced motion отключает декоративную анимацию.

### Стек

HTML5-формы · CSS3-анимации · JavaScript · Tailwind CSS (CDN) · GitHub Pages

### Как запустить

Откройте `index.html` в браузере.

### Границы демонстрации

Поиск переводит на Google. Собственного поискового движка здесь нет; анимированная версия также зависит от подключения Tailwind CDN.

### Дальнейшее развитие

Ниже перечислены предложения, а не уже реализованные функции.

- Визуал: единые контраст и фокус с клавиатуры в обеих версиях; нейтральный favicon лупы.
- Инженерия: собирать Tailwind локально вместо runtime CDN и добавить проверку перехода с возвратом «Назад».
- Функции: необязательная локальная история запросов с явной очисткой; внешнюю выдачу отделить от локальной страницы.

---

<a name="hebrew"></a>

<div dir="rtl">

## עברית

**טופסי חיפוש של Google**

שתי גרסאות של טופס חיפוש ששולח את השאילתה ל-Google, ודף קטן לבחירה ביניהן. שיעור בקורס Full Stack על טפסים ב-HTML.

**הדגמה:** https://dubnovalexey.github.io/L_09_Google/

### מה כדאי לנסות

השוו בין Standard Version ל-Animated Version. הקלידו שאילתה, עברו לתוצאות Google וחזרו באמצעות Back כדי לבדוק את שחזור הממשק ואיפוס מחוון הטעינה.

### טכנולוגיות

HTML5 · CSS3 · JavaScript · Tailwind CSS (CDN) · GitHub Pages

### הרצה מקומית

פתחו את `index.html` בדפדפן.

מחוון הטעינה מתאפס לאחר חזרה אחורה, והעדפת reduced motion עוצרת אנימציות דקורטיביות.

### גבולות ההדגמה

החיפוש מעביר אל Google. הפרויקט אינו מנוע חיפוש עצמאי; הגרסה המונפשת תלויה גם בחיבור ל-CDN של Tailwind.

### המשך פיתוח

הסעיפים הבאים הם הצעות להמשך, לא יכולות שכבר יושמו.

- עיצוב: ניגודיות ומיקוד עקביים בשתי הגרסאות; סמל לשונית ניטרלי של זכוכית מגדלת.
- הנדסה: בניית Tailwind מקומית במקום סקריפט CDN בזמן ריצה ובדיקת ניווט וחזרה באמצעות Back.
- יכולות: היסטוריית חיפוש מקומית לבחירה עם פעולת ניקוי ברורה; הבחנה גלויה בין האתר המקומי לתוצאות החיצוניות.

</div>
