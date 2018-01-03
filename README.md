# caharte.github.io


![Alt text](https://g.gravizo.com/source/custom_mark1?https%3A%2F%2Fraw.githubusercontent.com%2caharte%2Fcaharte.github.io%2FREADME.md?1)
<details> 
<summary></summary>
custom_mark13
@startuml;
actor User;
participant "First Class" as A;
participant "Second Class" as B;
participant "Last Class" as C;
User -> A: DoWork;
activate A;
A -> B: Create Request;
activate B;
B -> C: DoWork;
activate C;
C -> B: WorkDone;
destroy C;
B -> A: Request Created;
deactivate B;
A -> User: Done;
deactivate A;
@enduml
custom_mark13
</details>

