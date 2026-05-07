# EGFRIndb: Epidermal Growth Factor Receptor Inhibitor Database

**EGFRIndb** is a specialized, literature-curated database focused on small synthetic molecular inhibitors of the **Epidermal Growth Factor Receptor (EGFR)** family.
This resource centralizes experimental data on compounds targeting EGFR and its various isoforms, which are critical pharmacological targets due to their association with cancers such as lung and breast cancer.

**Web Server:** https://webs.iiitd.edu.in/raghava/egfrindb/


## About the Database

The EGFR family consists of four trans-membrane protein isoforms: **EGFR (ErbB1)**, **ErbB2**, **ErbB3**, and **ErbB4**. Aberrant activity, such as overexpression or mutation in these receptors, often leads to uncontrolled cell proliferation and cancer.
EGFRIndb was developed to pool scattered biological activity data into a single platform to support drug discovery and decision-making.

* **Data Scope:** Curated from PubMed and Google Scholar search results through December 2013.
* **Target Diversity:** Includes inhibitors for EGFR, ErbB2, ErbB4, and clinically relevant mutants.


## Key Features

### 1. Comprehensive Compound Data
The database currently houses **4,581 unique synthetic compounds**. Each entry provides:
* **Structural Information:** 2D and 3D structures, SMILES, InChI, and InChIKey.
* **Inhibitory Activity:** Quantitative values such as $IC_{50}$, $K_{i}$, $K_{d}$, $EC_{50}$, and percentage inhibition.
* **Physicochemical Properties:** Molecular mass, logP, polar surface area (PSA), and hydrogen bond donor/acceptor counts.

### 2. Specialized Inhibitor Categories
EGFRIndb tracks specific classes of inhibitors designed to overcome clinical drug resistance:
* **Irreversible Inhibitors:** 367 compounds that bind covalently to specific residues, such as Cys773 of EGFR or Cys805 of ErbB2.
* **Dual Inhibitors:** 618 compounds that target both EGFR and ErbB2 simultaneously.
* **Mutant Inhibitors:** Data for compounds targeting resistant mutations like **T790M**, **L858R**, and the double mutant **L858R/T790M**.

### 3. Drug-Likeness and Selectivity
* **Filters:** Compounds are evaluated against rules like **Lipinski’s rule of five**, Veber, Ghose, Muegge, and Lead-likeliness to determine oral bioavailability and drug-likeliness.
* **Selectivity Data:** Provides curated inhibitory activity against other non-EGFR kinases to help assess compound specificity and selectivity.


## Integrated Tools and Access

EGFRIndb offers several user-friendly modules for data exploration:
* **Simple & Advanced Search:** Query by molecule name, IUPAC name, PMID, or specific ranges of physicochemical properties and inhibitory values.
* **Similarity Search:** Features an integrated **JME molecular editor** allowing users to draw structures online and search for similar molecules in the database.
* **Browse Module:** Allows access to the entire collection by inhibitor class (e.g., quinazolines, pyrimidines), cell line (e.g., **A431**, **MCF-7**), or inhibitory range.
* **Data Download:** Supports single compound downloads in **mol format** or batch downloads of specific datasets.


## Applications

* **Chemo-informatics:** Developing **QSAR models** and virtual screening protocols.
* **Lead Optimization:** Identifying scaffolds with higher potency than established drugs like **gefitinib** or **erlotinib**.
* **Mechanism Research:** Understanding the chemistry of reversible versus irreversible binding modes.


## Contact & Authors

**Dr. Subhash M. Agarwal** (Corresponding Author) 

**Prof. Gajendra P.S. Raghava** (Corresponding Author) raghava@iiitd.ac.in Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.

## License & Support

EGFRIndb was supported by the **Department of Biotechnology (DBT)** and the **Indian Council of Medical Research (ICMR)**.
The website is hosted on the **Open Source Drug Discovery (OSDD)** platform and **IIIT Delhi**.
