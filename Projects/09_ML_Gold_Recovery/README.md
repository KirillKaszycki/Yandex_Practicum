# ML_gold_recovery

Восстановление золота из руды
- Подготовьте прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.
- Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Используйте данные с параметрами добычи и очистки.
- Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

# Инструкция по выполнению проекта
# Подготовьте данные

- Проверьте, что эффективность обогащения рассчитана правильно. Вычислите её на обучающей выборке для признака rougher.output.recovery. Найдите MAE между вашими расчётами и значением признака. Опишите выводы.

- Проанализируйте признаки, недоступные в тестовой выборке. Что это за параметры? К какому типу относятся?

- Проведите предобработку данных.

- Проанализируйте данные

- Для прогноза коэффициента нужно найти долю золота в концентратах и хвостах. Причём важен не только финальный продукт, но и черновой концентрат.
- Итоговое sMAPE = 0.25 * sMAPE(rougher) * 0.75 sMAPE(final)
