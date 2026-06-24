# Музей древней истории

Учебная HTML-страница для выполнения задания по билету №2.

## Состав проекта

- `index.html` — структура и содержание страницы;
- `styles.css` — оформление и адаптивная вёрстка;
- `README.md` — описание проекта и инструкция по публикации.

## Как открыть страницу на компьютере

Откройте файл `index.html` двойным щелчком. Для удобной разработки можно использовать расширение Live Server в Visual Studio Code.

## Как загрузить проект на GitHub через браузер

1. Войдите в GitHub и создайте новый репозиторий.
2. Назовите его `museum-ancient-history` и выберите видимость `Public`.
3. В репозитории нажмите `Add file` → `Upload files`.
4. Загрузите `index.html`, `styles.css` и `README.md`.
5. Введите сообщение коммита, например `Добавлена страница музея`, и подтвердите загрузку.
6. Откройте `Settings` → `Pages`.
7. В разделе `Build and deployment` выберите:
   - `Source`: `Deploy from a branch`;
   - `Branch`: `main`;
   - папка: `/(root)`.
8. Нажмите `Save`.

Адрес опубликованной страницы будет иметь вид:

```text
https://ВАШ-ЛОГИН.github.io/museum-ancient-history/
```

## Как загрузить проект через Git

Сначала создайте на GitHub пустой репозиторий `museum-ancient-history`, затем откройте терминал в папке проекта и выполните:

```bash
git init
git add .
git commit -m "Создана страница музея"
git branch -M main
git remote add origin https://github.com/ВАШ-ЛОГИН/museum-ancient-history.git
git push -u origin main
```

После этого включите GitHub Pages по инструкции выше.

## Как отправить последующие изменения

```bash
git add .
git commit -m "Обновлена страница музея"
git push
```

## Проверка перед сдачей

- файл называется именно `index.html`;
- `index.html` находится в корне репозитория;
- файл `styles.css` загружен рядом с `index.html`;
- в настройках Pages выбрана ветка `main` и папка `/(root)`;
- опубликованная ссылка открывается без авторизации.
