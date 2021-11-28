## Описание класса Vehicle
**Vehicle** - класс, представляющий спецтехнику, которая числится в центре спецтехники.
# Атрибуты
- **ID**: int
- **CategoryOfVehicle**: [CategoryOfVehilce](https://github.com/dedneded/UML-Diargam/blob/main/Information/CategoryOfVehicle.md)
- **IsNeedDelivery**: bool
- **BrandAndModel**: string
- **YearOfIssue**: DateTime
- **GosNum**: string
- **Mass**: int
- **AvgGas**: double
- **AvgSpeed**: int
- **ShipmentTime**: int
- **DrivingCategory**: DrivingCategories
- **PricePerHour**: decimal
- **Branch**: [Branch](https://github.com/dedneded/UML-Diargam/blob/main/Information/Branch.md)
- **Comment**: string
# Описание атрибутов
- **ID** - идентификатор в БД
- **CategoryOfVehicle** - категория техники
- **IsNeedDelivery** - атрибут, показывающий нуждается ли спецтехника в доставке
- **BrandAndModel** - бренд и модель техники
- **YearOfIssue** - дата выпуска
- **GosNum** - госномер
- **Mass** - масса
- **AvgGas** - средний расход бензина
- **AvgSpeed** - средняя скорость
- **ShipmentTime** - время, занимающая погрузка/отгрузка 
- **DrivingCategory** - категории прав, которые необходимы для вождения данной техники
- **PricePerHour** - стоимость аренды в час
- **Branch** - филиал, где числится данная техника
- **Comment** - дополнительная информация о технике
