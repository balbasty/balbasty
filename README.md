### <img src="https://upload.wikimedia.org/wikipedia/commons/1/10/PyTorch_logo_icon.svg" height="20" /> PyTorch extensions

These repositories are small self-contained tools written in pure PyTorch, 
that I have found useful in many projects. 

They are (relatively) stable, as backward-compatible as possible with 
respect to PyTorch versions, and can be used as core dependencies to 
higher level projects.

| Package                                                        | Description | Readiness |
| -------------------------------------------------------------- | ----------- | --------- |
| [`torch-bounds`](https://github.com/balbasty/torch-bounds)     | Boundary conditions (circulant, mirror, reflect) and real transforms (DCT, DST) | 🟢 |
| [`torch-interpol`](https://github.com/balbasty/torch-interpol) | High-order spline interpolation | 🟢 |
| [`torch-distmap`](https://github.com/balbasty/torch-distmap)   | Euclidean distance transform | 🟢 |
| [`torch-relay`](https://github.com/balbasty/torch-relay)       | Backward-compatible PyTorch functions (work-in-progress) | 🔴 |
| [`torch-diffeo`](https://github.com/balbasty/torch-diffeo)     | Scaling-and-squaring and Geodesic Shooting layers in PyTorch (work-in-progress) | 🟠 |
| [`jitfields`](https://github.com/balbasty/jitfields)           | Fast functions for dense scalar and vector fields, implemented using just-in-time compilation | 🟠 |

> [!NOTE]
> The last package, `jitfields`, reimplements many of the utilities from the other core
> packages, but does it directly in CUDA/C++.
>
> The CUDA/C++ sources are compiled 
> just-in-time using [`cupy`](https://github.com/cupy/cupy) 
> and [`cppyy`](https://github.com/wlav/cppyy).

### 🧠 Machine Learning for NeuroImaging

These packages underpin my research in medical image computing.

In general, my aim is to write a set of mid-level packages that 
specialize in various tasks (data augmentation, network architectures, 
modality-specific tasks, etc.). 

| Package                                                        | Description | Readiness |
| -------------------------------------------------------------- | ----------- | --------- |
| [`cornucopia`](https://github.com/balbasty/cornucopia)         | An abundance of augmentation layers | 🟢 |
| [`nitorch`](https://github.com/balbasty/nitorch)               | An (overweight and poorly maintained) package for everything neuroimaging | 🟠 |
| [`synthsurf`](https://github.com/balbasty/synthsurf)           | Surface-based image synthesis and PyTorch utilities for triangular surfaces | 🟠 |
| [`synthspline`](https://github.com/balbasty/synthspline)       | Synthetic tubular structures (vessels, axons) for NN pretraining  | 🟠 |
| [`cassetta`](https://github.com/balbasty/cassetta)             | A deep learning toolbox (under early development) | 🔴 |
| [`braindataprep`](https://github.com/balbasty/braindataprep)   | Download, bidsify and preprocess public datasets (work-in-progress) | 🔴 |

### <img src="https://www.svgrepo.com/show/354127/numpy.svg" height="20" /> Numpy tools

| Package                                                                | Description | Readiness |
| ---------------------------------------------------------------------- | ----------- | --------- |
| [`variational_staple`](https://github.com/balbasty/variational_staple) | STAPLE and variants | 🟢 |
| [`optimal_affine`](https://github.com/balbasty/optimal_affine)         | Build optimal "subject to mean space" affines from "subject to subject" pairwise affines | 🟢 |
| [`metrics`](https://github.com/balbasty/metrics)                       | A bunch of metrics | 🔴 |

### <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/21/Matlab_Logo.png/268px-Matlab_Logo.png" height="20" /> Matlab tools 

| Package                                                            | Description | Readiness |
| ------------------------------------------------------------------ | ----------- | --------- |
| [`spm_mni_align`](https://github.com/balbasty/optimal_affine)      | SPM toolbox to align an image to SPM's template space | 🟠 |
| [`multi-bias`](https://github.com/balbasty/multi-bias)             | Fit a multi-view bias field | 🟢 |
| [`super-resolution`](https://github.com/balbasty/super-resolution) | MTV-based denoising/super-resolution | 🟢 |
| [`cmaps`](https://github.com/balbasty/cmaps)                       | (Some) Matplotlib colormaps in Matlab | 🟢 |

### <img src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Tensorflow_logo.svg" height="20" /> Tensorflow tools

| Package                                                        | Description | Readiness |
| -------------------------------------------------------------- | ----------- | --------- |
| [`tfaffine `](https://github.com/balbasty/tfaffine )           | Affine matrices encoded in their Lie algebra, in tensorflow | 🟢 |

<!--
**balbasty/balbasty** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
