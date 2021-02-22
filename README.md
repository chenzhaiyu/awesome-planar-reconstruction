# Awesome Planar Reconstruction [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Papers

Those with piece-wise planarity are **highlighted**.

### Plane Extraction / Detection

| Title                                                        | Authors                      | Venue | Year | Resources                                                    |
| :----------------------------------------------------------- | ---------------------------- | ----- | ---- | ------------------------------------------------------------ |
| Efficient RANSAC for Point-Cloud Shape Detection             | Ruwen Schnabel et al.       | Computer Graphics Forum  | 2007 | [[PDF]](https://cg.cs.uni-bonn.de/en/publications/paper-details/schnabel-2007-efficient/) [[CODE]](https://cg.cs.uni-bonn.de/en/publications/paper-details/schnabel-2007-efficient/) |
| The 3D Hough Transform for Plane Detection in Point Clouds: A Review and a new Accumulator Design | Dorit Borrmann et al. | 3D Research | 2011 | [[PDF]](https://www.researchgate.net/publication/228754371_The_3D_Hough_Transform_for_plane_detection_in_point_clouds_A_review_and_a_new_accumulator_design) |
| Planar Shape Detection at Structural Scales | Hao Fang et al. | CVPR | 2018 | [[PDF]](https://hal.inria.fr/hal-01741650/document) |
| Plane Segmentation Based on the Optimal-vector-field in LiDAR Point Clouds | Sheng Xu et al. | PAMI  | 2020 | [[PDF]](https://ieeexplore.ieee.org/document/9095372)|
| From Planes to Corners: Multi-Purpose Primitive Detection in Unorganized 3D Point Clouds | Christiane Sommer et al. | ICRA | 2020 | [[PDF]](https://arxiv.org/ftp/arxiv/papers/2001/2001.07360.pdf) [[CODE]](https://github.com/c-sommer/orthogonal-planes) |

### Single-view Reconstruction

| Title                                                        | Authors                           | Venue | Year | Resources                                                    |
| :----------------------------------------------------------- | --------------------------------- | ----- | ---- | ------------------------------------------------------------ |
| **PlaneNet: Piece-wise Planar Reconstruction from a Single RGB Image** | Chen Liu et al.                   | CVPR  | 2018 | [[PDF]](https://arxiv.org/pdf/1804.06278.pdf) [[CODE]](https://github.com/art-programmer/PlaneNet) |
| **Recovering 3D Planes from a Single Image via Convolutional Neural Networks** | Fengting Yang and Zihan Zhou      | ECCV  | 2018 | [[PDF]](https://faculty.ist.psu.edu/zzhou/paper/ECCV18-plane.pdf) [[CODE]](https://github.com/fuy34/planerecover) |
| **PlaneRCNN: 3D Plane Detection and Reconstruction from a Single Image** | Chen Liu et al.                   | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1812.04072.pdf) [[CODE]](https://github.com/NVlabs/planercnn) |
| **Single-Image Piece-wise Planar 3D Reconstruction via Associative Embedding** | Zehao Yu et al.                   | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1902.09777.pdf) [[CODE]](https://github.com/svip-lab/PlanarReconstruction) |
| Deep Mesh Reconstruction from Single RGB Images via Topology Modification Networks | Junyi Pan et al.                  | ICCV  | 2019 | [[PDF]](https://arxiv.org/pdf/1909.00321.pdf) [[CODE]](https://github.com/jnypan/TMNet) |
| Mesh R-CNN                                                   | Georgia Gkioxari et al.           | ICCV  | 2019 | [[PDF]](https://arxiv.org/pdf/1906.02739.pdf) [[CODE]](https://github.com/facebookresearch/meshrcnn) |
| Learning Pairwise Inter-Plane Relations for Piecewise Planar Reconstruction | Yiming Qian and Yasutaka Furukawa | ECCV  | 2020 | [[PDF]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520324.pdf) |


### Multi-view Reconstruction

| Title                                                        | Authors                   | Venue                      | Year | Resources                                                    |
| :----------------------------------------------------------- | ------------------------- | -------------------------- | ---- | ------------------------------------------------------------ |
| **Reconstructing piecewise planar scenes with multi-view regularization** | Weijie Xi and Xuejin Chen | Computational Visual Media | 2019 | [[PDF]](https://link.springer.com/content/pdf/10.1007/s41095-019-0159-7.pdf) |

### Generative / Implicit Field

| Title                                                        | Authors                   | Venue | Year | Resources                                                    |
| :----------------------------------------------------------- | ------------------------- | ----- | ---- | ------------------------------------------------------------ |
| Continuous Signed Distance Functions for 3D Vision           | Simen Haugo et al.        | 3DV   | 2017 | [[PDF]](https://lightbits.github.io/papers/haugo2017continuous.pdf) |
| AtlasNet: A Papier-Mâché Approach to Learning 3D Surface     | Thibault Groueix et al.   | CVPR  | 2018 | [[PDF]](https://arxiv.org/pdf/1802.05384.pdf) [[CODE]](https://github.com/ThibaultGROUEIX/AtlasNet) |
| DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation | Jeong Joon Park et al.    | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1901.05103.pdf) [[CODE]](https://github.com/facebookresearch/DeepSDF) |
| Occupancy Networks: Learning 3D Reconstruction in Function Space | Lars Mescheder et al.     | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1812.03828) [[CODE]](https://github.com/autonomousvision/occupancy_networks) |
| Learning Implicit Fields for Generative Shape Modeling       | Zhiqin Chen and Hao Zhang | CVPR  | 2019 | [[PDF]](https://arxiv.org/pdf/1812.02822.pdf) [[CODE]](https://github.com/czq142857/implicit-decoder) |
| Learning Shape Templates with Structured Implicit Functions  | Kyle Genova et al.        | ICCV  | 2019 | [[PDF]](https://arxiv.org/pdf/1904.06447.pdf)                |
| Local Deep Implicit Functions for 3D Shape                   | Kyle Genova et al.        | CVPR  | 2020 | [[PDF]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Genova_Local_Deep_Implicit_Functions_for_3D_Shape_CVPR_2020_paper.pdf) |
| **BSP-Net: Generating Compact Meshes via Binary Space Partitioning** | Zhiqin Chen et al.        | CVPR  | 2020 | [[PDF]](https://arxiv.org/pdf/1911.06971.pdf) [[CODE]](https://github.com/czq142857/BSP-NET-pytorch) |
| Points2Surf: Learning Implicit Surfaces from Point Clouds    | Philipp Erler et al.      | ECCV  | 2020 | [[PDF]](https://arxiv.org/pdf/2007.10453.pdf) [[CODE]](https://github.com/ErlerPhilipp/points2surf) |
| Overfit Neural Networks as a Compact Shape Representation    | Thomas Davies et al.      | arXiv | 2020 | [[PDF]](https://arxiv.org/pdf/2009.09808.pdf)                |
| Implicit Geometric Regularization for Learning Shapes        | Amos Gropp et al.         | ICML  | 2020 | [[PDF]](https://arxiv.org/pdf/2002.10099.pdf) [[CODE]](https://github.com/amosgropp/IGR) |
| Deep Parametric Shape Predictions using Distance Fields      | Dmitriy Smirnov et al.    | CVPR  | 2020 | [[PDF]](https://arxiv.org/pdf/1904.08921.pdf) [[CODE]](https://github.com/dmsm/DeepParametricShapes) |
| **PolyGen: An Autoregressive Generative Model of 3D Meshes** | Charlie Nash et al.       | arXiv | 2020 | [[PDF]](https://arxiv.org/pdf/2002.10880v1.pdf)              |
| **CvxNet: Learnable Convex Decomposition**                   | Boyang Deng et al.        | arXiv | 2020 | [[PDF]](https://arxiv.org/pdf/1909.05736.pdf) [[CODE]](https://github.com/tensorflow/graphics/tree/master/tensorflow_graphics/projects/cvxnet) |
| Local Deep Implicit Functions for 3D Shape                   | Kyle Genova et al.        | CVPR  | 2020 | [[PDF]](https://ldif.cs.princeton.edu/assets/paper.pdf) [[CODE]](https://github.com/google/ldif) |
| Coupling Explicit and Implicit Surface Representations for Generative 3D Modeling | Omid Poursaeed et al.     | ECCV  | 2020 | [[PDF]](https://arxiv.org/pdf/2007.10294.pdf)                |

### Kinetic Reconstruction

| Title                                                       | Authors                                   | Venue    | Year | Resources                                                    |
| :---------------------------------------------------------- | ----------------------------------------- | -------- | ---- | ------------------------------------------------------------ |
| KIPPI: KInetic Polygonal Partitioning of Images             | JEAN-PHILIPPE BAUCHET and FLORENT LAFARGE | CVPR     | 2018 | [[PDF]](https://hal.inria.fr/hal-01740958/file/kippi.pdf) [[CODE]](https://www-sop.inria.fr/members/Florent.Lafarge/code/kippi.rar) |
| Approximating shapes in images with low-complexity polygons | Muxingzi Li et al.                        | CVPR     | 2020 | [[PDF]](https://hal.inria.fr/hal-02526028/document) [[CODE]](https://www-sop.inria.fr/members/Florent.Lafarge/code/ASIP.zip) |
| **Kinetic Shape Reconstruction**                            | JEAN-PHILIPPE BAUCHET and FLORENT LAFARGE | SIGGRAPH | 2020 | [[PDF]](https://hal.inria.fr/hal-02924409/document)          |

### Mesh Deformation

| Title                                                        | Authors                             | Venue    | Year | Resources                                                    |
| :----------------------------------------------------------- | ----------------------------------- | -------- | ---- | ------------------------------------------------------------ |
| **Point2Mesh: A Self-Prior for Deformable Meshes**           | RANA HANOCKA et al.                 | SIGGRAPH | 2020 | [[PDF]](https://arxiv.org/pdf/2005.11084.pdf) [[CODE]](https://github.com/ranahanocka/Point2Mesh/) |
| ShapeFlow: Learnable Deformations Among 3D Shapes            | Chiyu Jiang et al.                  | NeurIPS  | 2020 | [[PDF]](https://arxiv.org/abs/2006.07982) [[CODE]](https://github.com/maxjiang93/ShapeFlow) |
| Neural Mesh Flow: 3D Manifold Mesh Generation via Diffeomorphic Flows | Kunal Gupta and Manmohan Chandraker | NeurIPS  | 2020 | [[PDF]](https://arxiv.org/pdf/2007.10973.pdf) [[CODE]](https://github.com/KunalMGupta/NeuralMeshFlow) |
| Learning Deformable Tetrahedral Meshes for 3D Reconstruction | Jun Gao et al.                      | NeurIPS  | 2020 | [[PDF]](https://arxiv.org/abs/2011.01437) [[CODE]](https://github.com/nv-tlabs/DefTet) |

### Constructive / Parametric Geometry

| Title                                                        | Authors                   | Venue                  | Year | Resources                                                    |
| :----------------------------------------------------------- | ------------------------- | ---------------------- | ---- | ------------------------------------------------------------ |
| Boolean operations on 3D selective Nef complexes: Data structure, algorithms, optimized implementation and experiments | Peter Hachenberger et al. | Computational Geometry | 2007 | [[PDF]](https://www.sciencedirect.com/science/article/pii/S0925772107000181) [[CODE]](https://doc.cgal.org/latest/Nef_3/index.html) |
| Mesh arrangements for solid geometry                         | Qingnan Zhou et al.       | SIGGRAPH               | 2016 | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/2897824.2925901) [[CODE]](https://libigl.github.io/tutorial/#boolean-operations-on-meshes) |
| 3D-PRNN: Generating Shape Primitives with Recurrent Neural Networks | Chuhang Zou et al.        | ICCV                   | 2017 | [[PDF]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Zou_3D-PRNN_Generating_Shape_ICCV_2017_paper.pdf) [[CODE]](https://github.com/zouchuhang/3D-PRNN) |
| CSGNet: Neural Shape Parser for Constructive Solid Geometry  | Gopal Sharma et al.       | CVPR                   | 2018 | [[PDF]](https://arxiv.org/pdf/1712.08290.pdf)                |
| ParSeNet: A Parametric Surface Fitting Network for 3D Point Clouds | Gopal Sharma et al.       | ECCV                   | 2020 | [[PDF]](https://arxiv.org/pdf/2003.12181.pdf) [[CODE]](https://github.com/Hippogriff/parsenet-codebase) |
| PQ-NET: A Generative Part Seq2Seq Network for 3D Shapes arXiv:1911.10949v3 | Rundi Wu et al.           | CVPR                   | 2020 | [[PDF]](https://arxiv.org/pdf/1911.10949.pdf) [[CODE]](https://github.com/ChrisWu1997/PQ-NET) |
| **UCSG-Net -- Unsupervised Discovering of Constructive Solid Geometry Tree** | Kacper Kania et al.       | NIPS                   | 2020 | [[PDF]](https://arxiv.org/pdf/2006.09102v3.pdf) [[CODE]](https://github.com/kacperkan/ucsgnet) |

### Triangulation

| Title                                               | Authors                            | Venue | Year | Resources                                                    |
| :-------------------------------------------------- | ---------------------------------- | ----- | ---- | ------------------------------------------------------------ |
| PointTriNet: Learned Triangulation of 3D Point Sets | Nicholas Sharp and Maks Ovsjanikov | ECCV  | 2020 | [[PDF]](https://nmwsharp.com/media/papers/learned-triangulation/learned_triangulation.pdf) [[CODE]](https://github.com/nmwsharp/learned-triangulation) |

### Urban Reconstruction

| Title                                                        | Authors               | Venue          | Year | Resources                                                    |
| :----------------------------------------------------------- | --------------------- | -------------- | ---- | ------------------------------------------------------------ |
| LOD Generation for Urban Scenes                              | Yannick Verdie et al. | ACM TOG        | 2015 | [[PDF]](https://hal.inria.fr/hal-01113078/file/manuscript.pdf) |
| Manhattan-world Urban Reconstruction from Point Clouds       | Minglei Li et al.     | ECCV           | 2016 | [[PDF]](https://3d.bk.tudelft.nl/liangliang/publications/2016/manhattan/manhattan_eccv2016.pdf) |
| **Connect-and-Slice: an hybrid approach for reconstructing 3D objects** | Hao Fang et al.       | CVPR           | 2020 | [[PDF]](https://hal.inria.fr/hal-02541349/document)          |
| **Relation-Constrained Automatic 3D Reconstruction of Buildings in Metropolitan Areas from Photogrammetric Point Clouds** | Yuan Li and Bo Wu     | Remote Sensing | 2021 | [[PDF]](https://www.mdpi.com/2072-4292/13/1/129/pdf)         |

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
