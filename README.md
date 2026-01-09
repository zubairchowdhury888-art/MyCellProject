[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18195391.svg)](https://doi.org/10.5281/zenodo.18195391)

MyCellProject v4: Fungal Electrical Grammar
Schizophyllum commune electrical grammar analysis from 137-hour recordings. Replicates and expands Adamatzky (2023) Scientific Reports on multiscalar fungal spiking.

Key Results
Grammar complexity peaks at T=1.0 (Adamatzky entropy threshold)

90 rules, max depth=3 (low-entropy S. commune vs. trivial Cordyceps/Omphalotus)

Interferometry confirms bio-topological memory

Cross-species grammar comparison (5 datasets)

Co-authorship: Prof. Andrew Adamatzky (UWE Bristol)

🚀 Quick Start
bash
pip install -r requirements.txt
python 02_analysis/run_full_analysis.py
📁 Structure
text
MyCellProject/
├── 02_analysis/           # Grammar extraction + figures
├── Research/              # Methods + processed data
├── Zenodo_Upload_Final/   # v4 preprint + supplementary
└── requirements.txt
📊 Reproducibility
Download raw data: Zenodo (Cordyceps 108MB, Ghost 156MB, etc.)

python 02_analysis/grammar_extraction.py

python 02_analysis/merge_entropy_grammar.py

Figures auto-generated

🧬 Background
Expands Adamatzky's analysis of electrical spiking in fungi, identifying grammar-like structures in spike patterns. S. commune shows higher complexity than simpler species.
​

🔗 Related Work
Multiscalar electrical spiking in Schizophyllum commune

Language of fungi derived from electrical spiking

📤 Publish
Preprint in Zenodo_Upload_Final/. Target bioRxiv/Google Scholar/Academia.edu.

🙏 Cite
text
@misc{mycellproject_v4,
  author = {Chowdhury, Zubair E. and Adamatzky, Andrew},
  title = {Fungal Electrical Grammar: Schizophyllum commune Analysis},
  doi = {10.5281/zenodo.18195391},
  year = {2026}
}
GitHub: https://github.com/zubairchowdhury888-art/MyCellProject
