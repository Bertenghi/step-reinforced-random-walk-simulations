# Step-reinforced random walk simulations

A step-reinforced random walk (SRRW) is a fascinating stochastic process that allows us to simulate how reinforcement mechanisms, such as memory effects. Further, the phenomenon of anomalous diffusioon often arises in theoretical models by incorpartion of the same underlying mechanics. A fascinating property of such processes is that they admit a phase transition from diffusive to super-diffusive behaviour, typically governed by some underlying memory parameter regulating the strength of the memory.

Here we implement a GPU‑accelerated, tensor‑based step‑reinforced random walk with amnesic memory capabilities (potentially retrograde amne‑
sia) in PyTorch, utilizing CUDA for enhanced computational efficiency
