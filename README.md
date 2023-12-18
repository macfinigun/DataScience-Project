# DataScience-Project

Полное описание проектов:
# 5.
Тема: Статистический анализ данных, проверка гипотез.
Проект: Определение перспективного тарифа для телеком-компании
«Мегалайн» — федеральный оператор сотовой связи. Клиентам предлагается два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

В соответствии с данными 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом используют, сколько звонков и сообщений каждую отправлено за 2018 год. Необходимо:

сделать предварительный анализ тарифов на небольшой выборке клиентов — какие объемы услуг используются пользователями каждого тарифа, какой доход получает компания;
проверить гипотезы:
существуют средние доходы пользователей тарифов «Ультра» и «Смарт»;
Средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов.
# 6.
Тема: Простейшие модели ML, подбор гиперпараметров
Проект: Рекомендация тарифов для клиентов (бинарная классификация)
Автор мобильной связи «Мегалайн»: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную учитывать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

В данных о содержании клиентов, которые уже перешли на эти тарифы (см. проект 5 в этой же репозитории). Необходимо построить модель для целевой группы, которая выберет соответствующий тариф. Предобработка данных не требуется, так как она уже проведена.

Необходимо построить модель с максимально большим значением точности (>0,75). Для этого рассматривайте различные модели с различными гиперпараметрами.

ключи: двоичная классификация, логистическая регрессия, DecisionTreeClassifier, RandomForestClassifier, точность.
# 7.
Тема: Бинарная классификация при дисбалансе классов, различных метриках классификации
Проект: Предсказание ухода за клиентом банка (бинарная классификация)
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи рассчитали: сохранение текущих клиентов дешевле, чем привлечение новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Необходимо построить модель с предельно большими значениями F1-меры (>=0,59). Дополнительное измерение AUC-ROC, сравнивающее ее значение с F1-мерой.

ключи: несбалансированная двоичная классификация, GridSearchCV, LogisticReгрессия, DecisionTreeClassifier, RandomForestClassifier, f1, точность, отзыв, auc-roc, OHE
# 8.
Тема: Связь метрика бизнеса и метрика машинного обучения, применение машинного обучения в бизнесе
Проект: Предсказать наиболее перспективный регион для разработки нефтяных скважин.
В добывающей компании «ГлавРосГосНефть» необходимо решить, где бурить новую скважину. Предоставлены пробы нефти в трех регионах. Характеристики каждой скважины в предложениях уже представлены.

Шаги для выбора локации обычно такие:

В избранном предложении собираются характеристики скважин: качество нефти и объем ее запасов;
Строить модель для предсказания объема запасов в новых скважинах;
Выбирают скважины с переменным повышением оценок;
Определяют регион с максимальной прибылью видимых скважин.
Необходимо построить модель для региона определения, где добыча приносит наибольшую прибыль, учитывая возможную прибыль и риски (техника Bootstrap).

ключи: регрессия, бутстрап, доверительный интервал, прибыль и убыток, линейная регрессия, RMSE.
# 9. ML в промышленности. Большой проект.
Тема: Кросс-валидация, применение машинного обучения в промышленности
Проект: Предсказать коэффициент восстановления золота из золотосодержащей руды на основе физических данных технологических процессов.
Когда добытая руда проходит первичную обработку, получается дроблёная смесь. Их отправляют на флотацию (обогащение) и двухэтапную очистку. Необходимо смоделировать процесс восстановления золота из золотосодержащей руды.

Необходимо спрогнозировать сразу две величины:

эффективность обогащения черного концентрата грубая.выработка.восстановление;
эффективность обогащения концентрата Final.output.recovery.
Итоговая метрика складывается из двухзначной формулы

(Данных и частных задач много, подробнее опишите в самом проекте)

ключи: регрессия, перекрестная проверка, sMAPE, бизнес-метрики, множественные прогнозы, настройка функций, DecisionTreeRegressor, RandomForestRegressor, LinearReгрессия
