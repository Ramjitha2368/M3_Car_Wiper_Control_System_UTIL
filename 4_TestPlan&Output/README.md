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

# OUTPUT IMAGES

## When the red led is "ON" the output will be
![red Led on](https://user-images.githubusercontent.com/101034610/168323785-9ae96080-0c9d-4068-b0c9-db761eaaab1a.png)

## When the green led is "ON" the output will be
![green Led on](https://user-images.githubusercontent.com/101034610/168323983-895709cf-16fa-46fb-992d-32fbbc0d13bd.png)

## When the Orange led is "ON" the output will be
![orange led on](https://user-images.githubusercontent.com/101034610/168324177-2803d366-6965-4f2a-9e8c-e3619fb90300.png)
