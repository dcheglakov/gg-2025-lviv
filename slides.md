---
theme: default
background: ./welcome.png
title: Інді-секрети виживання
drawings:
  persist: false
transition: slide-left
mdc: true
---

# Інді-секрети виживання: уроки від ветеранів

### Досвід майже 20-річної інді студії, що ділиться секретами успіху.

<button @click="$slidev.nav.next" class="mt-8 py-2 px-4 rounded-lg" hover:bg="white op-20">
Почнемо <carbon:arrow-right />
</button>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-right
image: ./me.png
---

# Хто я і чому роблю цей доклад?

<br/>

## Дмитро Чеглаков

<br/>

- Майже **20 років** є співзасновником Specialbit Studio
- Геймер з **35 річним** досвідом
- Батько **двох прекрасних** дітей

Розберемо **помилки** які наша студія або я наробили за ці **20 років**, на кожному етапі розробки, щоб вам **не довелося**.

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image-left
image: ./idea.png
---

<br />

# Ідея та Планування

Чому це важливо?

- Жанр
- Вибір стиля
- Монетизація
- Потенційні платформи
- Формування команди
- Оцінка ресурсів

---
layout: two-cols
layoutClass: gap-16 pt-18
---

# Карткова гра

<img src="./cards.png" alt="" />

::right::

# Питання

- 2D або 3D?
- Pixel art?
- AI супротивник?
- PVP?
- Сервер?
- Free / Paid / Ads / IAP?
- Платформи?
- Unity, Godot, Unreal?
- або Threejs?

---
layout: image-right
image: ./card-blue.png
title: Соло розробник карткова гра
---

<div class="h-full flex flex-col justify-center">
<h1>Соло розробник</h1>

- **Pixel Art** - арт стиль
- **Threejs/Thretle** - 2D/3D рендерінг
- **Svelte** - UI
- **boardgame.io** - PVP та AI
- **Phaser Ads** - монетизація
- **Hetzner** - хостинг
- **PWA** - для мобілок
</div>

---
layout: image-left
image: ./card-red.png
title: Команда карткова гра
---

<div class="h-full flex flex-col justify-center">
<h1>Команда</h1>

- **3D** - арт стиль
- **Unity** - 3d рушій
- **Unity UI** - UI
- **Mirror** - PVP та AI
- **Unity Ads** - монетизація
- **Hetzner** - хостинг
- **Unity** - для мобілок та консолей
</div>

---
layout: image-right
image: ./team.png
---

<br />

# Команда

Питання на які треба відповісти

- Хто нам потрібен?
- Розмір команди?
- Що ми можемо запропонувати?
- Де шукати?
- Як платити?

---
layout: two-cols
layoutClass: pt-16
---

# Соло розробник

Починай працювати

<p class="text-9xl pt-24">🧑‍💻</p>

::right::

# Команда

Потрібний мінімум

- Геймплей-програміст
- Мережеві програміст
- UI/UX дизайнер
- 3D-моделер
- Геймдизайнер?
- 2D-художник?

---
layout: two-cols
layoutClass: pt-16
---

# Founders 🏠

Було б добре щоб вміли в

- Продюсери
- Маркетологи
- Спеціалісти з монетизації
- Аналітики

::right::

# Outsource 🏢

Віддати зовні і не треба в штаті

- Маркетологи
- Спеціалісти з комунікацій та PR
- Тестувальники QA
- Локалізатори

---
layout: image-right
image: ./team.png
---

<br />

# Команда

Питання на які треба відповісти

- Хто нам потрібен?
- Розмір команди?
- Що ми можемо запропонувати?
- Де шукати?
- Як платити?

---


---


---


---


---
src: ./pages/imported-slides.md
hide: false
---

---


---
layout: center
class: text-center
---

# Learn More

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />
