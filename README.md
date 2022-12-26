# Memory-Management-cpp
The project is designed to help [arties perform a coalition.
the method of forming a coalition is by letting multiple "agents" 
from different parties try their best to create a 61 coalition as fast as possible.
In this project, I wrote a C++ program that simulates the "Coalition Race" and report
the first coalition formed (or failure).
The simulator is based on a graph that contains:
● Parties as vertices
● Collaborations as edges (2 parties that agree to cooperate)
● “Similarity score” as edge weight, for every 2 connected parties

Each agent belongs to a party. In every step, the agent offers an adjacent party to join. When a
party has decided to join a coalition, it should clone the agent who made the offer to the
newly joined party (so the joined party can now help the coalition).
To clarify:
● Coalition is a set of connected parties.
● In each party, there is a single agent if the party belongs to a coalition (state Joined).
● The total number of agents in the simulation equals the number of parties in the graph
belonging to some coalition (state Joined).
