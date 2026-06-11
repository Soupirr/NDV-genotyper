# NDV Genotyper

A Streamlit web application for Newcastle Disease Virus F gene genotyping.

---

## Requirements

- Python 3.9+
- [MAFFT](https://mafft.cbrc.jp/alignment/software/)
- [FastTree](http://www.microbesonline.org/fasttree/)

---

## Launch the app

### Windows

Make sure `mafft.exe` and `FastTree.exe` are in your PATH (installed by default in the project folder), then run:

```bash
streamlit run app.py
```

### WSL (Ubuntu)

Make sure `mafft` and `FastTree` are installed (`sudo apt install mafft fasttree`), then run:

```bash
streamlit run app.py
```

The app will open automatically in your browser at `http://localhost:8501`.

---

For more information on how to use the app and how to add sequences to the database, see **QUICK_START.md**.

---

## References

- **MAFFT** — Katoh K, Standley DM. *MAFFT Multiple Sequence Alignment Software Version 7: Improvements in Performance and Usability.* Molecular Biology and Evolution, 30(4):772–780, 2013. https://doi.org/10.1093/molbev/mst010

- **FastTree** — Price MN, Dehal PS, Arkin AP. *FastTree 2 – Approximately Maximum-Likelihood Trees for Large Alignments.* PLOS ONE, 5(3):e9490, 2010. https://doi.org/10.1371/journal.pone.0009490

- **Dimitrov et al. (2019)** - Updated unified phylogenetic classification system and revised
nomenclature for Newcastle disease virus, https://doi.org/10.1016/j.meegid.2019.103917

- **Wang et al. (2017)** - Comprehensive analysis of amino acid sequence diversity at the F protein cleavage site of Newcastle disease virus in fusogenic activity, https://doi.org/10.1371/journal.pone.0183923.