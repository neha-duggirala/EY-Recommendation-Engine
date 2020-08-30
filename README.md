# EY-Recommendation-Engine
The concept behind building the recommendation system is collaborative badge recommendations. This engine helps an individual to pick up a right badge eliminating the burden of scrolling through hundreds of badges present on the EY badge platform. The following scenarios that are taken into consideration:
1.	GDS SL - Domain Affinity: The degree to which service level tends to choose which domain.
2.	Domain – Sub Domain Similarity: Measure most employees who have chosen a domain tend to take which sub domain.
3.	Rank Name – Badge Type Similarity: The grade level and experience of an employee plays an important role in choosing badge difficulty. 
The key idea behind this is that similar individuals share the same interest and that similar badges are liked by an individual.
1. Level – based: The domain recommendation is given by which GDS SL and Rank they belong to. What are the most common domains picked up to the users belonging to that level?
2. Domain & Sub Domain based: The sub domain recommendation is given by comparison of a domain and most popular sub domain picked up the users of same GDS SL level and Rank.
Based on the above two points, two matrices have been extracted by performing a few operations and computation.  From the derived engine, when an individual finishes a badge, the engine inputs the badge details and gives the top matching recommendations. 
