[[Component]]
[[Global context]]

`Модульность:`
- повышает `переиспользование` кода
- упрощает интеграцию компонентов
- улучшает компоновку и тестирование программ по частям
`Ограничения:`
- `модули` не должны использовать `глобальные переменные`, модифицировать базовые `классы/прототипы/функции ЯП`, платформы и/или фреймворка
- `модули` должны быть `слабо связаны`, а взаимодействовать друг с другом должны через `внешнее API` или `шину событий`