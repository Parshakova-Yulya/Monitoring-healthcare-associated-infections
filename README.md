# Monitoring-healthcare-associated-infections
Рабочий проект &#9763; &#128105;&#8205;&#128188; &#128202; &#9877;
**Краткая информация по проекту:** Основную проблему нашего отдела на протяжении нескольких лет можно описать так: 
* *«Как проводить анализ заболеваемости инфекциями, связанными с оказанием медицинской помощи (ИСМП) в стационаре, где более 2000 коек из которых 200 реанимационных, при наличии всего 2 врачей-эпидемиологов?»*. 


Традиционными методами «поиска ИСМП» являются: 
* просмотр всех историй болезни пациентов с положительными результатами микробиологических исследований; 
* получение информации от лечащих врачей; 
* ежедневный мониторинг пациентов, находящихся в отделениях реанимации. 
В наших реальных условиях использование рутинных методов невозможно. Мы столкнулись с необходимостью создания системы "с загорающейся лампочкой", которая даст нам возможность оперативно отреагировать на ухудшение эпидемиологической обстановки в стационаре. 
**Задачи которые мы поставили:**
* разработать формы для ретроспективного и оперативного анализа


В рамках решения поставленных задач мной был разработан и частично внедрен (на данный момент) проект основанный на анализе результатов микробиологических исследований пациентов. 


**Основная идея проекта: поиск «критических точек» (отделения риска, вспышечная заболеваемость) для более детального анализа и проведения эпидемиологических расследований.**

* Для проведения ретроспективного анализа — **написан код на Python**, позволяющий создавать полноценные отчеты с описанием и выводами для дальнейшей передачи информации заинтересованным лицам (фармакологи, заместители главного врача по медицинской части). Данная часть проекта полностью внедрена в работу. Время, которое необходимо для проведения годового  рестроспективного анализа сократилось с 2 недель до 3 дней. 
* Для оперативного анализа — **разработан макет дашборда в Tableau Public** (для его внедрения, необходимо подключение соответствующих сотрудников it-отдела, имеющих доступ к написанию скриптов и редактированию форм для выгрузки данных и МИС).
*примечание* *здесь представлен самый первый вариант, который создавался на обезличенных, искусственных данных. В последствии код и дашборд редактировались с использованием реальных данных, публикация которых невозможна (содержит данные, которые являются конфиденциальными,  "врачебной тайной", содержат персональные данные врачей и пациентов.)*
