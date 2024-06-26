# Sales Analysis
Были проанализированы данные о продажах в интернет магазине электроники в США за 2019 год и были найдены ответы на бизнес вопросы о данных. 

## База данных включает в себя:
Папка с 12 csv файлами с данными о продаж за каждый месяц года.
  
## Использованные библиотеки:
pandas, os, datetime, matplotlib, seaborn, itertools, calendar

## В ходе анализа были найдены ответы на следующие вопросы:

1. Какой наилучший месяц для продаж? Сколько выручки было получено за этот месяц?
2. В каком городе у магазина наибольшие продажи?
3. В какое время мы должны показывать рекламу, чтобы увеличить вероятность того, что клиент купит продукт ?
4. Какие пары товаров чаще всего вместе продаются?
5. Какой самый популярный товар в магазине?
## В ходе анализа были сделанны следующие выводы:
1. Наибольшая выручка была в декабре, вероятнее всего это связано с новогодними празниками, так как люди в предверии праздников часто покупают в подарок электронику. Вторые по величине выручки у нас Апрель и Октябрь, такой скачок в продажах возможна из-за маркетинга магазина, возможно в эти месяцы магазин больше рекламировался.
2. По количеству проданных товаров и по выручке Сан-Франциско значительно превосходит другие города. Возможна данная тенденция связана с тем что в Силиконовой долине бОльшая потребность в электронике чем в других городах, так как город специализируется по большей части на ИТ - отрасли. Еще одной возможной причиной может быть то,что в Сан-Франциско доля обеспечанных людей больше чем в других городах. Также видно, что Потрланд очень сильно уступает по продажам, возможно стоит обратить внимание на маркетинговую стратегию в данном городе.
3. Я бы рекомендовала запускать рекламу к 11 и 19 часам, так как наибольшая активность пользователей зафиксированно с этом промежутке.

 ![image](https://github.com/azizabobojonova/sales_analyses/assets/157654767/d51b3be9-16ff-402b-b273-8128a268b44a)

5. Наиболее популярные пары товаров это всегда телефоны и к телефону подходящее зарядное устройство или наушники.
6. Наиболее популярные товары в магазине это батарейки и зарядные устройства. Наиболее очевидная причина этого, то что эти тоары дешевле, например чем LG Dryer. Также был построен график объема продаж и цен для отслеживания корреляции и взаимосвязи двух метрик.

 ![image](https://github.com/azizabobojonova/sales_analyses/assets/157654767/540b6049-8d14-4186-b699-4a85f6856b72)

Гипотеза о том,что дорогие продукты продаются реже потверждается, у батареек и зарядных устройств цена ниже всего --> они чаще всего покупаются. Однако по графику видно, что например Macbook Pro имеет экстремально выскоую цену по сравнению с другими товарами магазина, одна продается чаще чем например LG Dryer или Whasing Machine. Я предполагаю, что это объясняется тем, что на ноутбуки выше спрос в США чем на бытовую технику, так как много студентов, работников покупают макбуки для работы/учебы.
   
