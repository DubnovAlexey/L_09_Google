<!--suppress MarkdownUnresolvedFileReference -->

# Google Search Forms

[English](#english) · [Русский](#russian) · [עברית](#hebrew) · [Español](#spanish) · [Français](#french)

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

- Visual: keep contrast and keyboard focus consistent across both versions.
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

- Визуал: единые контраст и фокус с клавиатуры в обеих версиях.
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

- עיצוב: ניגודיות ומיקוד עקביים בשתי הגרסאות.
- הנדסה: בניית Tailwind מקומית במקום סקריפט CDN בזמן ריצה ובדיקת ניווט וחזרה באמצעות Back.
- יכולות: היסטוריית חיפוש מקומית לבחירה עם פעולת ניקוי ברורה; הבחנה גלויה בין האתר המקומי לתוצאות החיצוניות.

</div>

---

<a name="spanish"></a>

## Español

**Formularios de búsqueda de Google**

Dos versiones de un formulario de búsqueda que envía la consulta a Google y una pequeña página «hub» para elegir. Una lección del curso Full Stack sobre formularios HTML.

**Demo:** https://dubnovalexey.github.io/L_09_Google/

### Pruébelo

Compare Standard Version y Animated Version. Escriba una consulta, vaya a los resultados de Google y vuelva con el botón «Atrás» para comprobar que el formulario se restablece.

### Qué hay dentro

- **Versión estándar**: un formulario HTML sencillo con su propio CSS.
- **Versión animada**: el mismo formulario con Tailwind CSS: un marco luminoso que recorre el borde y suaves manchas difuminadas en el fondo.
- Ambos formularios usan `action="https://www.google.com/search"`, `method="get"` y el campo `name="q"`: el navegador arma solo la dirección de búsqueda, sin JavaScript.
- Caben en la pantalla de un móvil.
- Al volver con el botón «Atrás», el indicador de carga se reinicia; reduced motion desactiva la animación decorativa.

### Tecnologías

Formularios HTML5 · animaciones CSS3 · JavaScript · Tailwind CSS (CDN) · GitHub Pages

### Cómo ejecutarlo

Abra `index.html` en el navegador.

### Alcance de la demo

La búsqueda lleva a Google. Aquí no hay un motor de búsqueda propio; la versión animada depende además de Tailwind por CDN.

### Desarrollo futuro

Lo que sigue son propuestas, no funciones ya implementadas.

- Visual: el mismo contraste y el mismo foco de teclado en ambas versiones.
- Ingeniería: compilar Tailwind en local en lugar del CDN en tiempo de ejecución y añadir una prueba de la vuelta con «Atrás».
- Funciones: un historial local de consultas opcional con borrado explícito; separar los resultados externos de la página local.

---

<a name="french"></a>

## Français

**Formulaires de recherche Google**

Deux versions d'un formulaire de recherche qui envoie la requête à Google, et une petite page « hub » pour choisir. Une leçon du cours Full Stack sur les formulaires HTML.

**Démo :** https://dubnovalexey.github.io/L_09_Google/

### À essayer

Comparez Standard Version et Animated Version. Saisissez une requête, allez aux résultats de Google, puis revenez avec le bouton « Retour » pour vérifier que le formulaire est rétabli.

### Ce qu'il y a dedans

- **Version standard** : un formulaire HTML simple avec son propre CSS.
- **Version animée** : le même formulaire en Tailwind CSS, avec un cadre lumineux qui court sur le bord et de douces taches floues en fond.
- Les deux formulaires utilisent `action="https://www.google.com/search"`, `method="get"` et le champ `name="q"` : le navigateur construit seul l'adresse de recherche, sans JavaScript.
- Ils tiennent sur un écran de téléphone.
- Au retour par le bouton « Retour », l'indicateur de chargement est remis à zéro ; reduced motion coupe l'animation décorative.

### Technologies

Formulaires HTML5 · animations CSS3 · JavaScript · Tailwind CSS (CDN) · GitHub Pages

### Lancer le projet

Ouvrez `index.html` dans le navigateur.

### Limites de la démo

La recherche mène à Google. Il n'y a pas ici de moteur de recherche propre ; la version animée dépend en plus de Tailwind par CDN.

### Évolutions possibles

Ce qui suit sont des propositions, pas des fonctions déjà réalisées.

- Visuel : le même contraste et le même focus clavier dans les deux versions.
- Ingénierie : compiler Tailwind en local au lieu du CDN à l'exécution et ajouter un test du retour par « Retour ».
- Fonctions : un historique local des requêtes facultatif avec effacement explicite ; séparer les résultats externes de la page locale.
