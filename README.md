# Диаграммы UML
Здесь собраны диаграммы UML для проекта: «Прокат спецтехники».

**Цель программы** - Автоматизация выполнения различных видов деятельности в центре проката спецтехники для повышения эффективности работы центра и наблюдения за статистическими показателями. Задачи, которые должна решать программа:

- Удобное формирование и изменение заявок на оказание услуг, связанных с прокатом спецтехники
- Отслеживание принятых заявок
- Ведение учета сотрудников и спецтехники
- Управление списков предоставляемых услуг
- Проведение анализа деятельности(формирование статистики за периоды времени).
Приложение доступно [в данном репозитории](https://github.com/dedneded/VehicleRentalService).

## Описание бизнес-процесса:
1) Клиент звонит по телефону или приходит в филиал.
2) Менеджер дабавляет клиента в базу, если он ранее не пользовался услугами центра.
3) Менеджер формирует заказ. Согласовывав с клиентом, менеджер указывает технику, которая будет браться в аренду, сроки аренды, информацию о доставке(если она необходима), дополнительные услуги(по желанию клиента), скидку(если клиент попадает под льготные условия), комментарий(если он необходим).
4) После согласования заказа, клиент должен оплатить заказ в течение 24 часов, в противном случае заказ становится отмененным.
5) Заказ становится активным, техника и доставка забронированными
6) Если техника не требует доставки и услуги водителя, то клиент сам забирает технику с центра. Если же доставка нужна, то техника доставляется на адрес(статус заказа доставка туда), доставщик возвращается на стоянку, если время доставки техники(туда-обратно) не превышает времени аренды, то доставщик остается ждать окончания аренды.
7) Техника отрабатывается арендованное время(статус заказа аренда), а после ее забирает доставка(статус заказа доставка обратно)
8) Техника доставляется обратно в центр, заказ закрывается, становится выполненным
## Диаграмма прецедентов
![UseCaseDiagram](https://github.com/dedneded/UML-Diargam/blob/main/Images/UseCaseDiagram.png)
## Диаграмма классов
![ClassDiagram](https://github.com/dedneded/UML-Diargam/blob/main/Images/ClassDiagram.png)
### Список классов
- [Person](https://github.com/dedneded/UML-Diargam/blob/main/Information/Person.md)
- [Client](https://github.com/dedneded/UML-Diargam/blob/main/Information/Client.md)
- [Employee](https://github.com/dedneded/UML-Diargam/blob/main/Information/Employee.md)
- [Driver](https://github.com/dedneded/UML-Diargam/blob/main/Information/Driver.md)
- [Role](https://github.com/dedneded/UML-Diargam/blob/main/Information/Role.md)
- [Permission](https://github.com/dedneded/UML-Diargam/blob/main/Information/Permission.md)
- [TimetableEmployee](https://github.com/dedneded/UML-Diargam/blob/main/Information/TimetableEmployee.md)
- [Order](https://github.com/dedneded/UML-Diargam/blob/main/Information/Order.md)
- [OrderLog](https://github.com/dedneded/UML-Diargam/blob/main/Information/OrderLog.md)
- [Service](https://github.com/dedneded/UML-Diargam/blob/main/Information/Service.md)
- [ServiceInOrder](https://github.com/dedneded/UML-Diargam/blob/main/Information/ServiceInOrder.md)
- [Vehicle](https://github.com/dedneded/UML-Diargam/blob/main/Information/Vehicle.md)
- [CategoryOfVehilce](https://github.com/dedneded/UML-Diargam/blob/main/Information/CategoryOfVehicle.md)
- [Branch](https://github.com/dedneded/UML-Diargam/blob/main/Information/Branch.md)
- [TimetableBranch](https://github.com/dedneded/UML-Diargam/blob/main/Information/TimetableBranch.md)
- [Discount](https://github.com/dedneded/UML-Diargam/blob/main/Information/Discount.md)
## Диаграмма состояний
![StatechartDiagram](https://github.com/dedneded/UML-Diargam/blob/main/Images/statechart.png)
Данная диаграмма описывает состояния заказа. В коде программы состояния хранятся в виде enumeration.
## Диаграмма деятельности
![ActivityDiagram](https://github.com/dedneded/UML-Diargam/blob/main/Images/activity_diagram.png)
Данная диаграмма описывает процесс выполнения заказа.
## Диаграмма последовательности
### Добавление водителя
![SequenceDiagramAddDriver](https://github.com/dedneded/UML-Diargam/blob/main/Images/SequenceDiagram_AddDriver.png)
Данная диаграмма показывает процесс добавления водителя в программе.
### Создание заказа
[Данная диаграмма](https://github.com/dedneded/UML-Diargam/blob/main/Diagram/SequenceDiagram_AddOrder.vsdx) показывает процесс создания заказа в программе.
## Диаграмма коммуникаций
![CommunicationDiagram](https://github.com/dedneded/UML-Diargam/blob/main/Images/CommunicationDiagram_AddClient.png)
Данная диаграмма описывает процесс добавления в каталог нового клиента.
## API
### Внимание! Диаграммы представленные ниже не полностью реализованы в самом проекте. Это пример того, как выглядело бы взаимодействие с системой, если бы разработка осуществлялась с помощью API.  
## Схема endpoint'ов  
![ComponentDiagram1](https://github.com/dedneded/UML-Diargam/blob/main/Images/Сomponentdiagram.png)
<hr>

## Диаграмма интерфейсов
![InterfaceDiagram](https://github.com/dedneded/UML-Diargam/blob/main/Images/Interface%20diagram.png)


