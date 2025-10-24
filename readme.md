<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Connectomics
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/ceesem/awesome-connectomics/actions/workflows/lint.yaml/badge.svg)](https://github.com/ceesem/awesome-connectomics/actions/workflows/lint.yaml)

<!-- subtitle -->

A curated list of awesome connectomics resources, tools, and particularly well-curated datasets to use them on.

<!-- image -->

<!-- <a href="" target="_blank" rel="noopener noreferrer">
  <img src="" />
</a> -->

<!-- description -->

This list focuses on circuit-scale synapse resolution volumetric neuroanatomy datasets and tools such as those produced by electron microscopy (EM).
It includes resources for data access, neuronal morphology analysis and visualization, network analysis and statistics, and well-curated datasets from various organisms.
The aim is to highlight tools that are broadly applicable across datasets or that might inspire new approaches.
If in doubt that a tool is quite mature enough to be included, we encourage discovery even if a tool is not yet fully mature.

Note: This repository is just starting out and will be expanded over time. Contributions welcome, and please take no offense if your tools or datasets are not yet listed! Please see the [contributing guidelines](contributing.md) to help us grow this list.

</div>

<!-- TOC -->

## Table of Contents

- [Awesome Connectomics](#awesome-connectomics)
  - [Table of Contents](#table-of-contents)
  - [Data Access](#data-access)
  - [Morphology Analysis and Visualization Tools](#morphology-analysis-and-visualization-tools)
  - [Network Analysis and Statistics](#network-analysis-and-statistics)
  - [Online Data Viewing](#online-data-viewing)
  - [Volumetric Data Analysis and Processing](#volumetric-data-analysis-and-processing)
  - [Papers with Code](#papers-with-code)
  - [Datasets](#datasets)
    - [Archives](#archives)
    - [Vertebrates](#vertebrates)
    - [Invertebrates](#invertebrates)
  - [Contributing](#contributing)
    - [Contributors](#contributors)

<!-- CONTENT -->

## Data Access

- [CAVEclient](https://github.com/CAVEconnectome/CAVEclient) - A Python client for accessing CAVE datasets.
- [CloudVolume](https://github.com/seung-lab/cloud-volume) - A Python library for accessing and manipulating Neuroglancer-compatible volumetric data.
- [NatVerse](https://natverse.org) - An R package for accessing and analyzing large-scale neuroanatomical datasets, with a focus on Drosophila.
- [Neuprint-python](https://connectome-neuprint.github.io/neuprint-python/docs/) — A Python client for accessing NeuPrint databases.

## Morphology Analysis and Visualization Tools

- [NAVIS](https://navis-org.github.io/navis/) - A Python library and viewer for the analysis and visualization of neuronal  skeleton data. Excellent for working with transformations between Drosophila dataset coordinate systems.
- [MeshParty](https://github.com/CAVEconnectome/MeshParty) - A Python library for working with 3D mesh, skeleton, and annotation data for neurons and other structures, with an emphasis on CAVE datasets. Reaching end-of-life.
- [MorphoPy](https://github.com/berenslab/MorphoPy) - A Python library for morphometry and topological feature extraction for neuronal skeletons.
- [neuVid](https://github.com/connectome-neuprint/neuVid) - Python scripts to generate Blender animations of mesh-based connectomics data.

## Network Analysis and Statistics

- [Graspologic](https://github.com/graspologic-org/graspologic) - A Python library for graph statistics and machine learning, with a focus on applications in neuroscience such as graph matching.
- [DotMotif](https://github.com/aplbrain/dotmotif) - A Python library for high performance graph motif search and subgraph isomorphism.

## Online Data Viewing

- [Neuroglancer](https://github.com/google/neuroglancer) - A web-based viewer for 3D volumetric data, including support for large cloud datasets and CAVE-based proofreading. The de facto standard for cloud-based volumetric data viewing in connectomics.
- [NGLui](https://github.com/CAVEconnectome/nglui) — A Python library for programmatic generation of Neuroglancer states, including mapping data to Neuroglancer annotations.
- [NeuPrint](https://github.com/connectome-neuprint/neuPrint) - A web-based interface and database for querying connectomics datasets hosted in a Neo4j graph database (see [NeuPrint Explorer](https://github.com/connectome-neuprint/neuPrintExplorer) for the web interface).
- [Codex](https://github.com/murthylab/codex) - A web application for exploring and analyzing neurons and annotations from FlyWire and related datasets.

## Volumetric Data Analysis and Processing

- [Kimimaro](https://github.com/seung-lab/kimimaro/) - A Python library for dense skeletonization of volumetric segmentation data.
- [FastMorph](https://github.com/seung-lab/fastmorph) - A Python library for fast morphological 3D image operations (e.g. dilation and erosion) that are tuned for working with dense 3D labeled data.
- [Igneous](https://github.com/seung-lab/igneous) - A Python library and pipeline for downsampling, meshing, and skeletonizing large volumetric neuroanatomy datasets.
- [euclidean-distance-transform-3d](https://github.com/seung-lab/euclidean-distance-transform-3d) — A Python library for efficiently computing the exact Euclidean distance transform on large 3D volumetric data, which provides a minimum distance to object boundaries.

## Papers with Code

- [Perisomatic Ultrastructure Efficiently Classifies Cells in Mouse Cortex (Elabbady et al. 2025)](https://github.com/AllenInstitute/Perisomatic_Based_CellTyping) - Uses ultrastructural features around the soma to classify cell types in the MICrONs mouse cortex dataset.

## Datasets

### Archives

- [BossDB](https://bossdb.org/) - Hosts imagery, segmentation, and other information for numerous public datasets for volume neuroanatomy, mostly from electron microscopy.

### Vertebrates

- [MICrONs mm3](https://microns-explorer.org/) - A cubic millimeter of functionally imaged mouse visual cortex spanning ~80,000 neurons imaged by the Allen Institute as part of the MICrONs project. See also [MICrONs tutorials](https://tutorial.microns-explorer.org/) for detailed information about data access.
- [H01 (Human)](https://h01-release.storage.googleapis.com/landing.html) - A cubic millimeter EM dataset of human temporal cortex from the Lichtman Lab.

### Invertebrates

- [FlyWire](https://flywire.ai/) - An online community for exploring and proofreading a nearly complete adult Drosophila brain EM dataset.
- [BANC](https://github.com/jasper-tms/the-BANC-fly-connectome/wiki/) - A full adult Drosophila brain EM dataset from the Lee Lab at Harvard Medical School.
- [Janelia NeuPrint](https://neuprint.janelia.org) - Several Drosophila EM datasets hosted by Janelia Research Campus, including the full male CNS, Hemibrain, male nerve cord (MANC), optic lobe, and more.

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/ceesem/awesome-connectomics/graphs/contributors)!
