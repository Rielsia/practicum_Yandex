В начале проекта были поставлены две ключевые задачи:

1. Построить модель для предсказания снижения покупательской активности.
2. Выделить сегменты покупателей на основе данных модели и информации о прибыльности для разработки персонализированных предложений.

Для решения этих задач были использованы четыре основные таблицы данных:

- **market_file.csv:** содержит информацию о поведении клиентов на сайте, коммуникации с ними и их покупательском поведении.
- **market_money.csv:** предоставляет данные о выручке от каждого клиента за период взаимодействия с сайтом.
- **market_time.csv:** содержит информацию о времени, проведенном клиентом на сайте в течение периода.
- **money.csv:** предоставляет среднемесячную прибыль клиента за последние три месяца.

Шаги, выполненные для поиска лучшей модели, включали в себя:

1. Изучение и первичный анализ данных для понимания их структуры и содержания.
2. Обработка пропущенных значений и удаление дубликатов для подготовки данных к дальнейшему анализу.
3. Проведение анализа на выбросы и аномалии для улучшения качества данных.
4. Исследование взаимосвязей между количественными признаками с помощью корреляционного анализа.
5. Объединение данных из разных таблиц для создания более полного и информативного набора признаков для обучения моделей.
6. Настройка автоматизации процесса обучения моделей с использованием пайплайнов, в которых были опробованы различные типы моделей, включая линейные и на основе метода k-ближайших соседей (KNeighborsClassifier).

В результате анализа лучшей моделью для задачи предсказания снижения покупательской активности оказался SVC. Это позволяет эффективно прогнозировать поведение клиентов и адаптировать маркетинговые стратегии для различных сегментов аудитории, повышая общую прибыльность и удовлетворение клиентов.

Для стимулирования покупательской активности была выбрана **группа клиентов с низкой активностью.** Анализ наиболее значимых признаков, выявленных моделью, подтвердил необходимость внимания к этой группе. Особое внимание следует уделить клиентам, которые редко просматривают страницы и проводят минимальное время на платформе.

Для увеличения их активности рекомендуется улучшить пользовательский опыт, например, путем оптимизации интерфейса для удобства навигации и предложением персонализированных рекомендаций. Также эффективными могут быть акционные предложения и уведомления о специальных акциях, которые могут заинтересовать эту группу потребителей.