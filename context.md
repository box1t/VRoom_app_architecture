# Контекст решения

## Контекстная диаграмма

```
@startuml
!include https://raw.githubusercontent.com/plantuml-stdlib/C4-PlantUML/master/C4_Container.puml


Person(user, "Пользователь")

System(sandbox_app, "VR-приложение", "Песочница проектирования дизайна квартиры")


Rel(user, sandbox_app, "Выбор и размещение объектов")
Rel(user, sandbox_app, "Взаимодействие с меню")
Rel(user, sandbox_app, "Перестановка и поворот объектов")
@enduml
```


![image](https://user-images.githubusercontent.com/113284506/233922910-ab90f38c-6a55-414c-a458-b27f56c065ed.png)



## Назначение систем
| Система | Описание |
|-------|---------|
| VR-приложение | Позволяет проектировать дизайн квартиры. Реализовано на основе MVC архитектуры. |

