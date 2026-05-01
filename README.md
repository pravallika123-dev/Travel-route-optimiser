Project Overview
This project is a Travel Route Optimizer implemented in C that solves the Travelling Salesman Problem (TSP) using:


Greedy Algorithm (Nearest Neighbour)


Dynamic Programming (Held-Karp Algorithm)


The program compares both approaches based on:


Total travel distance


Execution time


Optimality of the route


It demonstrates the trade-off between speed and accuracy in algorithm design.

🚀 Features


Calculates distances between cities using Euclidean distance


Builds a complete distance matrix


Finds routes using:


Greedy approach


Dynamic Programming approach




Compares algorithm performance


Displays:


Route taken


Total distance


Execution time


Analysis and insights





🧠 Algorithms Used
1. Greedy Algorithm (Nearest Neighbour)
Idea
At every step, visit the nearest unvisited city.
Advantages


Very fast


Easy to implement


Works well for large inputs


Disadvantages


Does not always produce the optimal route


Early choices can lead to poor final results


Time Complexity
O(N2)O(N^2)O(N2)

2. Dynamic Programming (Held-Karp)
Idea
Uses bitmask DP to explore all possible subsets of cities efficiently.
Advantages


Guarantees optimal solution


Finds minimum possible route distance


Disadvantages


Exponential complexity


High memory usage


Time Complexity
O(N2×2N)O(N^2 \times 2^N)O(N2×2N)

🏙️ Cities Used
The project currently includes these cities:
IndexCity0Hyderabad1Vijayawada2Visakhapatnam3Tirupati4Guntur5Nellore6Kurnool7Kakinada

📂 Project Structure
travel-route-optimizer/│├── main.c          # Main source code├── README.md       # Project documentation

⚙️ Requirements


GCC Compiler


C Standard Library



▶️ How to Compile
gcc main.c -o tsp

▶️ How to Run
./tsp

📊 Sample Output
TRAVEL ROUTE OPTIMIZER — CCC Algorithm ProjectGreedy vs Dynamic Programming (TSP)RUNNING GREEDY ALGORITHM...Algorithm : Greedy (Nearest Neighbour)Route     : Hyderabad → Kurnool → Tirupati → Nellore → ...Distance  : 1800 kmTime      : 0.0100 msRUNNING DP (HELD-KARP) ALGORITHM...Algorithm : Dynamic Programming (Held-Karp)Route     : Hyderabad → Vijayawada → Guntur → ...Distance  : 1650 kmTime      : 0.1500 ms

📈 Comparison
FeatureGreedyDynamic ProgrammingSpeedFastSlowOptimal Solution❌ No✅ YesMemory UsageLowHighScalabilityGoodLimitedComplexityO(N2)O(N^2)O(N2)O(N22N)O(N^2 2^N)O(N22N)

🎯 Key Learning Outcomes


Understanding the Travelling Salesman Problem


Comparing approximate vs exact algorithms


Learning bitmask dynamic programming


Performance analysis of algorithms


Practical implementation of graph optimization



🔮 Future Improvements


Add real map coordinates using APIs


Visualize routes graphically


Add more cities dynamically


Implement Genetic Algorithm / A* Search


Support weighted road distances instead of Euclidean distance



👨‍💻 Author
Pravallika-AP24110011874
Sk.Summaya-AP24110011879
Anusha bhai-AP24110011886
Priya-AP24110011956
B.Tech CSE — Algorithm Project

📜 License
This project is for educational purposes only.
