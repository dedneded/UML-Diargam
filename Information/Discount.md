## Описание класса Discount
**Discount** - класс, представляющий скидки, доступные в центре проката спецтехники.
# Атрибуты
- **ID**: int
- **Name**: string
- **Start**: DateTime
- **End**: DateTime
- **PriceModifier**: decimal
- **IsOptional**: bool
- **Branch**: [Branch](https://github.com/dedneded/UML-Diargam/blob/main/Information/Branch.md)
# Описание атрибутов
- **ID** - идентификатор в БД
- **Name** - нименование скидки
- **Start** - время начала действия скидки
- **End** - время окончания действия скидки
- **PriceModifier** - размер скидки
- **IsOptional** - атрибут, показывающий актуальность скидки(Например, скидка в день рождения - это optional, а скидка на новый год - это not optional)
- **Branch** -  филиал, в котором действует скидка
