# A/A/B - tests [(Посмотреть проект)](https://github.com/Denis-Ponomarev/My_projects-yandex_data_analyst/blob/main/07%20%D0%A1%D0%B1%D0%BE%D1%80%D0%BD%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%E2%84%962/AA%D0%92_%D1%82%D0%B5%D1%81%D1%82.ipynb)
## Описание проекта
Мы работаем в стартапе, который продаёт продукты питания. Нужно разобраться, как ведут себя пользователи нашего мобильного приложения. 
Изучим воронку продаж. Узнаем, как пользователи доходят до покупки. Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах? На каких именно?
После этого исследуем результаты A/A/B-эксперимента. Дизайнеры захотели поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно. Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. Выясним, какой шрифт лучше.

## Описание данных
Каждая запись в логе — это действие пользователя, или событие. 
- EventName — название события;
- DeviceIDHash — уникальный идентификатор пользователя;
- EventTimestamp — время события;
- ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.
## Используемые навыки и инструменты
`статистический анализ данных`, `Python`, `Pandas`, `Numpy`, `Seaborn`, `Plotly`,`scipy`, `A/B test`


