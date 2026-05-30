# UI Kit — Дизайн-система для итогового проекта

## 📦 Структура проекта
- `src/scss/` — исходные SCSS-файлы (переменные, сброс, компоненты)
- `src/index.html` — страница документации с примерами
- `dist/main.css` — скомпилированный CSS (генерируется автоматически)

##  Установка и запуск
1. Установите Sass: `npm install -g sass`
2. Скомпилируйте стили: `sass src/scss/main.scss dist/main.css --watch`
3. Откройте `src/index.html` в браузере.

##  Компоненты
- **Button**: Primary, Secondary, Disabled | Sizes: small, medium, large | States: hover, active, focus
- **Input**: Normal, Focus, Error + message | Support icons & checkboxes/radio
- **Card**: With/without image | Sizes: small, medium, large
- **Navbar**: Desktop horizontal | Mobile hamburger (pure CSS)
- **Layout**: Centered container + Auto-fit Grid

## 📜 Методология
Все классы написаны по БЭМ. Стили разделены на модули. Полная адаптивность через `@media` и CSS Grid/Flexbox.