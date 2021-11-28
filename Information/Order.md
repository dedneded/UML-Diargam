## Описание класса Order
**Order** -  класс, представляющий собой заказ, связанный с оказанием услуг спецтехники.
# Атрибуты
- **ID**: int
- **Start**: DateTime
- **End**: DateTime
- **Client**: [Client](https://github.com/dedneded/UML-Diargam/blob/main/Information/Client.md)
- **Price**: decimal
- **ByCash**: bool
- **Status**: Status
- **Distance**: int
- **Address**: string
- **Branch**: [Branch](https://github.com/dedneded/UML-Diargam/blob/main/Information/Branch.md)
- **Employee**: [Employee](https://github.com/dedneded/UML-Diargam/blob/main/Information/Employee.md)
- **Comment**: string
- **DiscountPare**: Dictionary<[CategoryOfVehilce](https://github.com/dedneded/UML-Diargam/blob/main/Information/CategoryOfVehicle.md), [Discount](https://github.com/dedneded/UML-Diargam/blob/main/Information/Discount.md)>
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
