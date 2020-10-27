# Awesome Planar Reconstruction [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Papers

### Plane extraction/detection

| Title                                                        | Authors                      | Venue | Year | Resources                                                    |
| :----------------------------------------------------------- | ---------------------------- | ----- | ---- | ------------------------------------------------------------ |
| Efficient RANSAC for Point-Cloud Shape Detection             | Ruwen Schnabel et al.       | Computer Graphics Forum  | 2007 | [[PDF]](https://cg.cs.uni-bonn.de/en/publications/paper-details/schnabel-2007-efficient/) [[CODE]](https://cg.cs.uni-bonn.de/en/publications/paper-details/schnabel-2007-efficient/) |
| Plane Segmentation Based on the Optimal-vector-field in LiDAR Point Clouds | Sheng Xu et al. | PAMI  | 2020 | [[PDF]](https://ieeexplore.ieee.org/document/9095372)|

### Single-view Reconstruction

| Title                                                        | Authors                      | Venue | Year | Resources                                                    |
| :----------------------------------------------------------- | ---------------------------- | ----- | ---- | ------------------------------------------------------------ |
| **PlaneNet: Piece-wise Planar Reconstruction from a Single RGB Image** | Chen Liu et al.              | CVPR  | 2018 | [[PDF]](https://arxiv.org/pdf/1804.06278.pdf) [[CODE]](https://github.com/art-programmer/PlaneNet) |
| **Recovering 3D Planes from a Single Image via Convolutional Neural Networks** | Fengting Yang and Zihan Zhou | ECCV  | 2018 | [[PDF]](https://faculty.ist.psu.edu/zzhou/paper/ECCV18-plane.pdf) [[CODE]](https://github.com/fuy34/planerecover) |
| **PlaneRCNN: 3D Plane Detection and Reconstruction from a Single Image** | Chen Liu et al.              | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1812.04072.pdf) [[CODE]](https://github.com/NVlabs/planercnn) |
| **Single-Image Piece-wise Planar 3D Reconstruction via Associative Embedding** | Zehao Yu et al.              | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1902.09777.pdf) [[CODE]](https://github.com/svip-lab/PlanarReconstruction) |
| Deep Mesh Reconstruction from Single RGB Images via Topology Modification Networks | Junyi Pan et al.             | ICCV  | 2019 | [[PDF]](https://arxiv.org/pdf/1909.00321.pdf) [[CODE]](https://github.com/jnypan/TMNet) |


### Multi-view Reconstruction

| Title                                                        | Authors                   | Venue                      | Year | Resources                                                    |
| :----------------------------------------------------------- | ------------------------- | -------------------------- | ---- | ------------------------------------------------------------ |
| **Reconstructing piecewise planar scenes with multi-view regularization** | Weijie Xi and Xuejin Chen | Computational Visual Media | 2019 | [[PDF]](https://link.springer.com/content/pdf/10.1007/s41095-019-0159-7.pdf) |

### Generative / Implicit Field

| Title                                                        | Authors                   | Venue | Year | Resources                                                    |
| :----------------------------------------------------------- | ------------------------- | ----- | ---- | ------------------------------------------------------------ |
| DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation | Jeong Joon Park et al.    | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1901.05103.pdf) [[CODE]](https://github.com/facebookresearch/DeepSDF) |
| Learning Implicit Fields for Generative Shape Modeling       | Zhiqin Chen and Hao Zhang | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1812.02822.pdf) [[CODE]](https://github.com/czq142857/implicit-decoder) |
| **BSP-Net: Generating Compact Meshes via Binary Space Partitioning** | Zhiqin Chen et al.        | CVPR  | 2020 | [[PDF]](https://arxiv.org/pdf/1911.06971.pdf) [[CODE]](https://github.com/czq142857/BSP-NET-pytorch) |
| **Points2Surf: Learning Implicit Surfaces from Point Clouds** | Philipp Erler et al.      | ECCV  | 2020 | [[PDF]](https://arxiv.org/pdf/2007.10453.pdf) [[CODE]](https://github.com/ErlerPhilipp/points2surf) |
| Overfit Neural Networks as a Compact Shape Representation    | Thomas Davies et al.      | arXiv | 2020 | [[PDF]](https://arxiv.org/pdf/2009.09808.pdf)                |
| Implicit Geometric Regularization for Learning Shapes        | Amos Gropp et al.         | ICML  | 2020 | [[PDF]](https://arxiv.org/pdf/2002.10099.pdf) [[CODE]](https://github.com/amosgropp/IGR) |
| Deep Parametric Shape Predictions using Distance Fields      | Dmitriy Smirnov et al.    | CVPR  | 2020 | [[PDF]](https://arxiv.org/pdf/1904.08921.pdf) [[CODE]](https://github.com/dmsm/DeepParametricShapes) |
| **PolyGen: An Autoregressive Generative Model of 3D Meshes** | Charlie Nash et al.       | arXiv | 2020 | [[PDF]](https://arxiv.org/pdf/2002.10880v1.pdf)              |

### Kinetic Reconstruction

| Title                            | Authors                                   | Venue   | Year | Resources                                     |
| :------------------------------- | ----------------------------------------- | ------- | ---- | --------------------------------------------- |
| **Kinetic Shape Reconstruction** | JEAN-PHILIPPE BAUCHET and FLORENT LAFARGE | ACM TOG | 2020 | [[PDF]](https://arxiv.org/pdf/1812.02822.pdf) |

### Mesh Deformation

| Title                                              | Authors             | Venue    | Year | Resources                                                    |
| :------------------------------------------------- | ------------------- | -------- | ---- | ------------------------------------------------------------ |
| **Point2Mesh: A Self-Prior for Deformable Meshes** | RANA HANOCKA et al. | SIGGRAPH | 2020 | [[PDF]](https://arxiv.org/pdf/2005.11084.pdf) [[CODE]](https://github.com/ranahanocka/Point2Mesh/) |
| ShapeFlow: Learnable Deformations Among 3D Shapes  | Chiyu Jiang et al.  | NeurIPS  | 2020 | [[PDF]](https://arxiv.org/abs/2006.07982) [[CODE]](https://github.com/maxjiang93/ShapeFlow) |

### Constructive / Parametric Geometry

| Title                                                        | Authors             | Venue | Year | Resources                                                    |
| :----------------------------------------------------------- | ------------------- | ----- | ---- | ------------------------------------------------------------ |
| CSGNet: Neural Shape Parser for Constructive Solid Geometry  | Gopal Sharma et al. | CVPR  | 2018 | [[PDF]](https://arxiv.org/pdf/1712.08290.pdf)                |
| ParSeNet: A Parametric Surface Fitting Network for 3D Point Clouds | Gopal Sharma et al. | ECCV  | 2020 | [[PDF]](https://arxiv.org/pdf/2003.12181.pdf) [[CODE]](https://github.com/Hippogriff/parsenet-codebase) |

### Triangulation

| Title                                               | Authors                            | Venue | Year | Resources                                                    |
| :-------------------------------------------------- | ---------------------------------- | ----- | ---- | ------------------------------------------------------------ |
| PointTriNet: Learned Triangulation of 3D Point Sets | Nicholas Sharp and Maks Ovsjanikov | ECCV  | 2020 | [[PDF]](https://nmwsharp.com/media/papers/learned-triangulation/learned_triangulation.pdf) [[CODE]](https://github.com/nmwsharp/learned-triangulation) |

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
