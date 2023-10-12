# emc-wiki
Tracking analysis tools for interfacing with EM connectomics datasets

## Data access and manipulation
- [PyChunkedGraph](https://github.com/seung-lab/PyChunkedGraph): implementation of the proofreading/segmentation format ChunkedGraph.
- [MeshParty](https://github.com/sdorkenw/MeshParty): tools for storing and manipulating neuronal meshes and/or skeletons.
   - [Documentation](https://meshparty.readthedocs.io/en/latest/)
- [CAVEclient](https://github.com/seung-lab/CAVEclient): client code for accessing services in the Connectome Annotation Versioning Engine (CAVE).
   - [Documentation](https://caveclient.readthedocs.io/en/latest/?badge=latest#) 

## Feature extraction and processing
- [pcg_skel](https://github.com/AllenInstitute/pcg_skel): package for quickly making skeletons from PyChunkedGraph representations.
- [skeleton_keys](https://github.com/AllenInstitute/skeleton_keys): tools for computing morphological features from skeletons, similar to how this is done for PatchSeq neurons.
   - Requires access to the Allen Institute internal LIMS system for some features
   - Depends on [neuron_morphology](https://github.com/alleninstitute/neuron_morphology/tree/dev) for some computations

## Visualization
- [skeleton_plot](https://github.com/AllenInstitute/skeleton_plot): package for plotting skeletons (with annotations) in Matplotlib.
- [TrimeshVtk](https://github.com/AllenInstitute/TrimeshVtk): tools for creating neuron visualizations in VTK.
   - In the process of splitting these visualization tools out from MeshParty.
- [nglui](https://github.com/seung-lab/NeuroglancerAnnotationUI): tools for generating neuroglancer links programatically.
