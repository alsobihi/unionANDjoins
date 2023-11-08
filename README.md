# Union AND Sql Joins 




## نظرة عامة عن البيانات 😎

البيانات عبارة عن جدول أصناف متجر جوالات  وجدولين للمبيعات عام `2022` وعام `2023`

قم بتحميل هذه البيانات :bar_chart:

+ [x] [product.csv](product.csv)
+ [x] [2022.csv](2022.csv)
+ [x] [2023.csv](2023.csv)


### product.csv

1. العامود الأول أسم الجدول `table_name`
1. العامود الثاني الرقم المميز للمنتج `id`
1. العامود الثالث أسم المنتج `name`
1. العامود الرابع سعر المنتج `price`

| **table_name** | **id** | **name**                 | **price** |
|:--------------:|:------:|:------------------------:|:---------:|
| product        | 1      | iPhone 11                | 5000      |
| product        | 2      | iPhone SE 2              | 5000      |
| product        | 3      | iPhone 12                | 5000      |
| product        | 4      | iPhone 13                | 5000      |
| product        | 5      | iPhone SE 3              | 5000      |
| product        | 6      | Samsung Galaxy S21 FE    | 5000      |
| product        | 7      | Samsung Galaxy S22       | 5000      |
| product        | 8      | Samsung Galaxy S22 Ultra | 5000      |
| product        | 9      | Samsung Galaxy S23       | 5000      |
| product        | 10     | Samsung Galaxy S23 Ultra | 5000      |





### 2022.csv
جدول المبيعات لعام 2022

1. العامود الأول أسم الجدول `table_name`
1. العامود الثاني الرقم المميز للمنتج المباع `product_id`
1. العامود الثالث عدد المنتجات المباعة `qty`


| **table_name** | **product_id** | **qty** |
|:--------------:|:--------------:|:-------:|
| sales          | 1              | 1       |
| sales          | 2              | 2       |
| sales          | 3              | 1       |
| sales          | 4              | 1       |
| sales          | 6              | 3       |
| sales          | 7              | 1       |
| sales          | 8              | 1       |
| sales          | 9              | 4       |
| sales          | 11             | 5       |

### 2023.csv
جدول المبيعات لعام 2023

1. العامود الأول أسم الجدول `table_name`
1. العامود الثاني الرقم المميز للمنتج المباع `product_id`
1. العامود الثالث عدد المنتجات المباعة `qty`


| **table_name** | **product_id** | **qty** |
|:--------------:|:--------------:|:-------:|
| sales          | 5              | 3       |
| sales          | 10             | 7       |
| sales          | 12             | 2       |
