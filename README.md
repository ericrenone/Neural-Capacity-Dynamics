# Capacity as a Learning Limit

---

## Core Result
**Some targets are unreachable under constrained updates**—even with:
- Smooth, convex loss
- Infinite training time
- Stable gradients

**Root cause**: Representation capacity, not optimization.

---

## Simulation
Two learners optimize the same objective:

| Learner       | Update Power         | Outcome            |
|---------------|----------------------|--------------------|
| Low capacity  | Restricted algebra   | Stalls permanently |
| High capacity | Full gradient descent| Converges          |

**Visualization**: Live plot (red = fails, blue = succeeds).

---

## Why It Matters
Explains failures in:
- Low-rank adaptation (LoRA)
- Quantized models
- Federated learning

**Key insight**: Finite distance ≠ learnability.


