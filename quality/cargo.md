# Cargo Quality Report
###_1.Stereotype statistic_
| Stereotypes | AggregateRoot | AggregatePart | Repository | Entity | ValueObjet | Service | Specification|  Event   |
| ----------- | ------------  | ------------- | ---------- | ------ | ---------- | ------- |  ----------  | -------- |
| Quantity    |1|0|2|4|4|1|0|0|
###_2.Violate Constraints_
|Error code|Class|Rule|
|----------|-----|----|
|102401|casestudy.cargo.DeliverySpecification|violate Must have Boolean-typed return Parameter|
402|casestudy.cargo.Cargo|violate Aggregate must contain at least one part|
###_3.Circle Dependency_ 
![cargo](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/thorgits/Image/master/quality/cargo.puml)

