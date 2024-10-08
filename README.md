# Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста
### Опсиание проекта 
Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.

### Задача: 
Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами

### Инструменты: 
Python, Pandas, Matplotlib, SciPy, проверка статистических гипотез, A/B - тестирование

### Ключевые слова: 
A/B-тест, статистический тест, фреймворк, RICE, ICE

### Выводы
- Есть статистически значимое различие в среднем числе заказов между группами по сырым данным, так и после фильтрации аномалий, однако группа B выигрывает груупу А.
- По сырым данным нет статистически значимого различия по среднему чеку между группами, после удаления аномалий статистически значимое различия также нет. При этом группа B уже проигрывает группе А.
- График различия среднего количества заказов на посетителя между группами сообщает, что результаты группы B лучше группы A: зафиксировались около среднего значения.
- График различия среднего чека колеблется, однако группа B в основном выиграет группу А.
- По итогу тестирования можно остановить тест, признать победу группы В.
