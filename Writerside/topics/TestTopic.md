# TestTopic

Пишу что-то для заметок

<code-block lang="plantuml">
@startuml
actor Пользователь
participant "Веб-приложение" as App
participant "База данных" as DB

Пользователь -> App : Вводит логин и пароль
App -> DB : Проверяет учетные данные
DB --> App : Возвращает результат проверки
App --> Пользователь : Сообщает об успехе или ошибке
@enduml
</code-block>


![Логотип JetBrains](../images/completion_procedure.png)

