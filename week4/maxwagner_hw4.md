# Assignment 4 - Data 620 - Project 1 Pre-Work

#### Max Wagner

### Goals:
1. Identify and load a network dataset that has some categorical information available for each node.
2. For each of the nodes in the dataset, calculate degree centrality and eigenvector centrality.
3. Compare your centrality measures across your categorical groups.

### Plan:

Using a data set from [U Mich](http://www-personal.umich.edu/~mejn/netdata/), specifically a data set on the cast and connections in the novel *Les Miserables*. The current graph file provides relationships and names. I will be adding a categorical aspect to the graph file by including the sex of the characters. This is fairly easily done using **networkX** or **Gehpi**. Additional categorical variables may be added if it seems fit.

The loading of the data would mostly be done using **networkX** and eventual visualization and verification will be done using **Gephi**. If a database structure is needed it will be done using **Pandas**. 

The outcome expectations are expected to be co-aligned with the [Bechdel Test](https://en.wikipedia.org/wiki/Bechdel_test), which states that women do not often speak with each other in movies. This is a somewhat flawed crossover as the data set only tests when they "appear" together, not when they speak. The expected results would be that males have connections to males and females, while females will be more likely to be connected to a male, than another female. A small disclaimer being that I have not read the novel, nor seen the movie, so my expectations are not biased by what I have seen/read.
