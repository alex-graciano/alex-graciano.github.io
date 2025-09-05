---
layout: paper
slug: hr example
title: Real-time visualization of 3D terrains and subsurface geological structures
---

Geological structures, both at the surface and subsurface levels, are typically represented by means of voxel data. This model presents a major drawback: its large storage requirements. In this paper, we address this problem and propose the use of a stack-based representation for geological surface-subsurface structures. Although this representation has been mainly used for volumetric terrain visualization in previous works, it has been used as an auxiliary data structure. Therefore, our main contribution in this work is its use as a first-class representation for both processing and visualization of surface and subsurface information. The proposed solution provides real-time visualization of volumetric terrains and subsurface geological structures represented as stacks using a compact data representation in the GPU. Different GPU memory implementations of the stacks have been described, discussing the tradeoffs between performance and storage efficiency. We also introduce a novel algorithm for the calculation of the surface normal vectors using a hybrid object-image space strategy. Moreover, important features for geoscientific applications such as visualization of boreholes or geological cross sections, and selective attenuation of strata have also been implemented in a straightforward way.

This article was originally published in:
- [Advances in Enginerring Software](https://www.sciencedirect.com/science/article/abs/pii/S0965997817304830)
