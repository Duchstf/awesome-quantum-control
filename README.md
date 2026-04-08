# Awesome Quantum Control
A curated list of libraries, projects, tutorials, papers, and other resources on quantum control systems. Organized to help researchers and developers navigate machine-learning and control methods for quantum computing.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# Papers

## ML Integrated Control

* [ML-Powered FPGA-based Real-Time Quantum State Discrimination Enabling Mid-circuit Measurements](https://arxiv.org/abs/2406.18807) - **Berkeley**: QubiCML, a field-programmable
gate array (FPGA) based system for real-time qubit state discrimination enabling mid-circuit measurement—the ability to measure the qubit state at the electronic control circuit before/without transferring quantum data to a host computer. 
* [Realizing a deep reinforcement learning agent for real-time quantum feedback](https://www.nature.com/articles/s41467-023-42901-3) - **ETH**: RL-agent for sub-microsecond latency control to realize the full potential of quantum technologies, which requires precise real-time control on time scales much shorter than the coherence time.
* [Reinforcement Learning Control of Quantum Error Correction](https://arxiv.org/pdf/2511.08493) - **Google Quantum AI/DeepMind**: Reinforcement learning framework that repurposes error detection events to continuously calibrate quantum control parameters without halting computation. 
* [[arXiv](https://arxiv.org/abs/2402.03931)] [Fully autonomous tuning of a spin qubit](https://www.nature.com/articles/s41928-025-01562-4) - **ETH**:  Autonomous tuning of a semiconductor qubit, from a grounded device to Rabi oscillations, integrates deep learning, Bayesian optimization and computer vision techniques. Demonstrate this automation in a germanium–silicon core–shell nanowire device.
* [Reinforcement Learning for Quantum Technology](https://arxiv.org/pdf/2601.18953) - **Max Planck Institute**: A review of reinforcement learning for quantum control, covering major applications, experiments, and open challenges.

## Classic Control

* [Millisecond-Scale Calibration and Benchmarking of Superconducting Qubits](https://arxiv.org/pdf/2602.11912) - **Uni of Copenhagen**: Closed-loop on-FPGA calibration protocol in ms latency on Quantum Machines. Many techniques enssembled together in order to enable the automatic on-chip loop. 
*  [Silicon spin qubit noise characterization using real-time feedback protocols and wavelet analysis](https://pubs.aip.org/aip/apl/article/124/11/114003/3272522/Silicon-spin-qubit-noise-characterization-using) - **Applied Physics Letters**: benefits and drawbacks of qubit parameter feedback, as feedback related overhead increases
* [Real-time two-axis control of a spin qubit](https://www.nature.com/articles/s41467-024-45857-0): FPGA-based control for full Hamiltonian estimation to dynamically stabilize and optimize qubit performance.
* [Suppressing qubit dephasing using real-time Hamiltonian estimation](https://www.nature.com/articles/ncomms6156) - **Harvard**: Improve the coherent time of singlet-triplet qubit formed by two gate-defined lateral quantum dots (QDs) in a GaAs/AlGaAs heterostructure by using FPGA-based Hamiltonian parameter estimation. 
* [Real-Time Adaptive Tracking of Fluctuating Relaxation Rates in Superconducting Qubits](https://journals.aps.org/prx/pdf/10.1103/gk1b-stl3) - **Fabrizio Berritta (Uni of Copenhagen)**: FPGA-based controller (Bayesian Estimation) that accurately tracks the relaxation time of superconducting qubits and reports that the relaxation time switches orders of magnitude within milisecond timescales as opposed to hours.
* [Robust online Hamiltonian learning](https://iopscience.iop.org/article/10.1088/1367-2630/14/10/103013): Combining Monte Carlo and Bayesian inference for online estimation dynamical parameters of a quantum system.

## ML4Quantum

* [Reconstructing Quantum Dot Charge Stability Diagrams with Diffusion Models](https://arxiv.org/pdf/2603.26432) - **Vinicius Hernandes et al, Delt**: Diffusion models to accurately measure charge stability diagrams from sparse measurement. 

## Quantum Error Correction

* [Quantum error correction below the surface code threshold](https://www.nature.com/articles/s41586-024-08449-y) - **Google Quantum AI**: Distance-7 code and a distance-5 code integrated with a real-time decoder.

## General Quantum Technologies

* [A two-dimensional 10-qubit array in germanium with robust
and localised qubit control](https://arxiv.org/pdf/2412.16044) - **Delt**: Two-dimensional 10-spin qubit array. 

## Reviews

* [Learning Quantum Systems](https://arxiv.org/pdf/2207.00298): Theoretical proposals and successful implementations
across different multiple-qubit architectures. 

# Repositories
* [Model-Free Quantum Control with Reinforcement Learning](https://github.com/v-sivak/quantum-control-rl?tab=readme-ov-file)

# Concepts
This section mainly explains the terminology in an intuituive way for learning purposes.

* **Rabi Oscillations:** This is the "heartbeat" of a qubit. If you graph the data, it looks like a wave going up and down. It proves you can rotate the qubit from 0 to 1 and back again smoothly. Rabi oscillations show that you can continuously and precisely rotate a qubit’s state. If you see this clean wave, your qubit is controllable.
* **Bayesian Optimization:** Imagine you are looking for the highest peak on a foggy mountain range. Instead of walking everywhere (which takes too long), you check a few spots, and then use math to predict where the peak likely is based on those checks. The algorithm uses this to find the best voltage settings efficiently. Bayesian optimization finds the best settings with very few tests by predicting where the maximum likely is instead of searching everywhere.
