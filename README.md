# Awesome Quantum Control
A curated list of libraries, projects, tutorials, papers, and other resources on quantum control systems. Organized to help researchers and developers navigate machine-learning and control methods for quantum computing.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# Papers


## Quantum Error Correction

* [FPGA-tailored algorithms for real-time decoding of quantum LDPC codes](https://arxiv.org/pdf/2511.21660) - IBM Quantum: We analyze FPGA-tailored versions of three decoder classes for quantum low-density parity-check (qLDPC) codes: message passing, ordered statistics, and clustering. 
* [A scalable and real-time neural decoder for topological quantum codes](https://arxiv.org/pdf/2512.07737): AlphaQubit 2, a neural-network decoder that achieves near-optimal logical error rates for both surface and color codes at scale under realistic noise. 
* [Local Clustering Decoder as a fast and adaptive hardware decoder for the surface code](https://arxiv.org/pdf/2411.10343)-**Riverlane, Cambridge, UK**: Local Clustering Decoder as a solution that simultaneously achieves the accuracy and speed requirements of a real-time decoding system. Our decoder is implemented.
on FPGAs and exploits hardware parallelism to keep pace with the fastest qubit types. 
* [Local active error correction from simulated confinement](https://arxiv.org/pdf/2510.08056) - **Ethan Lake (Berkeley):** Studies the problem of performing real-time
decoding on topological stabilizer codes in a way where all operations—both classical and quantum—are geometrically local.   
* [Quantum error correction below the surface code threshold](https://www.nature.com/articles/s41586-024-08449-y) - **Google Quantum AI**: Distance-7 code and a distance-5 code integrated with a real-time decoder.

## Calibration

### ML Integrated Control

* [ML-Powered FPGA-based Real-Time Quantum State Discrimination Enabling Mid-circuit Measurements](https://arxiv.org/abs/2406.18807) - **Berkeley**: QubiCML, a field-programmable
gate array (FPGA) based system for real-time qubit state discrimination enabling mid-circuit measurement—the ability to measure the qubit state at the electronic control circuit before/without transferring quantum data to a host computer. 
* [Realizing a deep reinforcement learning agent for real-time quantum feedback](https://www.nature.com/articles/s41467-023-42901-3) - **ETH**: RL-agent for sub-microsecond latency control to realize the full potential of quantum technologies, which requires precise real-time control on time scales much shorter than the coherence time.
* [Reinforcement Learning Control of Quantum Error Correction](https://arxiv.org/pdf/2511.08493) - **Google Quantum AI/DeepMind**: Reinforcement learning framework that repurposes error detection events to continuously calibrate quantum control parameters without halting computation. 
* [[arXiv](https://arxiv.org/abs/2402.03931)] [Fully autonomous tuning of a spin qubit](https://www.nature.com/articles/s41928-025-01562-4) - **ETH**:  Autonomous tuning of a semiconductor qubit, from a grounded device to Rabi oscillations, integrates deep learning, Bayesian optimization and computer vision techniques. Demonstrate this automation in a germanium–silicon core–shell nanowire device.
* [Reinforcement Learning for Quantum Technology](https://arxiv.org/pdf/2601.18953) - **Max Planck Institute**: A review of reinforcement learning for quantum control, covering major applications, experiments, and open challenges.

### Classic Control

* [Millisecond-Scale Calibration and Benchmarking of Superconducting Qubits](https://arxiv.org/pdf/2602.11912) - **Uni of Copenhagen**: Closed-loop on-FPGA calibration protocol in ms latency on Quantum Machines. Many techniques enssembled together in order to enable the automatic on-chip loop. 
*  [Silicon spin qubit noise characterization using real-time feedback protocols and wavelet analysis](https://pubs.aip.org/aip/apl/article/124/11/114003/3272522/Silicon-spin-qubit-noise-characterization-using) - **Applied Physics Letters**: benefits and drawbacks of qubit parameter feedback, as feedback related overhead increases
* [Real-time two-axis control of a spin qubit](https://www.nature.com/articles/s41467-024-45857-0): FPGA-based control for full Hamiltonian estimation to dynamically stabilize and optimize qubit performance.
* [Suppressing qubit dephasing using real-time Hamiltonian estimation](https://www.nature.com/articles/ncomms6156) - **Harvard**: Improve the coherent time of singlet-triplet qubit formed by two gate-defined lateral quantum dots (QDs) in a GaAs/AlGaAs heterostructure by using FPGA-based Hamiltonian parameter estimation. 
* [Real-Time Adaptive Tracking of Fluctuating Relaxation Rates in Superconducting Qubits](https://journals.aps.org/prx/pdf/10.1103/gk1b-stl3) - **Fabrizio Berritta (Uni of Copenhagen)**: FPGA-based controller (Bayesian Estimation) that accurately tracks the relaxation time of superconducting qubits and reports that the relaxation time switches orders of magnitude within milisecond timescales as opposed to hours.
* [Robust online Hamiltonian learning](https://iopscience.iop.org/article/10.1088/1367-2630/14/10/103013): Combining Monte Carlo and Bayesian inference for online estimation dynamical parameters of a quantum system.

## MISC

* [Reconstructing Quantum Dot Charge Stability Diagrams with Diffusion Models](https://arxiv.org/pdf/2603.26432) - **Vinicius Hernandes et al, Delt**: Diffusion models to accurately measure charge stability diagrams from sparse measurement.
* [A two-dimensional 10-qubit array in germanium with robust
and localised qubit control](https://arxiv.org/pdf/2412.16044) - **Delt**: Two-dimensional 10-spin qubit array.
* [Learning Quantum Systems](https://arxiv.org/pdf/2207.00298): Theoretical proposals and successful implementations
across different multiple-qubit architectures. 
* [Model-Free Quantum Control with Reinforcement Learning](https://github.com/v-sivak/quantum-control-rl?tab=readme-ov-file)
* [Transversal Algorithmic Fault Tolerance for Low-Overhead Quantum Computing](https://www.youtube.com/watch?v=28zUBOFXFcE) - Harry Zhou, MIT. 
