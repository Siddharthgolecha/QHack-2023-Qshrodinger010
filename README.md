# QHack-2023-Qschrodinger010 Project Submission

## The ARKS Representation

ARKS (pronounced "ARCS" ) is a new way of representing Quantum states that allows us to visualize different states for more than one qudits, and also visualize quantum entanglement. The ARKS representation is a graph-based representation.

For a given statevector $|\psi\rangle$, the graph is contrcuted with the following rules - 
1. In the case of a single qudit state, the states are written in a column, with the corresponding probability amplitude below each state.
2. $d*number\\_of\\_qudits$ nodes are created, with each $Z$-basis state written in the same row.
3. Each qudit is in a column.
4. Weighted edges between states represent a state, with the weights given by the probability amplitude.

Let us look at two examples - 
### 3 Qubit state
![d2](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/d2_arks_repr.png)

### 2 Qutrit state
![d3](https://github.com/Siddharthgolecha/QHack-2023-Qshrodinger010/blob/main/media/d3_arks_repr.png)

## Potential applications
1. While the Bloch sphere is an extremely useful visual tool to represent single-qubit states, it is diffuclt to generalise it to multiqudit states. ARKS is a representation that displays the relationship between multiple qudits and states. 
2. In addition, it can be used as a measure of entanglment - with the presence of cycles in the graphs being an indicator of entanglement. A formalism to use the weights of the edges to quantise this can also be developed.
3. The program can be extended to support evolution of the state by application of unitaries, which would modify the edges and the weights. Thus, this representation would help visualise the changes a quantum system undergoes through the course of an algorithm.
