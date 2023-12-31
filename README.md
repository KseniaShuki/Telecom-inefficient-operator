# Телеком — Определение неэффективных операторов.

## Описание.

В данном проекте проведено исследование работы нового сервиса мониторинга телекомпровайдера по выявлению неэффективных операторов колл-центров. Оформлена презентация и дашборд.

## Задачи.

1. Изучить и обработать имеющиеся в распоряжении два .csv файла, содержащие информацию о совершенных звонках операторами коллцентров (клиентов провайдера).
2. Провести анализ эффективности работы операторов коллцентров, выявить неэффективных сотрудников.
3. Проверить влияние количественных показателей на неэффективность работы операторов статистическими гипотезами.

## Ход работы.

 - Загрузка данных из .csv файлов, изучение общей информации и предобработка данных: пропуски, дубликаты, типы данных. Создание дополнительных столбцов. Выявление и устраненеие редких и выбивающихся значений в данных.
 - Анализ данных по количественным показателям неэффективности работы операторов. Исследуемые метрики коллцентров, специализирующиеся на приеме звонков: FCR (Доля решенных проблем клиента), CAR (Неотработанные вызовы). Метрики коллцентров, специализирующихся на обзвонах: RSR (Показатель успешности ответа), AHT (Среднее время обработки), CRR (Коэффициент отказа от вызова).
 - Выдвижение и проверка статистических гипотез.
 - Выводы по проведенному анализу.
   
## Инструменты.

Python (pandas, numpy, matplotlib.pyplot, statistics, graph_objects, plotly.express, stats), PowerPoint, Tableau.
