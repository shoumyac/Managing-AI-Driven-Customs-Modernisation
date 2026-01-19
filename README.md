# Bridging the Bureaucracy-Agility Divide

## A Hybrid Framework for AI-Driven Customs Modernisation in Bangladesh

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📄 About

This repository contains the data and analysis code for the research paper:

> **Paul, S., Das, A., & Chowdhury, S.** Bridging the Bureaucracy-Agility Divide: A Hybrid Framework for AI-Driven Customs Modernisation in Bangladesh. *Cogent Business & Management* (Under Review).

### Abstract

Customs administrations in developing countries face a fundamental paradox: they must enforce rigid legal codes while adopting rapidly evolving AI technologies. This tension between bureaucratic stability and technological agility creates systemic project management challenges that existing frameworks fail to address. Through a survey of 130 stakeholders in Bangladesh Customs (Cronbach's α = 0.713–0.819), we find current practices score poorly (M=2.63/5.0), with resistance to change (M=4.29), policy volatility (M=4.28), and unclear requirements (M=4.26) emerging as primary barriers. Despite these challenges, stakeholders across all groups strongly favour hybrid approaches combining structured governance with iterative development (M=4.28; F(5,124)=0.34, p=.885), indicating barriers are structural rather than attitudinal. We propose a Hybrid Agile Framework that functions as an institutional boundary spanner, enabling "bounded agility" where iterative experimentation operates within governance guardrails.

---

## 📁 Repository Contents

```
├── README.md                              # This file
├── data/
│   └── survey_responses.csv               # Anonymous survey data (N=130)
└── notebook/
    └── Research_Analysis_Notebook.ipynb   # Complete analysis notebook
```

---

## 📊 Data Description

### Survey Structure

The survey instrument comprised 10 sections:

| Section | Focus | Items |
|---------|-------|-------|
| A | Background Information | 4 items |
| B | Project Characteristics | 3 items |
| C | Current PM Practices | 8 Likert items |
| D | AI-Specific Aspects | 5 Likert items |
| E | Perceived Challenges | 8 Likert items |
| F | Agile/Hybrid Attitudes | 5 Likert items |
| G | Framework Elements | 7 Likert items |
| H | Training & Change Management | 4 Likert items |
| I | Outcomes | 4 items |
| J | Open-Ended Questions | 5 questions |

### Sample Characteristics

- **Sample size:** N = 130
- **Stakeholder groups:** BCS Officers (34.6%), NBR Officials (19.2%), Trade Professionals (19.2%), Vendor IT (16.9%), Academics (6.2%), Government IT (3.8%)
- **Experience:** 86.9% with >5 years professional experience
- **Collection period:** October-November 2024

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scipy matplotlib seaborn
```

### Running the Analysis

1. Clone the repository:
```bash
git clone https://github.com/[username]/customs-hybrid-framework.git
cd customs-hybrid-framework
```

2. Open the Jupyter notebook:
```bash
jupyter notebook notebook/Research_Analysis_Notebook.ipynb
```

3. Run all cells to reproduce the analysis

> **Note:** The notebook reads data from `data/survey_responses.csv`. Ensure the folder structure is maintained.

---

## 📈 Key Findings

### RQ1: Current Practices
- PM practices significantly below neutral (M=2.63/5.0, p<.001)
- AI-specific practices similarly weak (M=2.54/5.0)

### RQ2: Key Challenges
- Resistance to change (M=4.29)
- Policy/leadership volatility (M=4.28)
- Unclear requirements (M=4.26)
- All challenges rated above 4.0/5.0

### RQ3: Hybrid Preference
- Strong consensus for hybrid approaches (M=4.28)
- No significant difference across stakeholder groups (p=.885)

### RQ4: Framework Elements
- Product owner importance (M=4.43)
- Clear acceptance criteria (M=4.41)
- All elements rated above 4.3/5.0

---

## 📜 Citation

If you use this data or code, please cite:

```bibtex
@article{paul2025bridging,
  title={Bridging the Bureaucracy-Agility Divide: A Hybrid Framework for AI-Driven Customs Modernisation in Bangladesh},
  author={Paul, Sushanta and Das, Anmita and Chowdhury, Shoumya},
  journal={Cogent Business \& Management},
  year={2025},
  note={Manuscript under review},
  publisher={Taylor \& Francis}
}
```

---

## 👥 Authors

- **Sushanta Paul** - Joint Commissioner, Bangladesh Customs, National Board of Revenue
  - ORCID: [0009-0007-8071-6971](https://orcid.org/0009-0007-8071-6971)

- **Anmita Das** - Faculty of Engineering and Information Technology, The University of Melbourne
  - ORCID: [0009-0000-1401-0494](https://orcid.org/0009-0000-1401-0494)

- **Shoumya Chowdhury** *(Corresponding Author)* - Faculty of Engineering and Information Technology, The University of Melbourne
  - ORCID: [0009-0005-5552-1094](https://orcid.org/0009-0005-5552-1094)
  - Email: shoumyac@student.unimelb.edu.au

---

## 📋 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

---

## 🙏 Acknowledgements

We gratefully acknowledge the National Board of Revenue (NBR), Bangladesh for facilitating access to customs officials and stakeholders. We extend our sincere thanks to all 130 survey respondents who generously shared their time and insights.

---

## 📧 Contact

For questions about this research or data:
- **Email:** shoumyac@student.unimelb.edu.au
- **Issues:** Please open an issue in this repository
