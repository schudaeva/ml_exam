# ml_exam
Теория: https://docs.google.com/document/d/1xXAaLrHzaH0kTjB4hj7qZ0AgMFTl3pcfYIWX7nLffOU/edit?usp=sharing

3 вар: https://github.com/koroteevmv/ML_course/tree/2023_new/ML4.5%20hyperparameters\

4 вар: https://github.com/koroteevmv/ML_course/tree/2023_new/ML4.3%20diagnostics

      Там хотят чтобы мы сначала обучили модельку на датасете который есть
      Потом смотрим, какие признаки например можно выкинуть - для этого можно глянуть корреляцию признаков с целевой переменной, если она почти на нуле - можно смело от признака избавиться
      Далее, добавление признаков в модель - тут выбери какой признак и попробуй его преобразовать в полином (делали в классных)
      Вообще нет. Этот вариант предполагает как раз что мы должны более ответственно подойти не столько к модели, сколько именно к датасету который ей кормим
      И покрутили именно датасет, а не модель
      Первый больше на обучение разных моделей и их сравнение, второй на анализ датасета
      А тут мы его меняем и стараемся выбрать оптимальный набор данных
      Ну и заодно чекаешь нет ли в данных сбитых единиц измерения и прочей "грязи"
      Короче чтобы данные были адекватные
      Ну очистка данных и удаление какого-то признака не совсем одно и то же, хотя в первом варианте тоже будет полезно какой-то совсем не значимый признак удалить
      Короче смотри в первом варианте - очень внимательно с пропусками в данных, преобразованием категориальных в числовые и прочими приколами, можно будет в принципе какой-то признак исключить
      Четвёртый вариант - после очистки целенаправленно сначала обучаешь на всём датасете, чекаешь метрики качества, потом выкидываешь один признак и снова обучаешь, чекаешь. Дальше можешь ещё какой-то признак выкинуть и заново сравнить
      Ну и в конце можешь какой-то признак к полиному привести


https://github.com/Genudza/ML_course_2023_new-PI21-1-7-and-PM21-1-6-/tree/2023_new

https://github.com/BorisovNikita/3rdYear/tree/master/ML

https://github.com/GeorgiyDemo/FA/tree/master/Course_III/ML
