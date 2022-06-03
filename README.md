# Optimal-Path-Planning | AI61005-Assignment

Question Statement: Consider a city network where we need to route a set of electric vehicles which may require to be charged during its journey from some source to some destination. Let us assume that we have n cities (v1, v2, . . . , vn) and the distance between cities vi and vj be eij (if two cities are not connected directly then eij = ∞ and eij = eji). Assume that each city has a single charging station which can charge one EV at a time. Consider a set of k EVs namely P1, P2, . . . , Pk. For each EV the following information is provided - 
(a) Sr - source node 
(b) Dr - destination node 
(c) Br - battery charge status initially 
(d) cr - charging rate for battery at a charging station (energy per unit time) (e) dr - discharging rate of battery while traveling (distance travel per unit charge) (f) Mr - maximum battery capacity 
(g) sr - average traveling speed (distance per unit time). 
Assume that all vehicles start their journey at t = 0 and Pr reaches it destination at t = Tr. We need to route all the vehicles from their respective sources to destinations such that max{Tr} is minimized. You need to develop both optimal as well as heuristic algorithms.

![Untitled](https://user-images.githubusercontent.com/57285244/112749086-ad1f8300-8fdd-11eb-9cff-a2ba84f2d33d.png)
