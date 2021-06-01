# Logistics
Uses the Ford-Fulkerson algorithm in order to route the maximum amount of supplies from a start to an end node.

This algorithm works by searching all possible paths in the graph and finding one that reaches the end. It then fills that path with however much capacity you can push to the end. This is very easy to implement with Ford-Fulkerson which is another reason I chose to use this algorithm, since we learned it in class. It has a runtime complexity of at worst about O(n^2) since we have a BFS within a loop. Most of the time, the runtime will not be this bad and even if it was, speed is not a requirement for this task, as long as it distributes the product correctly. The space complexity is O(n), because I only need to store the path to the end. 
