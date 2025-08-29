# Лендинг-резюме Ольги Морозовой

Современный лендинг-резюме с портфолио, созданный с использованием React, TypeScript, Tailwind CSS и Motion.

## 🚀 Быстрый старт

### Установка зависимостей
```bash
npm install
```

### Запуск в режиме разработки
```bash
npm run dev
```

### Сборка для продакшена
```bash
npm run build
```

### Предварительный просмотр сборки
```bash
npm run preview
```

## 📦 Деплой

### Vercel
1. Подключите репозиторий к Vercel
2. Настройки сборки будут подхвачены автоматически
3. Деплой произойдет автоматически при пуше в main

### Netlify
1. Подключите репозиторий к Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`

### GitHub Pages
1. Установите gh-pages: `npm install --save-dev gh-pages`
2. Добавьте в package.json:
   ```json
   "homepage": "https://yourusername.github.io/repository-name",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```
3. Запустите: `npm run deploy`

## 🛠 Технологии

- **React 18** - UI библиотека
- **TypeScript** - типизация
- **Tailwind CSS v4** - стилизация
- **Motion** - анимации
- **Recharts** - графики и диаграммы
- **Lucide React** - иконки
- **Vite** - сборщик

## 📁 Структура проекта

```
├── components/          # Компоненты
│   ├── ui/             # UI компоненты
│   └── figma/          # Figma компоненты
├── styles/             # Стили
└── README.md
```

## 🎨 Особенности

- Адаптивный дизайн
- Плавные анимации
- Интерактивные графики навыков
- Современный UI/UX
- Оптимизация для SEO
- Быстрая загрузка

## 📧 Контакты

**Ольга Морозова**
- Email: morozova31@gmail.com
- Telegram: @oljona
- GitHub: https://github.com/morozovaolga
- LinkedIn: https://linkedin.com/in/olga-morozova