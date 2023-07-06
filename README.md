# Awsome-AIDD

- [Review](#Review)
- [Representations for Small Molecules](#Representations-for-Small-Molecules)
- [Representations for Proteins](#Representations-for-Proteins)
  - [Protein Language Models (PLMs)](#Protein-Language-Models-(PLMs))
  - [Learning from Protein Structures](#Learning-from-Protein-Structures)  
- [Protein Structure Prediction](#Protein-Structure-Prediction)
- [Effects of Mutations](#Effects-of-Mutations)
- [Compound-protein Interaction (CPI)](#Compound-protein-Interaction-(CPI))
- [Protein-protein Interaction (PPI)](#Protein-protein-Interaction-(PPI))
- [De Novo Molecule Design](#De-Novo-Molecule-Design)
  - [Protein](#Protein)
- [Targeted Protein Degradation](#Targeted-Protein-Degradation)
  - [PROTAC](#PROTAC)
    - [Generation](#Generation)
- [Antibody](#Antibody)
- [Machine Learning Algorithms](#Machine-Learning-Algorithms)
  - [Uncertainty](#Uncertainty)


## Review
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Advancing targeted protein degradation via multiomics profiling and artificial intelligence | JACS | [Link](10.1021/jacs.2c11098) | - |


## Representations for Small Molecules
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Out-of-the-box deep learning prediction of pharmaceutical properties by broadly learned knowledge-based molecular representations | Nat Mach Intell | [Link](https://doi.org/10.1038/s42256-021-00301-6) | [link](https://github.com/shenwanxiang/bidd-molmap) |


## Representations for Proteins 
### [awesome-protein-representation-learning](https://github.com/LirongWu/awesome-protein-representation-learning) is highly recommanded
### Protein Language Models (PLMs)
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2018 | Learned protein embeddings for machine learning | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/bty178) | [Link](https://github.com/fhalab/embeddings_reproduction/) |
| 2019 | Learning protein sequence embeddings using information from structure | ICLR 2019 | [Link](https://openreview.net/pdf?id=SygLehCqtm) | [Link](https://github.com/tbepler/protein-sequence-embedding-iclr2019) |
| 2019 | Evaluating protein transfer learning with TAPE (TAPE)| ICLR 2019 | [Link](https://dl.acm.org/doi/abs/10.5555/3454287.3455156) | [Link](https://github.com/songlab-cal/tape) |
| 2019 | Unified rational protein engineering with sequence-based deep representation learning (UniRep) | Nat Methods | [Link](https://doi.org/10.1038/s41592-019-0598-1) | [Link1](https://github.com/churchlab/UniRep) [Link2](https://github.com/churchlab/UniRep-analysis) |
| 2021 | Learning the protein language: Evolution, structure, and function (ProSE) | Cell Syst | [Link](https://doi.org/10.1016/j.cels.2021.05.017) | [Link](https://github.com/tbepler/prose) |
| 2021 | Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences (ESM-1b) | PNAS | [Link](https://doi.org/10.1073/pnas.201623911) | [Link](https://github.com/facebookresearch/esm) |
| 2021 | MSA Transformer (ESM-MSA-1b) | ICML 2021 | [Link](https://proceedings.mlr.press/v139/rao21a.html) | [Link](https://github.com/facebookresearch/esm) |
| 2021 | Language models enable zero-shot prediction of the effects of mutations on protein function (ESM-1v) | NeurIPS 2021 | [Link](https://openreview.net/forum?id=uXc42E9ZPFs) | [Link](https://github.com/facebookresearch/esm) |
| 2023 | Evolutionary-scale prediction of atomic-level protein structure with a language model (ESM-2, ESMFold) | Science | [Link](10.1126/science.ade2574) | [Link1](https://github.com/facebookresearch/esm) [Link2](https://zenodo.org/record/7566741) |
### Learning from Protein Structures
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2019 | Generative models for graph-based protein design | NeurIPS 2019 | [Link](https://papers.nips.cc/paper_files/paper/2019/hash/f3a4ff4839c56a5f460c88cce3666a2b-Abstract.html) | [Link](https://github.com/jingraham/neurips19-graph-protein-design) |
| 2021 | Learning from protein structure with geometric vector perceptrons (GVP) | ICLR 2021 | [Link](https://openreview.net/forum?id=1YLJDvSx6J4) | [Link](https://github.com/drorlab/gvp) |
| 2022 | Learning inverse folding from millions of predicted structures (ESM-IF1) | ICML 2022 | [Link](https://proceedings.mlr.press/v162/hsu22a.html) | [Link](https://github.com/facebookresearch/esm) |
| 2022 | Pre-Training of Equivariant Graph Matching Networks with Conformation Flexibility for Drug Binding (ProtMD) | Adv Sci (Weinh) | [Link](10.1002/advs.202203796) | [Link](https://github.com/smiles724/ProtMD) |
| 2023 | Protein representation learning by geometric structure pretraining (GearNet) | ICLR 2023 | [Link](https://openreview.net/forum?id=to3qCB3tOh9) | [Link](https://github.com/DeepGraphLearning/GearNet) |


## Protein Structure Prediction
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Evolutionary-scale prediction of atomic-level protein structure with a language model (ESM-2, ESMFold) | Science | [Link](10.1126/science.ade2574) | [Link1](https://github.com/facebookresearch/esm) [Link2](https://zenodo.org/record/7566741) |


## Effects of Mutations
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2017 | Mutation effects predicted from sequence co-variation | Nat Biotechnol | [Link](10.1038/nbt.3769) | [Link](https://github.com/debbiemarkslab/EVcouplings) |
| 2018 | Quantitative Missense Variant Effect Prediction Using Large-Scale Mutagenesis Data | Cell Syst | [Link](10.1016/j.cels.2017.11.003) | [Link](https://github.com/FowlerLab/Envision2017) |
| 2018 | Deep generative models of genetic variation capture the effects of mutations (DeepSequence) | Nat Methods | [Link](https://doi.org/10.1038/s41592-018-0138-4) | [Link](https://github.com/debbiemarkslab/DeepSequence) |
| 2020 | Learning mutational semantics | NeurIPS 2020 | [Link](https://proceedings.neurips.cc/paper/2020/hash/6754e06e46dfa419d5afe3c9781cecad-Abstract.html) | [Link](https://github.com/brianhie/mutational-semantics-neurips2020) |
| 2021 | Learning the language of viral evolution and escape | Science | [Link](https://doi.org/10.1126/science.abd7331) | [Link1](https://github.com/brianhie/viral-mutation), [Link2](https://zenodo.org/record/4034681) |
| 2021 | Protein design and variant prediction using autoregressive generative models | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-22732-w) | [Link1](https://github.com/facebookresearch/esm](https://github.com/debbiemarkslab/SeqDesign)) [Link2](https://doi.org/10.5281/zenodo.4606785) |
| 2021 | ECNet is an evolutionary context-integrated deep learning framework for protein engineering | Nat Commun | [Link](10.1038/s41467-021-25976-8) | [Link1](https://github.com/luoyunan/ECNet) [Link2](https://doi.org/10.5281/zenodo.5294461) |
| 2021 | Language models enable zero-shot prediction of the effects of mutations on protein function (ESM-1v) | NeurIPS 2021 | [Link](https://openreview.net/forum?id=uXc42E9ZPFs) | [Link](https://github.com/facebookresearch/esm) |


## Compound-protein Interaction (CPI)
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2018 | DeepDTA: deep drug-target binding affinity prediction | Bioinformatics | [Link](10.1093/bioinformatics/bty593) | [Link](https://github.com/hkmztrk/DeepDTA) |
| 2019 | DeepAffinity: interpretable deep learning of compound–protein affinity through unified recurrent and convolutional neural networks | Bioinformatics | [Link](10.1093/bioinformatics/btz111) | [Link](https://github.com/Shen-Lab/DeepAffinity) |
| 2020 | MONN: a multi-objective neural network for predicting compound-protein interactions and affinities | Cell Syst | [Link](https://doi.org/10.1016/j.cels.2020.03.002) | [Link](https://github.com/lishuya17/MONN) |
| 2020 | GraphDTA: predicting drug–target binding affinity with graph neural networks | Bioinformatics | [Link](10.1093/bioinformatics/btaa921) | [Link](https://github.com/thinng/GraphDTA) |
| 2020 | TransformerCPI: improving compound–protein interaction prediction by sequence-based deep learning with self-attention mechanism and label reversal experiments | Bioinformatics | [Link](10.1093/bioinformatics/btaa524) | [Link]([https://github.com/thinng/GraphDTA](https://github.com/lifanchen-simm/transformerCPI)) |
| 2020 | Predicting drug–protein interaction using quasi-visual question answering system (DrugVQA) | Nat Mach Intell | [Link](10.1038/s42256-020-0152-y) | [Link](https://github.com/prokia/drugVQA) |
| 2020 | DeepACTION: A deep learning-based method for predicting novel drug-target interactions | Anal Biochem | [Link](10.1016/j.ab.2020.113978) | - |
| 2021 | Multi-PLI: interpretable multi-task deep learning model for unifying protein-ligand interaction datasets | J Cheminform | [Link](10.1186/s13321-021-00510-6) | [Link](https://github.com/Siat-Code/Multi-PLI/) |
| 2021 | MolTrans: Molecular Interaction Transformer for drug-target interaction prediction | Bioinformatics | [Link](10.1093/bioinformatics/btaa880) | [Link](https://github.com/kexinhuang12345/moltrans) |
| 2021 | DeepDTAF: a deep learning method to predict protein–ligand binding affinity | Brief Bioinform | [Link](10.1093/bib/bbab072) | [Link](github.com/KailiWang1/DeepDTAF) |
| 2022 | HyperAttentionDTI: improving drug–protein interaction prediction by sequence-based deep learning with attention mechanism | Bioinformatics | [Link](10.1093/bioinformatics/btab715) | [Link1](https://github.com/zhaoqichang/HpyerAttentionDTI) [Link2](https://zenodo.org/record/5039589) |
| 2022 | DeepREAL: a deep learning powered multi-scale modeling framework for predicting out-of-distribution ligand-induced GPCR activity | Bioinformatics | [Link](10.1093/bioinformatics/btac154) | [Link](https://github.com/XieResearchGroup/DeepREAL) |
| 2022 | MGraphDTA: deep multiscale graph neural network for explainable drug–target binding affinity prediction | Chem Sci | [Link](10.1039/d1sc05180f) | [Link](https://github.com/guaguabujianle/MGraphDTA) |
| 2022 | BridgeDPI: a novel Graph Neural Network for predicting drug–protein interactions | Bioinformatics | [Link](10.1093/bioinformatics/btac155) | [Link](https://github.com/SenseTime-Knowledge-Mining/BridgeDPI) |
| 2022 | Structure-Aware Multimodal Deep Learning for Drug–Protein Interaction Prediction | JCIM | [Link](10.1021/acs.jcim.2c00060) | [Link](https://github.com/biomed-AI/STAMP-DPI) |
| 2022 | TransDTI: Transformer-Based Language Models for Estimating DTIs and Building a Drug Recommendation Workflow | ACS Omega | [Link](10.1021/acsomega.1c05203) | [Link](https://github.com/TeamSundar/transDTI) |
| 2022 | AttentionSiteDTI: an interpretable graph-based model for drug-target interaction prediction using NLP sentence-level relation classification | Brief Bioinform | [Link](10.1093/bib/bbac272) | [Link](https://github.com/yazdanimehdi/AttentionSiteDTI) |
| 2022 | CoaDTI: multi-modal co-attention based framework for drug-target interaction annotation | Brief Bioinform | [Link](10.1093/bib/bbac446) | [Link](https://github.com/Layne-Huang/CoaDTI) |
| 2022 | Improved compound-protein interaction site and binding affinity prediction using self-supervised protein embeddings | BMC Bioinformatics | [Link](10.1186/s12859-022-05107-w) | [Link](https://github.com/Jwoods14/SPE-MONN) |
| 2023 | Improving the generalizability of protein-ligand binding predictions with AI-Bind | Nat Commun | [Link](10.1038/s41467-023-37572-z) | [Link1](https://github.com/ChatterjeeAyan/AI-Bind) [Link2](https://doi.org/10.5281/zenodo.7730755)|
| 2023 | Interpretable bilinear attention network with domain adaptation improves drug–target prediction (DrugBAN) | Nat Mach Intell | [Link](10.1038/s42256-022-00605-1) | [Link1](https://github.com/peizhenbai/DrugBAN) [Link2](https://doi.org/10.24433/CO.3558316.v1)|


## Protein-protein Interaction (PPI)
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Large-scale discovery of protein interactions at residue resolution using co-evolution calculated from genomic sequences | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-21636-z) | [Link](https://github.com/debbiemarkslab/EVcouplings) |


## De Novo Molecule Design
### Protein
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Large language models generate functional protein sequences across diverse families (ProGen) | Nat Biotechnol | [Link](10.1038/s41587-022-01618-2) | [Link](https://github.com/debbiemarkslab/EVcouplings](https://github.com/salesforce/progen)) [Link2](https://zenodo.org/record/7296780) |


## Targeted Protein Degradation
### PROTAC
#### Generation
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Deep Generative Models for 3D Linker Design (DeLinker) | JCIM | [Link](10.1021/acs.jcim.9b01120) | [Link](https://github.com/oxpig/DeLinker) |
| 2021 | Deep generative design with 3D pharmacophoric constraints (DEVELOP）| Chem Sci | [Link](10.1039/d1sc02436a) | [Link](https://github.com/oxpig/DEVELOP) |


## Antibody
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Protein design and variant prediction using autoregressive generative models | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-22732-w) | [Link1](https://github.com/facebookresearch/esm](https://github.com/debbiemarkslab/SeqDesign)) [Link2](https://doi.org/10.5281/zenodo.4606785) |


## Machine Learning Algorithms
### Uncertainty
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Leveraging uncertainty in machine learning accelerates biological discovery and design | Cell Syst | [Link](10.1016/j.cels.2020.09.007) | [Link](https://github.com/brianhie/uncertainty) |


# Related Awesome
* [awesome-protein-representation-learning](https://github.com/LirongWu/awesome-protein-representation-learning)
* [awesome-AI-based-protein-design](https://github.com/opendilab/awesome-AI-based-protein-design)
* [awesome-graph-representation-learning](https://github.com/zlpure/awesome-graph-representation-learning)
* [awesome-graph-self-supervised-learning](https://github.com/LirongWu/awesome-graph-self-supervised-learning)
* [awesome-self-supervised-gnn](https://github.com/ChandlerBang/awesome-self-supervised-gnn)
* [awesome-self-supervised-learning-for-graphs](https://github.com/SXKDZ/awesome-self-supervised-learning-for-graphs)
