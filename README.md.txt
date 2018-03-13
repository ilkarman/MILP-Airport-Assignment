# Airport Gate Assignment Tutorial - Linear Programming

Imagine we have planes arriving into and departing from our airport. For now we assume that we have three terminals (A, B, C) and those contain a certain number of gates. We also assume that we can't move a plane to a different gate so the gate the plane arrives at is the gate it departs from. This will be relaxed later when we look at towing an aircraft to a 'holding' area.
We will look at ways of mathematically modelling this assignment problem subject to:

1. hard-rules such as not of all our gates can take an airplane of a certain size
2. soft-rules such as preferring a certain terminal for certain destinations 
3. objectives such as minimising the number of different gates-used.