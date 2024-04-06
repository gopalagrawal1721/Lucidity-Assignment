Overview:

* The DeliveryScheduler program provides functionality to calculate the shortest delivery route and total time for a batch of orders to be delivered by a delivery executive.
* It employs the Nearest Neighbor Algorithm to find a heuristic solution for the Traveling Salesman Problem (TSP), optimizing the delivery route.


Assumptions:

* All locations are represented using latitude and longitude coordinates.
* Travel time between locations is calculated using the Haversine formula, assuming an average speed of 20 km/hr.
* Preparation time for each order at the restaurant is provided in hours.
* The delivery executive is stationed at a fixed location and does not move during delivery.
* Orders are assigned to a single delivery executive.
* The Nearest Neighbor Algorithm provides a relatively good route in a reasonable amount of time but may not always produce the optimal solution.


Usage:

* Define locations for Aman, restaurants, consumers, and delivery executives using latitude and longitude coordinates.
* Create orders specifying the restaurant, consumer, delivery executive, and preparation time.
* Call the calculateTotalTime method to compute the total time required for delivering all orders.
* Adjust parameters and test different scenarios to optimize delivery routes and times.


Testing:

* The program includes test cases to verify the correctness of the implementation.
* Test cases cover the calculation of travel time, total time for delivering orders, and the nearest neighbor algorithm.
