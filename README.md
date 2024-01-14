# Apac
Automated Parcellation tool for human Auditory Cortex (APAC)

APAC is a lightweight module to parcellate human primary auditory cortex comparable to the core in non-human primates using structural MRI (myelin-sensitive index and curvature).

## Requirements
The current version was developed using the data obtained from HCP pipelines.
- Example of required files
```
sbj.L.curvature.32k_fs_LR.shape.gii
sbj.L.midthickness.32k_fs_LR.surf.gii
sbj.L.SmoothedMyelinMap_BC.32k_fs_LR.func.gii
sbj.L.sphere.32k_fs_LR.surf.gii
sbj.L.sulc.32k_fs_LR.shape.gii
sbj.L.thickness.32k_fs_LR.shape.gii
sbj.L.very_inflated.32k_fs_LR.surf.gii
sbj.L.white.32k_fs_LR.surf.gii

sbj.R.curvature.32k_fs_LR.shape.gii
sbj.R.midthickness.32k_fs_LR.surf.gii
sbj.R.SmoothedMyelinMap_BC.32k_fs_LR.func.gii
sbj.R.sphere.32k_fs_LR.surf.gii
sbj.R.sulc.32k_fs_LR.shape.gii
sbj.R.thickness.32k_fs_LR.shape.gii
sbj.R.very_inflated.32k_fs_LR.surf.gii
sbj.R.white.32k_fs_LR.surf.gii
```
## Required library (python>=3.6)
```
nilearn
sklearn
scipy
os
glob
numpy
nibabel
sklearn.mixture
```

