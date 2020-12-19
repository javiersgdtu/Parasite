# Parasite
PARASITE film Datasets.

In **scenes.csv** you can find the whole film described. Each row represents a character in a location/sublocation during a time range. Columns:

* **scene**: I divided the film into several scenes or moments. 
* **description**: Brief description of main action(s) in the time range.
* **location**: Location where the scene takes place: *Kim's House*, *Park's House*...
* **sublocation**: Used in some locations to detail in which room the action is taking place. 
* **character**: Character performing the action in the time range.
* **Selection starts**: Time when the action described starts. Time format (H:MM:SS)
* **Selection ends**: Time when the action described finishes. Time format (H:MM: SS)
* **Diff.**: Selection ends - Selection starts (in seconds)
* **State**: To tell when a character die. Categorical: *death*, *unconscious*. 
* **Movement**: To describe the movement of a character in the time range. A character can perform several movements within a time range. Categorical: *Move, Up, Down, Static, Down, Hiding*. This variable is only present in Park’s house. As the dataset [was created for this viz project]( https://javiersgvisual.online/src/Parasite/main.html) 
* **Note**: notes on certain rows.

In **characters.csv** you can find information about the main characters that appear in the film. The Columns there are self-explanatory.


