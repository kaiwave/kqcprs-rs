# kqcprs-rs
### what
kaiwaves quantum computing probabilistic rudimentary simulator

gonna make some buns qubit simulator or something.

long term plan tho. probs gonna be slow 

### why
i really like quantum mechanics. or at least the concept of it. i havent learned much in uni.

hopefully the understanding that i develop from this will help my future career in physics research. please let me into honours.

outside of the obvious physics, will be good to learn probability and linear algebra implementations in rust and programming skills in general

### outline?
good question. likely gonna make a small 2 or 4 qbit sim using linalg techniques like matrix mult and probabilities.

doing in rust to challenge myself and also teach skills like memory safety. if i can do it in rs, i can do it in anything. i hope

i will need to improve my maths and my coding together but here is a rough idea. the code will drip through glacially while i work through the intuition and develop an actual understanding for computing 

1. rust implementations of vector spaces to represent the state vector of qubits
- gotta understand what a state vector is 
- using ndarray [[https://docs.rs/ndarray/]]
- will mostly go in src/engine.rs
2. understanding the math of tensor products and implementing them in rust
3. creating matrices in rust to represent superposition and other quantum specific gates
4. create an engine that can apply matrix multiplication to the qubits
5. some sort of wave function collapse to simulate observation