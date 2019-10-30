# Cost-and-Route-Optimization-for-Vaccine-Distribution-

Tools Used: Excel, AMPL

•	A linear and Dynamic Program was developed to minimize the drone scheduling costs from the CDC labs to cities around Philadelphia. The demand was obtained based on the population. An initial heuristic using “Add & Swap” was employed for minimizing the Cost and distance.

•	A distance matrix was developed using Python and then vehicle routing was performed by Subtour elimination and MTZ Constrain using AMPL.

•	MTZ Constrains did cut off the cost by 3% relative to the next best model of Subtour elimination.
