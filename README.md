# GP 2. The way of diabetes overcoming.
### Team 29

Групповой проект, выполненный командой 29 с составом: Десятникова Алиса, Казакова Алёна, Полетаева Кристина, Филюшкина Ксения группа 226

Файлы полученные после 1 этапа:
drug_pages_solo.zip,
page_expanded.html,
ATC_categories_diabitis.csv,
ATC_categories_full.csv


Файлы полученные после 2 этапа:
update drug_pages_solo.zip


Файлы полученные после 3 этапа:
all_drug_info.csv


Файлы полученные после 4 этапа:
data_for_eda


### Описание признакогв из таблицы, с которой мы работали в итоге в EDA:
**Краткий обзор набора данных features_data.csv**

Наш набор данных features_data.csv содержит информацию о различных кодах ATC и связанных с ними атрибутах.

**Ключевые атрибуты включают:**

* ATC, ATC_info, ATC_hierarchy: Идентификаторы и классификации.
* used_in_diabetes: Булевый флаг для актуальности при диабете.
* Mechanism of Action, Targets, Indication: Подробные текстовые описания.
* Категориальный признак: indication_category
* Количественные признаки:
  * num_dfg,	num_ingridients - число способов применения (групп к которым относят лекарства по способу применения), число ингридиентов
  * number_of_children, num_targets, mechanism_complexity.
  * Средние метрики сходства и совпадения: avg_mechanism_similarity, avg_target_overlap.

* Булевые флаги для пропущенных данных: Например, missing_mechanism, missing_targets.

