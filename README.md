   - Problem Statement:
Efficiently navigating complex graphs  is a crucial challenge, Traditional manual planning methods are time-consuming and prone to human error. The goal is to find the most optimal solution.

   - What is IntelliSolver:
     
IntelliSolver offers a cutting-edge solution to the complex graph searching problem. Leveraging its advanced algorithms and user-friendly interface.Using IntelliSolver, users can effortlessly input the graph  details, including nodes, edges, and associated costs such as distances or travel times. The graphical interface simplifies the construction of the network, allowing the user to specify start and destination points with ease.
     Once the graph is defined, IntelliSolver empowers users to choose from a range of search algorithms tailored to their specific requirements. Informed search algorithms, such as A* or Greedy Best-First Search, utilize heuristic information to efficiently find optimal solutions. Uninformed search algorithms, such as Breadth-First Search or Depth-First Search, explore the network systematically to discover feasible paths; it  Implements the Mini-max algorithm with Alpha-Beta pruning to create an adversarial search agent. These algorithms are implemented in the games that the tool provides , the toolbox allows users to play a game against the program/agent. it can provide a selection of games chess or Connect Four.
     IntelliSolver's intelligent algorithms analyze the given graph , considering various factors (cost), dis. By leveraging the power of informed decision-making, IntelliSolver calculates the most efficient solution.The user-friendly interface of IntelliSolver provides a visual representation of the optimized path.This streamlines decision-making.

   - Guidelines:
                       
- Enter  start and goal states for a well-structured representation of the problem space.
  
- Construct search trees or graphs , input edges and associated costs in a specified format in the label entry “ input your graph “ , such as "1 2 3" denoting a path from node 1 to node 2 with a cost of 3.

- Choose one algorithm from the provided list from the label “search algorithm”.

- In case of choosing an informed search algorithm you have to enter heuristic values for each node using the " input Heuristic values " label  in this specific format
  “ node  heuristic-value” for exemple 1 3 that means that node 1 has heuristic value 3 each line will define the heuristic value of a node .
   
- Visualizations:
Initiate the search process clicking on the start button , then the graph will be displayed showing smoothly the path taken by the search algorithm in a different color .

Note: IntelliSolver works with numeric values, nodes need to be represented as numbers.
