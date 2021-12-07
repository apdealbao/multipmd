# Multiple-path-metadynamics (MultiPMD) and PathMaps.

MultiPMD is path-based enhanced sampling technique in which multiple walkers are used to simultaneously sample multiple molecular transition paths. In order to favor the exploration of different reaction channels, some walkers can be used as _repellers_ to push the paths away from each other. Similarly, other walkers can be used as _attractors_ to pinpoint known landmarks. The rest of the walkers perform regular free-energy calculations along the paths. Once the paths have been located, we can render a PathMap, i.e. a 2D free-energy surface projected along the weighted progress along all of the paths and the path indices. The PathMap provides an interpretable view of the merging and forking of the paths, as well as of the free-energy valleys and barriers. 

Here, we present PLUMED input files for the following simulations:

1. MultiPMD with two repellers applied to sample two C7eq-to-C7ax paths in alanine dipeptide
2. PMD with an attractor applied to sample an intermediate path between the two C7eq-to-C7ax paths in alanine dipeptide found in 1.
3. CyclePMD with an attractor applied to sample a cyclic C7eq-to-C7ax-to-C7eq path in alanine dipeptide
4. MultiPMD with six repellers applied to sample six PP1-to-PP2 paths in tetrameric polyproline
5. PathMap applied to the six PP1-to-PP2 paths in tetrameric polyproline found in 4.
