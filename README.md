# Calc AB Test
Собираю в одном месте функции, используемые мной для анализа A/B тестов.
Здесь будет несколько блокнотов Yupiter Notebook. Прикладываю также csv, используемый в функциях.
## 1. Calc AB Test
- [Ссылка на файл](https://github.com/a-efimov/Calc-AB-Test/blob/main/Calc%20AB%20Test.ipynb).
### Функции для работы с экспериментами:
- **Расчет продолжительности эксперимента** - calc_duration_ab_test;
- **Расчет p-value Хи-квадрат** - calc_pvalue_chi_square_ab_test;
- **Расчет p-value Т-тест** - calc_ttest_ab_test;
- **Расчет p-value Манна-Уитни** - calc_mannwhitneyu_ab_test.
## 2. Calc Bootstrap
[Ссылка на файл](https://github.com/a-efimov/Calc-AB-Test/blob/main/Calc%20Bootstrap.ipynb).
### Функции для расчета бутстрапа
Делаем множество подвыборок из датафрейма, рассчитываем, сравниваем и визуализируем метрики подвыборок.
