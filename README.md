# Fragment-Based Drug Discovery: A Practical Cheminformatics Tutorial

## Scaffold Fragmentation, Fragment Library Analysis, Rule of Three Filtering, and Fragment Linking Strategies

A reproducible educational tutorial for Fragment-Based Drug Discovery (FBDD) using Python and RDKit.

This project demonstrates how to:

* Build fragment datasets from public chemical resources
* Apply Rule of Three (Ro3) filtering
* Perform scaffold fragmentation and molecular standardization
* Analyze fragment libraries using cheminformatics workflows
* Deduplicate molecules using InChIKey identifiers
* Explore fragment linking concepts for early-stage drug discovery
* Generate publication-quality outputs for research and teaching

The notebook is designed for:

* MSc and PhD students
* Computational chemistry researchers
* Medicinal chemistry learners
* Drug discovery educators
* Scientists transitioning into cheminformatics

---

## Authors

* Festus Ogungbemiro
* Jane Anebi

**Institution:** CBIOS – Research Center for Biosciences & Health Technologies, Universidade Lusófona, Lisboa, Portugal

---

## Tutorial Overview

This notebook walks through a complete mini-workflow used in Fragment-Based Drug Discovery.

### Topics Covered

| Section                     | Description                                      |
| --------------------------- | ------------------------------------------------ |
| Environment Validation      | Verifies package versions and reproducibility    |
| Astex Dataset Processing    | Extraction and sanitization of ligand structures |
| ChEMBL Fragment Retrieval   | Collection of Rule of Three compliant compounds  |
| Dataset Integration         | Standardization and InChIKey-based deduplication |
| Rule of Three Filtering     | Fragment-space filtering strategy                |
| Fragmentation Analysis      | Scaffold and substructure decomposition          |
| Fragment Library Statistics | Physicochemical descriptor analysis              |
| Fragment Linking Concepts   | Educational demonstration of linking strategies  |
| Visualization               | Molecular rendering and exploratory analysis     |

---

## Scientific Background

Fragment-Based Drug Discovery (FBDD) is a modern drug discovery strategy that identifies low-molecular-weight compounds that bind weakly to biological targets and then optimizes them into potent lead compounds.

Compared with traditional high-throughput screening, FBDD:

* Samples chemical space more efficiently
* Uses smaller and simpler molecules
* Enables rational optimization
* Produces high ligand efficiency hits
* Supports structure-guided drug design

This tutorial combines practical cheminformatics implementation with medicinal chemistry concepts.

---

## Key Features

* Fully reproducible notebook workflow
* RDKit-based cheminformatics pipeline
* Public dataset integration
* ChEMBL REST API retrieval
* InChIKey-based chemical deduplication
* Rule of Three fragment filtering
* Scaffold fragmentation examples
* Educational explanations in every section
* Publication-oriented workflow structure

---

## Technologies Used

| Tool                       | Purpose                                    |
| -------------------------- | ------------------------------------------ |
| Python                     | Core programming language                  |
| RDKit                      | Molecular processing and cheminformatics   |
| Pandas                     | Data handling                              |
| NumPy                      | Numerical analysis                         |
| Matplotlib                 | Visualization                              |
| Seaborn                    | Statistical plotting                       |
| ChEMBL Web Resource Client | Public bioactivity and structure retrieval |
| Jupyter Notebook           | Interactive tutorial environment           |

---

## Project Structure

```text
.
├── fragment_fbdd_tutorial.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/festusoladayoonline-debug/cheminformatics-drug-discovery-tutorial-1.git
cd cheminformatics-drug-discovery-tutorial-1
```

### 2. Create a Virtual Environment

```bash
python -m venv fbdd_env
```

### 3. Activate the Environment

#### Windows

```bash
fbdd_env\Scripts\activate
```

#### macOS / Linux

```bash
source fbdd_env/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Recommended Requirements File

Create a `requirements.txt` file containing:

```text
rdkit
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
chembl_webresource_client
```

---

## Running the Tutorial

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
fragment_fbdd_tutorial.ipynb
```

Run the notebook sequentially from Cell 0 onward.

---

## Educational Objectives

After completing this tutorial, learners should be able to:

* Understand the principles of Fragment-Based Drug Discovery
* Apply Rule of Three filtering in fragment selection
* Process molecular structures using RDKit
* Perform molecular standardization and sanitization
* Deduplicate compounds using InChIKey identifiers
* Analyze fragment physicochemical properties
* Interpret fragment library characteristics
* Understand scaffold fragmentation strategies
* Explore computational medicinal chemistry workflows

---

## Example Applications

This workflow can be adapted for:

* Academic teaching laboratories
* MSc and PhD coursework
* Drug discovery workshops
* Virtual screening preparation
* Fragment library curation
* Medicinal chemistry training
* Computational chemistry education

---

## Dataset Sources

### Astex Diverse Set

Hartshorn MJ, Verdonk ML, Chessari G, Brewerton SC, Mooij WTM, Mortenson PN, Murray CW.

The Astex Diverse Set: structure validation and analysis of a diverse set of protein-ligand complexes for use as benchmarks.

Journal of Medicinal Chemistry (2007).

### ChEMBL Database

Gaulton A et al.

ChEMBL: a large-scale bioactivity database for drug discovery.

Nucleic Acids Research.

---

## References

### Fragment-Based Drug Discovery

Congreve M, Carr R, Murray C, Jhoti H.
A rule of three for fragment-based lead discovery.
Drug Discovery Today. 2003.

Erlanson DA, Fesik SW, Hubbard RE, Jahnke W, Jhoti H.
Twenty years on: the impact of fragments on drug discovery.
Nature Reviews Drug Discovery. 2016.

Murray CW, Rees DC.
The rise of fragment-based drug discovery.
Nature Chemistry. 2009.

### RDKit

Landrum G.
RDKit: Open-source cheminformatics.
[https://www.rdkit.org](https://www.rdkit.org)

---

## Reproducibility

The notebook includes:

* Environment validation
* Package version checks
* Standardized workflows
* Explicit molecular sanitization
* Deterministic structure handling

This improves reproducibility across different systems.

---

## Citation

If you use this tutorial in teaching, research, or derivative work, please cite:

```text
Ogungbemiro F, Anebi J.
Fragment-Based Drug Discovery: A Practical Cheminformatics Tutorial.
CBIOS – Universidade Lusófona.
GitHub Repository.
```

---

## Contributing

Contributions are welcome.

Possible contributions include:

* Bug fixes
* Additional visualization modules
* Improved documentation
* New fragment analysis workflows
* Expanded medicinal chemistry examples
* Machine learning integration

To contribute:

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Submit a pull request

---

## License

This project is intended for educational and research purposes.

You may choose an appropriate open-source license such as:

* MIT License
* BSD 3-Clause License
* Apache 2.0 License

---

## Acknowledgments

Special acknowledgment to:

* RDKit development community
* ChEMBL database contributors
* Open-source scientific computing communities

---

## Contact

Festus Ogungbemiro

Email: [festusoladayoonline@gmail.com](mailto:festusoladayoonline@gmail.com)

GitHub Repository:

[https://github.com/festusoladayoonline-debug/fragment_fbdd_tutorial](https://github.com/festusoladayoonline-debug/fragment_fbdd_tutorial)
