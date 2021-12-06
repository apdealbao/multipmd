# Multiple-path-metadynamics (MultiPMD) and PathMaps.

MultiPMD is path-based enhanced sampling technique in which multiple walkers are used to simultaneously sample multiple paths. In order to favor the exploration of different transition channels, some walkers can be used as ``repellers'' to push the paths away from each other. Similarly, other walkers can be used as ``attractors'' to known landmarks. The rest of the walkers can perform regular free-energy calculations along the paths. 

1. MultiPMD applied to sample two C7eq-to-C7ax paths in alanine dipeptide
2. PMD with an attractor applied to sample an intermediate path between the two C7eq-to-C7ax paths in alanine dipeptide found in 1.
3. CyclePMD applied to sample a C7eq-to-C7ax-to-C7eq path in alanine dipeptide
4. MultiPMD applied to sample six PP1-to-PP2 paths in tetrameric polyproline
5. PathMap applied to the six PP1-to-PP2 paths found in 4.
