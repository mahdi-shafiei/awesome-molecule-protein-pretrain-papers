# awesome-pretrain-molecule-protein-papers
- [awesome-pretrain-molecule-protein-papers](#awesome-pretrain-molecule-protein-papers)
- [Molecule](#molecule)
  - [Molecule Pretrain Model / Representation Learning](#molecule-pretrain-model--representation-learning)
  - [Molecule Generative Model](#molecule-generative-model)
  - [Molecule Protein Docking Model](#molecule-protein-docking-model)
- [Tetrahedral Molecular Geometry](#tetrahedral-molecular-geometry)
  - [Chemistry Toolkits](#chemistry-toolkits)
  - [Molecule Dataset](#molecule-dataset)
- [Protein](#protein)
  - [Protein Pretrain Model / Representation Learning](#protein-pretrain-model--representation-learning)
  - [Protein Generative Model](#protein-generative-model)
  - [Protein Dataset](#protein-dataset)
- [3D Model](#3d-model)
  - [SE(3) Model](#se3-model)

# Molecule
## Molecule Pretrain Model / Representation Learning
1. [2023 ICLR] **Uni-Mol: A Universal 3D Molecular Representation Learning Framework** [[paper]](https://openreview.net/forum?id=6K2RM6wVqKu)[[code]]( https://github.com/dptech-corp/Uni-Mol.)
1. [2023 ICLR] **One Transformer Can Understand Both 2D & 3D Molecular Data** [[paper]](https://arxiv.org/pdf/2210.01765.pdf)[[code]](https://github.com/lsj2408/Transformer-M)
1. [2023 KDD] **Automated 3D Pre-Training for Molecular Property Prediction** [[paper]](https://arxiv.org/pdf/2306.07812.pdf)[[code]](https://github.com/LARS-research/3D-PGT)
1. [2022 KDD] **Unified 2D and 3D Pre-Training of Molecular Representations** [[paper]](https://arxiv.org/pdf/2207.08806.pdf)[[code]](https://github.com/teslacool/UnifiedMolPretrain)
1. [2023 KDD] **Dual-view Molecule Pre-training** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3580305.3599317)[[code]](https://github.com/microsoft/DVMP)
1. [2022 arXiv] **CoSP: Co-supervised pretraining of pocket and ligand** [[paper]](https://arxiv.org/pdf/2206.12241.pdf)
1. [2022 Nature Machine Intelligence] **Molecular contrastive learning of representations via graph neural networks** [[paper]](https://arxiv.org/pdf/2102.10056.pdf)[[code]](https://github.com/yuyangw/MolCLR)
1. [2023 ICML] **Enhancing Activity Prediction Models in Drug Discovery with the Ability to Understand Human Language** [[paper]](https://openreview.net/forum?id=oeRMR0La70)
1. [Briefings in Bioinformatics] **MG-BERT: leveraging unsupervised atomic representation learning for molecular property prediction** [[paper]](https://www.researchgate.net/profile/Dong-Sheng-Cao/publication/351363304_MG-BERT_leveraging_unsupervised_atomic_representation_learning_for_molecular_property_prediction/links/609743a9458515d31507d9e2/MG-BERT-leveraging-unsupervised-atomic-representation-learning-for-molecular-property-prediction.pdf)[[code]](https://github.com/zhang-xuan1314/Molecular-graph-BERT)
1. [2021 NIPS] **Motif-based Graph Self-Supervised Learning for Molecular Property Prediction** [[paper]](https://arxiv.org/pdf/2110.00987.pdf)[[code]](https://github.com/zaixizhang/MGSSL)
1. [2022 ICLR] **Spherical Message Passing for 3D Molecular Graphs** [[paper]](https://openreview.net/pdf?id=givsRXsOt9r)[[code]](https://github.com/divelab/DIG)
1. [2022 NIPS] **ComENet: Towards Complete and Efficient Message Passing for 3D Molecular Graphs** [[paper]](https://openreview.net/pdf?id=mCzMqeWSFJ)[[code]](https://github.com/divelab/DIG)
1. [2022 Nvidia] **MegaMolBART** [[web-link]](https://docs.nvidia.com/launchpad/ai/clara-megamolbart/latest/clara-megamolbart-overview.html)[[code]](https://github.com/NVIDIA/MegaMolBART)
1. [2020 NIPS workshop] **Message Passing Networks for Molecules with Tetrahedral Chirality** [[paper]](https://arxiv.org/pdf/2012.00094.pdf)[[code]](https://github.com/PattanaikL/chiral_gnn)
## Molecule Generative Model
1. [2021 ICML] **GraphDF: A Discrete Flow Model for Molecular Graph Generation** [[paper]](https://proceedings.mlr.press/v139/luo21a.html)[[code]](https://github.com/divelab/DIG)
1. [2023 ICLR workshop] **Improving Small Molecule Generation using Mutual Information Machine** [[paper]](https://openreview.net/forum?id=iOJlwUTUyrN) 
1. [2020 KDD] **MoFlow: An Invertible Flow Model for Generating Molecular Graphs** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403104)[[code]](https://github.com/calvin-zcx/moflow)
1. [2022 ICLR] **Geodiff: A geometric diffusion model for molecular conformation generation** [[paper]](https://arxiv.org/pdf/2203.02923.pdf)[[code]](https://github.com/MinkaiXu/GeoDiff)
1. [2022 ICML] **Equivariant Diffusion for Molecule Generation in 3D** [[paper]](https://arxiv.org/pdf/2203.17003.pdf)[[code]](https://github.com/ehoogeboom/e3_diffusion_for_molecules)
1. [2022 NIPS] **Torsional Diffusion for Molecular Conformer Generation** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/994545b2308bbbbc97e3e687ea9e464f-Paper-Conference.pdf)[[code]](https://github.com/gcorso/torsional-diffusion)
1. [2022 ICLR] **An Autoregressive Flow Model for 3D Molecular Geometry Generation from Scratch** [[paper]](https://openreview.net/pdf?id=C03Ajc-NS5W)[[code]](https://github.com/divelab/DIG)
1. [2023 ICLR] **Diffdock: Diffusion steps, twists, and turns for molecular docking** [[paper]](https://arxiv.org/pdf/2210.01776.pdf%3C/p%3E)[[code]](https://github.com/gcorso/DiffDock)
1. [2023 ICLR] **De novo molecular generation via connection-aware motif mining** [[paper]](https://arxiv.org/pdf/2302.01129.pdf)[[code]](https://github.com/MIRALab-USTC/AI4Sci-MiCaM)

## Molecule Protein Docking Model
1. [2015 Bioinformatics] **Fast, accurate, and reliable molecular docking with QuickVina 2** [[paper]](https://academic.oup.com/bioinformatics/article/31/13/2214/195750)
1. [2016 Journal of Chemical Information and Modeling] **Protein-Ligand Scoring with Convolutional Neural Networks** [[paper]](https://arxiv.org/pdf/1612.02751.pdf)
1. [2017 Scientific Reports] **Protein-Ligand Blind Docking Using QuickVina-W With Inter-Process Spatio-Temporal Integration** [[paper]](https://www.nature.com/articles/s41598-017-15571-7)
1. [2018 Journal of Cheminformatics] **P2Rank: machine learning based tool for rapid and accurate prediction of ligand binding sites from protein structure** [[paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0285-8)[[code]](http://github.com/rdk/p2rank)
1. [2019 Journal of Chemical Information and Modeling] **Are the Apo Proteins Suitable for the Rational Discovery of Allosteric Drugs?** [[paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.8b00735)
1. [2021 Journal of Cheminformatics] **GNINA 1.0: molecular docking with deep learning** [[paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00522-2)[[code]](https://github.com/gnina/gnina)
1. [2022 ICML] **EQUIBIND: Geometric Deep Learning for Drug Binding Structure Prediction** [[paper]](https://proceedings.mlr.press/v162/stark22b/stark22b.pdf)[[code]](https://github.com/HannesStark/EquiBind)
1. [2022 NIPS] **TANKBind: Trigonometry-Aware Neural NetworKs for Drug-Protein Binding Structure Prediction** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/2f89a23a19d1617e7fb16d4f7a049ce2-Paper-Conference.pdf)[[code]](https://github.com/luwei0917/TankBind)
1. [2022 Molecular Systems Biology] **Benchmarking AlphaFold-enabled molecular docking predictions for antibiotic discovery**[[paper]](https://www.embopress.org/doi/full/10.15252/msb.202211081)
1. [2022 arXiv] **CoSP: Co-supervised pretraining of pocket and ligand** [[paper]](https://arxiv.org/pdf/2206.12241.pdf)
1. [2023 ICLR] **Diffdock: Diffusion steps, twists, and turns for molecular docking** [[paper]](https://arxiv.org/pdf/2210.01776.pdf%3C/p%3E)[[code]](https://github.com/gcorso/DiffDock)
1. [2023 ICLR] **E3Bind: An End-to-End Equivariant Network for Protein-Ligand Docking** [[paper]](https://arxiv.org/pdf/2210.06069.pdf)
1. [2023 PNAS] **Contrastive learning in protein language space predicts interactions between drugs and protein targets** [[paper]](https://www.pnas.org/doi/abs/10.1073/pnas.2220778120)[[code]](https://github.com/samsledje/ConPLex_dev)

# Tetrahedral Molecular Geometry
1. [2020 NIPS workshop] **Message Passing Networks for Molecules with Tetrahedral Chirality** [[paper]](https://arxiv.org/pdf/2012.00094.pdf)[[code]](https://github.com/PattanaikL/chiral_gnn)
## Chemistry Toolkits
1. [RDKit](http://www.rdkit.org/): Open-source cheminformatics software
2. [PyMOL](https://pymol.org/2/): A user-sponsored molecular visualization system on an open-source foundation
## Molecule Dataset

# Protein 

## Protein Pretrain Model / Representation Learning
1. [2020 bioRxiv] **Transformer protein language models are unsupervised structure learners** [[paper]](https://www.biorxiv.org/content/10.1101/2020.12.15.422761v1.full.pdf)[[code]](https://github.com/facebookresearch/esm)
1. [2021 PNAS] **Biological Structure and Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences** [[paper]](https://www.pnas.org/doi/abs/10.1073/pnas.2016239118)[[code]](https://github.com/facebookresearch/esm)
1. [2021 ICML] **MSA Transformer** [[paper]](http://proceedings.mlr.press/v139/rao21a/rao21a.pdf)[[code]](https://github.com/facebookresearch/esm) 
1. [2021 NIPS] **Language models enable zero-shot prediction of the effects of mutations on protein function** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2021/file/f51338d736f95dd42427296047067694-Paper.pdf)[[code]](https://github.com/facebookresearch/esm) 
1. [2021 Nature] **Highly accurate protein structure prediction with AlphaFold** [[paper]](https://www.nature.com/articles/s41586-021-03819-2)[[code]](https://github.com/deepmind/alphafold)
1. [2021 Science] **Accurate prediction of protein structures and interactions using a three-track neural network** [[paper]](https://www.science.org/doi/10.1126/science.abj8754)[[code]](https://github.com/RosettaCommons/RoseTTAFold)
1. [2022 ICML] **Learning inverse folding from millions of predicted structures** [[paper]](https://proceedings.mlr.press/v162/hsu22a/hsu22a.pdf)[[code]](https://github.com/deepmind/alphafold)
1. [2022 bioRxiv] **OpenFold: Retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization** [[paper]](https://www.biorxiv.org/content/10.1101/2022.11.20.517210v3.full.pdf)[[code]](https://github.com/aqlaboratory/openfold)
1. [2021 PNAS] **Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences** [[paper]](https://www.pnas.org/doi/abs/10.1073/pnas.2016239118)[[code]](https://github.com/facebookresearch/esm)
1. [2022 bioRxiv] **Language models of protein sequences at the scale of evolution enable accurate structure prediction** [[paper]](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1.full.pdf?utm_campaign=M2D2%20Community%20Round-Up&utm_medium=email&utm_source=Revue%20newsletter)
1. [2023 Science] **Evolutionary-scale prediction of atomic-level protein structure with a language model** [[paper]](https://www.science.org/doi/abs/10.1126/science.ade2574)[[code]](https://github.com/facebookresearch/esm)
1. [2022 Nature Communications] **ProtGPT2 is a deep unsupervised language model for protein design** [[paper]](https://www.nature.com/articles/s41467-022-32007-7)[[code]](https://huggingface.co/docs/transformers/main_classes/trainer)
## Protein Generative Model
1. [2023 ICLR] **Learning Hierarchical Protein Representations via Complete 3D Graph Networks**[[paper]](https://openreview.net/forum?id=9X-hgLDLYkQ)[[code]](https://github.com/divelab/DIG)
1. [2023 ICML] **Se(3) diffusion model with application to protein backbone generation** [[paper]](https://arxiv.org/pdf/2302.02277.pdf)[[code]](https://github.com/jasonkyuyim/se3_diffusion)
1. [2023 ICLR] **Diffusion probabilistic modeling of protein backbones in 3d for the motif- scaffolding problem** [[paper]](https://openreview.net/forum?id=6TxBxqNME1Y)[[code]](https://github.com/blt2114/ProtDiff_SMCDiff)
## Protein Dataset

# 3D Model 
## SE(3) Model
1. [2013 Doc] **Lie groups for 2d and 3d transformations** [[paper]](https://ethaneade.org/lie.pdf)
1. [2018 arXiv] **Tensor field networks: Rotation- and translation-equivariant neural networks for 3D point clouds** [[paper]](https://arxiv.org/pdf/1802.08219.pdf)[[code]](https://github.com/tensorfieldnetworks/tensorfieldnetworks)
1. [2020 NIPS] **SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks** [[paper]](https://arxiv.org/abs/2006.10503)[[code]](https://github.com/FabianFuchsML/se3-transformer-public)
1. [2022 ICLR workshop] **Denoising diffusion probabilistic models on so (3) for rotational alignment** [[paper]](https://openreview.net/pdf?id=BY88eBbkpe5)
1. [2022 arXiv] **e3nn: Euclidean Neural Networks** [[paper]](https://arxiv.org/pdf/2207.09453.pdf)