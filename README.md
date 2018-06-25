Reads in a text file that specifies an FSA and creates a respective FSA.
Each line in the file represents a record.
Records can refer to states, transitions, initial states, final states, or comments.

States have stateName, xPos, and yPos variables.
Transitions have fromState, toState, and event variables.
Initial states need to already be existing states, which are then set to initial.
Final states need to already be existing states, which are then set to final.
Comment records are ignored.
