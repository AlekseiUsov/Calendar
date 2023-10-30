## Календарь

### Описание

Небольшое приложение на React, ReduxToolkit и Typescript.

### Логика работы приложения

- Календарь должен открываться на текущей дате
- При выборе конкретной даты должна открываться панель с информацией:
  + В панели указывается выбранная дата (число, месяц, год).\
  26 октября 2022 года.
  + Если выбранная дата является праздничным днем под ней указывается название праздника.\
  8 марта 2023 года.\
  Международный женский день.
- При нажатии на месяц должна открываться панель выбора месяца
- При нажатии на стрелочки на панели выбора дней должны переключаться месяца
- При нажатии на стрелочки на панели выбора месяцев должны переключаться года
- Семантически именованы компоненты и организованы файлы по методологии Atomic Design

### Технологический стек:

- HTML
- SCSS
- React (FC, custom hooks)
- Redux Toolkit
- TypeScript

### Инструкция по развёртыванию

1. Создайте папку для проекта;
2. В терминале или консоли перейдите в эту папку;
3. Клонируйте в нее репозиторий командой ниже:

```
git clone https://github.com/AlekseiUsov/calendar.git .
```

4. Установите все необходимые пакеты командой ниже:

```
npm i
```

5. Запустите проект, написав в консоли следующую команду:

```
npm run start
```
