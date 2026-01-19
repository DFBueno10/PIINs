# Case Study: Resonant Cavities

## Physical problem
Resonant cavities are closed domains in which waves reflect at the boundaries, producing standing wave patterns at specific resonant frequencies.

## PINN formulation
A Physics-Informed Neural Network is trained to approximate the field distribution inside the cavity by minimizing a loss function composed of:
- the partial differential equation residual (loss_pde);
- the boundary condition error (loss_bc);

## Results
The PINN is able to capture the resonant modes of the cavity, showing qualitative agreement with the expected standing wave patterns. Although, in this case the PIIN needs to be more complex and takes time to converge.

