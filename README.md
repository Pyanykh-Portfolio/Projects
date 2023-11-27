# Портфолио: аналитик данных
## Обо мне 
Привет! Меня зовут Ирина Пьяных, я начинающий аналитик данных. Мне нравится работать с цифрами, искать взаимосвязи и программировать. В ближайшее время хочу освоить Python. 
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>
## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Системы управления базами данных: ``PostgreSQL``
- Средства визуализации данных: ``Metabase``, ``Excel``
## Проекты
<p> Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
Посчитать юнит-экономику и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность.
  <li>Задача №2.</li>
Исследовать данные о пользователях и их поведении.
</ol>
<p>Как решала: на основе финансовых данных рассчитала Retention, CAC, маржинальность, далее создала калькулятор для юнит-экономики, где определила средний Retention, LT, LTR, CAC и FC на юнит; для исследования поведения пользователей были построены различные сводные таблицы, а также был проведен анализ контента кинотеатра.<p>
> <a href="https://docs.google.com/spreadsheets/d/1mh3-5UvKLWhFeIKOK0lu5HT_ESRF5v0o/edit?usp=sharing&ouid=100455908590688858168&rtpof=true&sd=true">Ссылка на проект</a>
  
<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  Чтобы выйти на 25% маржинальность юнита (подписки), необходимо пересмотреть маркетинговую политику и стремиться привлечь минимум 4154 новых подписчиков, затратив на привлечение каждого максимум 1 578,17 рублей. Также стоит повысить базовую стоимость подписки на 14,29%, объём скидок можно сохранить на уровне 9,33%. Такой показатель как Retention следует увеличить до 90% (в этом могут помочь данные, полученные в ходе изучения поведения подписчиков и представленные на вкладке «Визуализация»).
  <li>Итог №2</li>
  Анализируя, графики, представленные на вкладке «Визуализация», можно сделать вывод, что следует пересмотреть текущий контент кинотеатра, поскольку только 72 фильма из более чем 5000 обеспечивают половину всех просмотров. Следует также дополнительно изучить предпочтения пользователей, находящихся в UTC 0, +1, +2, +3 (к этим часовым поясам относятся страны Африки, Европы и Северо-западная, Юго-Западная и Западная части России). Необходимо выяснить какие жанры они предпочитают, какие самые высокочастотные запросы вводят, и особое внимание уделить тем высокочастотным запросам, на которые в нашей базе фильмы отсутствуют. Также следует убедиться, что оборудование работает стабильно в пиковые моменты (особенно это касается вечера субботы). Выполнение данных рекомендаций должно положительным образом сказаться на лояльности существующих клиентов и повысить привлекательность онлайн-кинотеатра перед новыми подписчиками.
</ol>
<br> 
<p>Проект 2: Моделирование изменения балансов студентов</p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  Смоделировать изменение балансов студентов. Баланс — это количество уроков, которое есть у каждого студента. Важно понять сколько всего уроков было на балансе <strong>всех учеников</strong> за каждый календарный день и как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков). Сделать визуализации и на их основании собрать гипотезы.
  <li>Задача №2.</li>
  Создать таблицу, где будут балансы <strong>каждого студента</strong> за каждый день. Сделать визуализации и на их основании собрать гипотезы.
</ol>
<p>Как решала: вычислила дату первой транзакции для каждого студента (начиная с этой даты, аккумулируется баланс уроков), собрала список всех дат оплаты от всех студентов, далее создала для каждого студента список дат после первой транзакции, нашла все изменения балансов, связанные с успешными транзакциями, затем рассчитала баланс студентов, который сформирован только транзакциями, нашла изменения балансов из-за прохождения уроков и снова рассчитала баланс, сформировала единый баланс для каждого студента и для всех студентов. <p>

> <a href="https://github.com/Skyproportfolio/data-analytics-5month/blob/main/Проект%205.xlsx">Ссылка на проект</a>
<br>
(ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
  

 <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  В целом можно отметить положительную тенденцию на увеличение количества проходимых уроков студентами. 
К концу года накопилось достаточно много непройденных уроков (4534). Возможно, необходимо ввести дополнительную мотивацию для студентов для прохождения уроков. 
Активные всплески транзакций наблюдаются в осенне-зимний период, что означает, что в это время студенты более активны, а, значит, нагрузка на преподавателей выше. Также можно заметить, что оплаты происходят в основном в начале месяца, в связи с этим, различные акции на покупку уроков лучше проводить в этот период, так как людям проще расставаться с деньгами.
  <li>Итог №2</li>
  Исходя из полученных данных, можно сделать вывод, что некоторые студенты проходили не триальные уроки бесплатно. Об этом говорит отрицательный баланс уроков. Следует подробнее изучить данную ситуацию и обсудить ее с data-инженерами.
  </ol>
  
## Контактная информация
- Email: name@email.com
