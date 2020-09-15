# degress-of-separation
Algorithm to find the smallest degree of separation between 2 Hollywood actors

## Background
According to the Six Degrees of Kevin Bacon game, anyone in the Hollywood film industry can be connected to Kevin Bacon within six steps, where each step consists of finding a film that two actors both starred in.

In this problem, we’re interested in finding the shortest path between any two actors by choosing a sequence of movies that connects them. For example, the shortest path between Jennifer Lawrence and Tom Hanks is 2: Jennifer Lawrence is connected to Kevin Bacon by both starring in “X-Men: First Class,” and Kevin Bacon is connected to Tom Hanks by both starring in “Apollo 13.”

## Steps to run:  
1. Use the following command in terminal on the root folder:  
  `python degrees.py large`  
  or  
  `python degrees.py small`  
2. Enter any 2 Hollywood names:  
  `Name: Emma Watson  
  Name: Jennifer Lawrence`  
3. The output will show the degrees of separation between the 2 actors:  
  `3 degrees of separation.`  
  `1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix`  
  `2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us`  
  `3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class`
