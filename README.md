Брокер сообщений - это отдельное приложение, которое пересылает сообщения между другими приложениями.

Зачем они нужны и почему приложение не может напрямую передать данные в другое приложение?

Брокер сообщений позволяют убрать жесткую связь и стандартизировать механизмы общения.

Клиенты брокера могут быть двух типов: поставщики сообщений и потребители сообщений. В большинстве случаев одно и то же приложение сразу осуществляют роль поставщика и потребителя.

Отличительной чертой общение через брокер является асинхронность событий, то есть сообщение отправляется без ожидания подтверждения его доставки до потребителя.

Рассмотрим пример. Вы звоните другу по телефону и ждете его ответ. Это синхронное действия. Вам и другу нужны быть у аппарата в одно и то же время.

Если у друга установлен автоответчик, то вы можете оставить сообщение автоответчику и положить трубку. Друг придет и прослушает сообщение, когда у него будет возможность. Это асинхронное действие. Вы и друг выполняют отправку и прием сообщения в разное время.