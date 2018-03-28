## Code
* **Voxel-Level Functional Connectivity:** [MATLAB code](https://github.com/cbaldassano/Voxel-Level-Functional-Connectivity) implementing functional connectivity methods from "Voxel-Level Functional Connectivity using Spatial Regularization" and "Discovering Voxel-Level Functional Connectivity Between Cortical Regions." Sample data and a demo function are included.

* **MVPA Decoding:** [MATLAB code](https://github.com/cbaldassano/MVPA-Decoding) for performing category decoding from ROIs or whole-brain searchlights.

* **Parcellation of Brain Connectivity:** [MATLAB and python code]](https://github.com/cbaldassano/Parcellating-connectivity/tree/release) implementing spatially-coherent clustering methods from "Parcellating connectivity in spatial maps." A demo function on synthetic data is included.

* **Event Segmentation:** Implementations of the event segmentation model described in "Discovering event structure in continuous narrative perception and memory." The python version is available as part of the [Brain Imaging Analysis Kit](https://github.com/IntelPNI/brainiak), and the MATLAB version is hosted on [GitHub](https://github.com/cbaldassano/Event-Segmentation).

## Datasets
* Baldassano et al. (2016), "Human–Object Interactions Are More than the Sum of Their Parts."
    * [Raw data (Experiment 2) in BIDS format](https://openneuro.org/datasets/ds001235/)
    * [Decoding maps](resources/HumanObjectMaps.zip)
    * Stimuli: [Experiment 1](https://figshare.com/articles/Human-Object_Stimuli_Experiment_1/5213320), [Experiment 2](https://figshare.com/articles/Human-Object_Stimuli_Experiment_2/5213350)

## Cortical Atlases
* **172-parcel atlas** from Baldassano et al. (2015), "Parcellating connectivity in spatial maps," derived from the original S500 group eigenmap release from the Human Connectome Project.
  * [Atlas172.dscalar.nii](resources/Atlas172.dscalar.nii): CIFTI-2 format, the HCP grayordinate coordinate system.
  * [Atlas172.nii](resources/Atlas172.nii): A volumetric version of the atlas, in MNI space. Voxels whose centers were within 3mm of a surface grayordinate were set to the parcellation label of the closest grayordinate.
  * [Atlas172\_PPA.nii](resources/Atlas172_PPA.nii): A version of Atlas172 masked to contain only voxels in the Parahippocampal Place Area, defined by MNI-transforming PPA localizers from 24 subjects and keeping voxels where at least 5 subjects overlapped. PPA covers three parcels in each hemisphere, the most posterior approximately corresponding to PHC1 (#8 left, #93 right) and PHC2 (#17 left, #101 right), and an "anterior PPA" (#16 left, #100 right).
* **Two scene networks** from Baldassano et al. (2016), "Two distinct scene processing networks connecting vision and memory," in MNI space: [twoNetworks.nii.gz](resources/twoNetworks.nii.gz)
