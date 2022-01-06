Итоговый проект по курсу "Машинное обучение в бизнесе".
Стек:
ML: sklearn, pandas, numpy 
API: flask 
Данные: https://www.kaggle.com/c/choose-tutors/data
Задача: предсказать вероятность того, подойдет ли репетитор для подготовки к экзамену по математике. 
Используемые признаки:
* age - возраст, 
* years_of_experience - опыт, 
* lesson_price - стоимость урока, 
* qualification - квалификация, 
* physics - преподает ли репетитор физику, 
* chemistry - преподает ли репетитор химию, 
* biology - преподает ли репетитор биологию,
* mean_exam_points - средний балл на экзамене.

Модель: logreg

Клонируем репозиторий и создаем образ:
git clone https://github.com/fimochka-sudo/GB_docker_flask_example.git
