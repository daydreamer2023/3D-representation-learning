# 3D-Representation-learning

# Survey & Tutorial Deep Geometry Learning
- A Survey on Deep Geometry Learning: From a Representation Perspective (2020) https://arxiv.org/abs/2002.07995
- Learning Generative Models of 3D Structures(2019) https://3dstructgen.github.io/

# Learning 3D Geometry
## Generative Models: High fidelity content is challenging in generative models.
- AtlasNet: A papier-mache approach to learning 3D surface generation. In CVPR, 2018.
- Occupancy networks: Learning 3D reconstruction in function space. In CVPR, 2019
- SCORES: Shape composition with recursive substructure priors. 

## Shape Deformation & Modelling
- 3D-CODED : 3D Correspondences by Deep Deformation https://arxiv.org/pdf/1806.05228.pdf
- SDM-NET: Deep Generative Network for Structured Deformable Mesh (2019)http://geometrylearning.com/sdm-net/
- CAD-Deform: Deformable Fitting of CAD Models to 3D Scans https://arxiv.org/abs/2007.11965
- Joint Learning of 3D Shape Retrieval and Deformation https://arxiv.org/pdf/2101.07889.pdf (2021)
- Deformation-Aware 3D Model Embedding and Retrieval https://arxiv.org/pdf/2004.01228.pdf (ECCV 2020)
- Neural Cages for Detail-Preserving 3D Deformations https://yifita.github.io/publication/deep_cage/ (CVPR 2020)
- MeshODE: A Robust and Scalable Framework for Mesh Deformation https://arxiv.org/pdf/2005.11617.pdf (2020)
- 3DN: 3D Deformation Network https://arxiv.org/pdf/1903.03322.pdf (2019)
- Unsupervised cycle-consistent deformation for shape matching https://arxiv.org/pdf/1907.03165.pdf (2019)
- - code: https://github.com/ThibaultGROUEIX/CycleConsistentDeformation 
- DeformSyncNet: Deformation Transfer via Synchronized Shape Deformation Spaces https://arxiv.org/pdf/2009.01456.pdf (2020)
- Retrieval on Parametric Shape Collections https://cfg.mit.edu/assets/files/retrieval-on-parametric-shape-collections.pdf
- Compositionally Generalizable 3D Structure Prediction https://arxiv.org/pdf/2012.02493.pdf (2020)
- DeepMetaHandles: Learning Deformation Meta-Handles of 3D Meshes with Biharmonic Coordinates https://arxiv.org/pdf/2102.09105.pdf (2021)
- Parsing Geometry Using Structure-Aware Shape Templates https://arxiv.org/pdf/1808.01337.pdf (2018)
- Learning Semantic Deformation Flows with 3D Convolutional Networks http://geometry.cs.ucl.ac.uk/projects/2016/semantic_learning/paper_docs/DefFlow3D.pdf
- Retrieval on Parametric Shape Collections https://dl.acm.org/doi/pdf/10.1145/2983618 (2017)

## Part-Based Understanding
- Towards Part-Based Understanding of RGB-D Scans (2020) https://arxiv.org/pdf/2012.02094.pdf
- DSM-Net: Disentangled Structured Mesh Net for Controllable Generation of Fine Geometry https://arxiv.org/pdf/2008.05440.pdf
- Learning Adaptive Hierarchical Cuboid Abstractions of 3D Shape Collections https://isunchy.github.io/projects/cuboid_abstraction.html (SIGGRAPH Asia 2019)
- SCORES: Shape Composition with Recursive Substructure Priors https://kevinkaixu.net/projects/scores.html (2018)
- StructureNet: Hierarchical Graph Networks for 3D Shape Generation https://arxiv.org/pdf/1908.00575.pdf (2019)
- Monte Carlo Scene Search for 3D Scene Understanding https://arxiv.org/pdf/2103.07969.pdf (2021)
- PartNet: A Large-scale Benchmark for Fine-grained and Hierarchical Part-level 3D Object Understanding https://arxiv.org/pdf/1812.02713.pdf (2018)

## 3D Object Detection
- MLCVNet: Multi-Level Context VoteNet for 3D Object Detection (2020) https://arxiv.org/abs/2004.05679

## 3D Instance Segmentation
- PointGroup: Dual-Set Point Grouping for 3D Instance Segmentation (CVPR 2020) https://arxiv.org/abs/2004.01658

## 3D Geometric Features
- Fully Convolutional Geometric Features (FCGF): https://chrischoy.github.io/publication/fcgf/ (2019)
- What Do Single-view 3D Reconstruction Networks Learn? https://openaccess.thecvf.com/content_CVPR_2019/papers/Tatarchenko_What_Do_Single-View_3D_Reconstruction_Networks_Learn_CVPR_2019_paper.pdf (2019)

