# Power BI Дашборд для анализа продаж
## 📋 Описание
Этот репозиторий содержит проект Power BI, направленный на анализ ключевых показателей эффективности (KPI) для бизнес-кейса. Анализ включает различные метрики и визуализации, которые позволяют детально изучить показатели продаж, прибыльности и сегментов покупателей.

## 📊 Ключевые показатели
В Power BI были рассчитаны следующие KPI с использованием мер:

- Выручка: Общий объем продаж.
- Прибыль: Чистая прибыль после вычета затрат.
- Рентабельность: Процент прибыли от выручки.
- АКБ: Количество активных клиентов за период.
- Средний чек: Средний размер заказа на одного клиента.
- Затраты на логистику: Расходы на транспортировку и доставку.
## 📈 Визуализации
В проекте созданы следующие визуализации для представления данных:

- Динамика KPI: Линейный график, отображающий динамику ключевых показателей (выручка, прибыль, средний чек) с течением времени.
- Показатели по сегментам покупателей: Разбиение ключевых показателей по сегментам покупателей, представленные в виде столбчатых и круговых диаграмм.
- Дрилл-даун по номенклатуре: Иерархический анализ показателей по категориям, подкатегориям и номенклатурным позициям, с возможностью глубокого анализа.
- Распределение показателей на карте: Визуализация ключевых показателей на географической карте по разным регионам.
- ABC-анализ номенклатуры: Категоризация товаров на группы A, B и C в зависимости от их вклада в общую выручку.
- Продажи с отрицательной прибылью по менеджерам: Таблица с менеджерами, которые продавали товары с отрицательной прибылью, с указанием количества таких заказов.

## 🛠 Подготовка данных

- Очистка данных
- Нормализация: Данные были нормированы для удаления пустых и лишних строк.
- Приведение типов данных: Типы данных были приведены к стандартным значениям для обеспечения корректности расчетов.
- Таблица календаря
Поскольку справочник с датами заказов не содержит всех дат, была создана собственная таблица календаря с использованием DAX для полноценного временного анализа.
## 📋 Требования

Power BI Desktop (последняя версия).
Файл данных (включен в репозиторий).
