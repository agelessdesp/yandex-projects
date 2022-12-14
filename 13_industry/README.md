# Прогнозирование температуры плавления стали

## Задача:
Чтобы оптимизировать производственные расходы, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. Вам предстоит построить модель, которая предскажет температуру стали.

## Итог работы:
В ходе тестирования модели CatBoost, удалось достичь результата целевой метрики **MAE: 5.98**. С подробным отчетом можно ознакомиться в самом проекте.

## Описание данных:

- `data_arc.csv` — данные об электродах;
- `data_bulk.csv` — данные о подаче сыпучих материалов (объём);
- `data_bulk_time.csv` *—* данные о подаче сыпучих материалов (время);
- `data_gas.csv` — данные о продувке сплава газом;
- `data_temp.csv` — результаты измерения температуры;
- `data_wire.csv` — данные о проволочных материалах (объём);
- `data_wire_time.csv` — данные о проволочных материалах (время).

Во всех файлах столбец key содержит номер партии. В файлах может быть несколько строк с одинаковым значением key: они соответствуют разным итерациям обработки.

## Используемые навыки и инструменты:
- Python
- Pandas
- Matplotlib
- NumPy
- Scikit-learn
- исследовательский анализ данных

Ключевые слова: анализ данных, регрессия, кастомные метрики.
