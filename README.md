# Delivery-Route-Optimization-with-Reinforcement-Learning
This project implements a Reinforcement Learning (RL) environment for optimizing delivery routes between cities. The system models multiple transport modes (flight, train, truck, ship) with varying costs and speeds. The agent learns to choose the most efficient and cost-effective delivery strategy.
 
---

## How It Works  

- Cities are represented as nodes in a **graph**.  
- Each connection (edge) has multiple transport options: **flight, train, truck, ship**.  
- Each mode has a trade-off:  
  - Flight → Fast but expensive  
  - Train → Balanced  
  - Truck → Flexible but slower  
  - Ship → Cheapest but limited to coastal cities  
- An **RL agent** is trained in a custom Gym environment.  
- The agent receives rewards based on **efficiency (time + cost)** and learns optimal strategies.  
- Visualizations show the delivery routes, city graph, and learned strategies.  

---

## Tech Used  

- Python  
- Gym (custom RL environment)  
- NumPy (calculations)  
- NetworkX (graph of cities and routes)  
- Matplotlib (visualizations)  

---

## Example Use  

- Define a **source city** and **destination city**.  
- Train the RL agent to choose the best delivery routes.  
- Visualize the city graph and transport modes.  
- Analyze the trade-off between **fast vs cheap delivery**.  


