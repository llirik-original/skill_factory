→ Основные цели и задачи проекта:

   Отследить влияние условий жизни учащихся в возрасте от 15 до 22 лет на их успеваемость по математике, 
   чтобы на ранней стадии выявлять студентов, находящихся в группе риска.

   Сделать это можно с помощью модели, которая предсказывала бы результаты госэкзамена по математике для 
   каждого ученика школы.

   Чтобы определиться с параметрами будущей модели, необходимо провести разведывательный анализ данных и 
   составить отчёт по его результатам.

→ Краткая информация о данных

   Датасет из 395 строк, включающий в себя 29 признаков и целевую колонку для предсказания "score"
   
   Описание признаков:
   school — аббревиатура школы, в которой учится ученик
   sex — пол ученика ('F' - женский, 'M' - мужской)
   age — возраст ученика (от 15 до 22)
   address — тип адреса ученика ('U' - городской, 'R' - за городом)
   famsize — размер семьи('LE3' <= 3, 'GT3' >3)
   Pstatus — статус совместного жилья родителей ('T' - живут вместе 'A' - раздельно)
   Medu — образование матери (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее)
   Fedu — образование отца (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее)
   Mjob — работа матери ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое)
   Fjob — работа отца ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое)
   reason — причина выбора школы ('home' - близость к дому, 'reputation' - репутация школы, 'course' - образовательная программа, 'other' - другое)
   guardian — опекун ('mother' - мать, 'father' - отец, 'other' - другое)
   traveltime — время в пути до школы (1 - <15 мин., 2 - 15-30 мин., 3 - 30-60 мин., 4 - >60 мин.)
   studytime — время на учёбу помимо школы в неделю (1 - <2 часов, 2 - 2-5 часов, 3 - 5-10 часов, 4 - >10 часов)
   failures — количество внеучебных неудач (n, если 1<=n<=3, иначе 0)
   schoolsup — дополнительная образовательная поддержка (yes или no)
   famsup — семейная образовательная поддержка (yes или no)
   paid — дополнительные платные занятия по математике (yes или no)
   activities — дополнительные внеучебные занятия (yes или no)
   nursery — посещал детский сад (yes или no)
   higher — хочет получить высшее образование (yes или no)
   internet — наличие интернета дома (yes или no)
   romantic — в романтических отношениях (yes или no)
   famrel — семейные отношения (от 1 - очень плохо до 5 - очень хорошо)
   freetime — свободное время после школы (от 1 - очень мало до 5 - очень мого)
   goout — проведение времени с друзьями (от 1 - очень мало до 5 - очень много)
   health — текущее состояние здоровья (от 1 - очень плохо до 5 - очень хорошо)
   absences — количество пропущенных занятий
   score — баллы по госэкзамену по математике

→ Этапы работы над проектом:

   1. Очистить данные от выбросов. Проанализировать признаки на предмет количества пропусков данных.
   2. Проанализировать качественный состав признаков, исключить коррелирующие и не влияющие на итоговый балл.
   3. Сформировать итоговый набор признаков, которые будут использоваться при разработке ML-модели.


→ Ответы на вопросы саморефлексии:

1. Какова была ваша роль в команде?
Единственный член команды

2. Какой частью своей работы вы остались особенно довольны?
Этот Юнит был абсолютно тем, что мне нужно. Но это только основы. Нужно идти глубже.

3. Что не получилось сделать так, как хотелось? Над чем ещё стоит поработать?
Все темы нужно изучать глубже. Нужна практика в визуализации данных, нужно углублять теорию и математическую часть.
С визуализацией вообще далек от желаемого - в идеале хотелось бы рисовать без гугла, как сейчас.
 
4. Что интересного и полезного вы узнали в этом модуле?
Освежил в памяти основы статистики и теории вероятности (самый минимум). Визуализация

5. Что является вашим главным результатом при прохождении этого проекта?
Честно говоря, то, что я вообще успел пройти все его модули, пусть и с отсрочкой.

6. Планируете ли вы менять стратегию изучения последующих модулей?
Да. По вечерам учиться, а не работать.