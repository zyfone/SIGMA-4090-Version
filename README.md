SIGMA with CUDA 4090 Support
This repository is based on the original (https://github.com/CityU-AIM-Group/SIGMA) project developed by the CityU-AIM Group.

Overview
We have made specific modifications to this repository to support the latest CUDA versions compatible with the NVIDIA RTX 4090 GPU. The adjustments were made to ensure compatibility and optimized performance on modern hardware.

Modifications
Two main files have been modified:

fcos_core/csrc: Updated to ensure compatibility with the latest CUDA libraries.
setup.py: Adjusted to properly configure the environment and build process for CUDA support on the RTX 4090.
These changes were necessary to enable efficient and error-free execution on systems utilizing the NVIDIA RTX 40XX GPU with up-to-date CUDA drivers.
