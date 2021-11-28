## Описание класса Vehicle
**Vehicle** - класс, представляющий спецтехнику, которая числится в центре спецтехники.
# Атрибуты
- **ID**: int
- **CategoryOfVehicle**: CategoryOfVehicle +IsNeedDelivery: bool
- **BrandAndModel**: string
- **YearOfIssue**: DateTime
- **GosNum**: string
- **Mass**: int
- **AvgGas**: double
- **AvgSpeed**: int
- **ShipmentTime**: int
- **DrivingCategory**: DrivingCategories
- **PricePerHour**: decimal
- **Branch**: Branch
- **Comment**: string
# Описание атрибутов
- **ID** - идентификатор в БД
- **CategoryOfVehicle** - категория техники
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
