
<h2 align="center">
<img src="https://avatars.mds.yandex.net/i?id=9abf606bc4c1494e135dcecb929d713f398973c9-7672861-images-thumbs&n=13" width="30%" >  </h2>

<h2 align="center">Yandex.Practicum</h2>

| №| Название проекта| Описание | Стек |
|:-:| :-:|:-:|:-:|
| 1 | [Исследование платёжеспособности клиентов банка](https://github.com/romanmvch/Portfolio/tree/main/Credits) | Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга.|pandas|
| 2 |[Анализ объявлений недвижимости](https://github.com/romanmvch/Portfolio/tree/main/Real_estate) |Исходый датасет - архив объявлений за несколько лет о продаже квартир в Санкт-Петербурге и соседних населённых пунктах. Требуется выполнить предобработку данных и изучить их, чтобы найти особенности и зависимости, которые существуют на рынке недвижимости. О каждой квартире в базе содержится два типа данных: добавленные пользователем и картографические. Например, к первому типу относятся площадь квартиры, её этаж и количество балконов, ко второму — расстояния до центра города, аэропорта и ближайшего парка. | pandas, matplotlib |
| 3 | [Рекомендация тарифов сотового оператора](https://github.com/romanmvch/Portfolio/tree/main/Mobile_users_behavior)| Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег. Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов. В распоряжении данные 500 пользователей: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018-й год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше. | accuracy, scipy, p-value |
| 4 | [Cборный проект 1. Анализ рынка видеоигр](https://github.com/romanmvch/Portfolio/tree/main/Videogame_market_analysis) | Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Требуется выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.|python, EDA|
| 5 | [Прогнозирование оттока клиентов банка](https://github.com/romanmvch/Portfolio/tree/main/Bank_customer)| Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет на основе исторических данных о поведении клиентов и расторжении договоров с банком.| F1, AUC-ROC |
| 6 | [Выбор локации для скважины](https://github.com/romanmvch/Portfolio/tree/main/Best_well_location) | Нужно решить, где бурить новую скважину. Вам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Постройте модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap. | Bootstrap |
| 7 | [Cборный проект 2. Извлечение золота](https://github.com/romanmvch/Portfolio/tree/main/Gold_extraction) | Требуется построить прототип модели машинного обучения. Компания разрабатывает решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В вашем распоряжении данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. | и с выравниванием по центру |
| 8 | [Защита персональных данных клиентов](https://github.com/romanmvch/Portfolio/tree/main/Personal_data) |Необходимо защитить данные клиентов страховой компании. Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.| Linear algebra |
| 9 | [Определение стоимости автомобилей](https://github.com/romanmvch/Portfolio/tree/main/Autos_sales) |Сервис по продаже автомобилей с пробегом разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. Требуется построить модель, которая умеет её определять. Критерии, которые важны заказчику: качество предсказания; время обучения модели;время предсказания модели.| CatBoost|
| 10 | [Прогнозирование заказов такси](https://github.com/romanmvch/Portfolio/tree/main/Taxi) |Компания собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания. Значение метрики RMSE на тестовой выборке должно быть не больше 48.| Временные ряды |
| 11 | [Классификация комментариев](https://github.com/romanmvch/Portfolio/tree/main/Comment_classification) |Интернет-магазин запускает новый сервис: пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.| nltk, spacy, TfidfVectorizer |
| 12 | [Финальный проект](https://github.com/romanmvch/Portfolio/tree/main/Steel_processing%20(final%20project))| Чтобы оптимизировать производственные расходы, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. Вам предстоит построить модель, которая предскажет температуру стали. |  |

<h2 align="center">Kaggle</h2>

| №| Название проекта| Описание | Стек |
|:-:| :-:|:-:|:-:|
| 1 | [Анализ продаж магазинов](https://github.com/romanmvch/Portfolio/tree/main/Stores_Sales)|Анализ параметров, оказывающих влияние на продажи магазина.|  |
| 2 | [Students Adaptability]([https://github.com/romanmvch/Portfolio/tree/main/Stores_Sales](https://github.com/romanmvch/Portfolio/tree/main/Students_Adaptability) |Анализ параметров, оказывающих влияние на продажи магазина.|  |

<h2 align="center">МГТУ Баумана</h2>

| №| Название проекта| Описание | Стек |
|:-:| :-:|:-:|:-:|
