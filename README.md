# ![MeshLab Logo](src/meshlab/images/eye64.png) MeshLab


![Linux](https://github.com/cnr-isti-vclab/meshlab/workflows/Linux/badge.svg)
![MacOS](https://github.com/cnr-isti-vclab/meshlab/workflows/MacOS/badge.svg)
![Windows](https://github.com/cnr-isti-vclab/meshlab/workflows/Windows/badge.svg)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5114037.svg)](https://doi.org/10.5281/zenodo.5114037)

This is the official repository for the source and the binaries of [MeshLab](https://www.MeshLab.net).

MeshLab is an open source, portable, and extensible system for the processing and editing of unstructured large 3D triangular meshes. It is aimed to help the processing of the typical not-so-small unstructured models arising in 3D scanning, providing a set of tools for editing, cleaning, healing, inspecting, rendering and converting this kind of meshes.

MeshLab is mostly based on the open source C++ mesh processing library [VCGlib](http://www.vcglib.net) developed at the [Visual Computing Lab](http://vcg.isti.cnr.it) of [ISTI - CNR](http://www.isti.cnr.it). VCG can be used as a stand-alone large-scale automated mesh processing pipeline, while MeshLab makes it easy to experiment with its algorithms interactively.

MeshLab is available for Windows, macOS, and Linux.

# Releases

You can find the last MeshLab release in the [Releases Tab](https://github.com/cnr-isti-vclab/meshlab/releases) for your favourite platform.
You can also test a built version of MeshLab generated by the last commit pushed in this repository, by downloading the artifacts of the last [Github Actions](https://github.com/cnr-isti-vclab/meshlab/actions) workflow.

# Build instructions

We provide a set of scripts that build and deploy MeshLab automatically. All the scripts can be found in the [scripts](https://github.com/cnr-isti-vclab/meshlab/tree/master/scripts) folder.
For specific build instructions see the [src](https://github.com/cnr-isti-vclab/meshlab/blob/master/src/README.md) folder.

# Structure of the Repository

The MeshLab repository is organized as follows:

* `distrib`: this folder contains a set of prebuilt libraries and shaders that will be used by MeshLab once it is compiled. For more details, check the readme [here](https://github.com/cnr-isti-vclab/meshlab/tree/master/distrib/README.md);
* `docs`: doxygen scripts for generating MeshLab documentation. For more details, check the readme [here](https://github.com/cnr-isti-vclab/meshlab/tree/master/docs);
* `sample` and `textures`: a set of files (meshes, images) used for tests;
* `scripts`: in this folder there is a set of platform-dependent scripts to build and deploy MeshLab. For more details, check the readme [here](https://github.com/cnr-isti-vclab/meshlab/tree/master/scripts/README.md);
* `src`: this folder contains all the source code of MeshLab, its plugins and the external libraries that it requires. For more details, check the readme [here](https://github.com/cnr-isti-vclab/meshlab/blob/master/src/README.md);
* `unsupported`: this folder contains a set of old and unsupported MeshLab plugins that are no longer included and built under MeshLab.

# License

 The Meshlab source is released under the [GPL License](LICENSE.txt).

# Copyright

```
   MeshLab
   http://www.meshlab.net
   All rights reserved.

   VCGLib  http://www.vcglib.net                                     o o
   Visual and Computer Graphics Library                            o     o
                                                                  _   O  _
   Paolo Cignoni                                                    \/)\/
   Visual Computing Lab  http://vcg.isti.cnr.it                    /\/|
   ISTI - Italian National Research Council                           |
   Copyright(C) 2005-2021                                             \
```

# References

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5114037.svg)](https://doi.org/10.5281/zenodo.5114037)


Please, when using this tool, cite the references listed in the official web page https://www.meshlab.net/#references according to you needs, or if you are lazy just cite:

```
@software{meshlab,
  author       = {Paolo Cignoni, Alessandro Muntoni, Guido Ranzuglia, Marco Callieri},
  title        = {{MeshLab}},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.5114037}
}

@inproceedings {LocalChapterEvents:ItalChap:ItalianChapConf2008:129-136,
  booktitle = {Eurographics Italian Chapter Conference},
  editor    = {Vittorio Scarano and Rosario De Chiara and Ugo Erra},
  title     = {{MeshLab: an Open-Source Mesh Processing Tool}},
  author    = {Cignoni, Paolo and Callieri, Marco and Corsini, Massimiliano and Dellepiane, Matteo and Ganovelli, Fabio and Ranzuglia, Guido},
  year      = {2008},
  publisher = {The Eurographics Association},
  ISBN      = {978-3-905673-68-5},
  DOI       = {10.2312/LocalChapterEvents/ItalChap/ItalianChapConf2008/129-136}
}
```

# Contacts

 - Paolo Cignoni (paolo.cignoni (at) isti.cnr.it)
 - Alessandro Muntoni (alessandro.muntoni (at) isti.cnr.it)

# Feedback

For documented and repeatable bugs, feature requests, etc., please use the [GitHub issues](https://github.com/cnr-isti-vclab/meshlab/issues).

For general questions use [StackOverflow](http://stackoverflow.com/questions/tagged/meshlab).
