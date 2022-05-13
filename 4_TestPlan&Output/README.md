# TestCases
## Highlevel Testcases

|Test condition |Inputdata |Expected result |Result Obtained|
|---------------|----------|----------------|---------------|
|when water is present |Amount of water is high  from 2.5v-4v |Turn on wiper accordingly |Water availability checked & motor is in on mode after voltage>2.5&<=4v|        
|when water is present |Amount of water is high  from 4v-5v |Turn on wiper accordingly  |Water availability checked & motor is in on mode after voltage>4v&<=5v|

## Lowlevel Testcases

|Test condition |Inputdata |Expected result |Result Obtained|
|---------------|----------|----------------|---------------|
|when water is present |Amount of water is low from lessthan 1v |Turn off wiper accordingly |Water availability checked & motor is in off mode after voltage<1v|        
|when water is present |Amount of water is low from1v-2.5v |Turn on wiper accordingly  |Water availability checked & motor is in on mode after voltage>1&<=2.5v|
