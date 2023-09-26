# 2022-realty-spb
Исследование объявлений о продаже недвижимости

# **ПРОЕКТ «Исследование объявлений о продаже квартир в Санкт-Петербурге и Ленинградской области»**

---

## **Примененные библиотеки**

* Pandas, Numpy, Random, Matplotlib, Seaborn

---

## **Цель и задачи проекта**

**Цель** - провести исследовательский анализ данных датасета с объявлениями о продаже квартир.

**Задачи**:

* загрузить данные и изучить общую информацию о датасете;

* предобработать данные;

* создать новые признаки в датасете: цена одного квадратного метра; день недели публикации объявления; месяц публикации объявления; год публикации объявления; тип этажа квартиры; расстояние до центра города в километрах;

* изучить параметры объектов недвижимости;

* изучить, как быстро продавались квартиры после публикации объявления о продаже;

* выявить факторы, больше всего влияющие на общую  (полную) стоимость квартиры;

* определить среднюю стоимость одного квадратного метра в десяти населенных пунктах с самым большим числом объявлений;

* для квартир из Санкт-Петербурга вычислить среднюю стоимость одного квадратного метра в зависимости от расстояния до центра города.

---

## **Основные результаты**

**(1)** Общая площадь  основной части продаваемых квартир находится в пределах от 25 до 75 квадратных метров;  жилая площадь – от 35 до 50 квадратных метров; площадь кухни – от 10 до 13 квадратных метров. Количество комнат в продаваемых квартирах составляет от одной до трех; количество предлагаемых квартир с четырьмя и более комнатами ограничено в размерах. Самая распространенная высота потолка – 2,65 метров, также предлагается значительное число квартир с высотой потолка 2,5 и 3 метра. Примерно 40% продаваемых квартир находятся на этажах с 1 по 4-й, еще около 40% на этажах с 5 по 10-й, остальные - в домах повышенной этажности и высотных домах. Примерно по 12,5% квартир находятся на первом и последнем этаже, все остальные – на этажах со второго до предпоследнего. Самыми часто встречающимися являются дома с 5-ю, 9-ю и 10-ю этажами, немало объявлений о продаже квартир в 16-ти и 25-ти этажных домах.

**(2)** Самая дорогая квартира в исследуемом массиве данных стоит 76 млн. рублей. Широко представлены дорогие квартиры стоимостью от 8 до 20 млн. рублей. Основное количество продаваемых квартир оценены их продавцами в размере от 4 до 6 млн. рублей.

**(3)** Проведен расчет средней цены одного квадратного метра в 10 населённых пунктах с наибольшим числом объявлений***. Установлено, что этими населенными пунктами являются: Санкт-Петербург, Мурино, Кудрово, Шушары, Всеволожск, Пушкин, Колпино, Парголово, Гатчина, Выборг. В указанной выборке максимальная стоимость одного квадратного метра жилья выявлена в Санкт-Петербурге (124 тыс. рублей), минимальная – в Выборге (58 тыс. рублей).
