# Distributions and moments 

PennyLane notebooks
- **2Dgaussian.ipynb**: Loading a 2D Gaussian distribution. Tensor of 2 distributions from 2 qubit registers. Generalization to higher dimensions follows.
- **QuantumGaussianFittingVQE.ipynb**: using pennylane optimizers to fit a variational quantum circuit's wavefunction to a target vector
- **QuantumGaussianMomenta.ipynb**: Retrieving momenta (mean and variance) of gaussian distribution embedded in amplitudes qml.AmplitudeEmbedding in PennyLane. The operators for the momenta are built from Pauli gates through qml.pauli_decompose
