# Awesome Quantum Control
A curated list of libraries, projects, tutorials, papers, and other resources on quantum control systems. Organized to help researchers and developers navigate machine-learning and control methods for quantum computing.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# Papers

## ML Integrated Control

* [[arXiv](https://arxiv.org/abs/2402.03931)] [Fully autonomous tuning of a spin qubit](https://www.nature.com/articles/s41928-025-01562-4):  Autonomous tuning of a semiconductor qubit, from a grounded device to Rabi oscillations, integrates deep learning, Bayesian optimization and computer vision techniques. Demonstrate this automation in a germanium–silicon core–shell nanowire device.

* [Reinforcement Learning for Quantum Technology](https://arxiv.org/pdf/2601.18953): A review of reinforcement learning for quantum control, covering major applications, experiments, and open challenges.

## Classic Control

# Concepts
This section mainly explains the terminology in an intuituive way for learning purposes.

* **Rabi Oscillations:** This is the "heartbeat" of a qubit. If you graph the data, it looks like a wave going up and down. It proves you can rotate the qubit from 0 to 1 and back again smoothly. Rabi oscillations show that you can continuously and precisely rotate a qubit’s state. If you see this clean wave, your qubit is controllable.
* **Bayesian Optimization:** Imagine you are looking for the highest peak on a foggy mountain range. Instead of walking everywhere (which takes too long), you check a few spots, and then use math to predict where the peak likely is based on those checks. The algorithm uses this to find the best voltage settings efficiently. Bayesian optimization finds the best settings with very few tests by predicting where the maximum likely is instead of searching everywhere.
