# Модель прецедентів

![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/MAIN_MODEL.puml)


![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/USER_1.puml)


![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/MODERATOR_2.puml)


### ID: UC_1
- Назва: Створити обліковий запис
- Учасники: Користувач, Система
- Передумови: Відсутні
- Результат: Користувач зареєстрований у системі.
- Виключні ситуації: Відсутні  
### Основний сценарій:

![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC_1.puml)


### ID: UC_2.1
- Назва: Аналіз даних
- Учасники: Користувач, Система
- Передумови: UC_2.2
- Результат: Система відображає дані в інтерактивному виді.
- Виключні ситуації: Відсутні  
### Основний сценарій:

![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC21.puml)

### ID: UC_2.2
- Назва: Пошук даних
- Учасники: Користувач, Система
- Передумови: Відсутні
- Результат: Система відображає знайдену інформацію у базі даних.
- Виключні ситуації: Відсутні  
### Основний сценарій:

![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC22.puml)

### ID: UC_3
- Назва: Завантажувати дані.
- Учасники: Користувач, Система.
- Передумови: UC_2.1, можливо UC_2.2.
- Результат: Дані завантажені на носії Користувача.
- Виключні ситуації: Відсутні  
### Основний сценарій:

![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC3.puml)

### ID: UC_4
- Назва: Залишати коментарі.
- Учасники: Користувач, Система.
- Передумови: UC_2.1.
- Результат: Коментар прикріплений до набору даних.
- Виключні ситуації: Відсутні  
### Основний сценарій:

![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC4.puml)

### ID: UC_5.1
- Назва: Додати дані.
- Учасники: Менеджер, Система.
- Передумови: Відсутні
- Результат: Новий масив даних доданий до бази.
- Виключні ситуації: Відсутні  
### Основний сценарій:
![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC51.puml)

### ID: UC_5.2
- Назва: Оновлювати  дані.
- Учасники:  Менеджер, Система.
- Передумови: UC_2.1
- Результат: Дані оновлені.
- Виключні ситуації: Відсутні  
### Основний сценарій:
![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC52.puml)

### ID: UC_6
- Назва: Відповідати на коментарі.
- Учасники: Менеджер, Система.
- Передумови: UC_2.1
- Результат: Відповідь прикріплена до набору даних.
- Виключні ситуації: Відсутні  
### Основний сценарій:
![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC6.puml)

### ID: UC_7
- Назва: Оформлювати звіт.
- Учасники: Менеджер, Система.
- Передумови: UC_3
- Результат: Звіт прикріплений до набору даних.
- Виключні ситуації: Відсутні  
### Основний сценарій:
![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC7.puml)

### ID: UC_8
- Назва: Надавати права доступу.
- Учасники: Адміністратор, Система.
- Передумови: Відсутні.
- Результат: Користувач отримав права Модератора.
- Виключні ситуації: Відсутні  
### Основний сценарій:
![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC8.puml)

### ID: UC_9
- Назва: Авторизація.
- Учасники: Користувач, Система
- Передумови: UC_1
- Результат: Користувач авторизований.
- Виключні ситуації: Відсутні  
### Основний сценарій:
![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC9.puml)

### ID: UC_10
- Назва: Переглянути звіт.
- Учасники: Адміністратор, Система.
- Передумови: UC_7.
- Результат: Система відобразила звіт.
- Виключні ситуації: Відсутні  
### Основний сценарій:
![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/greg-sourse/obd/master/src/uml/UC10.puml)


