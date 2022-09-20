# Анализ данных интернет-магазина «Стримчик»

## **Задача:**
Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## **Итог работы:**
Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовался критерий Стьюдента для независимых выборок.

## **Описание данных:**

- **Name** — название игры
- **Platform** — платформа
- **Year_of_Release** — год выпуска
- **Genre** — жанр игры
- **NA_sales** — продажи в Северной Америке (миллионы проданных копий)
- **EU_sales** — продажи в Европе (миллионы проданных копий)
- **JP_sales** — продажи в Японии (миллионы проданных копий)
- **Other_sales** — продажи в других странах (миллионы проданных копий)
- **Critic_Score** — оценка критиков (максимум 100)
- **User_Score** — оценка пользователей (максимум 10)
- **Rating** — рейтинг от организации ESRB (англ. Entertainment Software Rating Board).Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

## **Используемые навыки и инструменты:**

- Python
- Pandas
- NumPy
- Matplotlib
- предобработка данных
- исследовательский анализ данных
- описательная статистика
- проверка статистических гипотез

Ключевые слова: обработка данных, histogram, boxplot, статистический тест, критерий Стьюдента, piechart.