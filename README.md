# Awesome-AIDD

- [Review](#Review)
- [Database](#Database)
- [Representations for Small Molecules](#Representations-for-Small-Molecules)
- [Representations for Proteins](#Representations-for-Proteins)
  - [Protein Language Models (PLMs)](#Protein-Language-Models-plms)
  - [Learning from Protein Structures](#Learning-from-Protein-Structures)  
- [Protein Structure Prediction](#Protein-Structure-Prediction)
- [Effects of Mutations](#Effects-of-Mutations)
- [Compound-protein Interaction (CPI)](#Compound-protein-Interaction-cpi)
  - [Protein Sequence Based](#Protein-Sequence-Based)
  - [Structure Based (CNN)](#Structure-Based-CNN)
  - [Structure Based (GNN)](#Structure-Based-GNN)
  - [Docking Based](#Docking-Based)
  - [Latent Biases](#Latent-Biases)
  - [Link Prediction](#Link-Prediction)
- [Protein-protein Interaction (PPI)](#Protein-protein-Interaction-ppi)
- [Molecular Property Prediction](#Molecular-Property-Prediction)
- [De Novo Molecule Design](#De-Novo-Molecule-Design)
  - [Protein](#Protein)
- [Targeted Protein Degradation](#Targeted-Protein-Degradation)
  - [PROTAC](#PROTAC)
    - [Generation](#Generation)
- [Antibody](#Antibody)
- [RNA](#RNA)
- [Machine Learning Algorithms](#Machine-Learning-Algorithms)
  - [Uncertainty](#Uncertainty)


## Review
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Advancing targeted protein degradation via multiomics profiling and artificial intelligence | JACS | [Link](https://doi.org/10.1021/jacs.2c11098) | - |


## Database
| Year | Title | Journal | Paper | Website |
| --- | --- | --- | --- | --- |
| 2022 | Therapeutic target database update 2022: facilitating drug discovery with enriched comparative data of targeted agents (TTD) | NAR | [Link](https://doi.org/10.1093/nar/gkab953) | [Link](https://idrblab.org/ttd/) |
| 2022 | NPCDR: natural product-based drug combination and its disease-specific molecular regulation | NAR | [Link](https://doi.org/10.1093/nar/gkab913) | [Link](https://idrblab.org/npcdr/) |
| 2022 | VARIDT 2.0: structural variability of drug transporter | NAR | [Link](https://doi.org/10.1093/nar/gkab1013) | [Link](https://idrblab.org/varidt/) |
| 2023 | DrugMAP: molecular atlas and pharma-information of all drugs | NAR | [Link](https://doi.org/10.1093/nar/gkac813) | [Link](https://idrblab.org/drugmap/) |
| 2023 | DRESIS: the first comprehensive landscape of drug resistance information | NAR | [Link](https://doi.org/10.1093/nar/gkac812) | [Link](https://idrblab.org/dresis) |


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
| 2023 | Evolutionary-scale prediction of atomic-level protein structure with a language model (ESM-2, ESMFold) | Science | [Link](https://doi.org/10.1126/science.ade2574) | [Link1](https://github.com/facebookresearch/esm) [Link2](https://zenodo.org/record/7566741) |
### Learning from Protein Structures
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2017 | TopologyNet: Topology based deep convolutional and multi-task neural networks for biomolecular property predictions | PLoS Comput Biol | [Link](https://doi.org/10.1371/journal.pcbi.1005690) | - |
| 2019 | Generative models for graph-based protein design | NeurIPS 2019 | [Link](https://papers.nips.cc/paper_files/paper/2019/hash/f3a4ff4839c56a5f460c88cce3666a2b-Abstract.html) | [Link](https://github.com/jingraham/neurips19-graph-protein-design) |
| 2021 | Learning from protein structure with geometric vector perceptrons (GVP) | ICLR 2021 | [Link](https://openreview.net/forum?id=1YLJDvSx6J4) | [Link](https://github.com/drorlab/gvp) |
| 2022 | Learning inverse folding from millions of predicted structures (ESM-IF1) | ICML 2022 | [Link](https://proceedings.mlr.press/v162/hsu22a.html) | [Link](https://github.com/facebookresearch/esm) |
| 2022 | Pre-training of equivariant graph matching networks with conformation flexibility for drug binding (ProtMD) | Adv Sci (Weinh) | [Link](https://doi.org/10.1002/advs.202203796) | [Link](https://github.com/smiles724/ProtMD) |
| 2023 | Protein representation learning by geometric structure pretraining (GearNet) | ICLR 2023 | [Link](https://openreview.net/forum?id=to3qCB3tOh9) | [Link](https://github.com/DeepGraphLearning/GearNet) |


## Protein Structure Prediction
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Evolutionary-scale prediction of atomic-level protein structure with a language model (ESM-2, ESMFold) | Science | [Link](https://doi.org/10.1126/science.ade2574) | [Link1](https://github.com/facebookresearch/esm) [Link2](https://zenodo.org/record/7566741) |


## Effects of Mutations
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2017 | Mutation effects predicted from sequence co-variation | Nat Biotechnol | [Link](https://doi.org/10.1038/nbt.3769) | [Link](https://github.com/debbiemarkslab/EVcouplings) |
| 2018 | Quantitative Missense Variant Effect Prediction Using Large-Scale Mutagenesis Data | Cell Syst | [Link](https://doi.org/10.1016/j.cels.2017.11.003) | [Link](https://github.com/FowlerLab/Envision2017) |
| 2018 | Deep generative models of genetic variation capture the effects of mutations (DeepSequence) | Nat Methods | [Link](https://doi.org/10.1038/s41592-018-0138-4) | [Link](https://github.com/debbiemarkslab/DeepSequence) |
| 2020 | Learning mutational semantics | NeurIPS 2020 | [Link](https://proceedings.neurips.cc/paper/2020/hash/6754e06e46dfa419d5afe3c9781cecad-Abstract.html) | [Link](https://github.com/brianhie/mutational-semantics-neurips2020) |
| 2021 | Learning the language of viral evolution and escape | Science | [Link](https://doi.org/10.1126/science.abd7331) | [Link1](https://github.com/brianhie/viral-mutation) [Link2](https://zenodo.org/record/4034681) |
| 2021 | Protein design and variant prediction using autoregressive generative models | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-22732-w) | [Link1](https://github.com/facebookresearch/esm](https://github.com/debbiemarkslab/SeqDesign)) [Link2](https://doi.org/10.5281/zenodo.4606785) |
| 2021 | ECNet is an evolutionary context-integrated deep learning framework for protein engineering | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-25976-8) | [Link1](https://github.com/luoyunan/ECNet) [Link2](https://doi.org/10.5281/zenodo.5294461) |
| 2021 | Language models enable zero-shot prediction of the effects of mutations on protein function (ESM-1v) | NeurIPS 2021 | [Link](https://openreview.net/forum?id=uXc42E9ZPFs) | [Link](https://github.com/facebookresearch/esm) |


## Compound-protein Interaction (CPI)
### Protein Sequence Based
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2018 | DeepDTA: deep drug-target binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/bty593) | [Link](https://github.com/hkmztrk/DeepDTA) |
| 2019 | DeepAffinity: interpretable deep learning of compound–protein affinity through unified recurrent and convolutional neural networks | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btz111) | [Link](https://github.com/Shen-Lab/DeepAffinity) |
| 2020 | MONN: a multi-objective neural network for predicting compound-protein interactions and affinities | Cell Syst | [Link](https://doi.org/10.1016/j.cels.2020.03.002) | [Link](https://github.com/lishuya17/MONN) |
| 2020 | GraphDTA: predicting drug–target binding affinity with graph neural networks | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btaa921) | [Link](https://github.com/thinng/GraphDTA) |
| 2020 | TransformerCPI: improving compound–protein interaction prediction by sequence-based deep learning with self-attention mechanism and label reversal experiments | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btaa524) | [Link](https://github.com/thinng/GraphDTA](https://github.com/lifanchen-simm/transformerCPI)) |
| 2020 | Predicting drug–protein interaction using quasi-visual question answering system (DrugVQA) | Nat Mach Intell | [Link](https://doi.org/10.1038/s42256-020-0152-y) | [Link](https://github.com/prokia/drugVQA) |
| 2020 | DeepACTION: A deep learning-based method for predicting novel drug-target interactions | Anal Biochem | [Link](https://doi.org/10.1016/j.ab.2020.113978) | - |
| 2021 | Multi-PLI: interpretable multi-task deep learning model for unifying protein-ligand interaction datasets | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00510-6) | [Link](https://github.com/Siat-Code/Multi-PLI/) |
| 2021 | MolTrans: Molecular Interaction Transformer for drug-target interaction prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btaa880) | [Link](https://github.com/kexinhuang12345/moltrans) |
| 2021 | DeepDTAF: a deep learning method to predict protein–ligand binding affinity | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbab072) | [Link](github.com/KailiWang1/DeepDTAF) |
| 2022 | HyperAttentionDTI: improving drug–protein interaction prediction by sequence-based deep learning with attention mechanism | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btab715) | [Link1](https://github.com/zhaoqichang/HpyerAttentionDTI) [Link2](https://zenodo.org/record/5039589) |
| 2022 | DeepREAL: a deep learning powered multi-scale modeling framework for predicting out-of-distribution ligand-induced GPCR activity | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac154) | [Link](https://github.com/XieResearchGroup/DeepREAL) |
| 2022 | MGraphDTA: deep multiscale graph neural network for explainable drug–target binding affinity prediction | Chem Sci | [Link](https://doi.org/10.1039/d1sc05180f) | [Link](https://github.com/guaguabujianle/MGraphDTA) |
| 2022 | BridgeDPI: a novel Graph Neural Network for predicting drug–protein interactions | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac155) | [Link](https://github.com/SenseTime-Knowledge-Mining/BridgeDPI) |
| 2022 | Structure-aware multimodal deep learning for drug–protein interaction prediction (STAMP-DPI) | JCIM | [Link](https://doi.org/10.1021/acs.jcim.2c00060) | [Link](https://github.com/biomed-AI/STAMP-DPI) |
| 2022 | TransDTI: transformer-based language models for estimating DTIs and building a drug recommendation workflow | ACS Omega | [Link](https://doi.org/10.1021/acsomega.1c05203) | [Link](https://github.com/TeamSundar/transDTI) |
| 2022 | AttentionSiteDTI: an interpretable graph-based model for drug-target interaction prediction using NLP sentence-level relation classification | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbac272) | [Link](https://github.com/yazdanimehdi/AttentionSiteDTI) |
| 2022 | CoaDTI: multi-modal co-attention based framework for drug-target interaction annotation | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbac446) | [Link](https://github.com/Layne-Huang/CoaDTI) |
| 2022 | Improved compound-protein interaction site and binding affinity prediction using self-supervised protein embeddings | BMC Bioinformatics | [Link](https://doi.org/10.1186/s12859-022-05107-w) | [Link](https://github.com/Jwoods14/SPE-MONN) |
| 2023 | Improving the generalizability of protein-ligand binding predictions with AI-Bind | Nat Commun | [Link](https://doi.org/10.1038/s41467-023-37572-z) | [Link1](https://github.com/ChatterjeeAyan/AI-Bind) [Link2](https://doi.org/10.5281/zenodo.7730755)|
| 2023 | Interpretable bilinear attention network with domain adaptation improves drug–target prediction (DrugBAN) | Nat Mach Intell | [Link](https://doi.org/10.1038/s42256-022-00605-1) | [Link1](https://github.com/peizhenbai/DrugBAN) [Link2](https://doi.org/10.24433/CO.3558316.v1)|
### Structure Based (CNN)
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2015 | AtomNet: a deep convolutional neural network for bioactivity prediction in structure-based drug discovery | arXiv | [Link](https://arxiv.org/abs/1510.02855) | - |
| 2017 | Protein–ligand scoring with convolutional neural networks | JCIM | [Link](https://doi.org/10.1021/acs.jcim.6b00740) | [Link](https://github.com/gnina/models) |
| 2018 | KDEEP: protein–ligand absolute binding affinity prediction via 3D-convolutional neural networks | JCIM | [Link](https://doi.org/10.1021/acs.jcim.7b00650) | - |
| 2018 | Development and evaluation of a deep learning model for protein–ligand binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/bty374) | [Link](http://gitlab.com/cheminfIBB/pafnucy) |
| 2018 | Protein family-specific models using deep neural networks and transfer learning improve virtual screening and highlight the need for more data | JCIM | [Link](https://doi.org/10.1021/acs.jcim.8b00350) | - |
| 2019 | OnionNet: a multiple-layer intermolecular-contact-based convolutional neural network for protein–ligand binding affinity prediction | ACS Omega | [Link](https://doi.org/10.1021/acsomega.9b01997) | [Link](http://github.com/zhenglz/onionnet/) |
| 2020 | RosENet: improving binding affinity prediction by leveraging molecular mechanics energies with an ensemble of 3D convolutional neural networks | JCIM | [Link](https://doi.org/10.1021/acs.jcim.0c00075) | [Link](https://github.com/DS3Lab/RosENet/tree/master) |
| 2020 | AK-Score: accurate protein-ligand binding affinity prediction using an ensemble of 3D-convolutional neural networks | Int J Mol Sci | [Link](https://doi.org/10.3390/ijms21228424) | - |
| 2021 | Virtual Screening with Gnina 1.0 | Molecules | [Link](https://doi.org/10.3390/molecules26237369) | - |
| 2021 | Improved protein–ligand binding affinity prediction with structure-based deep fusion inference | JCIM | [Link](https://doi.org/10.1021/acs.jcim.0c01306) | [Link1](https://github.com/llnl/fast) [Link2](ftp://gdobioinformatics.ucllnl.org/fast/pdbbind2016_model_checkpoints/) |
| 2023 | HAC-Net: a hybrid attention-based convolutional neural network for highly accurate protein–ligand binding affinity prediction | JCIM | [Link](https://doi.org/10.1021/acs.jcim.3c00251) | [Link](https://github.com/gregory-kyro/HAC-Net/) |
### Structure Based (GNN)
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2018 | PotentialNet for molecular property prediction | ACS Cent Sci | [Link](https://doi.org/10.1021/acscentsci.8b00507) | - |
| 2019 | Graph convolutional neural networks for predicting drug-target interactions | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00628) | - |
| 2019 | Predicting drug−target interaction using a novel graph neural network with 3D structure-embedded graph representation | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00387) | [Link](https://github.com/jaechanglim/GNN_DTI) |
| 2022 | PIGNet: a physics-informed deep learning model toward generalized drug-target interaction predictions | Chem Sci | [Link](https://doi.org/10.1039/d1sc06946b) | [Link](https://github.com/ACE-KAIST/PIGNet) |
### Docking Based
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Combining docking pose rank and structure with deep learning improves protein–ligand binding mode prediction over a baseline docking approach | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00927) | - |
| 2021 | Learning protein-ligand binding affinity with atomic environment vectors | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00536-w) | [Link1](https://github.com/bigginlab/aescore) [Link2](doi.org/10.5281/zenodo.4155365) |
| 2023 | AQDnet: deep neural network for protein–ligand docking simulation | ACS Omega | [Link](https://doi.org/10.1021/acsomega.3c02411) | [Link](https://github.com/koji11235/AQDnet) |
### Latent Biases
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Exploration and augmentation of pharmacological space via adversarial auto-encoder model for facilitating kinase-centric drug development | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00574-4) | [Link](http://github.com/xybai-dev/EPA) |
| 2022 | On the choice of active site sequences for kinase-ligand affinity prediction | JCIM | [Link](https://doi.org/10.1021/acs.jcim.2c00840) | [Link](https://github.com/PaccMann/paccmann_kinase_binding_residues) |
| 2023 | Latent biases in machine learning models for predicting binding affinities using popular data sets | ACS Omega | [Link](https://doi.org/10.1021/acsomega.2c06781) | [Link](https://github.com/devalab/Protein-Ligand-DatasetBias) |
### Link Prediction
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | DTi2Vec: drug–target interaction prediction using network embedding and ensemble learning | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00552-w) | [Link](https://github.com/MahaThafar/DTi2Vec) |


## Protein-protein Interaction (PPI)
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Large-scale discovery of protein interactions at residue resolution using co-evolution calculated from genomic sequences | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-21636-z) | [Link](https://github.com/debbiemarkslab/EVcouplings) |


## Molecular Property Prediction
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Chemical toxicity prediction based on semi-supervised learning and graph convolutional neural network | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00570-8) | [Link](https://github.com/chen709847237/SSL-GCN) |


## De Novo Molecule Design
### Protein
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Large language models generate functional protein sequences across diverse families (ProGen) | Nat Biotechnol | [Link](https://doi.org/10.1038/s41587-022-01618-2) | [Link](https://github.com/debbiemarkslab/EVcouplings](https://github.com/salesforce/progen)) [Link2](https://zenodo.org/record/7296780) |


## Targeted Protein Degradation
### PROTAC
#### Generation
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Deep generative models for 3D linker design (DeLinker) | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b01120) | [Link](https://github.com/oxpig/DeLinker) |
| 2021 | Deep generative design with 3D pharmacophoric constraints (DEVELOP）| Chem Sci | [Link](https://doi.org/10.1039/d1sc02436a) | [Link](https://github.com/oxpig/DEVELOP) |
| 2022 | De novo PROTAC design using graph-based deep generative models | arXiv | [Link](https://arxiv.org/abs/2211.02660) | [Link1](https://github.com/divnori/Protac-Design) [Link2](https://zenodo.org/record/7278277) |


## Antibody
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Protein design and variant prediction using autoregressive generative models | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-22732-w) | [Link1](https://github.com/debbiemarkslab/SeqDesign) [Link2](https://doi.org/10.5281/zenodo.4606785) |


## RNA
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | RNAincoder: a deep learning-based encoder for RNA and RNA-associated interaction | NAR | [Link](https://doi.org/doi.org/10.1093/nar/gkad404) | [Link](https://idrblab.org/rnaincoder/) |


## Machine Learning Algorithms
### Uncertainty
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Leveraging uncertainty in machine learning accelerates biological discovery and design | Cell Syst | [Link](https://doi.org/10.1016/j.cels.2020.09.007) | [Link](https://github.com/brianhie/uncertainty) |
| 2021 | A hybrid framework for improving uncertainty quantification in deep learning-based QSAR regression modeling | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00551-x) | [Link](https://github.com/wangdingyan/HybridUQ) |

# Related Awesome
* [awesome-protein-representation-learning](https://github.com/LirongWu/awesome-protein-representation-learning)
* [awesome-AI-based-protein-design](https://github.com/opendilab/awesome-AI-based-protein-design)
* [awesome-graph-representation-learning](https://github.com/zlpure/awesome-graph-representation-learning)
* [awesome-graph-self-supervised-learning](https://github.com/LirongWu/awesome-graph-self-supervised-learning)
* [awesome-self-supervised-gnn](https://github.com/ChandlerBang/awesome-self-supervised-gnn)
* [awesome-self-supervised-learning-for-graphs](https://github.com/SXKDZ/awesome-self-supervised-learning-for-graphs)
