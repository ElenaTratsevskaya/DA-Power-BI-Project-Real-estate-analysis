# DA-Power-BI-Project-Real-estate-analysis
Коммерческий проект: Создание интерактивной панели мониторинга / Create an interactive dashboard

**Постановка задачи**<br>
Целевая аудитория - владельцы недвижимости, сдающие свои объекты в аренду посуточно для туристов.  Вам нужно создать интерактивную панель мониторинга, которая позволит владельцу недвижимости определить, является ли его цена конкурентоспособной, и дать ему представление о том, как оптимизировать свою ценовую стратегию. <br><br>

**Интерактивный дашборд в загруженном файле**<br>
<br>
**Основные принципы в основе визуализации исходных данных**<br><br>
**Лист "характеристика объектов"**<br>
содержит в себе визуализации средней цены от следующих характеристик:<br>
**los** - количества ночей<br>
**maxoccupancy** - количество гостей, <br>
**roomtype** - типа номера,<br> 
**roomamenities** - атрибут номера<br>
Также выведена карточка с количеством номеров, которая позволяет увидеть сколько номеров соответствует каждой из перечисленных выше характеристик.<br>
Лист дополнена многострочной карточкой со списком отелей, что даёт возможность оперативно соотнести вышеуказанные данные с конкретным отелем.<br><br>
![Аналитический дашборд(1)](https://user-images.githubusercontent.com/110056199/223748381-5ae4a5fb-1aa4-4bf4-b38e-e039dac8b327.jpg)<br><br>


<span style="color:#006400">**Лист "характеристика объектов**</span>
<br>
содержит в себе визуализации средней цены от следующих характеристик:<br>
**los** - количества ночей, <br>
**maxoccupancy** - количество гостей, <br>
**roomtype** - типа номера, <br>
**roomamenities** - атрибут номера<br>
Также выведена карточка с количеством номеров, которая позволяет увидеть сколько номеров соответствует каждой из перечисленных выше характеристик.<br><br>
*Примечание:* в целом линия тренда базового и общего тарифа схожи, поэтому для снижения визуальной нагрузки в некоторых диаграммах использован только базовый тариф. Для выполнения действия “сравнение” важно, чтобы группы показателей применялись корректно и не происходило попадания в сравнительные данные информации из разных групп цены, т.е. базовая цена сравнивается с базовой, общая -  с общей по объектам.<br><br>
Лист дополнена многострочной карточкой со списком отелей, что даёт возможность оперативно соотнести вышеуказанные данные с конкретным отелем.<br><br>
![Аналитический дашборд(5)](https://user-images.githubusercontent.com/110056199/223749115-5fd99eb4-4da9-4bb0-b206-7b9650c9bc75.jpg)
<br><br>

**Лист "геолокация"**<br>
содержит визуализацию с привязкой к адресам.<br>
Диаграмму и карту по 10 объектам, а также дополнительная карта со всеми объектами из таблицы с описанием объектов.<br>
Кроме этого выведен фильтр по рейтингу.<br>
Страница дополнена многострочной карточкой со списком отелей, что даёт возможность оперативно соотнести вышеуказанные данные с конкретным отелем.<br>
Общее примечание: каждая страница снабжена фильтром по id.<br>
Многострочной карточкой названий объектов для удобства переключения и поиска объекта.<br><br>

![Аналитический дашборд(6)](https://user-images.githubusercontent.com/110056199/223750344-5baf0106-6d13-4d61-b4f8-b97b31e86d80.jpg)<br><br>

**Д О П У Щ Е Н И Е!** на листе отчёта “Заключение” изложен алгоритм проведения процедуры сравнения параметров объекта клиента с исходными параметрами объектов.<br>
Я не придумала, как мне получить объект клиента с конкретными параметрами для проведения сравнения.<br> 
Взят объект с id 1312730 и, добавила к id букву “А” (далее это обозначение объекта клиента), вынесла данные в отдельную таблицу 1312730_A, загрузила данную таблицу так же, как и исходные файлы, добавив “А” в два показателя: базовой и общей цены.<br><br>

**Лист "Заключение"**<br>
содержит матрицу с основными параметрами объекта клиента, график динамики средней базовой цены по датам и алгоритм сравнения параметров объекта недвижимости клиента с исходными.<br><br>
![Аналитический дашборд(7)](https://user-images.githubusercontent.com/110056199/223751582-b6a6176f-0a71-4a1e-a72a-31ec6b8b1715.jpg)





