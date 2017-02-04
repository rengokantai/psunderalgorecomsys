# psunderalgorecomsys
##2. Understanding Tasks Performed by Recommendation Systems
###5 Contrasting Different Recommendation Algorithms
Algos
- Content based filtering: find products with similar attributes
- Collaborative filtering: find products liked by similar users


##3. Recommending Products Based on the Nearest Neighbors Model
###4 Setting up the Book Crossing Data Set
[download](www.bookcrossing.com)
[data set](http://www2.informatik.uni-freiburg.de/~cziegler/BX/) download CSV Dump [25.475 KB]


###6 Computing the Distance Between Users
```
from scipy.spatial.distance import hamming
hamming(user1ratings,user2Ratings)
```

##5. Mining Data for Rules Underlying User Behavior
###4 Computing the Support for an Item Set
[trac](https://wiki.csc.calpoly.edu/datasets/wiki/ExtendedBakery) download 75000, then EB-build-goods.sql,75000-out1.csv
