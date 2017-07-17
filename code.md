## Public Code
* **Voxel-Level Functional Connectivity:** MATLAB code implementing functional connectivity methods from "Voxel-Level Functional Connectivity using Spatial Regularization" and "Discovering Voxel-Level Functional Connectivity Between Cortical Regions." Sample data and a demo function are included. <a href="https://github.com/cbaldassano/Voxel-Level-Functional-Connectivity">[GitHub]</a> <a href="https://github.com/cbaldassano/Voxel-Level-Functional-Connectivity/archive/master.zip">[zip]</a>

* **MVPA Decoding** MATLAB code for performing category decoding from ROIs or whole-brain searchlights.<a href="https://github.com/cbaldassano/MVPA-Decoding">[GitHub]</a> <a href="https://github.com/cbaldassano/MVPA-Decoding/archive/master.zip">[zip]</a>

* **Parcellation of Brain Connectivity:** MATLAB and python code implementing spatially-coherent clustering methods from "Parcellating connectivity in spatial maps." A demo function on synthetic data is included. <a href="https://github.com/cbaldassano/Parcellating-connectivity/tree/release">[GitHub]</a> <a href="https://github.com/cbaldassano/Parcellating-connectivity/archive/release.zip">[zip]</a>

* **Event Segmentation:** Implementations of the event segmentation model described in "Discovering event structure in continuous narrative perception and memory." The python version is available as part of the <a href="https://github.com/IntelPNI/brainiak">Brain Imaging Analysis Kit</a>, and the MATLAB version is hosted on <a href="https://github.com/cbaldassano/Event-Segmentation">GitHub</a>.

## Cortical Atlases
* **172-parcel atlas** from Baldassano et al. (2015), "Parcellating connectivity in spatial maps," derived from the original S500 group eigenmap release from the Human Connectome Project.
  * <a href="Atlas172.dscalar.nii">Atlas172.dscalar.nii</a>: CIFTI-2 format, the HCP grayordinate coordinate system.
  * <a href="Atlas172.nii">Atlas172.nii</a>: A volumetric version of the atlas, in MNI space. Voxels whose centers were within 3mm of a surface grayordinate were set to the parcellation label of the closest grayordinate.
  * <a href="Atlas172_PPA.nii">Atlas172_PPA.nii</a>: A version of Atlas172 masked to contain only voxels in the Parahippocampal Place Area, defined by MNI-transforming PPA localizers from 24 subjects and keeping voxels where at least 5 subjects overlapped. PPA covers three parcels in each hemisphere, the most posterior approximately corresponding to PHC1 (#8 left, #93 right) and PHC2 (#17 left, #101 right), and an "anterior PPA" (#16 left, #100 right).
* **Two scene networks** from Baldassano et al. (2016), "Two distinct scene processing networks connecting vision and memory," in MNI space: <a href="twoNetworks.nii.gz">twoNetworks.nii.gz</a>

## Maps from published papers
* Maps from Baldassano et al. (2016), "Human–Object Interactions Are More than the Sum of Their Parts." <a href="HumanObjectMaps.zip">[zip]</a>

## Stimuli
* Stimulus sets from Baldassano et al. (2016), "Human–Object Interactions Are More than the Sum of Their Parts." <a href="https://figshare.com/articles/Human-Object_Stimuli_Experiment_1/5213320">[Experiment 1]</a>, <a href="https://figshare.com/articles/Human-Object_Stimuli_Experiment_2/5213350">[Experiment 2, zip]</a>