## Loss Functions
- Contrastive Loss
  - Paper: http://yann.lecun.com/exdb/publis/pdf/hadsell-chopra-lecun-06.pdf (2006)
- Perceptual Loss
  - Paper: Perceptual Losses for Real-Time Style Transfer and Super-Resolution https://arxiv.org/pdf/1603.08155.pdf (2016)
- Beyond triplet loss: a deep quadruplet network for person re-identification https://arxiv.org/abs/1704.01719 (2017)

## Sampling
- Improved Embeddings with Easy Positive Triplet Mining https://openaccess.thecvf.com/content_WACV_2020/papers/Xuan_Improved_Embeddings_with_Easy_Positive_Triplet_Mining_WACV_2020_paper.pdf (2020)

## RGB-D Self-Supervised
- Self-supervised Geometric Perception https://arxiv.org/pdf/2103.03114.pdf (CVPR 2021 Oral)
- SPSG: Self-Supervised Photometric Scene Generation from RGB-D Scans https://arxiv.org/pdf/2006.14660.pdf (2020)
- Mask2CAD: 3D Shape Prediction by Learning to Segment and Retrieve https://arxiv.org/pdf/2007.13034.pdf (2020)

## 3D Reconstruction
- State of the Art on 3D Reconstruction with RGB-D Cameras https://www.cg.informatik.uni-siegen.de/data/Publications/2018/star1009-main.pdf (2018)
- KinectFusion: Real-Time Dense Surface Mapping and Tracking https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/ismar2011.pdf
- KinectFusion: Real-time 3D Reconstruction and Interaction Using a Moving Depth Camera https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/kinectfusion-uist-comp.pdf
- ElasticFusion: Dense SLAM Without A Pose Graph http://www.roboticsproceedings.org/rss11/p01.pdf
- Robust Reconstruction of Indoor Scenes https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Choi_Robust_Reconstruction_of_2015_CVPR_paper.html
- BundleFusion: Real-time Globally Consistent 3D Reconstruction using On-the-fly Surface Re-integration https://arxiv.org/abs/1604.01093
- Building Rome in a Day https://grail.cs.washington.edu/rome/ (ICCV 2009)

### Learning 3D Reconstruction & Implicit
- Occupancy Networks: https://avg.is.tuebingen.mpg.de/publications/occupancy-networks (CVPR 2019)
- DeepSDF https://arxiv.org/abs/1901.05103

## Metric Learning
- A Metric Learning Reality Check https://arxiv.org/pdf/2003.08505.pdf (2020)
- Bootstrap your own latent: A new approach to self-supervised Learning https://arxiv.org/abs/2006.07733 (2020) (without using negative samples)

## RGB-D to CAD Retrieval
- SHREC’17: RGB-D to CAD Retrieval with ObjectNN Dataset http://www.scenenn.net/pdf/objectnn_shrec17.pdf
- SHREC’18: RGB-D Object-to-CAD Retrieval https://craigyuyu.github.io/home/papers/shrec18.pdf
- A comparison of methods for 3D scene shape retrieval https://www.sciencedirect.com/science/article/pii/S1077314220301090?dgcid=author
- SHREC 2019 - Monocular Image Based 3D Model Retrieval https://diglib.eg.org/bitstream/handle/10.2312/3dor20191068/103-110.pdf?sequence=1&isAllowed=y
- Retrieval on Parametric Shape Collections https://dl.acm.org/doi/10.1145/2983618

## RGB to CAD Retrieval or Mesh (+pose)
- Mask2CAD: 3D Shape Prediction by Learning to Segment and Retrieve https://arxiv.org/pdf/2007.13034.pdf (2020)
- Mesh R-CNN https://arxiv.org/abs/1906.02739 (2019)
- Joint Embeddings of Shapes and Images via CNN Image Purification https://dl.acm.org/doi/pdf/10.1145/2816795.2818071

## Single View Reconstruction
- DISN: Deep Implicit Surface Network for High-quality Single-view 3D Reconstruction https://arxiv.org/abs/1905.10711 (NeurIPS 2019)
## Dataset
- ScanNet http://www.scan-net.org/
- ModelNet https://vision.cs.princeton.edu/projects/2014/ModelNet/# ?
- ShapeNet https://arxiv.org/abs/1512.03012
- DeepDeform: https://arxiv.org/abs/1912.04302 (2020)
- Pix3D http://pix3d.csail.mit.edu/ (image-shape pairs)

## GAN
- 3DGAN: http://3dgan.csail.mit.edu/
- Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks https://arxiv.org/abs/1511.06434 (ICLR 2016)

## 3D
- 3D ShapeNets: A Deep Representation for Volumetric Shapes https://arxiv.org/abs/1406.5670 (2015)

