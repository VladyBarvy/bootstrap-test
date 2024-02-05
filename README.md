# bootstrap-test

## Как добавить файлы Bootstrap локально в проект
1. Добавить в корень проекта папку bootstrap
2. Внутри папки bootstrap создать папку css, в которой будут располагаться css-файлы
3. В репозитории Bootstrap на GitHub зайти в папку dist и скачать отдельно нужные файлы
<https://github.com/twbs/bootstrap/tree/main/dist/css>
4. Для начала скачать только следующие файлы:
  - bootstrap.min.css
  - bootstrap-grid.min.css
  - bootstrap-utilities.min.css
5. Расположить скаченные файлы в папке bootstrap/css
6. В файле index.html подключить указанные файлы, разместив следующий код в тэге head:
```
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Подключение Bootstrap</title>

  <link rel="stylesheet" href="bootstrap/css/bootstrap.min.css">
  <link rel="stylesheet" href="bootstrap/css/bootstrap-grid.min.css">
  <link rel="stylesheet" href="bootstrap/css/bootstrap-utilities.min.css">
</head>
```
7. Подключение Bootstrap через ссылки на CDN не является надёжным, так что лучше локально подключать скаченные файлы