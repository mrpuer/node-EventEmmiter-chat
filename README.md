# События EventEmmiter

* `npm start` to start application.

***

Доработать `chat.js`

## Часть 1

1.  Добавить обработчик события `message` для Чата Вебинара (`webinarChat`), который выводит в консоль сообщение 'Готовлюсь к ответу'. Обработчик создать в отдельной функции.
2.  Для Вконтакте (`vkChat`) установить максимальное количество обработчиков событий, равное 2.
3.  Добавить обработчик 'Готовлюсь к ответу' из пункта 1.1 к чату Вконтакте.

## Часть 2

1.  В классе чата `ChatApp` добавить метод `close`, который будет вызывать событие `close` (событие вызывается один раз, `setInterval` как в констукторе, не нужен).
2.  Для чата вконтакте (`vkChat`) добавить обработчик `close`, выводящий в консоль текст "Чат вконтакте закрылся :(".
3.  Вызывать у чата вконтакте метод `close()`.

## Дополнительное задание

1.  Добавить код, который через 30 секунд отписывает `chatOnMessage` от вебинара `webinarChat`.
2.  Разбить существующий код на модули, запускаемый файл должен быть `index.js` или `index.js`