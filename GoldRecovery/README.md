# Исследование технологического процесса очистки золота

|Jupyter Notebook - [ipynb](https://github.com/tupperq/Portfolio/blob/main/GoldRecovery/GoldRecovery.ipynb)|
=
## Цель проекта
Подготовьте прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды.

## План проекта

- Исследовательский анализ данных
- Предобработка данных
- Подбор двух моделей для разных этапов и их гиперпараметров
- Тестирование

## Общие выводы

### Модель

Лучшей для первого этапа оказалась модель LinearRegression  (sMAPE = 0.04), а для второго этапа DecisionTreeRegression (sMAPE = 0.08) со следующими гиперпараметрами:

    + max_depth = 6
    + max_samples_leaf = 8

__Итоговый sMAPE = 0.07__

Подробный вывод представлен в тетрадке.