## SLAM
- SemanticFusion: Dense 3D Semantic Mapping with Convolutional Neural Networks https://arxiv.org/abs/1609.05130 (2016)

## PointCloud
- PointContrast: Unsupervised Pre-training for 3D Point Cloud Understanding https://arxiv.org/pdf/2007.10985.pdf (2020)
- Deep Learning for 3D Point Clouds: A Survey https://arxiv.org/pdf/1912.12033.pdf
- PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation https://arxiv.org/abs/1612.00593
- PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space https://arxiv.org/abs/1706.02413
- Neural Point-Based Graphics https://saic-violet.github.io/npbg/ (2020)
- SGPN: Similarity Group Proposal Network for 3D Point Cloud Instance Segmentation (2019) https://arxiv.org/abs/1711.08588

## Hand-Crafted 3D Features
- Spin Images: Using spin images for efficient object recognition in cluttered 3d scenes https://pdfs.semanticscholar.org/30c3/e410f689516983efcd780b9bea02531c387d.pdf
- USC: Unique shape context for 3d data description https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.726.7564&rep=rep1&type=pdf
- PFH: Aligning point cloud views using persistent feature histograms http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.391.5915&rep=rep1&type=pdf
- Fast Point Feature Histograms (FPFH) for 3D Registration https://www.cvl.iis.u-tokyo.ac.jp/class2017/2017w/papers/5.3DdataProcessing/Rusu_FPFH_ICRA2009.pdf (2009)
- SHOT: Unique Signatures of Histograms for Local Surface Description https://www.vision.deis.unibo.it/fede/papers/eccv10.pdf (2010)

## Optical flow
- PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume https://arxiv.org/abs/1709.02371 (2018)

## Instance Segmentation
- Shapemask: Learning to segment novel objects by refining shape priors. https://arxiv.org/abs/1904.03239 (2019)

## Neural Holography
- http://www.computationalimaging.org/publications/neuralholography/

## Differentiable Rendering
- Accelerating 3D Deep Learning with PyTorch3D: 
  - Paper: https://arxiv.org/abs/2007.08501 (2020)
  - Talk in ICML 2020 : https://www.youtube.com/watch?v=eCDBA_SbxCE&t=1408s&ab_channel=PyTorch
- OpenDR: http://files.is.tue.mpg.de/black/papers/OpenDR.pdf (ECCV 2014)
- Neural Mesh Renderer(NMR) https://hiroharu-kato.com/publication/neural_renderer/ (CVPR 2018)
- Soft Rasterizer(SoftRas) https://arxiv.org/abs/1904.01786 (ICCV 2019)
- DIB-R https://nv-tlabs.github.io/DIB-R/ (NeurIPS 2019)

## Neural Rendering
- Neural scene representation and rendering https://deepmind.com/blog/article/neural-scene-representation-and-rendering 2018
- Representing Scenes as Neural Radiance Fields for View Synthesis https://www.matthewtancik.com/nerf (ECCV 2020)
- Layered Neural Rendering for Retiming People in Video https://retiming.github.io/ (SIGGRAPH Asia 2020)
- Rig-space Neural Rendering https://arxiv.org/abs/2003.09820
- Neural Voxel Renderer: Learning an Accurate and Controllable Rendering Tool https://arxiv.org/pdf/1912.04591.pdf (2020)

## 3D Basics
- Delaunay triangulation http://multivis.net/lecture/delaunay.html
- Marching Cubes http://paulbourke.net/geometry/polygonise/
- Chamfer distance https://arxiv.org/pdf/1612.00603.pdf (2016)
- Poisson Surface Reconstruction http://sites.fas.harvard.edu/~cs277/papers/poissonrecon.pdf (2006)
- Laplacian Mesh Processing https://people.eecs.berkeley.edu/~jrs/meshpapers/Sorkine.pdf
- Efficient Variants of the ICP Algorithm http://www.pcl-users.org/file/n4037867/Rusinkiewicz_Effcient_Variants_of_ICP.pdf
- Mean Value Coordinates https://www.cse.wustl.edu/~taoju/research/meanvalue.pdf
- Catmull Clark Subvision https://people.eecs.berkeley.edu/~sequin/CS284/PAPERS/CatmullClark_SDSurf.pdf
- As-Rigid-As-Possible Shape Manipulation  https://www-ui.is.s.u-tokyo.ac.jp/~takeo/papers/rigid.pdf

## Courses
- Discrete Differential Geometry: https://brickisland.net/DDGSpring2021/
- Dynamic Deformables: Implementation and Production Practicalities: https://graphics.pixar.com/library/DynamicDeformablesSiggraph2020/paper.pdf
- Machine Learning Meets Geometry https://geoml.github.io/
- Laplace-Beltrami http://ddg.cs.columbia.edu/SGP2014/LaplaceBeltrami.pdf
