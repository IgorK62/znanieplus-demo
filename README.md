<div align="center">

# 📘 ЗнаниеПлюс — Landing Page

**Современный лендинг образовательной платформы**  
*Single-file • Zero dependencies • Production-ready*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)](https://developer.mozilla.org/docs/Web/JavaScript)
[![BEM](https://img.shields.io/badge/BEM-Methodology-0088CC?style=for-the-badge)](https://en.bem.info/methodology/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

[🚀 Live Demo](#-демо) • [✨ Возможности](#-возможности) • [📊 Метрики](#-производительность-и-качество) • [📖 Использование](#-использование)

</div>

---

## 📌 О проекте

Полноценный одностраничный лендинг для вымышленной образовательной платформы **«ЗнаниеПлюс»** — сервиса с пошаговыми решениями задач и ГДЗ для школьников 1–11 классов.

Проект создан как **демонстрация современных подходов к вёрстке** и лучших практик веб-разработки. Весь код находится в **одном HTML-файле** — без сборщиков, фреймворков и внешних зависимостей.

> 💡 **Концепция:** показать, что даже в одном файле можно реализовать production-ready страницу с тёмной темой, анимациями, SEO-оптимизацией и полной доступностью.

---

## 🌐 Демо

| Ссылка | Описание |
|--------|----------|
| [**Netlify**](https://znanieplus-demo.netlify.app/) | Основная демо-версия |
| [**GitHub Pages**](https://username.github.io/znanieplus-demo/) | Альтернативная ссылка |
| [**Исходный код**](./index.html) | Один файл — вся страница |

> ⚠️ *Замените ссылки на свои после деплоя.*

---

## ✨ Возможности

### 🎨 Дизайн и UX
- ✅ **Светлая и тёмная тема** с сохранением выбора в `localStorage`
- ✅ **Адаптивное меню-бургер** с анимацией и оверлеем
- ✅ **Scroll-анимации** появления элементов (Intersection Observer)
- ✅ **3D-parallax эффект** карточки в hero-секции
- ✅ **Анимированные счётчики** с easing-функцией
- ✅ **Прогресс-бар чтения** страницы
- ✅ **Кнопка «Наверх»** с плавным появлением
- ✅ **FAQ-аккордеон** на нативных `<details>/<summary>`
- ✅ **Пульсирующий индикатор** в hero-badge

### 🏗️ Архитектура и код
- ✅ **БЭМ-методология** — строгое следование конвенции
- ✅ **Семантическая HTML5-разметка** — `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- ✅ **CSS Custom Properties** — единая дизайн-система
- ✅ **Mobile-first подход** с брейкпоинтами 768px / 992px / 1024px
- ✅ **Vanilla JavaScript** — без jQuery, React и других зависимостей
- ✅ **Inline SVG-иконки** — 0 запросов к серверу

### 🔍 SEO и метаданные
- ✅ **Schema.org (JSON-LD)** — разметка `EducationalOrganization`, `WebSite`, `FAQPage`
- ✅ **Open Graph + Twitter Card** для красивого шаринга в соцсетях
- ✅ **Canonical URL**, `robots`, `keywords`, `description`
- ✅ **Иерархия заголовков** — один `<h1>`, логичная структура `<h2>` → `<h3>`
- ✅ **Favicon в SVG** — inline, без запросов

### ♿ Доступность (a11y)
- ✅ **Skip-link** для клавиатурной навигации
- ✅ **ARIA-атрибуты** — `role`, `aria-label`, `aria-labelledby`, `aria-expanded`, `aria-hidden`
- ✅ **`:focus-visible`** — видимый фокус только для клавиатуры
- ✅ **Контрастность WCAG 2.1 AA** для всех текстов
- ✅ **`prefers-reduced-motion`** — уважение к пользователям с особыми настройками
- ✅ **Логический порядок таб-навигации**

### ⚡ Производительность
- ✅ **Системный шрифтовой стек** — 0 запросов к серверу
- ✅ **`preconnect` / `dns-prefetch`** для внешних ресурсов
- ✅ **`requestAnimationFrame`** для scroll-обработчиков
- ✅ **Passive event listeners** для оптимизации скролла
- ✅ **`will-change`** только там, где это действительно нужно
- ✅ **Стили для печати** (`@media print`)

---

## 📊 Производительность и качество

Ожидаемые результаты в **Google Lighthouse**:

| Категория | Оценка |
|-----------|--------|
| 🚀 Performance | **100** |
| ♿ Accessibility | **100** |
| ✅ Best Practices | **100** |
| 🔍 SEO | **100** |

> *Для проверки запустите Lighthouse в DevTools браузера Chrome.*

---

## 🛠️ Технологический стек

| Технология | Применение |
|------------|------------|
| **HTML5** | Семантическая разметка, Schema.org |
| **CSS3** | Custom Properties, Grid, Flexbox, `clamp()`, `backdrop-filter` |
| **JavaScript (ES6+)** | Intersection Observer, localStorage, event delegation |
| **SVG** | Inline-иконки, favicon |
| **БЭМ** | Методология именования классов |
| **JSON-LD** | Структурированные данные для поисковиков |

---

## 📁 Структура проекта
