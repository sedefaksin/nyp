                    +----------------+
                    |    Building    |
                    +----------------+
                    | - floors       |
                    | - elevators    |
                    +----------------+
                    | + addFloor()   |
                    | + addElevator()|
                    +----------------+
                             ^
                             |
               +-------------+-------------+
               |                           |
         +-------------+            +----------------+
         |   Elevator  |            |   Floor        |
         +-------------+            +----------------+
         | - id        |            | - number       |
         | - capacity  |            | - doors        |
         | - position  |            | - arrivalBell  |
         | - direction |            | - signalLight  |
         | - doorsOpen |            | - callButtons  |
         +-------------+            +----------------+
         | + move()    |            | + pressButton()|
         | + openDoors()|            +----------------+
         | + closeDoors()|
         +-------------+
