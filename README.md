# Index Notation In Lean

This is a draft manuscript discussing the implementation of index notation into Lean 4. 
The actual implementation can be found as part of [HepLean](https://github.com/HEPLean/HepLean).

All the material here is very likely to change (at this stage there are many many typos 
and spelling mistakes).

Everything is copyrighted: Joseph Tooby-Smith 2024.

Comments are welcome.

## Abstract 

The physics community relies on index notation to effectively manipulate tensors of specific 
types. This paper introduces the first formally verified implementation of index notation in the
interactive theorem prover Lean 4. By integrating index notation into Lean, we bridge the gap between 
traditional physics notation and formal verification tools, 
making it more accessible for physicists to write and prove results within Lean.
In the background, our implementation leverages a novel application of category theory.