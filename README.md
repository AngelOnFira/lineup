# Lineup

#### Streamlined discord event management

Manage your events with lineup. Create events and hold more organized Q&A sessions among a group!

#### **Administrator commands**

**These commands are only available to those in a server with admin privileges OR those who have the role "Host". Please ensure that all who'll need use of these functions have admin privileges.**

**.begin**</u> (*String [event_name]*)

Starts an event with name [*event_name*]

**.end** (*int [event_id]*)

Ends event with id [*event_id*]

**.clear** (*int [event_id]*)

Clears all questions in event with id [*event_id*]

**.resolve** (*int [question_index]*)

Resolves and removes question from queue with given index [*question_index*]

**.move** (*int [position_1] int [position_2]*)

Moves question in queue at [*position_1*] to [*position_2*]



#### Universal commands

**These commands are available to anyone in the server**

**.help**

Displays all commands 

**.list_events**

Displays a list of all current events taking place on the server

**.queue** (*int [event_id]*)

Displays the queue of a given event with id [*event_id*]

**.enter** (*int [event_id]* *String [topic]*)

Enters given event with id [*event_id*] with topic [*topic*]

**.leave** (*int [event_id]* int[*question_index*])

Removes a topic asked by the user at index [*question_index*] of a given event with id [*event_id*] 
