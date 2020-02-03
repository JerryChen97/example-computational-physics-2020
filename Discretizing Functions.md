### The procedure
1. Choose basis -> "discretization method"
2. cut-off N -> "resolution"
3. show the result is independent of N -> "convergence"

### Example: P_l(x)
$ f(x) = \sum_{i=0}^N c^i P_i(x) $

Plot the error w.r.t. the basis number N: log E(N)
Convergence region.

Floating-point number accuracy => log(E) eventually vibrates around -16 (the lower bound).

### Derivatives
f(x) = \sum_i c^i P_i(x)
f'(x) = \sum_i c^i P'_i(x) = \sum_i c^i \sum_j d^j_i P_j(x) = d_i^j c^i P_j

### Quadratic
Gaussian
    different choices on collocation points

### Determine the coefficients
Calculate the projection

### PLC
basis for linear interpolations:
    each of the bases only takes 1 at one of the collocation points and zero at other points. "Delta functions".

    Also called "position basis"

### Other topics
## Finite differences
## Pseudo spectral
## Finite volumes
## Finite Elements
## Particles
