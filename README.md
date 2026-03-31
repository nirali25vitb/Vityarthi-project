# Vityarthi-project

# monthly-expense-management-
 The Monthly Expense Tracker is a Python-based project that helps users manage and analyze their daily expenses. Unlike traditional trackers, this project integrates Artificial Intelligence concepts using graph-based search algorithms such as BFS, DFS, and A* to provide smart insights and optimize spending behavior.

 Features:-
1. Add, update, and delete expenses
2. Categorize expenses (Food, Travel, Shopping, Bills, etc.)
3. Visualize spending using graphs
4. AI-based analysis of expense patterns
5. Graph-based modeling of financial data
6. Smart suggestions to reduce expenses
7. AIML Concepts Used
   
# Graph Representation
Expenses are modeled as a graph
Nodes → Categories (Food, Travel, etc.)
Edges → Transactions / relationships between categories

   1.) BFS (Breadth First Search)
Used for level-wise exploration of expenses
Helps identify:
All categories used in a time frame
Shortest path between expense categories

   2.) DFS (Depth First Search)
Used for deep analysis of spending patterns
Helps:
Detect overspending chains
Analyze category-wise detailed usage

3.) A* Algorithm  (Core Feature)
Used for optimal expense planning
Formula:
f(n) = g(n) + h(n)
Where:
g(n) = actual cost (current spending)
h(n) = estimated future cost

 Helps suggest:
1.Minimum cost spending path
2.Budget optimization strategies

Tech Stack
1. Language: Python
2. Libraries:
3. pandas
4. matplotlib
5. heapq
   
Concepts: AI Search Algorithms, Graph Theory
 

 
