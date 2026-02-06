# The "Resolution" Limit of Simplified Models

The Restricted (Red) model shows how hardware or software limits—like quantization—act as a hard barrier to intelligence. Because this model rounds its parameters to two decimal places, it hits a noise floor. No matter how much data it sees, it cannot reach a loss of zero, since the true target (e.g., 1.2599…) cannot be represented within its limited precision. In short: compressing a model saves memory but sacrifices the ability to capture “perfect” truth.

# Momentum as a Filter for Chaos

The High-Capacity (Blue) model demonstrates how momentum works as a sophisticated noise filter. The simulation injects intentional noise into the data. The Restricted model reacts to every small fluctuation, producing a jagged, erratic path. The High-Capacity model, however, uses its velocity to smooth out these bumps, showing that a model with a memory of its past steps is far more stable and efficient than one that reacts only to the present.

# The Stability of Information Topology

By tracking Fisher Information, the simulation shows how “smarter” models create a more stable relationship with their data. The Restricted model has unpredictable spikes in information density because its rounding errors create friction against the data. The High-Capacity model maintains a smoother trajectory through information space. This suggests that increasing model capacity not only improves accuracy but also makes learning more predictable and less prone to catastrophic failures.
