# AI_Search_Algorithms

the algorithms used to solve a traveling problems:


Algorithm 1: Depth Limited Search algorithm
Input: P roblem, M ax_depth ;
Output: Solution;
Call DFS algorithm with M ax_depth ;
Explore a node only if it has depth less than M ax_depth ;


Algorithm 2: Iterative Deepening Search algorithm
Input: P roblem, M ax_depth ;
Output: Solution;
Initialize solution to None ;
Initialize M ax_depth;
while solution == None do
solution = Depth_Limited_Search(Problem, M ax_depth);
Increment M ax_depth ;
end
