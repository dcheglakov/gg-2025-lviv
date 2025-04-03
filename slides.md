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

- Чи є чітке бачення гри?
- Яка її унікальна цінність?
- Які межі проєкту?
- Що має бути в MVP?
- Стратегія монетизації?
- Потенційні платформи?
- Який технологічний стек?
- Таймлайн?

---
layout: two-cols
layoutClass: gap-16 pt-18
---

# Карткова гра

<img src="./cards.png" alt="" />

::right::

# Питання

- 2D, 3D або Pixel art?
- AI, PVP?
- Сервер?
- Free / Paid / Ads / IAP?
- Mobile, Web, Console, PC?
- Unity, Godot, Unreal, Phaser, Babylon, Threejs?
- До одного року розробка?

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
- **Ads** - монетизація
- **Hetzner** - хостинг
- **PWA** - для мобілок
- **6 місяців** розробка
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
- **1 рік** розробки
</div>

---
layout: image-right
image: ./team.png
---

<br />

# Команда

Питання на які треба відповісти

- Хто нам потрібен?
- Які ролі критично необхідні?
- Що ми можемо запропонувати?
- Альтернативні форми винагороди?
- Які моделі співпраці?
- Як конкурувати з великими студіями?
- Де шукати?
- Юридичні аспекти?

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
- Мережевий програміст
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
image: ./boromir.jpeg
---

<br />

# Розробка

Не можна просто так взяти і зробити гру

- Чи відповідає архітектура потребам гри?
- Чи оптимальний технологічний стек?
- Як ми управляємо технічним боргом?
- На які платформи ми орієнтуємося?
- Як ми виявляємо вузькі місця в продуктивності?
- Інтеграцією сторонніх бібліотек?
- Як організований процес розробки?
- Як ми тестуємо гру?

---
layout: two-cols
layoutClass: pt-12 gap-12
---

# Ітеративна розробка

- Починайте з мінімально життєздатного прототипу
- Регулярно тестуйте продуктивність
- Спеціалісти з монетизації
- Використовуйте ітеративний підхід

## Технічна документація та стандарти

- Створіть чіткі стандарти
- Документуйте архітектурні рішення
- Ведіть технічний журнал проблем та їх вирішень

::right::

# Управління ризиками

- Ідентифікуйте технічно складні частини на початку проєкту
- Створіть прототипи для найризикованіших компонентів першими
- Майте план B для критичних технологій

## Баланс між ідеальним та практичним

- Визначте, де можна прийняти компроміси
- Робіть те, що гравець дійсно помітить
- Завершена гра краща за ідеальну, але незавершену

---
layout: image-right
image: ./release.png
---

<br />

# Реліз

Все горить і я горю

- Як ми виявляємо багі?
- Який план покращень?
- Чи стабільна гра на всіх платформах?
- Як ми забезпечуємо стабільність?
- Як підтримувати видимість гри?
- Як максимізувати органіку?
- Як заохочувати гравців ділитися грою?
- Як ми працюємо з відгуками, особливо негативними?

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
