# Python-Kerala-University

**Department of Statistics, University of Kerala**
**National Workshop on Python Programming with Machine Learning & Artificial Intelligence (WPMLAI-2026)**
16–20 November 2026

Hands-on Jupyter notebooks for the workshop, prepared and taught by **Mr. Mahesh Divakaran**.

---

## What's in this repository

This repository has the **Day 1 (16 November 2026)** material: a four-session introduction that takes participants from their first line of Python to a clean, merged, analysis-ready dataset.

| Session | Notebook | Topics | Open |
|---|---|---|---|
| 1 | [`Session1_Intro_to_Python_v2.ipynb`](Session1_Intro_to_Python_v2.ipynb) | Variables, data types, type casting, f-strings, lists, tuples, sets, dictionaries, `if/elif/else`, `for`/`while` loops, comprehensions, functions, `try/except` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itsmdivakaran/Python-Kerala-University/blob/main/Session1_Intro_to_Python_v2.ipynb) |
| 2 | [`Session2_NumPy.ipynb`](Session2_NumPy.ipynb) | Arrays vs lists, array creation, indexing and boolean masks, vectorised maths, `axis=0` vs `axis=1`, `np.nan`, broadcasting, reshaping, random numbers | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itsmdivakaran/Python-Kerala-University/blob/main/Session2_NumPy.ipynb) |
| 3 | [`Session3_Pandas.ipynb`](Session3_Pandas.ipynb) | Series and DataFrames, inspecting data, reading/writing CSV, `.loc` vs `.iloc`, filtering, new columns, `.str` and `.dt`, sorting and ranking | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itsmdivakaran/Python-Kerala-University/blob/main/Session3_Pandas.ipynb) |
| 4 | [`Session4_Data_Wrangling.ipynb`](Session4_Data_Wrangling.ipynb) | Missing values, duplicates, type conversion, text and date cleaning, `groupby`, `concat`/`merge`, `pivot_table`/`melt`, a `.pipe()` cleaning pipeline, export to CSV/Excel | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itsmdivakaran/Python-Kerala-University/blob/main/Session4_Data_Wrangling.ipynb) |

Session 1 assumes no programming background. Each session builds on the one before it.

## How the notebooks work

- **No downloads needed.** Every dataset is generated inside the notebook with a fixed seed, so everyone sees the same numbers as the instructor.
- **One story across the day.** All four sessions follow a small clinical study: patient records in Session 1, NumPy arrays of lab readings in Session 2, a 100-row visits table in Session 3, and messy versions of the same 25 patients to clean and merge in Session 4.
- **Same layout for every topic:** a short explanation of what it is and why it matters, a commented code cell, and a *"What to observe"* note telling you what to look for in the output.
- **Practice at the end.** Each notebook closes with three exercises (Beginner, Intermediate, Challenge). Solutions are in collapsed cells below them — try first, then open.

## Getting started

### Option 1 — Google Colab (easiest)
Click an **Open in Colab** badge above. Nothing to install; you only need a Google account.

### Option 2 — On your own computer
1. Install [Anaconda](https://www.anaconda.com/download) (includes Python, Jupyter, NumPy and pandas), or install Python 3.11+ and run:
   ```bash
   pip install numpy pandas openpyxl jupyterlab
   ```
2. Download this repository (**Code → Download ZIP**) or clone it:
   ```bash
   git clone https://github.com/itsmdivakaran/Python-Kerala-University.git
   cd Python-Kerala-University
   jupyter lab
   ```
3. Open a notebook and run the cells from top to bottom with **Shift + Enter**.

### Requirements

| Package | Version |
|---|---|
| Python | 3.11 or newer |
| NumPy | 2.x |
| pandas | 2.x or 3.x |
| openpyxl | any recent version (only for the Excel export in Session 4) |

> The notebooks are saved with their outputs, so you can read them before running anything. To start fresh in class, use **Kernel → Restart Kernel and Clear All Outputs** (JupyterLab) or **Edit → Clear all outputs** (Colab).

## Tips for participants

- Run cells **in order**. Later cells use variables created earlier.
- If something breaks, restart the kernel and run everything again from the top.
- Change the numbers and re-run — that is the quickest way to learn what each line does.
- The synthetic clinical data is for teaching only and does not describe real patients.

## Instructor

**Mr. Mahesh Divakaran**
Senior Technical Lead – Statistical Programming, Ephicacy · Research Scholar in Statistics, Amity University Lucknow

## License

Released under the [MIT License](LICENSE). You are welcome to reuse and adapt these materials; please credit the workshop and the author.
