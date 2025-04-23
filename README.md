# ComputeNet
ComputeNet is a comprehensive project that integrates a client-server file transfer system with high-performance computing modules. It provides a unified framework to solve computational problems using serial, parallel (OpenMP), and distributed (socket-based) implementations. The project is designed to highlight performance scaling, communication, and efficient resource utilization across machines.
***

**1. Client-Server File Sharing**  
  
_ A simple yet effective TCP-based client-server model.

_ The server maintains a list of files (e.g., .pdf, .docx, .txt) available for download.

_ The client requests and downloads files from the server.

_ Downloaded files are verified by opening them after the transfer.
***

**2. Scientific Computation Modules**
Each computational module supports:

_ Serial implementation – For correctness verification.

_ Parallel implementation (OpenMP) – For performance scaling on a single machine.

_ Distributed implementation (Sockets + optional OpenMP) – For computation across multiple machines.

**A. Array Summation**
_ Sums a large 1D array using the three modes.

_ Used to benchmark the overhead and speedup in distributed environments.

**B. Matrix Multiplication**
_ Performs large matrix multiplication.

_ 2D contour plots included to visualize correctness and computational patterns.

_ Shows how distributed systems can handle data beyond single-machine memory limits.

**C. 2D Laplace Equation Solver**
_ Solves Laplace’s equation on a grid with Dirichlet boundary conditions:

_ Top = 5V, Bottom = -5V, Left & Right = 0V.

_ Simulates the electric potential inside a capacitor.

_ Includes contour plots to visualize potential distribution.
