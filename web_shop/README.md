# Анализ маркетплейса

## Описание проекта
Интернет-магазин «В один клик» решает проблему снижения активности покупателей, применяя персонализированные предложения. Для этого строится модель прогнозирования вероятности снижения покупательской активности клиентов в следующие три месяца. Модель учитывает данные о прибыльности клиентов и различных характеристиках их покупок.

## Вывод
- **Обработка данных:**
  - Исправлены опечатки в данных.
  - Избавились от выбросов в выручке и расформировали ее по месяцам.
- **Характеристики клиентов:**
  - Большинство клиентов относится к категории "стандарт" (около 70%).
  - У 40% клиентов замечено снижение активности.
- **Категории товаров:**
  - Наиболее активные категории товаров - "Мелкая бытовая техника и электроника".
- **Поведение клиентов:**
  - У клиентов со сниженной активностью чаще встречаются неоплаченные товары и ошибки сервиса.
- **Модель прогнозирования:**
  - Разработан пайплайн для поиска лучшей модели, и лучшей моделью оказалась LogisticRegression с определенными гиперпараметрами.
- **Рекомендации:**
  - Использование персонализированных предложений, основанных на поведении и интересах клиентов, поможет повысить их покупательскую активность и, следовательно, прибыль компании.


## 🛠 Инструменты
<i class="devicon-scikitlearn-plain"></i>
 ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) 
 ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
 ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) 
 ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) 
 ![Seaborn](https://img.shields.io/badge/Seaborn-%230095D5.svg?style=for-the-badge&logo=seaborn&logoColor=white)
 ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) 
