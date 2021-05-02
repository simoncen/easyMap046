# easyMap046
Potato Interactive Development Group Geographic Information System Mapping App that runs on Linux OS.

## M2: Visualizing Interactive easyMap
### Map Selector
* Load a new map by clicking the Draw Map button and select Toronto, Canada.
<img width="870" alt="Screen Shot 2021-05-01 at 5 49 39 PM" src="https://user-images.githubusercontent.com/56233967/116795812-9ae5a880-aaa5-11eb-8ad8-b949ba3346a4.png">
<img width="832" alt="Screen Shot 2021-05-01 at 5 52 10 PM" src="https://user-images.githubusercontent.com/56233967/116795857-f4e66e00-aaa5-11eb-91b5-cc81fb568c0d.png">

### Find Distance
* Calculate the Euclidean distance between two selected points on the map.
<img width="1134" alt="Screen Shot 2021-05-01 at 5 53 18 PM" src="https://user-images.githubusercontent.com/56233967/116795881-219a8580-aaa6-11eb-980f-4189c7274bc8.png">

### Subways
* Check out the subway lines and stations.
<img width="615" alt="Screen Shot 2021-05-01 at 5 57 47 PM" src="https://user-images.githubusercontent.com/56233967/116795963-bdc48c80-aaa6-11eb-88b3-b09d52f676eb.png">
<img width="616" alt="Screen Shot 2021-05-01 at 5 58 54 PM" src="https://user-images.githubusercontent.com/56233967/116795990-e5b3f000-aaa6-11eb-8281-c188e21a215b.png">

### Find Street & Highlight Intersection
* Find the intersection entered on the textbar and look for its information.
<img width="745" alt="Screen Shot 2021-05-01 at 6 00 11 PM" src="https://user-images.githubusercontent.com/56233967/116796002-15fb8e80-aaa7-11eb-949f-d08fc77a9e4b.png">

### POI Filter
* Select the point of interests(POI) you want to see.
* You can check out the animation:
  https://user-images.githubusercontent.com/56233967/116796192-b8684180-aaa8-11eb-93e1-c3106669ff72.mov
<img width="1127" alt="Screen Shot 2021-05-01 at 6 06 06 PM" src="https://user-images.githubusercontent.com/56233967/116796094-e7ca7e80-aaa7-11eb-974b-596ce6487a0d.png">

### Help Button
* Learn more about the easyMap
<img width="823" alt="Screen Shot 2021-05-01 at 6 26 53 PM" src="https://user-images.githubusercontent.com/56233967/116796488-ce770180-aaaa-11eb-8868-cc042d2d572f.png">

## M3: Finding the Optimal Path
A* algorithm is utilized to find the optimal path between two points on the map.

* Click on two points on the map or type out the streetnames that make up the intersection you are seeking for.
<img width="963" alt="Screen Shot 2021-05-01 at 6 16 02 PM" src="https://user-images.githubusercontent.com/56233967/116796282-4b08e080-aaa9-11eb-83b6-052949363f9d.png">
- Clear view of the path.
<img width="963" alt="Screen Shot 2021-05-01 at 6 16 02 PM" src="https://user-images.githubusercontent.com/56233967/116796282-4b08e080-aaa9-11eb-83b6-052949363f9d.png">
- Simulate your travel (see directions): 
  https://user-images.githubusercontent.com/56233967/116796435-61fc0280-aaaa-11eb-902c-8713ce445f75.mov
  
## M4: Traveling Courier
Embedded system to find the optimal path for a delivery routed.
Depot -> Pickups -> Drop-offs -> Depot
* Multi-Dijkstra, Greedy algorithms, simulated annealing, and local permutation are utilized.
