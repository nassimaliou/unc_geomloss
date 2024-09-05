
## GeomLoss with Uncertainty and Transportation Plan Calculation

This repository contains a modified version of the GeomLoss library, which includes two new features:

1. **Incorporation of Uncertainty in Optimal Transport (OT) Cost**: The added code enables the inclusion of uncertainty values in the computation of the OT cost. This allows the user to account for varying levels of confidence or uncertainty in the input data, making the OT computations more robust and adaptable to real-world scenarios.

2. **Calculation of Transportation Plan from Dual Potentials**: This modification computes the transportation plan $\pi$ directly from the dual potentials obtained by the Sinkhorn algorithm ($f_{ba}$ and $g_{ab}$). This feature provides a direct way to visualize and analyze the optimal transportation mapping between distributions, which can be useful for various applications.

## References
- Séjourné, T., Feydy, J., Vialard, F. X., Trouvé, A., & Peyré, G. (2019). Sinkhorn divergences for unbalanced optimal transport. arXiv preprint arXiv:1910.12958.