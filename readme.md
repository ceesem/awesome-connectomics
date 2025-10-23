<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Connectomics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/ceesem/awesome-connectomics/actions/workflows/lint.yaml/badge.svg)](https://github.com/ceesem/awesome-connectomics/actions/workflows/lint.yaml)

<!-- subtitle -->

A curated list of awesome connectomics resources, tools, and particularly well-curated datasets to use them on.

<!-- image -->

<!-- <a href="" target="_blank" rel="noopener noreferrer">
  <img src="" />
</a> -->

<!-- description -->

This list focuses on circuit-scale synapse resolution volumetric neuroanatomy datasets and tools such as those produced by electron microscopy (EM). It includes resources for data access, neuronal morphology analysis and visualization, network analysis and statistics, and well-curated datasets from various organisms.

</div>

<!-- TOC -->

## Contents

- [Awesome Connectomics  ](#awesome-connectomics--)
  - [Contents](#contents)
  - [Data Access](#data-access)
  - [Analysis and Visualization Tools](#analysis-and-visualization-tools)
  - [Network Analysis and Statistics](#network-analysis-and-statistics)
  - [Online Data Viewers](#online-data-viewers)
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
- 
## Analysis and Visualization Tools

- [NAVIS](https://navis-org.github.io/navis/) - A Python library and viewer for the analysis and visualization of neuronal  skeleton data. Excellent for working with transformations between Drosophila dataset coordinate systems.
- [MeshParty](https://github.com/CAVEconnectome/MeshParty) - A Python library for working with 3D mesh, skeleton, and annotation data for neurons and other structures, with an emphasis on CAVE datasets. Reaching end-of-life.
- [NGLui](https://github.com/CAVEconnectome/nglui) — A Python library for programmatic generation of Neuroglancer states, including mapping data to Neuroglancer annotations.

## Network Analysis and Statistics

- [Graspologic](https://github.com/graspologic-org/graspologic) - A Python library for graph statistics and machine learning, with a focus on applications in neuroscience such as graph matching.
- [DotMotif](https://github.com/aplbrain/dotmotif) - A Python library for high performance graph motif search and subgraph isomorphism.

## Online Data Viewers

- [Neuroglancer](https://github.com/google/neuroglancer) - A web-based viewer for 3D volumetric data, including support for large cloud datasets and CAVE-based proofreading.

## Papers with Code

- [Perisomatic Ultrastructure Efficiently Classifies Cells in Mouse Cortex (Elabbady et al. 2025)](https://github.com/AllenInstitute/Perisomatic_Based_CellTyping) - Uses ultrastructural features around the soma to classify cell types in the MICrONs mouse cortex dataset.

## Datasets

### Archives

- [BossDB](https://bossdb.org/) - Hosts imagery, segmentation, and other information for numerous public datasets for volume neuroanatomy, mostly from electron microscopy.

### Vertebrates

- [MICrONs mm3](https://microns-explorer.org/) - A cubic millimeter of functionally imaged mouse visual cortex spanning ~80,000 neurons imaged by the Allen Institute as part of the MICrONs project. See also [MICrONs tutorials](https://tutorial.microns-explorer.org/) for detailed information about data access.
- [H01 (Human)](https://h01-release.storage.googleapis.com/landing.html) - A cubic millimeter EM dataset of human temporal cortex from the Lichtman Lab.

### Invertebrates

- FlyWire
- FANC
- BANC
- MANC
- Hemibrain

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/ceesem/awesome-connectomics/graphs/contributors)!
