# majordomo-sysinfo

Модуль сбора системной информации:
- загрузка CPU;
- использование RAM, диска;
- uptime.

Пока это все параметры, но собираемые данные будут расширятся.

В Object linked указывается имя объекта в котором будут заполняться поля с данными
Далее можно в классе объекта добавить поля для которых нужна история, и указать период хранения истории
И если необходимо, можно навесить на изменение поля свой метод (например при уменьшении свободного места на диске ниже порога выдать уведомление)

[Страница](https://connect.smartliving.ru/tasks/97.html)

[Форум](https://mjdm.ru/forum/viewtopic.php?f=5&t=4998&start=80)



SystemInfo

Системное имя модуля: sysinfo

Дополнение SystemInfo

![](https://connect.smartliving.ru/cms/data_images/85_image.png)
