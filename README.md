## Кейс: организация полного цикла работы с данными для аналитической отчётности

### 🎯 Цель

Автоматизировать сбор и анализ данных из разрозненных источников и заменить ручную отчетность на единую аналитическую систему для руководства.

### ⚙️ Что было
- Данные хранились в 1С и Excel
- Отчеты собирались вручную
- Не было единого источника данных

### 🛠️ Что сделал

1. Настроил сбор данных
- Организовал выгрузку данных из 1С (УТ, БП)
- Подключил Excel-файлы пользователей

2. Построил ETL-процессы (Pentaho)
- Очистка и нормализация данных
- Объединение источников
- Обработка ошибок и дублей

3. Реализовал DWH (PostgreSQL)
- Спроектировал структуру хранения
- Настроил загрузку данных

4. Разработал BI-отчетность (Power BI)
- Создал модель данных
- Реализовал метрики (DAX)
- Сделал интерактивные дашборды

### 📈 Результат
- 📉 Сократил время подготовки отчетности (с ручного до автоматического)
- 📊 Руководство получило доступ к актуальным данным в любой момент
- ✅ Повысилось качество данных (меньше ошибок и расхождений)
- 🔄 Появилась единая система аналитики вместо разрозненных источников

### 🧰 Стек
PostgreSQL, Pentaho, Power BI, DAX, Power Query, 1С, Excel


<p align="center">
  <img src="https://github.com/iaidarf/data-warehouse-etl-bi/blob/main/scheme.png" width=70% /> 
  <br>
  <em>Схема этапов реализации</em>
</p>

<p align="center">
  <img src="https://github.com/iaidarf/data-warehouse-etl-bi/blob/main/pentaho.PNG" width=70% /> 
  <br>
  <em>Пример процесса в pentaho</em>
</p>



<p align="center">
  <img src="https://github.com/iaidarf/data-warehouse-etl-bi/blob/main/summary.png" width=50% /> 
  <br>
  <img src="https://github.com/iaidarf/data-warehouse-etl-bi/blob/main/detail.png" width=50% /> 
  <br>
  <img src="https://github.com/iaidarf/data-warehouse-etl-bi/blob/main/comparison.png" width=50% /> 
  <br>
  <em>Примеры отчетов в PowerBI</em>
</p>

