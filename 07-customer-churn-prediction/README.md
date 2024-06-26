# Отток клиентов

## Описание проекта

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Требуется построить модель с предельно большим значением *F1*-меры (довести метрику до 0.59).

Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

## Навыки и инстуремнты

- python
- pandas
- scikit-learn

## Общий вывод

- В ходе исследования была выполнена предобработка данных, устранены пропуски и использован метод прямого кодирования.
- Проанализированы данные на предмент дисбаланса - есть сильный дисбаланс в сторону отрицательных классов.
- Исследованы модели решающего дерева, случайного леса и логистической регрессии на несбалансированных.
- Были применены методы увеличения и уменьшения классов для устранения дисбаланса. Эффективней себе показал upsampling.
- Изучены модели обученные на сбалансированных данных.
- Найдена лучшая модель - модель случайного леса с глубиной 10 и количеством деревьев 70. F1-мера равна 0.62, что было подтверждено на тестовой выборке.
