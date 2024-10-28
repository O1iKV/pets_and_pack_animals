# pets_and_pack_animals
<i>Итоговая контрольная работа по блоку специализация</i> <p>
Систему учёта для питомника, в котором живут домашние и вьючные животные.</p><p></p><p>
 1. Используя команду <b>cat</b> в терминале операционной системы Linux, создать
 два файла <b>Домашние животные</b> (заполнив файл <i>собаками,кошками,
 хомяками</i>) и <b>Вьючные животными</b> (заполнив файл <i>лошадьми,верблюдами и
 ослы</i>), а затем объединить их. Просмотреть содержимое созданного файла.
 Переименовать файл, дав ему новое имя (<b>Друзья человека</b>).</p><p>
 
![1](https://github.com/user-attachments/assets/5dd430d4-77b3-4d5e-aee0-6d088080dd50)
<p> 2. Создать директорию, переместить файл туда.</p><p>
 
![2](https://github.com/user-attachments/assets/619788b1-ec13-4fb9-a139-a3cb076bfbb1)
<p> 3. Подключить дополнительный репозиторий MySQL. Установить любой пакет
 из этого репозитория.</p><p>
 
 ![3](https://github.com/user-attachments/assets/d12dc2dd-796e-4dda-b7d7-92f5fa6148d8)
<p> 4. Установить и удалить deb-пакет с помощью <b>dpkg</b>.</p><p>

 ![4](https://github.com/user-attachments/assets/15c0505e-dbee-4938-adb5-56a2dbd4e767)
<p> 5. Выложить историю команд в терминале <b>ubuntu</b>.</p><p>

 ![5](https://github.com/user-attachments/assets/3673f1a8-b02a-4613-a789-19a76c7b3244)
 <p> 6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние
 животныеивьючныеживотные,всоставыкоторыхвслучаедомашних
 животныхвойдутклассы: собаки, кошки, хомяки, а в класс вьючные животные
 войдут: Лошади, верблюдыиослы).</p><p>

![6 drawio](https://github.com/user-attachments/assets/174251f8-13eb-4a90-86fe-19b47fe554ee)
<p> 7. В подключенном MySQL репозитории создать базуданных <b>“Друзья человека”</b></p><p>
 
 ![7](https://github.com/user-attachments/assets/6afa344a-92ad-4d7a-8900-176aec2a6a55)
<p> 8. Создать таблицы с иерархией из диаграммыв БД</p><p>

 ![8](https://github.com/user-attachments/assets/40fdbb40-e5f7-41d5-86a9-3f154e7e05fd)
<p>  9. Заполнить низкоуровневые таблицы именами(животных), командами
 которые они выполняют и датами рождения</p><p>

![9](https://github.com/user-attachments/assets/ca854680-666a-4cfd-892d-b0e298d48957)
<p> 10. Удалив из таблицы верблюдов,т.к. верблюдов решилиперевезти вдругой
 питомник назимовку. Объединить таблицы лошади,и ослы в одну таблицу.

 ![10](https://github.com/user-attachments/assets/68feaded-570a-4243-a9eb-bb893016fa5f)
<p> 11.Создать новую таблицу <b>“молодые животные”</b> в которую попадут все
 животные старше 1 года,но младше 3лет и в отдельном столбце с точностью
 до месяца подсчитать возраст животных вновойтаблице</p><p>

![11](https://github.com/user-attachments/assets/fe1916ec-d10f-4528-bb31-2a377e4305d5)
<p> 12. Объединить все таблицы водну, приэтомсохраняяполя, указывающие на
 прошлую принадлежность к старым таблицам.</p><p>

![12](https://github.com/user-attachments/assets/04142e83-ead9-4e93-8555-73ae7d37242e)
<p> 13.Создать класс с Инкапсуляцией методов и наследованием по диаграмме.</p><p>
<p> 14. Написать программу, имитирующую работу реестра домашних животных.
 В программе должен быть реализован следующий функционал: Завести новое животное; 
 определять животное в правильный класс; увидеть список команд, которое выполняет животное;
 обучить животное новым командам; Реализовать навигацию по меню</p><p>
<p> 15.Создайте класс Счетчик, у которого есть метод <b>add()</b>, увеличивающий
 значение внутренней <i>int</i> переменнойна 1 принажатие <b>“Завести новое
 животное”</b> Сделайте так, чтобы с объектом такого типа можнобылоработатьв
 блоке <i>try-with-resources</i>. Нужно бросить исключение, если работа с объектом
 типа счетчик была невресурсномtry и/или ресурс остался открыт. Значение
 считать в ресурсе <i>try</i>, если при заведения животного заполнены все поля.</p>

![13-15](https://github.com/user-attachments/assets/e4697a95-fe3f-4fcc-85b7-12922f1e20a1)

 
