Assignment-4: Friend Recommendation Engine

Dataset: 
The given data file contains the adjacency list and has multiple line in the format: <USER> TAB <FRIENDS>, where <USER> is a unique integer ID corresponding to a unique user and <FRIENDS> is a comma separated list of unique IDs corresponding to the friends of the user with the unique ID <USER>. Note that the friendships are mutual (i.e., edges are undirected): if A is a friend with B, then B is also a friend with A

Algorithm: Let us use a simple algorithm such that, for each user U, the algorithm recommends N = 10 users who are not already friends with U, but have the highest number of mutual friends in common with U