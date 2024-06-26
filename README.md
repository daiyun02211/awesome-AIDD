# Awesome-AIDD

- [Review](#Review)
- [Roadmap](#Roadmap)
- [Data](#Data)
  - [Databases](#Databases)
  - [Data Sets](#Data-Sets)
  - [Benchmark](#Benchmark)
- [Representations for Molecules](#Representations-for-Molecules)
- [Representations for Proteins](#Representations-for-Proteins)
  - [Protein Language Models (PLMs)](#Protein-Language-Models-plms)
  - [Learning from Protein Structures](#Learning-from-Protein-Structures)  
- [Protein Structure Prediction](#Protein-Structure-Prediction)
- [Enzyme](#Enzyme)
- [Effects of Mutations](#Effects-of-Mutations)
- [Binding Site Prediction](#Binding-Site-Prediction)
- [Compound-protein Interaction (CPI)](#Compound-protein-Interaction-cpi)
  - [Protein Sequence Based](#Protein-Sequence-Based)
  - [Structure Based (CNN)](#Structure-Based-CNN)
  - [Structure Based (GNN)](#Structure-Based-GNN)
  - [Docking Scoring Function](#Docking-Scoring-Function)
  - [Deep Docking](#Deep-Docking)
  - [Latent Biases](#Latent-Biases)
  - [Virtual Screening Pipeline](#Virtual-Screening-Pipeline)
  - [Link Prediction](#Link-Prediction)
- [Protein-protein Interaction (PPI)](#Protein-protein-Interaction-ppi)
- [Molecular Property Prediction](#Molecular-Property-Prediction)
  - [ADMET](#ADMET)
  - [Frequent Hitters](#Frequent-Hitters)
  - [Multitarget-directed Ligands](#Multitarget-directed-Ligands)
- [De Novo Molecule Design](#De-Novo-Molecule-Design)
  - [Protein](#Protein)
- [Targeted Protein Degradation](#Targeted-Protein-Degradation)
  - [PROTAC](#PROTAC)
    - [Docking](#Docking)
    - [Generation](#Generation)
- [Antigen-Antibody](#Antigen-Antibody)
- [RNA](#RNA)
  - [Protein-RNA Interaction](#Protein-RNA-Interaction)
- [Machine Learning Algorithms](#Machine-Learning-Algorithms)
  - [Uncertainty](#Uncertainty)
  - [Interpretation](#Interpretation)
  - [Sparsity and Popularity Biases](#Sparsity-and-Popularity-Biases)


## Review
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2016 | Protein binding pocket dynamics | Acc Chem Res | [Link](https://doi.org/10.1021/acs.accounts.5b00516) | - |
| 2018 | Markov State Models: from an art to a science | J Am Chem Soc | [Link](https://doi.org/10.1021/jacs.7b12191) | - |
| 2018 | Cryptic binding sites on proteins: definition, detection, and druggability | Curr Opin Chem Biol | [Link](https://doi.org/10.1016/j.cbpa.2018.05.003) | - |
| 2019 | Computational methods and tools for binding site recognition between proteins and small molecules: from classical geometrical approaches to modern machine learning strategies | J Comput Aided Mol Des | [Link](https://doi.org/10.1007/s10822-019-00235-7) | - |
| 2020 | Application of negative design to design a more desirable virtual screening library | J Med Chem | [Link](https://doi.org/10.1021/acs.jmedchem.9b01476) | - |
| 2020 | Integrated computational approaches and tools for allosteric drug discovery | Int J Mol Sci | [Link](https://doi.org/10.3390/ijms21030847) | - |
| 2020 | Investigating cryptic binding sites by molecular dynamics simulations | Acc Chem Res | [Link](https://doi.org/10.1021/acs.accounts.9b00613) | - |
| 2020 | A Review of Deep Learning Methods for Antibodies | Antibodies | [Link](https://doi.org/10.3390/antib9020012) | - |
| 2022 | Principles of kinase allosteric inhibition and pocket validation | J Med Chem | [Link](https://doi.org/10.1021/acs.jmedchem.2c00073) | - |
| 2023 | Advancing targeted protein degradation via multiomics profiling and artificial intelligence | JACS | [Link](https://doi.org/10.1021/jacs.2c11098) | - |
| 2023 | A systematic survey in geometric deep learning for structure-based drug design | arXiv| [Link](https://arxiv.org/pdf/2306.11768.pdf) | - |
| 2023 | AI-powered therapeutic target discovery | Trends Pharmacol Sci | [Link](https://doi.org/10.1016/j.tips.2023.06.010) | - |
| 2023 | Artificial intelligence in drug toxicity prediction: recent advances, challenges, and future perspectives | JCIM | [Link](https://doi.org/10.1021/acs.jcim.3c00200) | - |
| 2023 | From target discovery to clinical drug development with human genetics | Nature | [Link](https://doi.org/10.1038/s41586-023-06388-8) | - |
| 2023 | Recent advances in targeting the "undruggable" proteins: from drug discovery to clinical trials | Sig Transduct Target Ther | [Link](https://doi.org/10.1038/s41392-023-01589-z) | - |
| 2024 | Attention is all you need: utilizing attention in AI-enabled drug discovery | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbad467) | - |

## Roadmap
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2022 | CACHE (Critical Assessment of Computational Hit-finding Experiments): a public–private partnership benchmarking initiative to enable the development of computational methods for hit-finding | Nat Rev Chem | [Link](https://doi.org/10.1038/s41570-022-00363-z) | - |

## Data
### Databases
| Year | Title | Journal | Paper | Website |
| --- | --- | --- | --- | --- |
| 2022 | Therapeutic target database update 2022: facilitating drug discovery with enriched comparative data of targeted agents (TTD) | NAR | [Link](https://doi.org/10.1093/nar/gkab953) | [Link](https://idrblab.org/ttd/) |
| 2022 | NPCDR: natural product-based drug combination and its disease-specific molecular regulation | NAR | [Link](https://doi.org/10.1093/nar/gkab913) | [Link](https://idrblab.org/npcdr/) |
| 2022 | VARIDT 2.0: structural variability of drug transporter | NAR | [Link](https://doi.org/10.1093/nar/gkab1013) | [Link](https://idrblab.org/varidt/) |
| 2023 | DrugMAP: molecular atlas and pharma-information of all drugs | NAR | [Link](https://doi.org/10.1093/nar/gkac813) | [Link](https://idrblab.org/drugmap/) |
| 2023 | DRESIS: the first comprehensive landscape of drug resistance information | NAR | [Link](https://doi.org/10.1093/nar/gkac812) | [Link](https://idrblab.org/dresis) |
### Data Sets
| Year | Title | Journal | Paper | Website |
| --- | --- | --- | --- | --- |
| 2009 | Maximum unbiased validation (MUV) data sets for virtual screening based on PubChem bioactivity data | JCIM | [Link](https://doi.org/10.1021/ci8002649) | [Link](https://www.tu-braunschweig.de/en/pharmchem/forschung/baumann/translate-to-english-muv) |
| 2015 | Improving compound–protein interaction prediction by building up highly credible negative samples (human & C.elegans) | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btv256) | [Link](http://admis.fudan.edu.cn/negative-cpi/) |
| 2018 | Most ligand-based classification benchmarks reward memorization rather than generalization | JCIM | [Link](https://doi.org/10.1021/acs.jcim.7b00403) | [Link](http://pubs.acs.org/doi/suppl/10.1021/acs.jcim.7b00403/suppl_file/ci7b00403_si_001.zip) |
| 2018 | BioSNAP datasets: Stanford biomedical network dataset collection | - | [Link](https://snap.stanford.edu/biodata/) | - |
| 2020 | Machine learning classification can reduce false positives in structure-based virtual screening | PNAS | [Link](https://doi.org/10.1073/pnas.2000585117) | [Link1](https://data.mendeley.com/datasets/8czn4rxz68/) [Link2](https://github.com/karanicolaslab/vScreenML) |
| 2020 | Three-dimensional convolutional neural networks and a cross-docked data set for structure-based drug design | JCIM | [Link](https://doi.org/10.1021/acs.jcim.0c00411) | [Link](https://github.com/gnina/models) |
| 2021 | Generating property-matched decoy molecules using deep learning | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btab080) | [Link1](https://github.com/oxpig/DeepCoy) [Link2](http://opig.stats.ox.ac.uk/resources) |
| 2021 | Hierarchical clustering split for low-bias evaluation of drug-target interaction prediction | BIBM 2021 | [Link](https://doi.org/10.1109/BIBM52615.2021.9669515) | - |
| 2022 | TocoDecoy: A new approach to design unbiased datasets for training and benchmarking machine-learning scoring functions | J Med Chem | [Link](https://doi.org/10.1021/acs.jmedchem.2c00460) | [Link1](https://github.com/5AGE-zhang/TocoDecoy) [Link2](https://zenodo.org/record/5290011#.YSmecN--vVg) |
### Benchmark
| Year | Title | Journal | Paper | Website |
| --- | --- | --- | --- | --- |
| 2021 | Hierarchical clustering split for low-bias evaluation of drug-target interaction prediction | BIBM | [Link](https://ieeexplore.ieee.org/document/9669515) | - |
| 2022 | DrugOOD: Out-of-Distribution (OOD) dataset curator and benchmark for AI-aided drug discovery – A focus on affinity prediction problems with noise annotations | arXiv | [Link](https://arxiv.org/pdf/2201.09637.pdf) | [Link](https://drugood.github.io/) |
| 2023 | Does protein pretrained language model facilitate the prediction of protein–ligand interaction? | Methods | [Link](https://doi.org/10.1016/j.ymeth.2023.08.016) | [Link](https://github.com/brian-zZZ/PLM-PLI) |
| 2023 | ProteinInvBench: Benchmarking Protein Inverse Folding on Diverse Tasks, Models, and Metrics | NeurIPS 2023 | [Link](https://openreview.net/forum?id=bqXduvuW5E) | [Link](https://github.com/A4Bio/ProteinInvBench) |

## Representations for Molecules
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Molecular representation learning with language models and domain-relevant auxiliary tasks | NeurIPS 2020 ML4Molecules | [Link](https://arxiv.org/abs/2011.13230) | [Link](https://github.com/BenevolentAI/MolBERT) |
| 2021 | Out-of-the-box deep learning prediction of pharmaceutical properties by broadly learned knowledge-based molecular representations | Nat Mach Intell | [Link](https://doi.org/10.1038/s42256-021-00301-6) | [Link](https://github.com/shenwanxiang/bidd-molmap) |
| 2022 | Does GNN pretraining help molecular representation? | NeurIPS 2022 | [Link](https://openreview.net/forum?id=uytgM9N0vlR) | - |
| 2023 | Uni-Mol: a universal 3D molecular representation learning framework | ICLR 2023 | [Link](https://openreview.net/forum?id=6K2RM6wVqKu) | [Link](https://github.com/dptech-corp/Uni-Mol) |

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
| 2024 | ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing | arXiv | [Link](https://doi.org/10.48550/arXiv.2402.16445) | [Link](https://github.com/PKU-YuanGroup/ProLLaMA) |
| 2024 | Prot2Token: A multi-task framework for protein language processing using autoregressive language modeling | bioRxiv | [Link](https://doi.org/10.1101/2024.05.31.596915) | [Link](https://github.com/mahdip72/prot2token) |

### Learning from Protein Structures
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2017 | TopologyNet: Topology based deep convolutional and multi-task neural networks for biomolecular property predictions | PLoS Comput Biol | [Link](https://doi.org/10.1371/journal.pcbi.1005690) | - |
| 2019 | Generative models for graph-based protein design | NeurIPS 2019 | [Link](https://papers.nips.cc/paper_files/paper/2019/hash/f3a4ff4839c56a5f460c88cce3666a2b-Abstract.html) | [Link](https://github.com/jingraham/neurips19-graph-protein-design) |
| 2021 | Learning from protein structure with geometric vector perceptrons (GVP) | ICLR 2021 | [Link](https://openreview.net/forum?id=1YLJDvSx6J4) | [Link](https://github.com/drorlab/gvp) |
| 2022 | Learning inverse folding from millions of predicted structures (ESM-IF1) | ICML 2022 | [Link](https://proceedings.mlr.press/v162/hsu22a.html) | [Link](https://github.com/facebookresearch/esm) |
| 2022 | Pre-training of equivariant graph matching networks with conformation flexibility for drug binding (ProtMD) | Adv Sci (Weinh) | [Link](https://doi.org/10.1002/advs.202203796) | [Link](https://github.com/smiles724/ProtMD) |
| 2022 | Spherical message passing for 3D molecular graphs | ICLR 2022 | [Link](https://openreview.net/forum?id=givsRXsOt9r) | [Link](https://github.com/divelab/DIG) |
| 2023 | Protein representation learning by geometric structure pretraining (GearNet) | ICLR 2023 | [Link](https://openreview.net/forum?id=to3qCB3tOh9) | [Link](https://github.com/DeepGraphLearning/GearNet) |
| 2023 | Learning hierarchical protein representations via complete 3D graph networks | ICLR 2023 | [Link](https://openreview.net/forum?id=9X-hgLDLYkQ) | [Link](https://github.com/divelab/DIG) |
| 2023 | Learning harmonic molecular representations on riemannian manifold | ICLR 2023 | [Link](https://openreview.net/forum?id=ySCL-NG_I3) | [Link](https://github.com/bytedance/HMR) |

## Protein Structure Prediction
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2022 | Protein complex prediction with AlphaFold-Multimer | bioRxiv | [Link](https://doi.org/10.1101/2021.10.04.463034) | - |
| 2023 | Evolutionary-scale prediction of atomic-level protein structure with a language model (ESM-2, ESMFold) | Science | [Link](https://doi.org/10.1126/science.ade2574) | [Link1](https://github.com/facebookresearch/esm) [Link2](https://zenodo.org/record/7566741) |
| 2023 | Evaluation of AlphaFold-Multimer prediction on multi-chain protein complexes | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad424) | [Link](https://gitlab.com/ElofssonLab/afm-benchmark) |
| 2023 | EigenFold: generative protein structure prediction with diffusion models | ICLR 2023 MLDD | [Link](https://openreview.net/pdf?id=BgbRVzfQqFp) | [Link](https://github.com/bjing2016/EigenFold) |
| 2023 | Towards predicting equilibrium distributions for molecular systems with deep learning (Distributional Graphormer, DiG) | arXiv | [Link](https://arxiv.org/abs/2306.05445) | [Link](https://distributionalgraphormer.github.io/) |
| 2023 | Generalized Biomolecular Modeling and Design with RoseTTAFold All-Atom | bioRxiv | [Link](https://doi.org/10.1101/2023.10.09.561603) | - |
| 2023 | Performance and structural coverage of the latest, in-development AlphaFold model (AlphaFold-latest) | - | [Link](https://storage.googleapis.com/deepmind-media/DeepMind.com/Blog/a-glimpse-of-the-next-generation-of-alphafold/alphafold_latest_oct2023.pdf) | - |
| 2023 | Accurate prediction of protein–nucleic acid complexes using RoseTTAFoldNA | Nat Methods | [Link](https://doi.org/10.1038/s41592-023-02086-5) | [Link](https://github.com/uw-ipd/RoseTTAFold2NA) |
| 2023 | Predicting multiple conformations via sequence clustering and AlphaFold2 (AF-Cluster) | Nature | [Link](https://doi.org/10.1038/s41586-023-06832-9) | [Link](www.github.com/HWaymentSteele/AF_Cluster) |

## Protein Design
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | De novo design of protein structure and function with RFdiffusion | Nature | [Link](https://doi.org/10.1038/s41586-023-06415-8) | [Link](https://github.com/RosettaCommons/RFdiffusion) |

## Enzyme
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Turnover number predictions for kinetically uncharacterized enzymes using machine and deep learning | Nat Commun | [Link](https://doi.org/10.1038/s41467-023-39840-4) | [Link1](https://github.com/AlexanderKroll/Kcat_prediction) [Link2](https://doi.org/10.5281/zenodo.7849347) |

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
| 2023 | Mega-scale experimental analysis of protein folding stability in biology and design | Nature | [Link](https://doi.org/10.1038/s41586-023-06328-6) | [Link1](https://doi.org/10.5281/zenodo.7992926) [Link2](https://github.com/Rocklin-Lab/cdna-display-proteolysis-pipeline) |
| 2023 | Genome-wide prediction of disease variant effects with a deep protein language model | Nat Genet | [Link](https://doi.org/10.1038/s41588-023-01465-0) | [Link](https://github.com/ntranoslab/esm-variants) |
| 2023 | Accurate proteome-wide missense variant effect prediction with AlphaMissense | Science | [Link](https://doi/10.1126/science.adg7492) | [Link1](https://github.com/deepmind/alphamissense) [Link2](https://console.cloud.google.com/storage/browser/dm_alphamissense) |

## Binding Site Prediction
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2009 | Fpocket: an open source platform for ligand pocket detection | BMC Bioinformatics | [Link](https://doi.org/10.1186/1471-2105-10-168) | [Link](https://github.com/Discngine/fpocket) |
| 2013 | APoc: large-scale identification of similar protein pockets | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btt024) | [Link](https://anaconda.org/bioconda/apoc) |
| 2015 | The FTMap family of web servers for determining and characterizing ligand-binding hot spots of proteins | Nat Protoc | [Link](https://doi.org/10.1038/nprot.2015.043) | [Link](https://ftmap.bu.edu/login.php) |
| 2016 | A random forest model for predicting allosteric and functional sites on proteins | Mol Inform | [Link](https://doi.org/10.1002/minf.201500108) | - |
| 2016 | CryptoSite: expanding the druggable proteome by characterization and prediction of cryptic binding sites | J Mol Biol | [Link](https://doi.org/10.1016/j.jmb.2016.01.029) | [Link](https://modbase.compbio.ucsf.edu/cryptosite/) |
| 2018 | Comparative assessment of strategies to identify similar ligand-binding pockets in proteins | BMC Bioinformatics | [Link](https://doi.org/10.1186/s12859-018-2109-2) | [Link](https://osf.io/6ngbs/) |
| 2019 | Allosteric mechanism of the circadian protein Vivid resolved through Markov state model and machine learning analysis | PLoS Comput Biol | [Link](https://doi.org/10.1371/journal.pcbi.1006801) | - |
| 2019 | DeepDrug3D: classification of ligand-binding pockets in proteins with a convolutional neural network | PLoS Comput Biol | [Link](https://doi.org/10.1371/journal.pcbi.1006718) | [Link1](https://github.com/pulimeng/DeepDrug3D) [Link2](https://osf.io/enz69/) |
| 2019 | Computational methods and tools for binding site recognition between proteins and small molecules: from classical geometrical approaches to modern machine learning strategies | J Comput Aided Mol Des | [Link](https://doi.org/10.1007/s10822-019-00235-7) | - |
| 2019 | Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning (MaSIF) | Nat Methods | [Link](https://doi.org/10.1038/s41592-019-0666-6) | [Link1](https://github.com/lpdi-epfl/masif) [Link2](https://doi.org/10.5281/zenodo.2625420) |
| 2020 | Essential site scanning analysis: a new approach for detecting sites that modulate the dispersion of protein global motions | Comput Struct Biotechnol J | [Link](https://doi.org/10.1016/j.csbj.2020.06.020) | - |
| 2020 | Spatiotemporal identification of druggable binding sites using deep learning | Commun Biol | [Link](https://doi.org/10.1038/s42003-020-01350-0) | [Link1](https://github.com/i-Molecule/bitenet) [Link2](https://sites.skoltech.ru/imolecule/tools/bitenet)|
| 2021 | DeepSurf: a surface-based deep learning approach for the prediction of ligand binding sites on proteins | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btab009) | [Link](https://github.com/stemylonas/DeepSurf) |
| 2021 | Decrypting a cryptic allosteric pocket in H. pylori glutamate racemase | Commun Chem | [Link](https://doi.org/10.1038/s42004-021-00605-z) | - |
| 2021 | What features of ligands are relevant to the opening of cryptic pockets in drug targets? | Informatics | [Link](https://doi.org/10.3390/informatics9010008) | [Link](https://ochem.eu/model/913) |
| 2021 | Finding druggable sites in proteins using TACTICS| JCIM | [Link](https://doi.org/10.1021/acs.jcim.1c00204) | [Link](https://github.com/Albert-Lau-Lab/tactics_protein_analysis) |
| 2021 | Protein interaction interface region prediction by geometric deep learning | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btab154) | [Link](https://github.com/FTD007/PInet) |
| 2022 | ScanNet: an interpretable geometric deep learning model for structure-based protein binding site prediction | Nat Methods | [Link](https://doi.org/10.1038/s41592-022-01490-7) | [Link1](https://github.com/jertubiana/ScanNet) [Link2](https://zenodo.org/record/6521889#.YnPoYS8RpbW) |
| 2022 | GraphSite: ligand binding site classification with deep graph learning| Biomolecules | [Link](https://doi.org/10.3390/biom12081053) | [Link1](https://github.com/shiwentao00/Graphsite-classifier) [Link2](https://osf.io/svwkb/)|
| 2022 | PointSite: a point cloud segmentation tool for identification of protein ligand binding atoms | JCIM | [Link](https://doi.org/10.1021/acs.jcim.1c01512) | [Link](https://github.com/PointSite/PointSite) |
| 2022 | Classification of protein-binding sites using a spherical convolutional neural network| JCIM | [Link](https://doi.org/10.1021/acs.jcim.2c00832) | [Link](https://github.com/Jing9558/BindSiteS-CNN) |
| 2022 | Decoding surface fingerprints for protein-ligand interactions| ICLR 2022 MLDD | [Link](https://openreview.net/forum?id=YRb9-uZ4noQ) | - |
| 2022 | PASSer2.0: accurate prediction of protein allosteric sites through automated machine learning | Front Mol Biosci | [Link](https://doi.org/10.3389/fmolb.2022.879251) | [Link](https://passer.smu.edu/) |
| 2023 | PASSer: fast and accurate prediction of protein allosteric sites | NAR | [Link](https://doi.org/10.1093/nar/gkad303) | [Link](https://passer.smu.edu/) |
| 2023 | Coevolution-based prediction of key allosteric residues for protein function regulation | Elife | [Link](https://doi.org/10.7554/eLife.81850) | [Link](https://github.com/huilan1210/KeyAlloSite) |
| 2023 | Predicting allosteric pockets in protein biological assemblages | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad275) | [Link](https://github.com/Ambuj-UF/APOP) |
| 2023 | Accelerating cryptic pocket discovery using AlphaFold | J Chem Theory Comput | [Link](https://doi.org/10.1021/acs.jctc.2c01189) | [Link](https://github.com/sbhakat/AF-cryptic-pocket) |
| 2023 | PeSTo: parameter-free geometric deep learning for accurate prediction of protein binding interfaces | Nat Commun | [Link](https://doi.org/10.1038/s41467-023-37701-8) | [Link](https://github.com/LBM-EPFL/PeSTo) |
| 2023 | Predicting locations of cryptic pockets from single protein structures using the PocketMiner graph neural network | Nat Commun | [Link](https://doi.org/10.1038/s41467-023-36699-3) | [Link1](https://github.com/Mickdub/gvp/tree/pocket_pred) [Link2](https://github.com/meghana-kshirsagar/3DCNN_protein_structures/tree/main/models) |
| 2023 | PocketNet: ligand-guided pocket prediction for blind docking | ICLR 2023 MLDD | [Link](https://openreview.net/forum?id=XhfIVsvwHl) | - |
| 2023 | EquiPocket: an E(3)-equivariant geometric graph neural network for ligand binding site prediction | arXiv | [Link](https://arxiv.org/abs/2302.12177) | - |
| 2023 | PocketAnchor: Learning structure-based pocket representations for protein-ligand interaction prediction | Cell Syst | [Link](https://doi.org/10.1016/j.cels.2023.05.005) | [Link1](https://github.com/lishuya17/PocketAnchorData) [Link2](https://github.com/tiantz17/PocketAnchor) |


## Compound-protein Interaction (CPI)
### Protein Sequence Based
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2017 | Deep-learning-based drug−target interaction prediction (DeepDTI) | J Proteome Res | [Link](https://doi.org/10.1021/acs.jproteome.6b00618) | [Link](https://github.com/Bjoux2/DeepDTIs_DBN) |
| 2018 | DeepDTA: deep drug-target binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/bty593) | [Link](https://github.com/hkmztrk/DeepDTA) |
| 2019 | DeepConv-DTI: Prediction of drug-target interactions via deep learning with convolution on protein sequences | PLoS Comput Biol | [Link](https://doi.org/10.1371/journal.pcbi.1007129) | [Link](https://github.com/GIST-CSBL/DeepConv-DTI) |
| 2019 | DeepCPI: A deep learning-based framework for large-scale in silico drug screening | GPB | [Link](https://doi.org/10.1016/j.gpb.2019.04.003) | [Link](https://github.com/FangpingWan/DeepCPI) |
| 2019 | Compound–protein interaction prediction with end-to-end learning of neural networks for graphs and sequences (Tsubaki et al) | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/bty535) | [Link](https://github.com/masashitsubaki) |
| 2019 | DeepAffinity: interpretable deep learning of compound–protein affinity through unified recurrent and convolutional neural networks | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btz111) | [Link](https://github.com/Shen-Lab/DeepAffinity) |
| 2020 | MONN: a multi-objective neural network for predicting compound-protein interactions and affinities | Cell Syst | [Link](https://doi.org/10.1016/j.cels.2020.03.002) | [Link](https://github.com/lishuya17/MONN) |
| 2020 | DeepCDA: deep cross-domain compound–protein affinity prediction through LSTM and convolutional neural networks | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btaa544) | [Link](https://github.com/LBBSoft/DeepCDA) |
| 2020 | GraphDTA: predicting drug–target binding affinity with graph neural networks | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btaa921) | [Link](https://github.com/thinng/GraphDTA) |
| 2020 | TransformerCPI: improving compound–protein interaction prediction by sequence-based deep learning with self-attention mechanism and label reversal experiments | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btaa524) | [Link](https://github.com/thinng/GraphDTA](https://github.com/lifanchen-simm/transformerCPI)) |
| 2020 | Predicting drug–protein interaction using quasi-visual question answering system (DrugVQA) | Nat Mach Intell | [Link](https://doi.org/10.1038/s42256-020-0152-y) | [Link](https://github.com/prokia/drugVQA) |
| 2020 | DeepACTION: A deep learning-based method for predicting novel drug-target interactions | Anal Biochem | [Link](https://doi.org/10.1016/j.ab.2020.113978) | - |
| 2020 | MDeePred: Novel multi-channel protein featurization for deep learning-based binding affinity prediction in drug discovery | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btaa858) | [Link](https://github.com/cansyl/MDeePred) |
| 2021 | Deep learning integration of molecular and interactome data for protein–compound interaction prediction (Watanabe et al) | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00513-3) | [Link](https://github.com/Njk-901aru/multi_DTI) |
| 2021 | Multi-PLI: Interpretable multi-task deep learning model for unifying protein-ligand interaction datasets | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00510-6) | [Link](https://github.com/Siat-Code/Multi-PLI/) |
| 2021 | MSA-regularized protein sequence transformer toward predicting genome-wide chemical-protein interactions: Application to GPCRome deorphanization (DISAE) | JCIM | [Link](https://doi.org/10.1021/acs.jcim.0c01285) | [Link](https://github.com/XieResearchGroup/DISAE) |
| 2021 | MolTrans: Molecular interaction transformer for drug-target interaction prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btaa880) | [Link](https://github.com/kexinhuang12345/moltrans) |
| 2021 | Deep drug-target binding affinity prediction with multiple attention blocks (MATT_DTI) | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbab117) | [Link](https://github.com/ZengYuni/MATT_DTI/) |
| 2021 | DTI-MLCD: Predicting drug-target interactions using multi-label learning with community detection method | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbaa205) | [Link](https://github.com/a96123155/DTI-MLCD) |
| 2021 | DeepDTAF: A deep learning method to predict protein–ligand binding affinity | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbab072) | [Link](github.com/KailiWang1/DeepDTAF) |
| 2021 | Explainable deep relational networks for predicting compound–protein affinities and contacts (DeepAffinity+) | JCIM | [Link](https://doi.org/10.1021/acs.jcim.0c00866) | - |
| 2022 | NerLTR-DTA: drug–target binding affinity prediction based on neighbor relationship and learning to rank | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac048) | [Link](https://github.com/RUXIAOQING964914140/NerLTR-DTA) |
| 2022 | Cross-modality and self-supervised protein embedding for compound–protein affinity and contact prediction (CPAC) | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac470) | [Link](https://github.com/Shen-Lab/CPAC/tree/main) |
| 2022 | BACPI: A bi-directional attention neural network for compound–protein interaction and binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac035) | [Link](https://github.com/CSUBioGroup/BACPI) |
| 2022 | ELECTRA-DTA: a new compound-protein binding affinity prediction model based on the contextualized sequence encoding | J Cheminform | [Link](https://doi.org/10.1186/s13321-022-00591-x) | [Link](https://github.com/IILab-Resource/ELECTRA-DTA) |
| 2022 | Sequence-based prediction of protein binding regions and drug–target interactions | J Cheminform | [Link](https://doi.org/10.1186/s13321-022-00584-w) | [Link](https://github.com/GIST-CSBL/HoTS) |
| 2022 | Deep neural network-assisted drug recommendation systems for identifying potential drug–target interactions | ACS Omega | [Link](https://doi.org/10.1021/acsomega.2c00424) | [Link](https://github.com/TeamSundar/dNNDR-featx) |
| 2022 | DeepMHADTA: Prediction of drug-target binding affinity using multi-head self-attention and convolutional neural network | Curr Issues Mol Biol | [Link](https://doi.org/10.3390/cimb44050155) | - |
| 2022 | HyperAttentionDTI: Improving drug–protein interaction prediction by sequence-based deep learning with attention mechanism | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btab715) | [Link1](https://github.com/zhaoqichang/HpyerAttentionDTI) [Link2](https://zenodo.org/record/5039589) |
| 2022 | DeepREAL: a deep learning powered multi-scale modeling framework for predicting out-of-distribution ligand-induced GPCR activity | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac154) | [Link](https://github.com/XieResearchGroup/DeepREAL) |
| 2022 | MGraphDTA: deep multiscale graph neural network for explainable drug–target binding affinity prediction | Chem Sci | [Link](https://doi.org/10.1039/d1sc05180f) | [Link](https://github.com/guaguabujianle/MGraphDTA) |
| 2022 | BridgeDPI: a novel Graph Neural Network for predicting drug–protein interactions | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac155) | [Link](https://github.com/SenseTime-Knowledge-Mining/BridgeDPI) |
| 2022 | MGPLI: exploring multigranular representations for protein–ligand interaction prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac597) | [Link](https://github.com/IILab-Resource/MGDTA) |
| 2022 | Structure-aware multimodal deep learning for drug–protein interaction prediction (STAMP-DPI) | JCIM | [Link](https://doi.org/10.1021/acs.jcim.2c00060) | [Link](https://github.com/biomed-AI/STAMP-DPI) |
| 2022 | TransDTI: transformer-based language models for estimating DTIs and building a drug recommendation workflow | ACS Omega | [Link](https://doi.org/10.1021/acsomega.1c05203) | [Link](https://github.com/TeamSundar/transDTI) |
| 2022 | CoaDTI: multi-modal co-attention based framework for drug-target interaction annotation | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbac446) | [Link](https://github.com/Layne-Huang/CoaDTI) |
| 2022 | Mitigating cold-start problems in drug-target affinity prediction with interaction knowledge transferring (Nguyen et al) | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbac269) | [Link](https://github.com/ngminhtri0394/C2P2) |
| 2022 | Improved compound-protein interaction site and binding affinity prediction using self-supervised protein embeddings | BMC Bioinformatics | [Link](https://doi.org/10.1186/s12859-022-05107-w) | [Link](https://github.com/Jwoods14/SPE-MONN) |
| 2022 | Perceiver CPI: a nested cross-attention network for compound–protein interaction prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac731) | [Link](https://github.com/dmis-lab/PerceiverCPI) |
| 2023 | Improving compound−protein interaction predictionby self-training with augmenting negative samples | JCIM | [Link](https://doi.org/10.1021/acs.jcim.3c00269) | [Link](https://github.com/clinfo/kMoL-ST) |
| 2023 | MFR-DTA: a multi-functional and robust model for predicting drug–target binding affinity and region | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad056) | [Link](https://github.com/JU-HuaY/MFR) |
| 2023 | ArkDTA: attention regularization guided by non-covalent interactions for explainable drug–target binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad207) | [Link](https://github.com/dmis-lab/ArkDTA) |
| 2023 | Improving the generalizability of protein-ligand binding predictions with AI-Bind | Nat Commun | [Link](https://doi.org/10.1038/s41467-023-37572-z) | [Link1](https://github.com/ChatterjeeAyan/AI-Bind) [Link2](https://doi.org/10.5281/zenodo.7730755)|
| 2023 | Interpretable bilinear attention network with domain adaptation improves drug–target prediction (DrugBAN) | Nat Mach Intell | [Link](https://doi.org/10.1038/s42256-022-00605-1) | [Link1](https://github.com/peizhenbai/DrugBAN) [Link2](https://doi.org/10.24433/CO.3558316.v1)|
| 2023 | Contrastive learning in protein language space predictsinteractions between drugs and protein targets (ConPLex) | PNAS | [Link](https://doi.org/10.1073/pnas.2220778120) | [Link](https://github.com/samsledje/ConPLex_dev) |
| 2023 | Sequence-based drug design as a concept in computational drug design (TransformerCPI 2.0)| Nat Commun | [Link](https://doi.org/10.1038/s41467-023-39856-w) | [Link1](https://github.com/lifanchen-simm/transformerCPI2.0) [Link2](https://doi.org/10.5281/zenodo.7993486)|
| 2023 | MoDTI: modular framework for evaluating inductive biases in DTI modeling | ICLR 2023 MLDD | [Link](https://openreview.net/forum?id=Tj-bRjuhpJ5) | - |
| 2023 | An industrial evaluation of proteochemometric modelling: Predicting drug-target affinities for kinases | Artif Intell Life Sci | [Link](https://doi.org/10.1016/j.ailsci.2023.100079) | [Link](https://github.com/AstraZeneca/AdaptedGraphDTA) |
| 2023 | NHGNN-DTA: a node-adaptive hybrid graph neural network for interpretable drug–target binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad355) | [Link](https://github.com/hehh77/NHGNN-DTA) |
| 2023 | SAM-DTA: a sequence-agnostic model for drug–target binding affinity prediction | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbac533) | [Link](https://github.com/huzqatpku/SAM-DTA) |
| 2024 | GraphCL-DTA: A Graph Contrastive Learning With Molecular Semantics for Drug-Target Binding Affinity Prediction | IEEE J Biomed Health Inform | [Link](https://doi.org/10.1109/JBHI.2024.3350666) | - |
| 2024 | TEFDTA: a transformer encoder and fingerprint representation combined prediction method for bonded and non-bonded drug–target affinities | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad778) | [Link](https://github.com/lizongquan01/TEFDTA) |

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
| 2020 | Data set augmentation allows deep learning-based virtual screening to better generalize to unseen target classes and highlight important binding interactions | JCIM | [Link](https://doi.org/10.1021/acs.jcim.0c00263) | - |
| 2020 | AK-Score: accurate protein-ligand binding affinity prediction using an ensemble of 3D-convolutional neural networks | Int J Mol Sci | [Link](https://doi.org/10.3390/ijms21228424) | - |
| 2021 | Virtual Screening with Gnina 1.0 | Molecules | [Link](https://doi.org/10.3390/molecules26237369) | - |
| 2021 | Improved protein–ligand binding affinity prediction with structure-based deep fusion inference | JCIM | [Link](https://doi.org/10.1021/acs.jcim.0c01306) | [Link](https://github.com/llnl/fast) |
| 2023 | CAPLA: improved prediction of protein–ligand binding affinity by a deep learning approach based on a cross-attention mechanism | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad049) | [Link](https://github.com/lennylv/CAPLA) |
| 2023 | DataDTA: a multi-feature and dual-interaction aggregation framework for drug–target binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad560) | [Link](https://github.com/YanZhu06/DataDTA) |
| 2023 | HAC-Net: a hybrid attention-based convolutional neural network for highly accurate protein–ligand binding affinity prediction | JCIM | [Link](https://doi.org/10.1021/acs.jcim.3c00251) | [Link](https://github.com/gregory-kyro/HAC-Net/) |
### Structure Based (GNN)
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2018 | PotentialNet for molecular property prediction | ACS Cent Sci | [Link](https://doi.org/10.1021/acscentsci.8b00507) | - |
| 2019 | Graph convolutional neural networks for predicting drug-target interactions | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00628) | - |
| 2019 | Predicting drug−target interaction using a novel graph neural network with 3D structure-embedded graph representation | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00387) | [Link](https://github.com/jaechanglim/GNN_DTI) |
| 2022 | PIGNet: a physics-informed deep learning model toward generalized drug-target interaction predictions | Chem Sci | [Link](https://doi.org/10.1039/d1sc06946b) | [Link](https://github.com/ACE-KAIST/PIGNet) |
| 2022 | AttentionSiteDTI: an interpretable graph-based model for drug-target interaction prediction using NLP sentence-level relation classification | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbac272) | [Link](https://github.com/yazdanimehdi/AttentionSiteDTI) |
| 2023 | GraphscoreDTA: optimized graph neural network for protein–ligand binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btad340) | [Link](https://github.com/CSUBioGroup/GraphscoreDTA) |
### Docking Scoring Function
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Improving structure-based virtual screening performance via learning from scoring function components | Brief Bioinform | [Link](https://10.1093/bib/bbaa094) | [Link](https://github.com/xiongguoli/data_EATs-learning) |
| 2021 | The impact of compound library size on the performance of scoring functions for structure-based virtual screening | Brief Bioinform | [Link](https://10.1093/bib/bbaa095) | - |
| 2021 | Learning protein-ligand binding affinity with atomic environment vectors | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00536-w) | [Link1](https://github.com/bigginlab/aescore) [Link2](https://doi.org/10.5281/zenodo.4155365) |
| 2022 | Protein-ligand interaction graphs: learning from ligand-shaped 3D interaction graphs to improve binding affinity prediction | bioRxiv | [Link]( https://doi.org/10.1101/2022.03.04.483012) | [Link](https://github.com/MarcMoesser/ProteinLigand-Interaction-Graphs) |
| 2022 | Learning from docked ligands: ligand-based features rescue structure-based scoring functions when trained on docked poses | JCIM | [Link](https://doi.org/10.1021/acs.jcim.1c00096) | [Link1](https://github.com/oxpig/learning-from-docked-poses) [Link2](https://doi.org/10.6084/m9.figshare.13713226.v1) |
| 2023 | Reducing false positive rate of docking-based virtual screening by active learning | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbac626) | - |
### Deep Docking
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2019 | Learning from the ligand: using ligand-based features to improve binding affinity prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btz665) | [Link](http://opig.stats.ox.ac.uk/resources) |
| 2020 | Combining docking pose rank and structure with deep learning improves protein–ligand binding mode prediction over a baseline docking approach | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00927) | - |
| 2021 | Fast end-to-end learning on protein surfaces (dMaSIF) | CVPR 2021 | [Link](https://openaccess.thecvf.com/content/CVPR2021/papers/Sverrisson_Fast_End-to-End_Learning_on_Protein_Surfaces_CVPR_2021_paper.pdf) | [Link](https://github.com/FreyrS/dMaSIF) |
| 2021 | A geometric deep learning approach to predict binding conformations of bioactive molecules | Nat Mach Intell | [Link](https://doi.org/10.1038/s42256-021-00409-9) | [Link](https://github.com/OptiMaL-PSE-Lab/DeepDock) |
| 2022 | Artificial intelligence-enabled virtual screening of ultra-large chemical libraries with deep docking | Nat Protoc | [Link](https://doi.org/10.1038/s41596-021-00659-2) | [Link1](https://github.com/jamesgleave/DD_protocol) [Link2](https://doi.org/10.20383/102.0489) |
| 2022 | Benchmarking AlphaFold-enabled molecular docking predictions for antibiotic discovery | Mol Syst Biol | [Link](https://doi.org/10.15252/msb.202211081) | - |
| 2022 | Independent SE(3)-equivariant models for end-to-end rigid protein docking (EQUIDOCK) | ICLR 2022 | [Link](https://openreview.net/forum?id=GQjaI9mLet) | [Link](https://github.com/octavian-ganea/equidock_public) |
| 2022 | EQUIBIND: geometric deep learning for drug binding structure prediction | ICML 2022 | [Link](https://proceedings.mlr.press/v162/stark22b/stark22b.pdf) | [Link](https://github.com/HannesStark/EquiBind) |
| 2022 | TANKBind: trigonometry-aware neural networKs for drug-protein binding structure prediction | NeurIPS 2022 | [Link](https://openreview.net/forum?id=MSBDFwGYwwt) | - |
| 2023 | AQDnet: deep neural network for protein–ligand docking simulation | ACS Omega | [Link](https://doi.org/10.1021/acsomega.3c02411) | [Link](https://github.com/koji11235/AQDnet) |
| 2023 | DiffDock: diffusion steps, twists, and turns for molecular docking | ICLR 2023 | [Link](https://openreview.net/forum?id=kKF8_K-mBbS) | [Link](https://github.com/gcorso/DiffDock) |
| 2023 | Do deep learning models really outperform traditional approaches in molecular docking? | ICLR 2023 MLDD | [Link](https://openreview.net/pdf?id=JrtHZdbGtN) | - |
| 2023 | SCORCH: improving structure-based virtual screening with machine learning classifiers, data augmentation, and uncertainty estimation | J Adv Res | [Link](https://doi.org/10.1016/j.jare.2022.07.001) | [Link](https://github.com/SMVDGroup/SCORCH/) |
| 2023 | PoseBusters: AI-based docking methods fail to generate physically valid poses or generalise to novel sequences | Chem Sci | [Link](https://doi.org/10.1039/D3SC04185A) | [Link](https://github.com/maabuu/posebusters) |
### Latent Biases
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2016 | Benchmark of four popular virtual screening programs: construction of the active/decoy dataset remains a major determinant of measured performance | J Cheminform | [Link](https://doi.org/10.1186/s13321-016-0167-x) | - |
| 2017 | Structural and sequence similarity makes a significant impact on machine-learning-based scoring functions for protein–ligand interactions | JCIM | [Link](https://doi.org/10.1021/acs.jcim.7b00049) | - |
| 2019 | Hidden bias in the DUD-E dataset leads to misleading performance of deep learning in structure-based virtual screening | PLoS One | [Link](https://doi.org/10.1371/journal.pone.0220113) | - |
| 2020 | Tapping on the black box: How is the scoring power of a machine-learning scoring function dependent on the training set? | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00714) | - |
| 2021 | Exploration and augmentation of pharmacological space via adversarial auto-encoder model for facilitating kinase-centric drug development | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00574-4) | [Link](http://github.com/xybai-dev/EPA) |
| 2022 | On the choice of active site sequences for kinase-ligand affinity prediction | JCIM | [Link](https://doi.org/10.1021/acs.jcim.2c00840) | [Link](https://github.com/PaccMann/paccmann_kinase_binding_residues) |
| 2022 | Bias in the Benchmark: Systematic experimental errors in bioactivity databases confound multi-task and meta-learning algorithms | ICML-AI4Science | [Link](https://openreview.net/forum?id=Gc5oq8sr6A3) | - |
| 2023 | Latent biases in machine learning models for predicting binding affinities using popular data sets | ACS Omega | [Link](https://doi.org/10.1021/acsomega.2c06781) | [Link](https://github.com/devalab/Protein-Ligand-DatasetBias) |
### Virtual Screening Pipeline
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Machine learning-enabled pipeline for large-scale virtual drug screening | JCIM | [Link](https://doi.org/10.1021/acs.jcim.1c00710) | [Link](https://github.com/aaayushg/RPN11_inhibitors) |
### Link Prediction
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | DTi2Vec: drug–target interaction prediction using network embedding and ensemble learning | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00552-w) | [Link](https://github.com/MahaThafar/DTi2Vec) |
| 2021 | An end-to-end heterogeneous graph representation learning-based framework for drug–target interaction prediction | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbaa430) | [Link](https://github.com/MedicineBiology-AI/EEG-DTI) |
| 2021 | Drug–target interaction predication via multi-channel graph neural networks | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbab346) | [Link](https://github.com/catly/drug-target) |
| 2022 | Supervised graph co-contrastive learning for drug–target interaction prediction | Bioinformatics | [Link](https://doi.org/10.1093/bioinformatics/btac164) | [Link](https://github.com/catly/SGCL-DTI) |

## Protein-protein Interaction (PPI)
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Large-scale discovery of protein interactions at residue resolution using co-evolution calculated from genomic sequences | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-21636-z) | [Link](https://github.com/debbiemarkslab/EVcouplings) |


## Molecular Property Prediction
### ADMET
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Pushing the boundaries of molecular representation for drug discovery with the graph attention mechanism (Attentive FP) | J Med Chem | [Link](https://doi.org/10.1021/acs.jmedchem.9b00959) | [Link](https://github.com/OpenDrugAI/AttentiveFP) |
| 2021 | Chemical toxicity prediction based on semi-supervised learning and graph convolutional neural network | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00570-8) | [Link](https://github.com/chen709847237/SSL-GCN) |
| 2023 | Uni-QSAR: an auto-ML tool for molecular property prediction | arXiv | [Link](https://arxiv.org/abs/2304.12239) | - |
| 2023 | Domain-aware representation of small molecules for explainable property prediction models | ICLR 2023 MLDD | [Link](https://openreview.net/forum?id=C9WW17wQF7p) | - |
### Frequent Hitters
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2018 | Luciferase Advisor: High-Accuracy Model To Flag False Positive Hits in Luciferase HTS Assays | JCIM | [Link](https://doi.org/10.1021/acs.jcim.7b00574) | [Link](http://ochem.eu/) |
| 2019 | Computational advances in combating colloidal aggregation in drug discovery | Nat Chem | [Link](https://doi.org/10.1038/s41557-019-0234-9) | - |
| 2019 | Structural analysis and identification of colloidal aggregators in drug discovery | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00541) | [Link](https://admet.scbdd.com/ChemAGG/index/) |
| 2020 | Structural Analysis and Identification of False Positive Hits in Luciferase-Based Assays | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b01188) | [Link](http://admet.scbdd.com/chemfluc/index/) |
| 2020 | Frequent hitters: nuisance artifacts in high-throughput screening | Drug Discov Today | [Link](https://doi.org/10.1016/j.drudis.2020.01.014) | - |
| 2021 | Computational prediction of frequent hitters in target-based and cell-based assays | Artif Intell Life Sci | [Link](https://doi.org/10.1016/j.ailsci.2021.100007) | [Link](https://nerdd.univie.ac.at/hitdexter3) |
| 2021 | Combating small-molecule aggregation with machine learning | Cell Rep Phys Sci | [Link](https://doi.org/10.1016/j.xcrp.2021.100573) | [Link](https://github.com/tcorodrigues/DeepSCAMs) |
### Multitarget-directed Ligands
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2015 | The recognition of identical ligands by unrelated proteins | ACS Chem Biol | [Link](https://doi.org/10.1021/acschembio.5b00683) | - |
| 2016 | Prediction of protein pairs sharing common active ligands using protein sequence, structure, and ligand similarity | JCIM | [Link](https://doi.org/10.1021/acs.jcim.6b00118) | - |
| 2020 | Identification of target associations for polypharmacology from analysis of crystallographic ligands of the Protein Data Bank | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b00821) | - |
| 2020 | A computer vision approach to align and compare protein cavities: application to fragment-based drug design | J Med Chem | [Link](https://doi.org/10.1021/acs.jmedchem.0c00422) | - |
| 2023 | Kinome-wide polypharmacology profiling of small molecules by multi-task graph isomorphism network approach | Acta Pharm Sin B | [Link](https://doi.org/10.1016/j.apsb.2022.05.004) | [Link](http://cadd.zju.edu.cn/kip) |


## De Novo Molecule Design
### Protein
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Large language models generate functional protein sequences across diverse families (ProGen) | Nat Biotechnol | [Link](https://doi.org/10.1038/s41587-022-01618-2) | [Link1](https://github.com/salesforce/progen) [Link2](https://zenodo.org/record/7296780) |


## Targeted Protein Degradation
### PROTAC
#### Docking
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | PRosettaC: Rosetta based modeling of PROTAC mediated ternary complexes | JCIM | [Link](https://doi.org/10.1021/acs.jcim.0c00589) | [Link](https://prosettac.weizmann.ac.il/pacb/steps) |
| 2023 | High accuracy prediction of PROTAC complex structures | JACS | [Link](https://doi.org/10.1021/jacs.2c09387) | - |
| 2023 | Bayesian optimization for ternary complex prediction (BOTCP) | Artif Intell Life Sci | [Link](https://doi.org/10.1016/j.ailsci.2023.100072) | - |
#### Generation
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Deep generative models for 3D linker design (DeLinker) | JCIM | [Link](https://doi.org/10.1021/acs.jcim.9b01120) | [Link](https://github.com/oxpig/DeLinker) |
| 2021 | Deep generative design with 3D pharmacophoric constraints (DEVELOP）| Chem Sci | [Link](https://doi.org/10.1039/d1sc02436a) | [Link](https://github.com/oxpig/DEVELOP) |
| 2022 | De novo PROTAC design using graph-based deep generative models | arXiv | [Link](https://arxiv.org/abs/2211.02660) | [Link1](https://github.com/divnori/Protac-Design) [Link2](https://zenodo.org/record/7278277) |

## Antigen-Antibody
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2021 | Protein design and variant prediction using autoregressive generative models | Nat Commun | [Link](https://doi.org/10.1038/s41467-021-22732-w) | [Link1](https://github.com/debbiemarkslab/SeqDesign) [Link2](https://doi.org/10.5281/zenodo.4606785) |
| 2021 | Optimization of therapeutic antibodies by predicting antigen specificity from antibody sequence via deep learning | Nat Biomed Eng | [Link](https://doi.org/10.1038/s41551-021-00699-9) | [Link](https://github.com/dahjan/DMS_opt) |
| 2022 | Co-optimization of therapeutic antibody affinity and specificity using machine learning models that generalize to novel mutational space | Nat Commun | [Link](https://doi.org/10.1038/s41467-022-31457-3) | [Link](https://github.com/Tessier-Lab-UMich/Emi_Pareto_Opt_ML) |
| 2022 | Predicting unseen antibodies’ neutralizability via adaptive graph neural networks | Nat Mach Intell | [Link](https://doi.org/10.1038/s42256-022-00553-w) | [Link](https://github.com/enai4bio/DeepAAI) |
| 2023 | Critical review of conformational B-cell epitope prediction methods | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbac567) | [Link](https://github.com/3BioCompBio/BCellEpitope) |
| 2023 | Recent progress in antibody epitope prediction | Antibodies | [Link](https://doi.org/10.3390/antib12030052) | - |
| 2023 | Fast, accurate antibody structure prediction from deep learning on massive set of natural antibodies | Nat Commun | [Link](https://doi.org/10.1038/s41467-023-38063-x) | [Link1](https://github.com/Graylab/IgFold) [Link2](https://doi.org/10.5281/zenodo.7709609) |
| 2023 | Machine learning optimization of candidate antibody yields highly diverse sub-nanomolar affinity antibody libraries | Nat Commun | [Link](https://doi.org/10.1038/s41467-023-39022-2) | [Link1](https://github.com/AIforGreatGood/biotransfer) [Link2](https://doi.org/10.5281/zenodo.7927152) |
| 2023 | Optimization of therapeutic antibodies for reduced self-association and non-specific binding via interpretable machine learning | Nat Biomed Eng | [Link](https://doi.org/10.1038/s41551-023-01074-6) | [Link](https://github.com/Tessier-Lab-UMich/CST_Prop_Opt_ML) |

## RNA
### Protein-RNA Interaction
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2019 | A deep learning framework to predict binding preference of RNA constituents on protein surface (NucleicNet) | Nat Commun | [Link](https://doi.org/10.1038/s41467-019-12920-0) | [Link](https://github.com/NucleicNet/NucleicNet) |
| 2020 | Deep neural networks for interpreting RNA-binding protein target preferences | Genome Res | [Link](https://doi.org/10.1101/gr.247494.118) | [Link](https://github.com/ohlerlab/DeepRiPe) |
| 2021 | Predicting dynamic cellular protein–RNA interactions by deep learning using in vivo RNA structures | Cell Res | [Link](https://doi.org/10.1038/s41422-021-00476-y) | [Link1](https://github.com/kuixu/PrismNet) [Link2](https://github.com/huangwenze/PrismNet_analysis) |
| 2022 | Protein–RNA interaction prediction with deep learning: structure matters | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbab540) | - |
| 2023 | RNAincoder: a deep learning-based encoder for RNA and RNA-associated interaction | NAR | [Link](https://doi.org/doi.org/10.1093/nar/gkad404) | [Link](https://idrblab.org/rnaincoder/) |
| 2023 | A systematic benchmark of machine learning methods for protein–RNA interaction prediction | Brief Bioinform | [Link](https://doi.org/10.1093/bib/bbad307) | - |

## Machine Learning Algorithms
### Uncertainty
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2020 | Leveraging uncertainty in machine learning accelerates biological discovery and design | Cell Syst | [Link](https://doi.org/10.1016/j.cels.2020.09.007) | [Link](https://github.com/brianhie/uncertainty) |
| 2021 | A hybrid framework for improving uncertainty quantification in deep learning-based QSAR regression modeling | J Cheminform | [Link](https://doi.org/10.1186/s13321-021-00551-x) | [Link](https://github.com/wangdingyan/HybridUQ) |
| 2023 | Drug discovery under covariate shift with domain-informed prior distributions over functions | ICML 2023 | [Link](https://openreview.net/forum?id=BbZVFj0QPv) | [Link](https://github.com/leojklarner/Q-SAVI) |
### Interpretation
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | Interpreting graph neural networks with myerson values for cheminformatics approaches | ChemRxiv | [Link](https://doi.org/10.26434/chemrxiv-2023-1hxxc) | - |
### Sparsity and Popularity Biases
| Year | Title | Journal | Paper | Code |
| --- | --- | --- | --- | --- |
| 2023 | LightGCL: simple yet effective graph contrastive learning for recommendation | ICLR 2023 | [Link](https://github.com/HKUDS/LightGCL) | [Link](https://github.com/HKUDS/LightGCL) |

# Related Awesome
* [awesome-protein-representation-learning](https://github.com/LirongWu/awesome-protein-representation-learning)
* [awesome-AI-based-protein-design](https://github.com/opendilab/awesome-AI-based-protein-design)
* [awesome-graph-representation-learning](https://github.com/zlpure/awesome-graph-representation-learning)
* [awesome-graph-self-supervised-learning](https://github.com/LirongWu/awesome-graph-self-supervised-learning)
* [awesome-self-supervised-gnn](https://github.com/ChandlerBang/awesome-self-supervised-gnn)
* [awesome-self-supervised-learning-for-graphs](https://github.com/SXKDZ/awesome-self-supervised-learning-for-graphs)

# Related Workshop
* [ICML 2022 Workshop AI4Science](https://openreview.net/group?id=ICML.cc/2022/Workshop/AI4Science)
* [ICLR 2022 Workshop MLDD](https://openreview.net/submissions?page=1&venue=ICLR.cc%2F2022%2FWorkshop%2FMLDD)
* [ICLR 2023 Workshop MLDD](https://openreview.net/submissions?page=1&venue=ICLR.cc%2F2023%2FWorkshop%2FMLDD)
* [NeurIPS 2021 Workshop AI4Science](https://openreview.net/group?id=NeurIPS.cc/2021/Workshop/AI4Science)
* [NeurIPS 2022 Workshop AI4Science](https://openreview.net/group?id=NeurIPS.cc/2022/Workshop/AI4Science)
* [NeurIPS 2023 Workshop AI4Science](https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/AI4Science)
* [NeurIPS 2023 Workshop AI4D3](https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/AI4D3)
* [NeurIPS 2023 Workshop GenBio](https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/GenBio)

