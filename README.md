# QHack-2023-Qschrodinger010 Project Submission

Qschrodinger010 project submission contains two subproject:
1. The ARKS Representation
2. Polar Measurement Quantum Art

## The ARKS Representation

ARKS (pronounced "ARCS" ) is a new way of representing Quantum states that allows us to visualize different states for more than one qudits, and also visualize quantum entanglement. The ARKS representation is a graph-based representation.

For a given statevector $|\psi\rangle$, the graph is constructed with the following rules - 
1. In the case of a single qudit state, the states are written in a column, with the corresponding probability amplitude below each state.
2. $d*number\\_of\\_qudits$ nodes are created, with each $Z$-basis state written in the same row.
3. Each qudit is in a column.
4. Weighted edges between states represent a state, with the weights given by the probability amplitude.

Let us look at three examples - 
### 1 Qubit state
![d1](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/d2_q1_arks_repr.svg)

### 3 Qubit state
![d2](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/d2_arks_repr.svg)

### 2 Qutrit state
![d3](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/d3_arks_repr.svg)

## Potential applications
1. While the Bloch sphere is an extremely useful visual tool to represent single-qubit states, it is diffuclt to generalise it to multiqudit states. ARKS is a representation that displays the relationship between multiple qudits and states. 
2. In addition, it can be used as a measure of entanglment - with the presence of cycles in the graphs being an indicator of entanglement. A formalism to use the weights of the edges to quantise this can also be developed.
3. The program can be extended to support evolution of the state by application of unitaries, which would modify the edges and the weights. Thus, this representation would help visualise the changes a quantum system undergoes through the course of an algorithm.

## Polar Measurement Quantum Art

Polar projection is one of the underrated projections used today but we made Quantum Art using it.
### r = cos(4*theta) or Petal Design
![c1](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/Classical_petal.png)
### Quantum Petal Design
![q1](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/Quantum_petal.png)
### r = 1-sin(theta) or Heart Design
![c2](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/Classical_heart.png)
### Quantum Heart Design
![q2](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/Quantum_heart.png)
