⚙️ Theory & Methodology
Element Type: 4-node bilinear rectangular elements.

Material Model: Linear elastic, isotropic under plane-stress assumptions.

Numerical Methods: Utilizes SciPy's sparse matrix operations (coo_matrix) for efficient memory handling, spsolve for static linear equations, and eigsh for extracting eigenvalues/eigenvectors.

📊 Sample Results

Displacement & Strain Energy Validation: Errors approach zero when compared to Timoshenko beam theory for an aspect ratio of 50.

Stress Recovery: Axial stress correctly displays tension and compression on opposite sides, while shear stress exhibits the theoretical parabolic distribution.

Mode Shapes: The first mode captures the lowest bending shape, with higher modes containing expected additional curvatures
