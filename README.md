## Изменения и исправления
- Добавлен ввод карты из консоли. При запуске следует написать `-f <path/to/file.txt>`.
- Проект можно собирать под windows. Для этого необходима установка библиотеки `raylib`.
- Исправлен zoom. Теперь приближение происходит к центру экрана.
- Исправлено переполнение `uint8_t` в функции `map_import`, которое могло вызвать ошибку в случае загрузки чанка, целиком состоящего из стрелочек одного типа.