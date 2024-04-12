# Q2 Supplement

## Differences between HEEUP and [1].

| Difference   | HEEUP                                        | [1]                                      | Remarks                                     |
|--------------|----------------------------------------------|-----------------------------------------------|---------------------------------------------|
| Objective    | Minimize energy consumption for efficient urban layout | Adapt to complex terrain, optimize urban community spatial planning | Focus on energy efficiency vs. terrain adaptability |
| Strategy     | Hierarchical decision-making: from macro to micro optimization | Sequential decision-making: dynamic adaptation, continuous planning | Hierarchical vs. sequential decision-making process |
| State        | Comprehensive urban feature encoding (GAT+GAE), capturing full-spectrum multi-dimensional information | Progress and data encoding (GNN+Encoder), reflecting real-time planning dynamics | GAT enhances feature interrelation vs. GNN focuses on progress and statistics |
| Action       | Multi-dimensional actions, adjusting various aspects of urban planning from macro to micro | Focused on single decision-making for land use and roads | Multi-level refinement vs. single-point decision-making |
| Reward       | Energy efficiency as the core metric at each hierarchical level | Service quality, ecological balance, and traffic flow efficiency make up a composite reward system | Tiered focus on energy vs. diverse urban benefits |

## HEEUP v.s. [1] in energy saving.



| City   | MIAMI HEEUP | MIAMI [1] | Alq HEEUP | Alq [1] |
|--------|-------------|----------------|-----------|--------------|
| Exp. 1 | 9.05%       | -1.17%         | 7.30%     | -0.32%       |
| Exp. 2 | 7.72%       | 1.66%          | 7.25%     | -0.96%       |
| Exp. 3 | 8.74%       | 1.24%          | 7.15%     | 1.21%        |
| Exp. 4 | 8.86%       | 1.55%          | 7.33%     | 1.15%        |
| Exp. 5 | 9.11%       | 1.41%          | 7.19%     | 0.75%        |
| **Average** | **8.70%**   | **0.94%**      | **7.24%** | **0.37%**    |

**Table : Comparison of energy efficiency of HEEUP vs. [1]**

- **HEEUP** adopts a hierarchical, energy-saving optimization approach, progressing from Urban Structure -> Generate Land Use Configuration -> Adjust Building Design Parameters. Combine spatial attributes to carry out planning at all levels of decision-making to minimize energy consumption under reasonable layout.
- **[1]** employs a sequential decision-making model, addressing urban complexities and spatial planning needs. The urban identity is based on dynamic adaptation with a comprehensive reward system aimed at enhancing service delivery, ecological sustainability and transport efficiency.

In essence, HEEUP is engineered for energy optimization within urban layouts. While [1] multifaceted strategy to meet diverse urban service demands through adaptive spatial planning.
The results prove that HEEUP shows obvious advantages in promoting energy conservation.
