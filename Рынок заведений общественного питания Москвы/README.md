# Рынок заведений общественного питания Москвы

**Цель исследования:** провести исследование рынка Москвы, найти интересные особенности и презентовать полученные результаты, которые в будущем помогут в выборе подходящего инвесторам места для открытия кофейни

**Способ решения:** Проведение исследовательского анализа данных, распределение заведений по доступным критериям (категория, расположение, цена, рейтинг, количество мест и др) и их количественный анализ. Выделение признаков успешности заведения. Формулирование рекомендаций для открытия кофейни.

**Навыки и инструменты:** Python, Pandas, Plotly, Seaborn, визуализация данных

**Выводы:**
1. По количеству заведений лидируют категории кафе (28,3%), ресторан (24,3%), кофейня (16,8%), количество заведений остальных категорий не превышает 10%.
2. Медиана количества посадочных мест в заведениях общепита Москвы равна 79. Менее 25% заведений имеют меньше 40 или больше 143 посадочных мест.
3. Категории заведений различаются по количеству посадочных мест. Наибольшие медианы количества посадочных мест у ресторанов (90), баров и пабов (84), кофеен и столовых (по 80), заведений быстрого питания (75). Меньше мест у кафе (60), пиццерий (56) и булочных (52). Максимальное количество посадочных мест в некоторых заведениях превышает 1000, а минимальное составляет 1 место.
4. В Москве преобладают несетевые заведения - их 61,9%, а сетевых - 38,1%. Всего сетевых заведений: 3205, несетевых заведений: 5201. Несетевых заведений больше в 1.62 раза.
5. Несетевые заведения значительно преобладают среди кафе, ресторанов, баров, столовых и заведений быстрого питания. Сетевые с незначительным перимуществом преобладают среди кофеен, пиццерий и булочных.
6. Выбраны топ-15 популярных сетей в Москве, они занимают 25,5% рынка сетевых заведений. Количество заведений в этих сетях составляет от 120 в Шоколаднице до 27 в Му-Му. Проанализированы характеристики выбранных сетей (где известно): почти все они относятся к категории средних цен; большинство заведений в этих сетях имеют рейтинг выше 4, но ниже 4,5; самые популярные категории - кофейня, ресторан, пиццерия и кафе.
7. Наибольшее количество заведений - более 2000 расположено в Центральном административном округе. Наименьшее - в Северо-Западном административном округе, менее 500. В остальных округах находится от 600 до 900 заведений .
8. Средний рейтинг заведений разных категорий различается не очень сильно, от минимального 4 у заведений быстрого питания, до максимального 4,4 у баров и пабов.
9. Наивысший рейтинг у заведений Центрального административного округа.
10.  В топ 5 по количеству заведений входят Проспект Мира, Профсоюзная улица, проспект Вернадского, Ленинский проспект и Ленинградский проспект.
11. Выбраны улицы, на которых находится только один объект общепита. Таких улиц 458. Большинство из этих улиц находятся в Центральном административном округе. Большинство заведений, являющихся единственными на улице, являются кафе, ресторанами или кофейнями средней ценовой категории с рейтингом от 4 до 4,7
12. Средний чек самый высокий в центральном и западном административных округах. Самый низкий - в Юго-Восточном, Северо-Восточном и Южном административных округах.
13. Рейтинг заведений с более высоким средним чеком выше, чем с более низким
14. Самый высокий средний рейтинг и средний чек - в барах и ресторанах, самый низкий средний рейтинг и средний чек - в заведениях быстрого питания. В столовых самый низкий  средний чек, но при этом средний рейтинг.

**Рекомендации для открытия новой кофейни**

При формулировании рекомендаций будем считать, что заказчики не боятся конкуренции в этой сфере.  Рекомендации будут даны только на основании полученных при анализе результатов.

1. Рекомендуемые районы для открытия кофейни: Западный округ (самые высокие цены, но самый низкий рейтинг заведений), если наша кофейня получит высокие оценки, она будет выгодно выделяться. Однако стоит вначале исследовать причины низких рейтингов в этом районе. Также привлекательными для открытия кофейни являются Центральный округ (самые высокие цены и рейтинг заведений)или Юго-Западный округ (высокие цены и средний рейтинг). 
2.	Нежелательный район для открытия кофейни: Юго-Восточный (наименьшие рейтинги и стоимость кофе)
3.	При этом конкуренция в Центральном округе будем максимальной, так как там уже расположено больше всего кофеен. Конкуренция в Западном и Юго-Западном округах будет значительно ниже.
4.	При открытии кофейни следует ориентироваться на среднюю стоимость чашки капучино в округе. Для рекомендованных Центрального, Западного, Юго-Западного округов она составляет 187, 190 и 184 рубля, соответственно. 
5.	Круглосуточных кофеен меньше 5%, значит, они не пользуются спросом, не стоит выбирать такой график работы. 
6.	Следует запланировать не менее 40 посадочных мест, желательно около 80 мест, следует ориентироваться на этот показатель при выборе помещения.


Дополнительно следует изучить такие факторы, как плотность населения, проходимость на выбранной локации, целевая аудитория, конкуренты в непосредственной близости, цену аренды помещения и другие.
