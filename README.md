# ShopEasy

## Introduction
The main idea of this project is to order products from the information provided. This project will focus on the development of a system for an online store that specializes in selling cameras. The system will be designed to streamline the process of managing inventory, processing orders, and handling customer information.

The project will utilize data structures and algorithms to efficiently manage the store's inventory and process orders. The system will also include a user-friendly interface for customers.

In addition to the features mentioned previously, this project will also incorporate the use of various data structures to enhance the efficiency and performance of the system.

Overall, this project will demonstrate the practical application of various data structures and algorithms in the design and development of an online shopping store management system that sells cameras, by providing efficient and optimized solutions for data storage, retrieval, and pathfinding.

## Implemented Data Structures

• **Linked List**

Linked lists are a data structure that allows for efficient insertion and deletion of elements.

**Reason**  
The program uses linked lists to manage customer information and orders. The data of the user (Delivery, Take Away) is saved in the linked list. We used linked lists instead of arrays because of their dynamic size.

• **AVL (Adelson-Velsky and Landis) Tree**

The AVL tree is a self-balancing binary search tree that is well-suited for storing large amounts of data and allows for fast insertion, deletion, and searching operations.

**Reason**  
The AVL tree will be used to efficiently manage and maintain the store's inventory. All the operations of take-away users are handled using the AVL tree. Operations like searching, deletion, and insertion are performed more efficiently. Insertion and deletion are done by the order ID provided by the user.

• **Graphs**

Graphs are used in the project to show the areas where the parcel can be delivered. Graphs are represented through adjacency matrices.

**Reason**  
Graphs help in efficiently managing delivery areas, ensuring optimized delivery routes and distances.

• **Dijkstra’s Algorithm**

Dijkstra's algorithm is used to implement efficient searching and navigation within the system. It is a shortest path algorithm that can be used to find the shortest path between two nodes in a graph. The nodes are represented as cities, and this algorithm helps provide the distance between cities.

**Reason**  
This algorithm is often used in routing and as a subroutine in other graph algorithms. It helps in determining the shortest route between cities.

• **Prim’s Algorithm**

Prim's algorithm is used to find the minimum spanning tree of a graph, providing distances between areas in a city.

**Reason**  
Prim's algorithm is used between areas in a city to provide discounts to users. It ensures that the tree has the minimum total weight of any spanning tree that can be formed from the graph.

