# Malviso
This project aims to leaverage Image Visualization techniques for malware detection in MS Office files.

The selected dataset is available at [this link in Zenodo](https://zenodo.org/record/4559436) and is taken from [this paper from Computers & Security 2021](https://www.sciencedirect.com/science/article/pii/S0167404821004053).

## State of the art
We took inspiration from the structure of a [similar project](https://ieeexplore.ieee.org/abstract/document/8855273/).

Here the state of our implementation:

- PREPROCESSING
	- [x] Byte plot
	- [ ] Markov plot
- FEATURE EXTRACTION
	- Texture features
		- [x] Gabor filter
		- [ ] LBP - *Local Binary Patterns*
		- [ ] Local Entropy
	- Keypoint Descriptors
		- [x] SIFT - *Scale Invariant Feature Transform* (slower)
		- [x] ORB  - *Oriented FAST and Rotated BRIEF* (faster)
- CLASSIFICATION
	- [x] RF - Random Forest
	- [ ] DT - Decision Tree
	- [ ] KNN - K-nearest neighbors
- RESULTS COMPARISON
	- [ ] Popular antiviruses
	- [ ] PDF image visualization based malware detection
	- [ ] ...
