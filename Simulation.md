![SimStartEvent](./images/SimStartEventAll.png)

SemTalk Online includes the ability to use special simulation-specific Properties to analyze process flows. Behaviors of specific objects, or of execution flows, are analyzed to estimate variables such as waiting times and costs. Users can also customize these attributes to execute more sophisticated calculations, or to create custom dialogs related to dynamic behavior. 

EntryPoint Simulation Properties:
* Process Start and End Times
* Priority
* Distribultion Type
* Jobs
* Period
* WorkTime
* WorkTime2

Task Simulation Properties
* CostDriver
* Priority
* Distribultion Type
* WorkTime
* WorkTime2

SequenceFlow Association Simulation Properties
* TransportationTime
* FixedCost
* VariableCost
* Propability
* ConditionExpression
* Restart

Buffer Simulation Properties
* Capacity
* FixedCost
* InitialContents
* FlushTime
* FlushNumber

HumanResource Simulation Properties (Simulation Properties are edited in the OrgChart)
* Capacity
* Strategy
* SetUpTime
* FixedCost
* VariableCost

Right mouse click and select Properties on an EntryPoint, Task, Buffer or Association in a Business Process Diagram to access the Simulation Properties. Simulation Properties for HumanResources are found when you right mouse click on a HumanResource in an OrgChart.

![SimHumanRessources](./images/SimulationHumanResources.png)