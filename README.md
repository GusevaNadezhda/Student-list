
# Student-list

<p fr-original-style="" style="margin-top: 0px; margin-bottom: 12px; color: var(--ui-sb-color-text-main); box-sizing: border-box; font-size: 16px; line-height: 22px;">Создана панель управления студентами в виде таблицы с фильтрами и сортировкой, а также формой добавления нового студента. </p>

<ol fr-original-style="" style="margin-top: 0px; margin-bottom: 1rem; box-sizing: border-box; font-size: 16px; line-height: 22px;">
<li fr-original-style="" style="box-sizing: border-box;">Студенты должны храниться в массиве. Данные из массива должны выводиться в табличном виде. Каждая строка таблицы содержит информацию об одном студенте</li>
<li fr-original-style="" style="box-sizing: border-box;">Для добавления студентов на странице должна выводиться форма с полями, соответствующими данным студента. Форма должна проходить валидацию по следующим правилам:
<ul fr-original-style="" style="margin-top: 0px; margin-bottom: 1rem; box-sizing: border-box; font-size: 16px; line-height: 22px;">
 <li fr-original-style="" style="box-sizing: border-box;"> все поля обязательны для заполнения после применения к значению метода trim()
 </li>
<li fr-original-style="" style="box-sizing: border-box;"> дата рождения находится в диапазоне от 01.01.1900 до текущей даты;
</li>
<li fr-original-style="" style="box-sizing: border-box;"> год начала обучения находится в диапазоне от 2000-го до текущего года.
</li>
</ul>
Валидация должна происходить после нажатия на кнопку «Добавить студента», расположенную под полями для ввода. Если валидация прошла успешно, то все поля очищаются, а новый студент добавляется в таблицу. В противном случае над кнопкой выводится информативные сообщения с описанием ошибок для пользователя. </li>
<li fr-original-style="" style="box-sizing: border-box;">При нажатии на ячейку заголовочной строки должна происходить сортировка по соответствующим полям студентов </li>
<li fr-original-style="" style="box-sizing: border-box;">Перед таблицей выведены фильтры. При любых изменениях в полях для фильтрации содержимое таблицы изменяется в соответствии с указанными фильтрами. Если указано несколько фильтров, то все они применяются к массиву студентов по очереди.</li>
<li fr-original-style="" style="box-sizing: border-box;">Добавьте возможность сохранения списка студентов на сервере. При запуске приложения должна быть выполнена проверка на наличие данных на сервере. Если данные есть, то нужно вывести список студентов на экран.</li>
</ol>


## Технологии
![HTML5](https://img.shields.io/badge/-HTML5-e34f26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572b6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-f7df1e?logo=javaScript&logoColor=black)

### Инструменты
<div>
<a href="https://getbootstrap.com/docs/3.4/javascript/" target="_blank"><img style="margin: 30px" src="https://profilinator.rishav.dev/skills-assets/bootstrap-plain.svg" alt="Bootstrap" height="50" /></a>
</div>

## Ссылки проекта

<p fr-original-style="" style="margin-top: 0px; margin-bottom: 12px; color: var(--ui-sb-color-text-main); box-sizing: border-box; font-size: 16px; line-height: 22px;">Перед запуском убедитесь, что вы установили Node.js версии 12 или выше. Для запуска сервера скачайте <a fr-original-style="" href="https://gusevanadezhda.github.io./Student-list/backend/" rel="noopener noreferrer" style="user-select: auto; text-decoration: none; box-sizing: border-box;" target="_blank"> папку backend с репозиторием </a> и выполните команду `node index`. Для остановки нажмите сочетание клавиш CTRL+C. Важно разделить папку запуска сервера и клиентской части.</p>

<p fr-original-style="" style="margin-top: 0px; margin-bottom: 12px; color: var(--ui-sb-color-text-main); box-sizing: border-box; font-size: 16px; line-height: 22px;">Ссылка для просмотра <a fr-original-style="" href="https://gusevanadezhda.github.io./Tool-for-protoType/" rel="noopener noreferrer" style="user-select: auto; text-decoration: none; box-sizing: border-box;" target="_blank"> Инструмента для разработчика</a></p>





