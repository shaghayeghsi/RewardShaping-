## Sampled State Space

The sampled state space utilized for constructing the underlying graph in the reward shaping approach includes **100,000 turns**, collected based on the initial sparse reward function. 

Specifically, the initial sparse reward function is defined by **Equation (1)** (in paper), where the maximum number of turns (`max_turns`) is set to:
- **40** for the *movie ticket booking* domain,  
- **30** for the *other two domains*.  

This adjustment reflects the complexity of each domain, influencing the potential rewards or penalties accordingly.
