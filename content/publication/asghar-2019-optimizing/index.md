---
title: "Optimizing FPGA-Based Streaming Applications for Throughput Using Pipelining"
date: 2019-01-01
publishDate: 2020-08-13T14:33:24.652929Z
authors: ["Ali Asghar", "Rick van Loo", "Timon Kruiper", "Daniel Ziener"]
publication_types: ["1"]
abstract: "In this paper, we present an automated flow for insertion of pipeline stages in FPGA-based streaming applications in order to increase the throughput. The proposed approach involves the utilization of Xilinx's Automated Pipeline Analysis tool to estimate the number of pipeline stages, while the Rapid-Wright framework incorporate these stages into a synthesized design. The Vivado Design Suite is then used to place and route the modified netlist. Furthermore, a recycling approach has also been proposed to reduce excess registers. The results show a significant improvement in the maximum operating frequency for designs without any sequential loops (~51%) with a moderate resource overhead, while slight gains (~12%) were also observed for designs containing feedback loops."
featured: false
publication: "*2019 International Conference on Field-Programmable Technology (ICFPT)*"
url_pdf: "https://ieeexplore.ieee.org/document/8977878"
---

