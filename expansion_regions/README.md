# Выбор локации для новых скважин

Компании «ГлавРосГосНефть» стоит принять решение о месторасположении новой скважины. Для этого:

- В избранном регионе соберём характеристики для скважин: качество нефти и объём её запасов.
- Построим модель для предсказания объёма запасов в новых скважинах.
- Выберем скважины с самыми высокими оценками значений.
- Определим регион с максимальной суммарной прибылью отобранных скважин.

## Вывод

Проведен анализ качества данных, в ходе которого было установлено отсутствие пропусков и дубликатов.

Второй регион выделился особенно: обнаружена слишком сильная зависимость между признаком 'f2' и целевым, что может свидетельствовать об утечке информации.

Оценка средних значений запасов скважин показала, что они оказались ниже минимального значения для безубыточной разработки. Тем не менее, все регионы оказались прибыльными.

Риск убытков во всех регионах оказался менее 2.5%, что говорит о невысоком риске. Однако, для выбора региона мы ориентируемся на среднюю прибыль.



## 🛠 Инструменты
<i class="devicon-scikitlearn-plain"></i>
 ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) 
 ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
 ![Seaborn](https://img.shields.io/badge/Seaborn-%230095D5.svg?style=for-the-badge&logo=seaborn&logoColor=white)
 ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) 
 ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) 
 ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) 
