## Описание класса ServiceInOrder
**ServiceInOrder** - класс связывающий услугу и заказ. Нужен для того, чтоб была возможность регулировать количество одной и той же услуги в заказе.
# Атрибуты
- **ID**: int
- **Service**: [Service](https://github.com/dedneded/UML-Diargam/blob/main/Information/Service.md)
- **Driver**: [Driver](https://github.com/dedneded/UML-Diargam/blob/main/Information/Driver.md)
- **Vehicle**: [Vehicle](https://github.com/dedneded/UML-Diargam/blob/main/Information/Vehicle.md)
- **DeliveryVehicle**: [Vehicle](https://github.com/dedneded/UML-Diargam/blob/main/Information/Vehicle.md)
- **DeliveryDriver**: [Driver](https://github.com/dedneded/UML-Diargam/blob/main/Information/Driver.md)
- **Start**: DateTime
- **End**: DateTime
- **StartFrom**: DateTime
- **EndFrom**: DateTime
- **Price**: decimal
# Описание атрибутов
- **ID** - идентификатор в БД
- **Service** - услуга в заказе
- **Driver** - водитель, выполняющий услугу "Водитель"
- **Vehicle** -  техника, выполняющая услугу "Аренда"
- **DeliveryVehicle** - техника, выполняющая услугу "Доставка"
- **DeliveryDriver** - водитель, выполняющий услугу "Доставка"
- **Start** - начало оказания услуги
- **End** - окончание оказания услуги
- **StartFrom** - начало доставки от клиента
- **EndFrom** - окончание доставки от клиента
- **Price** - стоимость оказания услуг
