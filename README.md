## Sampled State Space

The sampled state space utilized for constructing the underlying graph in the reward shaping approach includes **100,000 turns**, collected based on the initial sparse reward function. 

Specifically, the initial sparse reward function is defined by **Equation (1)** (in paper), where the maximum number of turns (`max_turns`) is set to:
- **40** for the *movie ticket booking* domain,  
- **30** for the *other two domains*.  

This adjustment reflects the complexity of each domain, influencing the potential rewards or penalties accordingly.



## Dataset

In the experiments, benchmark task-oriented dialogue environments provided by the Microsoft Dialogue Challenge are used [7, 27] (in paper). 
The dataset used in this study is obtained from [paper](https://aclanthology.org/2020.acl-main.566.pdf) and can be accessed at the following repository: [GitHub - E2E Dialogue Challenge](https://github.com/xiul-msr/e2e_dialog_challenge).


Experiments were conducted in three application domains: **Movie ticket booking**, **Restaurant reservation**, and **Taxi ordering**. Each of these domains has its own specific goals and slots. 
The table below the statistics related to the datasets.


| Task                   | Intents | Slots | Dialogues |
|------------------------|---------|-------|-----------|
| Movie-Ticket Booking  | 11      | 29    | 2890      |
| Restaurant Reservation | 11      | 30    | 4103      |
| Taxi Ordering         | 11      | 29    | 3094      |
