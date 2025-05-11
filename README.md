# Micrograd

Rebuilt Karpathy's micrograd from scratch after watching his YouTube video.  
Tiny autograd + MLP lib, just for learning.

## what's here
- `Value`: tracks data + grad, supports basic ops (+, *, **, etc.)
- backprop from scratch: `.backward()` builds the graph and walks it
- a tiny MLP built using `Neuron`, `Layer`, `MLP`
