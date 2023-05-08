



# Introduction Ai npc movement

-  I itereated from using the hit variable of type RaycastHit in our first script clickmove.cs to create a player click function #which instructs our player Agent on where to move.Moved to creating a steer path powered agent which is able to follow a given path, this is all possible because of one of our linear interpolation technique (Slerp [Spherical Linear intERPolation])

#Credit 

Beginning Game AI with Unity

# Screenshots

![screenshot](ai.png)

# Path(Breadth first search)

- Breadth first search algorithm was used together with a waypoint system to create a path system. The navigation  wasnt smooth because of the waypoint system navigation to optimise our agent's movement we used Navmesh with A* search algorithm 


# A* + Nav mesh

- Path navigation optimised with Navigation mesh and A* search algorithm

![screenshot](Navmesh+A*.png)


# A* || Nav mesh || Finite state machines

- Using FSM i created a Guard agent with 3 states 

* patrol
* investigate
* chase

Our guard navigates our plane using The navmesh and navmesh agent we talked about above  

- Since its Guard against player Our player can trigger a Guard Investigation by knocking which changes our  guards state from patrol to investgate where the sound comes from .


# AI movement

