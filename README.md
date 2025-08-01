# sensor-gradient-issue
Minimal example for a gradient issue with camera intrinsics.

The problem is described in detail in a GitHub issue.

## Contents
- `cx_optimization.ipynb`: Optimization of the principal point offset in x-direction -- comparison of autodiff gradients and gradients from finite differences.
- `sample_ray_differential.ipynb`: Optimization using _sample_ray_differential_ directly instead of _render_.
- `scenes/`: Folder containing scene data.