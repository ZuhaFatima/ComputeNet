# ComputeNet
ComputeNet is a comprehensive project that integrates a client-server file transfer system with high-performance computing modules. It provides a unified framework to solve computational problems using serial, parallel (OpenMP), and distributed (socket-based) implementations. The project is designed to highlight performance scaling, communication, and efficient resource utilization across machines.

🧠 What This Project Does
1. Client-Server File Sharing
A simple yet effective TCP-based client-server model.

The server maintains a list of files (e.g., .pdf, .docx, .txt) available for download.

The client requests and downloads files from the server.

Downloaded files are verified by opening them after the transfer.

2. Scientific Computation Modules
Each computational module supports:

Serial implementation – For correctness verification.

Parallel implementation (OpenMP) – For performance scaling on a single machine.

Distributed implementation (Sockets + optional OpenMP) – For computation across multiple machines.

A. Array Summation
Sums a large 1D array using the three modes.

Used to benchmark the overhead and speedup in distributed environments.

B. Matrix Multiplication
Performs large matrix multiplication.

2D contour plots included to visualize correctness and computational patterns.

Shows how distributed systems can handle data beyond single-machine memory limits.

C. 2D Laplace Equation Solver
Solves Laplace’s equation on a grid with Dirichlet boundary conditions:

Top = 5V, Bottom = -5V, Left & Right = 0V.

Simulates the electric potential inside a capacitor.

Includes contour plots to visualize potential distribution.
