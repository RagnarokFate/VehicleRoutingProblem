# Introduction To AI - Vehicle Routing Problem

This project addresses the Vehicle Routing Problem (VRP), a combinatorial optimization problem involving the efficient distribution of goods or services from a central depot to various locations using a fleet of vehicles.

## Course Information
- **Course Title:** Introduction To AI
- **Course Code:** 324.3610
- **Assignment:** Vehicle Routing Problem
- **Due Date:** 05.04.2024

## Vehicle Routing Problem

### Introduction
The VRP aims to minimize transportation costs, including factors like distance traveled and time, while adhering to various constraints such as vehicle capacity and time windows for delivery.

### Class VRP
This section defines a Python class `VRP` and provides methods to handle VRP instances, compute distance matrices, plot locations and routes, and calculate route distances and times.

### Particle Swarm Optimization
PSO is utilized to solve the VRP. It is a bio-inspired optimization algorithm that iteratively refines solutions by adjusting particle positions and velocities based on personal and global best positions.

### Defining an Objective Function
An objective function is implemented to evaluate particle positions with regard to the VRP instance. It calculates the total cost of routes considering distance and time.

### Main
The main section demonstrates how to run the PSO algorithm on a VRP instance with defined parameters, such as swarm size, maximum routes, PSO constants, and maximum iterations. It also presents the results including optimized routes, total distance, and total time.

## Parameters versus Solution Quality & Runtime

| Parameter   | Solution Quality                                      | Runtime                                           |
|-------------|-------------------------------------------------------|---------------------------------------------------|
| SWARM_SIZE  | Increasing swarm size increases probability of finding better solution  | Larger swarm size increases computation time     |
| MAX_ITER    | More iterations allow exploring a larger search space | Runtime increases linearly with iterations        |
| (W_MIN, W_MAX) | High initial inertia weight promotes exploration; low final inertia weight encourages exploitation  | No significant effect on runtime            |
| C1, C2      | Higher C1 emphasizes a particle's own experience; higher C2 emphasizes the swarm's knowledge | No significant effect on runtime                |

## Submitting Results

### Ex1-d5
![image](https://github.com/RagnarokFate/VehicleRoutingProblem/assets/92100499/3171f59d-5ba9-4e0d-8230-328469574900)

**Route Details:**

- Total Distance: 6.24, Total Time: 6.23

### Ex2-d22
![image](https://github.com/RagnarokFate/VehicleRoutingProblem/assets/92100499/6c90408a-2a7a-4c96-8319-8e9a60ad8a6b)

**Route Details:**
- Total Distance: 366.43, Total Time: 113.75

### Ex3-d33

![image](https://github.com/RagnarokFate/VehicleRoutingProblem/assets/92100499/f7669473-b296-42b7-be1e-4b59c675aadc)


**Route Details:**
- Total Distance: 404.59, Total Time: 128.27
