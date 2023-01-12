**Внимание!** Оригинальный **командный** репозиторий проекта и вся история его развития, доступны по ссылкам ниже 
(текущий репозиторий - только копия финальной версии кода проекта): 
- Repo: https://github.com/andreybabynin/semantic_news_graph
- Project team (contributors): https://github.com/andreybabynin/semantic_news_graph/graphs/contributors
- Issues: https://github.com/andreybabynin/semantic_news_graph/issues?q=is%3Aissue
- Backlog: https://github.com/users/andreybabynin/projects/2/

Проект создан в рамках прохождения курса **"ML System Design. Autumn 22/23"**.
- Ссылки на курс: https://ods.ai/tracks/ml-system-design-22
- Защита проекта: https://youtu.be/3pJSXQuBd-s?t=7957
- Презентация проекта: https://github.com/wisoffe/semantic_news_graph/blob/main/reports/Presentation__News_graph_2023.01.08.pdf

# Граф новостей
## Описание
Проект доступен [здесь](http://5.178.2.42:5050/)

Идея проекта в птредставление новостей через графовую структуру. Это попытка запечатлеть взаимосвязь событий, людей и мест через их взаимную встречаемость в новостном потоке.

Сейчас проект собирает новости из нескольких каналов:
- [РИА НОВОСТИ](https://t.me/rian_ru)
- [ТАСС](https://t.me/tass_agency)

В качестве библиотеки для отрисовки графиков использована [d3.js](https://d3js.org/)

## Структура проекта
![project structure](imgs/News%20Graph%20Structure.png)

- docker - сборочные файлы для развертывания компонентов системы
- notebooks - история отдельных экспериментов с обработкой данных
- reports - сравнение вариантов выделения NEs
- src - исходный код проекта

## Описание препроцессинга
![preprocessing pipeline](imgs/Preporcessing%20pipeline.png)
