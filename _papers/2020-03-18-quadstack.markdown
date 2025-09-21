---
layout: post
title: >
    Quadstack: An efficient representation and direct rendering of layered datasets
date: 2020-03-18
subtitle: Alejandro Graciano, Antonio J Rueda, Adam Pospíšil, Jiří Bittner, Bedrich Benes
image: /assets/images/paper_2020_03_18.png
---

![Quadstack rendering procedure](/assets/images/paper_2020_03_18.png)


We introduce QuadStack, a novel algorithm for volumetric data compression and direct rendering. Our algorithm exploits the data redundancy often found in layered datasets which are common in science and engineering fields such as geology, biology, mechanical engineering, medicine, etc. QuadStack first compresses the volumetric data into vertical stacks which are then compressed into a quadtree that identifies and represents the layered structures at the internal nodes. The associated data (color, material, density, etc.) and shape of these layer structures are decoupled and encoded independently, leading to high compression rates (4× to 54× of the original voxel model memory footprint in our experiments). We also introduce an algorithm for value retrieving from the QuadStack representation and we show that the access has logarithmic complexity. Because of the fast access, QuadStack is suitable for efficient data representation and direct rendering. We show that our GPU implementation performs comparably in speed with the state-of-the-art algorithms (18-79 MRays/s in our implementation), while maintaining a significantly smaller memory footprint.

This article was originally published in:
- [IEEE Transactions on Visualization and Computer Graphics](https://ieeexplore.ieee.org/abstract/document/9040672)
