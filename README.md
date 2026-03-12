Hullo. [For English ➡️](README.en.md)

### Скиллы 📐
* **Core & Tech:** TypeScript (Strict, Generics, Guards), JavaScript (ES202x), React, Zustand, Redux, Vite, REST, WebSocket/SSE.
* **Архитектура:** Feature-Sliced Design (FSD), Dependency Injection (DI), EventBus (Pub/Sub), UI ↔ State ↔ Data.
* **Стили & UI:** Tailwind, CSS Modules, BEM, Grid/Flex, Figma (UI/UX, векторная графика).
* **Infra & QA:** Vitest (TDD), CI/CD (GitHub Actions), Netlify, SQLite, Lighthouse / Web Vitals.

### Стиль кодинга
* **Ясность:** Пишу доходчивый, декомпозированный код (JSDoc) без глубокого нестинга, guard clauses и строгие булевы проверки.
* **Адаптивность:** Интересно перенимать устоявшиеся паттерны для написание софта. 
* **Слабые связи:** Проектирую модули с явными границами ответственности. Бизнес-логика -> сервисы, компоненты остаются тонкими.
* **Аналитический подход:** Занимаюсь архитектурными вопросами и концептуализацией (бекграунд: философия, Advanced English, C1 German).

---

### Что готово уже сейчас

#### **[mmpy.chat](https://github.com/faustseele/mmpy.chat) 💌**
> *Stack: TypeScript | Handlebars | CSS Modules | Vite | XHR | WebSocket*

Стильный real-time мессенджер, созданный с нуля без React/Vue. 
* **Vanilla Core:** Самописная компонентная система (EventBus, Lifecycle, DI), кастомный реактивный Store и History API роутер.
* **Архитектура:** Жесткое разделение на слои по методологии FSD.

---

### 🏗 А что разработке

#### **Diane** ♾️
> *Stack: React | React Native | Zustand | Tailwind | Supabase*

Chat-based система ведения персональной базы знаний в виде единой бесконечной ленты.
* **Zero-Friction & Anti-Features:** Мгновенный ввод, обязательное тегирование и жесткий запрет на copy-paste для стимуляции активного мышления.

---

#### **CWYS (Control What You See)** 👁️
> *Методология и open-source middleware*

Радикальный контроль над UX: деконструирует перегруженные супер-аппы на независимые UI-компоненты (модули) с помощью семантического Middleware.

---

#### **Glider** 🪁
> *Stack: TDLib (Telegram API) | CWYS Middleware*

Практический MVP методологии CWYS: минималистичный модульный клиент Telegram, разбивающий монолитный опыт на изолированные UX-блоки.