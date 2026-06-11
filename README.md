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

Make sure `mafft.exe` and `FastTree.exe` are in your PATH (or in the project folder), then run:

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
