# kqcprs-rs
### What
Kaiwaves Quantum Computing Probabilistic Rudimentary Simulator

Don't mind the name, I needed something catchy and easy to pronounce as an acronym.

Gonna be trying to make some sort of model to simulate basic quantum computing concepts in Rust :3

### why
I think I like quantum mechanics, or at least to the level that I've learned as a measly second year student. 

Hopefully, the understanding that I develop from this will help my career in physics research. (Someone let me into honours please)

Outside of the obvious physics, will be good to learn probability and linear algebra implementations in Rust. And if I can do it in Rust, I can lowkey do it in anything.

### outline?
Likely gonna make a small 4 qbit sort of simulator using linear algebra models like complex matrix representations and what not. Details TBD

The code will drip through glacially while I work through the intuition and develop an actual understanding for building models. Which I am only now taking a class for.

I'm thinking right now to build it around some engine which executes the neccesary multiplication and arithmetic, with gates and programs in a seperate file. 

1. Rust implementations of vector spaces to represent the state vector of qubits
- gotta understand what a state vector is 
- using ndarray [[https://docs.rs/ndarray/]]
- will mostly go in src/engine.rs
2. Understanding the math of tensor products and implementing them in rust
3. Creating matrices in rust to represent superposition and other quantum specific gates
4. Create an engine that can apply matrix multiplication to the qubits
5. Some sort of wave function collapse to simulate observation