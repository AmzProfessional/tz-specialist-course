# Спеціаліст з розробки ТЗ для Amazon-лістингів

Навчальний курс для вакансії **«Спеціаліст з розробки технічних завдань (ТЗ) для Amazon-лістингів»**.
Побудований на [Quartz v4](https://quartz.jzhao.xyz/) (Obsidian → сайт).

🔗 **Сайт курсу:** https://amzprofessional.github.io/tz-specialist-course/

## Структура

- `content/` — уроки та матеріали курсу (Markdown у форматі Obsidian).
- Тести кожного уроку винесені в кінець сторінки окремим блоком (додаються в LMS).

## Локальний запуск

```bash
npm install
npx quartz build --serve
```

Далі відкрий http://localhost:8080

## Публікація

Будь-який `push` у гілку `main` автоматично збирає та публікує сайт на GitHub Pages.
