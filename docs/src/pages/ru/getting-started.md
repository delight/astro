---
layout: ~/layouts/MainLayout.astro
title: Начало Работы
---

Astro – это современный сборщик статических сайтов. Вы можете узнать всё об Astro на [главной странице](https://astro.build/) или из [нашего релизного поста](https://astro.build/blog/introducing-astro). Эта страница даёт общее представление о документации и всех относящихся к Asto материалах.

## Пробуем Astro

Самый простой способ попробовать Astro — запустить команду `npm init astro` в новой директории на вашем компьютере. Наш CLI установщик поможет вам в разворачивании нового проекта на Astro.

Для быстрого старта с Astro в 5 простых шагов, посетите страницу руководства по [быстрому старту](ru/quick-start).

Также вы можете развернуть проект с помощью [руководства по установке](/installation), которое пошагово проведёт через процесс разворачивания проекта с Astro.

### Примеры проектов

Если вы предпочитаете учить Astro по примерам, вы можете воспользоваться [полной библиотекой примеров](https://github.com/snowpackjs/astro/tree/main/examples) на GitHub.

Вы можете установить любой из этих примеров на вашу локальную машину с помощью команды `npm init astro` и дополнительного параметра `--template`. Флаг `--template` также поддерживает сторонние шаблоны.

```bash
# Запустить инициализацию и использовать официальный шаблон
npm init astro -- --template [OFFICIAL_EXAMPLE_NAME]
# Запустить инициализацию и использовать шаблон, предложенный сообществом
npm init astro -- --template [GITHUB_USER]/[REPO_NAME]
npm init astro -- --template [GITHUB_USER]/[REPO_NAME]/path/to/example
```

### Онлайн-песочницы

Если вы хотите попробовать Astro прямо в браузере, можно использовать онлайн-редакторы кода, например, Stackblitz, CodeSandbox, Gitpod или GitHub Codespaces.
Также вы можете нажать на кнопку "Open in Stackblitz" в любом из примеров в нашей [библиотеке](https://github.com/snowpackjs/astro/tree/main/examples). Или [нажмите здесь](https://stackblitz.com/fork/astro), чтобы запустить новый проект на [Stackblitz](https://stackblitz.com/fork/astro).

## Изучаем Astro

Люди, приходящие в Astro из разных областей, приносят свой уникальный стиль изучения. Независимо от того, какой стиль изучения вы предпочитаете: теоретический или практический, мы надеемся, этот раздел будет вам полезен.

- Если вы предпочитаете **изучение на практике**, начните с нашей [библиотеки примеров](https://github.com/snowpackjs/astro/tree/main/examples).
- Если вы предпочитаете **изучать принципы шаг за шагом**, начните с [основных принципов и руководств](/core-concepts/project-structure).

Как любая новая технология, Astro требует немного изучения.
Однако мы уверены, что при должной практике и некотором терпении вы быстро _научитесь_ этому.

### Изучаем `.astro` синтаксис

Когда вы начнёте изучать Astro, вы увидите много файлов, которые используют расширение `.astro`. **Синтаксис компонентов Astro** – это специальный, похожий на HTML-формат файл, который Astro изпользует для шаблонизации. Он был разработан так, чтобы быть знакомым для любого человека, у которого есть опыт работы с HTML или JSX.

Наше руководство по [Astro компонентам](/core-concepts/astro-components) даст вам представление о синтаксисе Astro, и это самый лучший путь для их изучения.

### Справочник API

Если вы хотите узнать больше деталей о конкретных Astro API, изучите справочник по API. Например, в нём можно найти документацию по [конфигурации](/reference/configuration-reference) с полным списком доступных настроек, или [полный список встроенных компонентов](/reference/builtin-components), таких как `<Markdown />` и `<Code />`.

### Документация на старые версии Astro

Эта документация всегда описывает последнюю стабильную версию Astro. Как только мы достигнем версии v1.0, добавим возможность для просмотра других версий документации.

## Обратная связь

Твиттер аккаунт [@astrodotbuild](https://twitter.com/astrodotbuild) является официальным источником обновлений от команды Astro.

Также мы выкладываем анонсы релизов в нашем сообществе в [Discord](https://astro.build/chat) в канале #announcements.

Не каждый релиз Astro заслуживает отдельной публикации в нашем блоге, но вы можете найти все детали в описании изменений к релизу в файле [`CHANGELOG.md`](https://github.com/snowpackjs/astro/blob/main/packages/astro/CHANGELOG.md) в нашем репозитории на Github.

## Что-то упущено?

Если в документации что-то пропущено или какая-то часть не совсем понятна, пожалуйста, [создайте issue по документации](https://github.com/snowpackjs/astro/issues/new/choose) с вашими предложениями об исправлениях или улучшениях, или упомяните наш [@astrodotbuild](https://twitter.com/astrodotbuild) Твиттер аккаунт в вашем твите. Мы всегда рады услышать ваши мысли об Astro!

## Благодарность

Этот гайд был основан на руководстве по быстрому старту с [React](https://reactjs.org/).
