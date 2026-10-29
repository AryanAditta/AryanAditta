# Arian Rahman Aditta

**Electronics & Communication Engineering Graduate · RF/mmWave IC Design · Analog/RF IC · VLSI/EDA · Design Automation**  
Khulna University of Engineering & Technology (KUET) · Dhaka, Bangladesh

[Google Scholar](https://scholar.google.com/citations?user=Id4ByyUAAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/arian-rahman-aditta/)  
[RFIC CV](https://aryanaditta.github.io/rfic-academic/Arian_Rahman_Aditta_RFIC_CV.pdf) · [EDA CV](https://aryanaditta.github.io/eda-academic/Arian_Rahman_Aditta_EDA_CV.pdf)

I am an ECE graduate working across two complementary hardware-design directions: **RF/mmWave integrated-circuit design** and **VLSI/EDA**. My research focuses on physically meaningful design, verification and design automation, with machine learning used where it adds measurable value rather than replacing circuit, geometric or EDA verification.

I am currently preparing for **Fall 2027 graduate research opportunities** in RF/mmWave IC design, analog/RF IC design, physical design automation and ML-assisted EDA.

## Current Research

### RF/mmWave IC Design

**28 GHz SiGe Power Amplifier Design & Verification**  
Undergraduate thesis · First-author manuscript submitted to ICCIT 2026

- Designed and simulated a two-stage 28 GHz Class-A SiGe PA using the **IHP SG13G2 130-nm SiGe BiCMOS Open PDK**.
- Built a progressive **ideal-passive → PDK-aware → EM-aware** realization flow using Qucs-S, ngspice/Xyce, KLayout and EM-aware modeling.
- The final process-aware configuration achieved **17.4 dB gain at 28 GHz**.
- ML-assisted candidate screening is used as a supporting design-space tool while circuit simulation and RF verification remain the primary evidence.
- Current continuation targets **full-custom layout, physical verification and GDSII-level realization**.



**27 GHz SiGe RF Front-End Design-Space Generation**  
Mentored research with Sultan Muhammad Ikram, RF/mmWave MMIC Designer, Neural Semiconductor Limited

- Parameterized **common-emitter and cascode PA** families in IHP SG13G2 with controlled variation of device sizing, bias, RF chokes and input/output matching networks.
- Building a private circuit parameter-performance dataset through repeatable **DC, small-signal, stability and large-signal** characterization using Qucs-S, ngspice, Xyce and Python.
- Extending the framework toward **common-emitter and cascode LNAs** for comparative PA/LNA topology analysis, surrogate modeling and later ML-assisted RFIC exploration.

[Public research repository →](https://github.com/AryanAditta/27GHz-RF-Front-End-Design-Space)

### VLSI / EDA

**GRACE: GNN-Guided Relational Decoding with Convex Shaping and Exact Repair for Constraint-Rich Floorplanning**  
Independent research · First-author manuscript submitted to ICEEICT 2027

- GRACE predicts **block relations and soft-block shapes rather than final coordinates**.
- Deterministic relational decoding, convex shaping and exact repair convert the learned guidance into hard-legal floorplans.
- On **100 unseen FloorSet-Lite confirmation layouts**, GRACE produced **100/100 hard-legal outputs** and outperformed the matched-time single-worker PARSAC CA-SA baseline on all 100 layouts.
- Controlled learned-start ablations show that the learned initialization accounts for most of the wirelength advantage, while exact repair provides legality-preserving optimization through constraint surgery, local moves and CP-SAT windows.



**Source-Aware RTL-to-QoR Prediction for Early Area and Timing Estimation**  
Research collaboration with Zakia Sultana, Ph.D. Candidate, MSCAD Laboratory, University of Arkansas · Manuscript in preparation

- Developed a source-aware RTL-to-QoR framework separating source-derived structural representations from physical labels generated independently through **Yosys/ABC and OpenSTA**.
- The development corpus contains **681 labelled RTL configurations grouped into 498 source-connected components**.
- On fresh prospective paired cohorts, the Area system improved MAE from approximately **8,382 to 3,015 µm²**, while TimingV2 improved MAE from approximately **0.167 to 0.136 ns**.
- Separate ongoing pilots extend the same reproducible-labeling philosophy toward **standardized RTL-to-power labeling** and **OpenROAD physical-design characterization** through floorplanning, placement, CTS, routing and post-route timing.

[Reproducibility repository →](https://github.com/AryanAditta/Rtl-Qor-Source-Aware-Evaluation)

## Peer-Reviewed Publications

1. **A. R. Aditta**, P. K. Das, U. R. Arshee and A. B. M. Aowlad Hossain, “SenseStick: A Bangla-English Edge-AI Cane for Road-Safety and Biomedical Reliability Monitoring,” **IEEE BECITHCON 2026**. *(First Author)*
2. P. K. Das, S. M. R. Islam and **A. R. Aditta**, “LMatchNet-V: Physics-Seeded Learning for Vendor-Aware RF L-Section Matching with Adaptive Safe-Library Search,” **IEEE MARSCON 2026**.
3. M. A. Jahin, S. Soudeep, **A. R. Aditta**, M. F. Mridha, N. Fahad and M. J. Hossen, “Vision Transformers for End-to-End Quark-Gluon Jet Classification from Calorimeter Images,” **Communications in Computer and Information Science, Springer**, 2025.

## Current Manuscripts

- **Progressive PDK-to-EM Realization of a 28 GHz Two-Stage Class-A SiGe Power Amplifier in an Open-Source RFIC Flow** — submitted to ICCIT 2026. *(First Author)*
- **GNN-Guided Relational Decoding with Convex Shaping and Exact Repair for Constraint-Rich Floorplanning** — submitted to ICEEICT 2027. *(First Author)*
- **Source-Aware Evaluation of RTL Area and Timing Prediction with Prospective Confirmation** — manuscript in preparation.

A separate broader ML-evaluation project on enhancer-prediction benchmark auditing is also maintained publicly as supporting methodological work: [Enhancer Benchmark Audit](https://github.com/AryanAditta/Enhancer-Benchmark-Audit).

## Research Repositories

| Repository | Scope |
|---|---|
| [27GHz-RF-Front-End-Design-Space](https://github.com/AryanAditta/27GHz-RF-Front-End-Design-Space) | SiGe PA/LNA design-space generation in IHP SG13G2 using Qucs-S, ngspice, Xyce and Python |
| [Rtl-Qor-Source-Aware-Evaluation](https://github.com/AryanAditta/Rtl-Qor-Source-Aware-Evaluation) | Reproducibility package for source-aware RTL Area/Timing prediction and prospective confirmation |
| [Enhancer-Benchmark-Audit](https://github.com/AryanAditta/Enhancer-Benchmark-Audit) | Broader ML-evaluation research on benchmark overlap, grouped evaluation and assay transfer |
| [SenseStick-Navigation-Aid](https://github.com/AryanAditta/SenseStick-Navigation-Aid) | Prototype code and project materials associated with the published SenseStick assistive-system work |
| [Dual-Band-Patch-Antenna](https://github.com/AryanAditta/Dual-Band-Patch-Antenna) | CST-based dual-band antenna design and full-wave EM analysis |

## Technical Toolkit

**RFIC / Circuit / EM**  
IHP SG13G2 · Qucs-S · ngspice · Xyce · KLayout · openEMS · CST Studio Suite · LTspice · Cadence Virtuoso · S-parameters · impedance matching · stability · noise analysis

**VLSI / EDA / RTL**  
Verilog · Yosys · ABC · OpenSTA · Nangate45 · OpenROAD-oriented physical-design workflows · floorplanning · constraint handling · CP-SAT · simulated annealing

**Machine Learning / Scientific Computing**  
Python · PyTorch · TensorFlow/Keras · scikit-learn · XGBoost · NumPy · Pandas · MATLAB · GNNs · CNNs · tree-based models · regression/classification

**Research Workflow**  
Git · LaTeX · Zotero · source/provenance tracking · grouped evaluation · prospective prediction freezes · reproducible experimentation

## Academic Snapshot

- **B.Sc. Engineering in Electronics and Communication Engineering**, KUET, 2022–2026
- **CGPA:** 3.71 / 4.00
- **Class Rank:** 5 / 60 *(Top 8.3%)*
- **Final four term GPAs:** 3.89, 4.00, 4.00, 3.88
- **Dean’s Awards:** 3rd and 4th Year
- **Technical Scholarship:** KUET
- **President:** KUET Research Society, ECE, 2025–2026
- **General Secretary:** KUET Debating Society, 2023–2026

## Research Direction

My long-term interest is in research where **physical hardware understanding and computational design methods reinforce each other**: RF/mmWave IC realization, analog/RF design, physical design automation, early hardware-quality prediction and learning-assisted optimization with explicit engineering verification.
