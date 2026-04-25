# Структура
 
```
├── mart_city_top_products_2MR23YG1K.zpln
├── screenshots/
│   ├── 2026-04-25_13_19_10.jpg
│   ├── 2026-04-25_13_19_26.jpg
│   ├── 2026-04-25_13_19_30.jpg
│   ├── 2026-04-25_13_19_38.jpg
│   ├── 2026-04-25_13_19_45.jpg
│   └── 2026-04-25_13_19_49.jpg
└── README.md
```
 
## Результаты
 
### 1. Revenue = qty × price
![revenue](Screenshots/2026-04-25_13_19_10.jpg)
 
### 2. Исходные данные
![source data](Screenshots/2026-04-25_13_19_26.jpg)
 
### 3. JOIN orders → users → products
![join](Screenshots/2026-04-25_13_19_30.jpg)
 
### 4. Агрегация по городу и товару
![aggregation](Screenshots/2026-04-25_13_19_38.jpg)
 
### 5. Top-2 по городу (оконная функция)
![top2](Screenshots/2026-04-25_13_19_45.jpg)
 
### 6. Запись в HDFS и чтение обратно
![hdfs](Screenshots/2026-04-25_13_19_49.jpg)
