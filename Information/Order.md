## Описание класса Order
**Order** -  класс, представляющий собой заказ, связанный с оказанием услуг спецтехники.
# Атрибуты
- **ID**: int
- **Start**: DateTime
- **End**: DateTime
- **Client**: Client
- **Price**: decimal
- **ByCas**: bool
- **Status**: Status
- **Distance**: int
- **Address**: string
- **Branch**: Branch
- **Employee**: Employee
- **Comment**: string
- **DiscountPare**: Dictionary<CategoryOfVehicle, Discount>
# Описание атрибутов
- **ID** - идентификатор в БД
- **Start** - начало заказа
- **End** - окончание заказа
- **Client** - клиент, которому будут оказываться услуги
- **Price** -  общая стоимость всех услуг
- **ByCas** - способ оплаты
- **Status** - статус заказа
- **Distance** - расстояния до адреса клиента(если нужна доставка)
- **Address** -  адрес клиента
- **Branch** - филиал, в котором принята заказ
- **Employee** - менеджер, который принял заказ
- **Comment** - комментарий к заказу
