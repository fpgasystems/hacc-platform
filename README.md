<!-- <div id="readme" class="Box-body readme blob js-code-block-container">
<article class="markdown-body entry-content p-3 p-md-6" itemprop="text"> -->
<p align="right">
<a href="https://github.com/fpgasystems">fpgasystems</a> <a href="https://github.com/fpgasystems/hacc">HACC</a> <a href="https://github.com/fpgasystems/sgrt">SGRT</a>
</p>

<p align="center">
<img src="https://github.com/fpgasystems/hacc/blob/main/hacc-removebg.png" align="center" width="350">
</p>

<h1 align="center">
  Hardware ACCeleration Platform
</h1>

Research in hardware acceleration is hampered by a lack of an open-​source community and open-​source resources that can be used to build larger systems. Especially when using FPGAs either for research, prototyping, or systems building, most projects start from scratch, having to build almost the entire stack with every system. We are invested considerable efforts to develop an open-​source infrastructure that can be used by us but also by other researchers to explore larger projects and embark on constructing systems that spawn more than a single FPGA or accelerator device. 

This infrastructure also helps to integrate FPGAs as first-​class devices in data centers and the cloud, facilitating their integration with existing systems. Many of these efforts are shared with industry partners, especially with AMD’s University Program and its <a href="https://www.amd-haccs.io">Heterogeneous Accelerated Compute Clusters (HACCs)</a> program.

## Sections

* [Acknowledgment and citation](#acknowledgment-and-citation)
* [Background Materials](/docs/account-renewal.md#account-renewal)
* [Overview](#overview)

# Overview

<p align="center">
<img src="https://github.com/fpgasystems/hacc-platform/blob/main/hardware-acceleration-platform.png" align="center" width="350">
</p>

## ETHZ-HACC
As a multi-core, GPU, and FPGA cluster, ETHZ-​HACC allows research in distributed systems, databases, cloud computing, and hardware acceleration of data science. Internally, we are using ETHZ-HACC to conduct extensive research to assemble our Infrastructure for heterogeneous architectures and hardware acceleration or HACC Platform. 

## Systems Group RunTime (SGRT)
All our advances are open-source and offered as a design platform through the Systems Group RunTime. With this initiative, we hope that ETHZ-HACC users will be able to develop their accelerated applications more quickly.

# Acknowledgment and citation

We encourage ETHZ-HACC users to acknowledge the support provided by AMD and ETH Zürich for their research in presentations, papers, posters, and press releases. Please use the following acknowledgment statement and citation.

## Acknowledgment

This work was supported in part by AMD under the Heterogeneous Accelerated Compute Clusters (HACC) program (formerly known as the XACC program - Xilinx Adaptive Compute Cluster program)

## Citation

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8340448.svg)](https://doi.org/10.5281/zenodo.8340448)

```
@misc{moya2023hacc,
  author       = {Javier Moya, Matthias Gabathuler, Mario Ruiz, Gustavo Alonso},
  title        = {fpgasystems/hacc: ETHZ-HACC 2022.1},
  howpublished = {Zenodo},
  year         = {2023},
  month        = sep,
  note         = {\url{https://doi.org/10.5281/zenodo.8344513}},
  doi          = {10.5281/zenodo.8340448}
}
```

### Download

To get a printed copy of cited resource, please follow [this link.](https://public.3.basecamp.com/p/nEfuexnX55Q1ys7gAUQLjEsN) 

# License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) 2023 FPGA @ Systems Group, ETH Zurich

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.