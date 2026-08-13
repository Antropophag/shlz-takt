# ЩЛЗ ТАКТ

Одностраничная концепция продуктового бренда нового модельного ряда пассажирских лифтов АО «ЩЛЗ».

## Запуск

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

Статическая сборка создаётся в `dist/`. Относительный `base` позволяет размещать сайт как в корне домена, так и по пути репозитория GitHub Pages.

## GitHub Pages

Workflow `.github/workflows/deploy-pages.yml` автоматически собирает и публикует сайт после каждого push в `main`. Источник Pages должен быть установлен в **GitHub Actions**.
