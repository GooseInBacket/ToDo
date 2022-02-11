# ToDo. Приложение "Список задач"
## Предварительные настройки
###**В проекте используется Python 3.10!**  
Для того, чтобы запустить приложение ToDo Вам необходимо выполнить несколько простых манипуляций:

* Установить виртуальное окружение `python -m venv env`
* Перейти и выполнить `cd env/scripts/activate.bat`
* Установить зависимости `pip install requirements.txt `
* Если всё прошло успешно, то приложение готово к использованию

###Возможные ошибки:
Если у вас ошибка в активации activate.bat через PowerShell, то  
в системном PS вы можете выполнить следующую команду `Set-ExecutionPolicy RemoteSigned`

##Описание приложения
Приложение "Список задач" позволяет планировать своё время и продуктивнее выполнять поставленные задачи.  
Для это в приложении реализована функция списков задач. 
* **Мой день** - задачи, которые вы можете распределить на текующий день (✅ - реализовано)
* **Важно** - задачи, которые вы выделяете по степени важности (доступно из контектсного меню) (✅ - реализовано)
* **Запланировано** - Задачи, которые Распределяются по дата создания (❌ - в разработке)
* **Все** - задачи собранные со всех списков задач (✅ - реализовано)
* **Завершенные** - задачи, которые переведены в статус завершенные (✅ - реализовано)
* **Назначить мне** - задачи, которые выделены специально для вас (✅ - реализовано)
* **Задачи** - отдельный список, в котором вы можете хранить важные для вас задачи (✅ - реализовано)

##Возможности
* Возможность настроить цвет интерфейса
* Возможность настроить размер иконок
* Планируется настройка шрифта
* Возможность добавить собственный список задач
* Возможность удалять, добавлять, изменять задачи
* Вызов контектсного меню для удобстава использоваия

