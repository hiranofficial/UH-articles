# 📚 Research Articles by Hiran Harilal  

Welcome to my research repository! This space hosts my academic papers from the **University of Hertfordshire**, covering topics in **Genetic Algorithms**, **Evolutionary Computing**, and **Flocking Behavior in Multi-Agent Systems**.  

Each paper in this repository provides **in-depth experimental analysis**, exploring key concepts in artificial intelligence and computational modeling.

---

## 📑 Contents  

- **[A Heuristic Study of Genetic Algorithm for Evolution](#1️⃣-a-heuristic-study-of-genetic-algorithm-for-evolution)**
- **[Implementation of Flocking Behavior Without Separation Rule](#2️⃣-implementation-of-flocking-behavior-without-separation-rule)**
- **[How to Cite These Papers](#📌-how-to-cite)**
- **[Future Work and Improvements](#🔍-future-work-and-improvements)**  
- **[Contact Information](#📬-contact)**  

---

## 1️⃣ A Heuristic Study of Genetic Algorithm for Evolution  
📄 **Full Paper:** [GeneticAlgorithm](GeneticAlgorithm.pdf)  

### 🔍 **Overview**  
This paper explores the **Genetic Algorithm (GA)** as a method for solving optimization problems based on principles of **natural selection and evolution**. The study focuses on understanding how various parameters, such as **mutation rates** and **population sizes**, affect the performance of evolutionary processes.

### 🎯 **Objectives**  
- Investigate **randomized search heuristics** used in genetic algorithms.
- Analyze how **population size** and **mutation rate** influence **evolutionary efficiency**.
- Implement a **GA simulation using Unity**, measuring performance under different conditions.

### 🛠 **Methodology**  
1. **Darwinian Natural Selection Principles**:  
   - **Heredity:** Traits are passed from parents to offspring.  
   - **Variation:** Random mutations introduce diversity.  
   - **Selection:** The most "fit" individuals survive and reproduce.  

2. **Implementation in Unity**:  
   - Created a **GA simulation** that evolves toward solving a predefined target phrase:  
     `"To be or not to be, that is the question"`.  
   - Applied **crossover, mutation, and selection mechanisms**.  

3. **Performance Testing**:  
   - **Experiment 1:** Varying **population sizes** while keeping mutation rates constant.  
   - **Experiment 2:** Varying **mutation rates** while keeping population size constant.  
   - Measured **convergence time, number of generations, and efficiency**.  

### 📊 **Key Findings**  
- **Larger populations** led to **faster convergence** but increased computational load.  
- **Mutation rate optimization** is critical—too high leads to randomness, too low results in stagnation.  
- The study reinforced **GA’s potential for solving optimization problems** where exhaustive search is impractical.  

### 🚀 **Real-World Applications**  
- **AI & Machine Learning**: Hyperparameter tuning, neural network weight optimization.  
- **Robotics & Evolutionary Design**: Self-improving control algorithms for robots.  
- **Finance & Logistics**: Portfolio optimization, route planning, and supply chain optimization.  

---

## 2️⃣ Implementation of Flocking Behavior Without Separation Rule  
📄 **Full Paper:** [FlockingBehaviour.pdf](FlockingBehaviour.pdf)  

### 🔍 **Overview**  
This paper investigates **flocking behavior in multi-agent systems** by simulating movement based on **alignment and cohesion**, **excluding the traditional separation rule**. The goal is to determine whether flocking can still be achieved **without explicit collision avoidance mechanisms**.

### 🎯 **Objectives**  
- Simulate **real-world flocking behavior** seen in birds and fish.  
- Evaluate whether removing the **separation rule** affects **group stability and coordination**.  
- Use **Unity’s physics engine** to conduct controlled experiments.  

### 🛠 **Methodology**  
1. **Three Classic Flocking Rules** (Reynolds' 1986 Model):  
   - **Alignment**: Steer toward the average heading of nearby agents.  
   - **Cohesion**: Steer toward the average position of nearby agents.  
   - **Separation (Omitted in this study)**: Normally prevents collisions by keeping agents apart.  

2. **Implementation Using Unity**:  
   - Developed **boids (agent-based entities)** to simulate flocking.  
   - Removed the separation rule and instead used **invisible colliders** to prevent agent overlap.  
   - Measured **distance consistency, velocity synchronization, and stability** across simulations.  

3. **Experimental Setup**:  
   - **Scenario 1**: Measuring **equidistance consistency** between agents under different velocities.  
   - **Scenario 2**: Introducing a **goal-seeking mechanism** to analyze coordinated movement.  

### 📊 **Key Findings**  
- The **boids successfully formed cohesive groups** even without the separation rule.  
- **Higher velocities** caused **instability**, suggesting a need for balancing **alignment and cohesion forces**.  
- Using **Unity’s physics colliders** effectively maintained spatial consistency.  

### 🚀 **Real-World Applications**  
- **Swarm Robotics**: Coordinating autonomous drones, self-driving vehicles.  
- **Game Development & Animation**: Simulating crowds, flocks, and swarm movement.  
- **Traffic Flow Analysis**: Understanding pedestrian and vehicle movement patterns.  

---

## 📌 How to Cite  
If you find these papers useful in your research, please consider citing them:  

```bibtex
@article{harilal2017genetic,
  author = {Hiran Harilal},
  title = {A Heuristic Study of Genetic Algorithm for Evolution},
  year = {2017},
  institution = {University of Hertfordshire}
}

@article{harilal2018flocking,
  author = {Hiran Harilal},
  title = {Implementation of Flocking Behavior Without Separation Rule},
  year = {2018},
  institution = {University of Hertfordshire}
}
```
## 🔍 Future Work and Improvements  
Both studies open avenues for further exploration:  

### 🧬 Genetic Algorithm Enhancements  
- Implementing **neural networks** to evolve fitness functions dynamically.  
- Applying **parallel computing** to accelerate GA performance.  

### 🕊️ Flocking Behavior Studies  
- Expanding experiments to **3D simulations** with real-world physics.  
- Integrating **reinforcement learning** to allow agents to adapt dynamically.  
- Testing in real-world **multi-robot coordination scenarios**.  

## 📬 Contact  
For discussions, feedback, or collaborations:  
📧 Email: hiranharilal@outlook.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hiranharilal)  

---

Feel free to fork, share, and contribute! 🚀

