# Задачи проекта:
Выполнение приоритизаций гипотез для увеличения выручки, подготовленных совместно с отделом маркетинга. Выполнение A/B-тестов
# Результат исследования
Произведен A/B тест. В ходе анализа результатов теста, определены аномальнные пользователи, которые совершили или слишком много или слишком дорогие покупки (но таких пользователей менее 1%).
Непараметрический тест Уилкоксона-Манна-Уитни показал:
- есть статистически значимое различие по количеству заказов между группами как по сырым данным, так и после фильтрации аномалий;
- по сырым данным и по очищенным нет статистически значимого различия по среднему чеку между группами.

В этой связи тест можно завершить и зафиксировать победу группы B. Количество среднее количество заказов у группы B на 15,9%, а средний чек на 2%.
# Стек:
python, pandas, Matplotlib, SkiPy, проверка статистических гипотез
# Статус: завершен
