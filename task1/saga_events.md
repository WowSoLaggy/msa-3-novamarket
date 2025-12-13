# Таблица-Реестр Событий Saga-Хореографии

| Этап | Тип События  | Название События   |
|------|--------------|--------------------|
| Выбор товара | Domain Event | item_added_to_cart |
| Оформление заказа | Domain Event | order_placed |
| Заказ зарезервирован | Domain Event | order_reserved |
| Заказ оплачен | Domain Event | payment_done |
| Заказ не зарезервирован | Failure Event | reserve_failed |
| Оплата не прошла | Failure Event | payment_failed |
| Оплаты не дождались | Timeout Event | payment_timeout |
