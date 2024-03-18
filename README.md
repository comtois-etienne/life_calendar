# life calendar
A weekly life calendar generated from a json file.

There are 2 types of activities named `events` and `journeys`.  

- `Journeys` have a `start` and `end` date in the json file. Up to 4 journeys can share the inside of a week box. 

- `Events` only have a `start` date in the json file. Only one event can be displayed around a week box.  

Note : The rendering is sub-optimal and takes about 20sec on a MBA-M1.  

![life.png](life.png)