# simmelian-backbone
Python code to calculate a Simmelian backbone from a network edgelist
## Overview
This software implemenets an Simmelian backbone network analysis as described by [Nick, Lee, Cunningham, and Brandes](https://www.researchgate.net/publication/262207813_Simmelian_backbones_amplifying_hidden_homophily_in_Facebook_networks) in 2013. The method has an almost magical ability to untangle "hairball" networks by removing links that are not part of embedded relationships.

Prior to this implementation, the analysis was only available in [Visone](https://visone.ethz.ch/), a GUI-based network analysis package. This Python implementation offers the same functionality for calculating the backbone as Visone, except in a stand-alone implementation that can be used for larger networks, in processing pipelines, etc.

The code was written by [Suraj J. Unni](https://github.com/surajjunni). Specifications and testing by [Steve Corman](https://github.com/networks1). We thank [Julian Müller](https://sn.ethz.ch/profile.html?persid=243533) and [Ulrik Brandes](https://github.com/ubrandes-ethz) of the Visone team for their assistance in understanding how to implement the Visone method.

## Dependencies
The code depends on the following implementations:
* Python 3.8
* [NetworKit](https://networkit.github.io/) 7.1
* [Pandas](https://pandas.pydata.org/) 1.4.3
