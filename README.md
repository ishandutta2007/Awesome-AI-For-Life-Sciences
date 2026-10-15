# Awesome-AI-For-Life-Sciences

## Top AI for Life Sciences Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Protein Structure Prediction, Drug Discovery & Scientific Agent Skills*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI for Life Sciences**. These tools enable researchers to predict protein structures, design novel molecules, analyze multi-omic data, and augment scientific workflows with validated AI agent skills—accelerating discovery from years to months.



**Examples** include Benchling, AlphaFold Server, Insilico Medicine, Schrödinger, Recursion, Owkin, Atomwise, Generate Biomedicines, Certara, and DNAnexus (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, protein folding, and open scientific AI—ideal for computational biologists, drug discovery teams, and developers seeking transparent, vendor-independent life sciences AI.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AlphaFold Server](https://alphafoldserver.com/)**  

  **DeepMind's hosted protein structure prediction service.** Free for non-commercial use with **AlphaFold 3** capabilities—predicting structures of proteins, DNA, RNA, ions, and small molecules in complex with each other. **The most accurate structure prediction available**—no setup, no GPU required.



- **[Benchling](https://www.benchling.com/)**  

  **The R&D cloud platform for biology** with electronic lab notebook (ELN), LIMS, and molecular biology tools. Features sequence editing, CRISPR design, structured data capture, and collaboration. **The industry standard for biotech R&D data management.**



- **[Schrödinger](https://www.schrodinger.com/)**  

  **Industry-leading computational platform for molecular modeling and drug discovery.** Features physics-based simulation, machine learning, and predictive analytics for lead identification and optimization. **The most widely used commercial platform in pharma R&D.**



- **[Insilico Medicine](https://insilico.com/)**  

  **AI-driven drug discovery platform** with generative chemistry (Chemistry42), target identification (PandaOmics), and clinical trial prediction. **Lead candidate discovered and designed using AI reached Phase II trials.**



- **[Recursion Pharmaceuticals](https://www.recursion.com/)**  

  **Clinical-stage biotech combining AI with high-throughput biology.** Features automated phenomics, deep learning for cellular image analysis, and digital chemistry for compound design.



- **[Owkin](https://www.owkin.com/)**  

  **AI platform for biomedical research** with federated learning capabilities. Features multi-institutional data analysis and predictive biomarker discovery without sharing patient data.



- **[Atomwise](https://www.atomwise.com/)**  

  **AI-powered virtual screening platform.** Features deep learning for structure-based drug discovery and hit identification.



- **[Generate Biomedicines](https://generatebiomedicines.com/)**  

  **Generative biology platform for protein therapeutics.** Features generative AI for designing novel proteins with desired functions.



- **[Certara](https://www.certara.com/)**  

  **Model-informed drug development platform.** Features pharmacokinetic/pharmacodynamic modeling, simulation, and regulatory writing.



- **[DNAnexus](https://www.dnanexus.com/)**  

  **Cloud platform for genomic data analysis and management.** Features scalable bioinformatics pipelines, data security, and collaboration.



## Open-Source GitHub Projects



- **[K-Dense-AI Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills)**  

  **The most comprehensive open-source collection of validated skills and scientific databases for biology/chemistry AI** (open-source). **The reference implementation for agent-augmented scientific workflows.** Provides **validated, reproducible skills** that AI agents can execute—connecting to authoritative scientific databases including **UniProt, PDB, ChEMBL, PubChem, Ensembl, NCBI, and others** . **Skills cover**: sequence retrieval and analysis, protein structure lookup, chemical property prediction, pathway enrichment, literature search, and data visualization . **Designed for agent frameworks** including Claude Code, Cursor, and MCP-compatible clients . **The bridge between LLM agents and real scientific databases.**



- **[AlphaFold](https://github.com/google-deepmind/alphafold)**  

  **The open-source implementation of AlphaFold 2** (Apache-2.0) from DeepMind. **The most influential AI breakthrough in structural biology.** **Predicts protein structures with atomic accuracy**—a problem that stood for 50 years. **Open-source code, model weights, and inference pipeline** available for non-commercial use. **18,000+ GitHub stars.** **Note**: Commercial use requires separate licensing from DeepMind .



- **[OpenFold](https://github.com/aqlaboratory/openfold)**  

  **Trainable, memory-efficient, and GPU/CPU optimized PyTorch reproduction of AlphaFold 2** (Apache-2.0) . **The most faithful open-source AlphaFold reproduction**—produced under the Open Molecular Software Foundation (OMSF) with support from AWS, NVIDIA, and other industry partners . **Supports training** (not just inference), **memory-efficient attention**, and **multi-GPU scaling** . **The foundation for community protein folding research**—serves as testbed for new architectures and training methods .



- **[Boltz-2](https://github.com/jwohlwend/boltz)**  

  **Open-source biomolecular structure prediction model** with **AlphaFold 3-class performance** (MIT) . **Faster than AlphaFold 3** with comparable accuracy on protein-ligand, protein-protein, and protein-nucleic acid complexes . **The most accessible open-source AlphaFold 3 alternative**—runs on consumer GPUs with reasonable memory requirements . **Growing adoption in pharma and academic labs** as a reproducible, permissively licensed alternative to proprietary services.



- **[Chai-1](https://github.com/chaidiscovery/chai-lab)**  

  **Open-source foundation model for molecular structure prediction** (Apache-2.0) from Chai Discovery. **AlphaFold 3-level accuracy** on protein-ligand, protein-protein, and antibody-antigen complexes . **The most competitive open-source AlphaFold 3 alternative**—achieved **77% success rate on antibody-antigen prediction** (vs 65% for AlphaFold 3) in independent benchmarks . **Available for both research and commercial use** under Apache 2.0—a critical differentiator from AlphaFold .



- **[ESM (Evolutionary Scale Modeling)](https://github.com/facebookresearch/esm)**  

  **Open-source protein language models** (MIT) from Meta AI. **The most widely used protein language models**—trained on millions of protein sequences to learn evolutionary patterns . **ESMFold** predicts structures directly from sequences without MSAs—**10x faster than AlphaFold 2** with comparable accuracy for many targets . **ESM-2 and ESM-3** models available with varying parameter counts (8M to 15B) . **The foundation for protein engineering and design.**



- **[RFdiffusion](https://github.com/RosettaCommons/RFdiffusion)**  

  **Open-source diffusion model for protein design** (BSD-3-Clause) from the Baker Lab (David Baker, 2024 Nobel Prize in Chemistry) . **The most influential open-source protein design tool**—generates novel protein structures with specified functions including binders, enzymes, and symmetric assemblies . **RFdiffusion + ProteinMPNN workflow** has produced experimentally validated designs for **antibody binders, enzyme scaffolds, and biosensors** . **The foundation for computational protein design.**



- **[ProteinMPNN](https://github.com/dauparas/ProteinMPNN)**  

  **Open-source deep learning model for protein sequence design** (MIT) from the Baker Lab. **The standard tool for designing sequences that fold into target structures** . **Combined with RFdiffusion** for the complete protein design pipeline. **Used in countless published protein engineering studies.**



- **[RDKit](https://github.com/rdkit/rdkit)**  

  **The most widely used open-source cheminformatics toolkit** (BSD-3-Clause) . **The foundation for virtually all open-source drug discovery pipelines.** Features molecular I/O, substructure searching, descriptor calculation, fingerprint generation, and 2D/3D coordinate generation . **Used by virtually every pharma company** for data processing and analysis .



- **[DeepChem](https://github.com/deepchem/deepchem)**  

  **Open-source Python framework for deep learning on molecular and materials data** (MIT) . **The most comprehensive open-source framework for molecular ML** —featurizer-pipeline abstraction for converting raw molecular data into numerical representations . **Includes molecular docking workflows**, graph neural networks, and pretrained models . **The standard library for ML-based drug discovery.**



- **[OpenMM](https://github.com/openmm/openmm)**  

  **Open-source molecular dynamics simulation toolkit** (MIT) . **The most widely used open-source MD engine**—high-performance simulation of biomolecules on GPUs and CPUs . **The foundation for protein dynamics, drug binding studies, and free energy calculations** . **Used extensively in academic and industrial research.**



- **[AutoDock Vina](https://github.com/ccsb-scripps/AutoDock-Vina)**  

  **Open-source molecular docking engine** (Apache-2.0). **The most widely used open-source docking tool**—predicts binding poses and affinity for small molecules to proteins . **Used in virtual screening campaigns** for hit identification .



- **[GNINA](https://github.com/gnina/gnina)**  

  **Open-source molecular docking software with deep learning CNN scoring functions** (license varies) . **Version 1.3** updated from Caffe to **PyTorch** for easier custom model integration . **Knowledge-distilled CNN scoring functions** for faster high-throughput screening. **Covalent docking** functionality added. **The most advanced open-source docking framework with deep learning scoring.**



- **[RDKit-based Deep Learning](https://github.com/rdkit/rdkit)**  

  See RDKit above.



### Additional Strong Open-Source Options



- **[Open Targets Platform](https://github.com/opentargets/platform)** — Open-source target identification platform (Apache-2.0) integrating genetics, genomics, and chemical data . **The most comprehensive open-source drug target discovery resource.**

- **[Open Targets Genetics](https://github.com/opentargets/genetics)** — Open-source genetics portal for target identification (Apache-2.0) .

- **[ChEMBL](https://github.com/chembl)** — Open-source bioactivity database (CC BY-SA 3.0) . **The standard open data resource for drug discovery.**

- **[OpenMM-PLUMED](https://github.com/plumed/plumed2)** — Open-source enhanced sampling library (LGPL) for molecular dynamics free energy calculations .

- **[GROMACS](https://github.com/gromacs/gromacs)** — Open-source molecular dynamics package (LGPL) . **The most widely used MD engine in academia.**

- **[BioPython](https://github.com/biopython/biopython)** — Open-source Python tools for biological computation (Biopython License) . **The foundational library for bioinformatics.**

- **[Scanpy](https://github.com/scverse/scanpy)** — Open-source single-cell analysis toolkit (BSD-3-Clause) . **The standard for single-cell RNA-seq analysis.**

- **[Squidpy](https://github.com/scverse/squidpy)** — Open-source spatial single-cell analysis toolkit (BSD-3-Clause) .

- **[PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric)** — Open-source GNN library (MIT) widely used for molecular graph learning .

- **[DGL-LifeSci](https://github.com/awslabs/dgl-lifesci)** — Open-source toolkit for deep learning on graphs in life sciences (Apache-2.0) .

- Community **n8n** workflows for scientific data pipeline automation and research alert routing.



**Frameworks for building custom systems**: Combine **K-Dense-AI Scientific Agent Skills** for validated scientific database access with **OpenFold** or **Boltz-2** for structure prediction, **RFdiffusion + ProteinMPNN** for protein design, **RDKit + DeepChem** for molecular ML, and **OpenMM** for molecular dynamics—creating a comprehensive AI for life sciences stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI for life sciences tools are **research aids, not clinical decision systems**. All predictions require experimental validation before clinical or therapeutic use. **Regulatory compliance (FDA, EMA) remains mandatory** for any clinical application.

- **Model licensing varies significantly.** AlphaFold 2 is Apache-2.0 but **commercial use requires separate licensing from DeepMind** . Chai-1 is **fully Apache 2.0 including commercial use** —a critical differentiator . Boltz-2 is MIT licensed . **Verify licensing before commercial deployment.**

- **Open-source structure prediction has reached parity.** Chai-1 and Boltz-2 achieve AlphaFold 3-class accuracy on protein-ligand and antibody-antigen complexes . Chai-1 exceeded AlphaFold 3 on antibody-antigen prediction (77% vs 65%) in independent benchmarks . **These are genuine alternatives to proprietary services.**

- **Protein design is an open-source strength.** RFdiffusion (Baker Lab, 2024 Nobel Prize) and ProteinMPNN are the foundation for computational protein design . **The combination has produced experimentally validated binders, enzymes, and biosensors** —work that previously required years of directed evolution.

- **Scientific agent skills bridge LLMs to real databases.** K-Dense-AI Scientific Agent Skills provides validated, reproducible access to UniProt, PDB, ChEMBL, PubChem, and other authoritative sources . **This is the emerging pattern for AI-augmented scientific workflows.**

- Self-hosted open-source solutions require proper GPU provisioning, bioinformatics expertise, and ongoing maintenance. **Computational predictions are hypotheses—wet-lab validation remains the rate-limiting step in drug discovery.**



---



**Made for computational biologists, drug discovery teams, and developers building transparent life sciences AI solutions.**  

Let's make AI for Life Sciences more open, data-driven, and scientifically validated.
