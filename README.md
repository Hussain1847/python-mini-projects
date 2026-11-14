<div align="center">

# 🐍 Python Mini Projects

**Beginner Python projects from PIAIC Quarter 1 (Modern AI Python)**

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Run%20in-Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

</div>

---

Each project is a self-contained Jupyter notebook. Click **Open in Colab** to run it in your browser with nothing to install.

## 📂 Projects

| # | Project | What it does | Concepts | Run |
|:-:|---------|--------------|----------|:---:|
| 1 | [📝 Mad Libs](Project1.ipynb) | Fills your words into a funny story | f-strings, functions, input validation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussainzia/python-mini-projects/blob/main/Project1.ipynb) |
| 3 | [🔢 Number Guessing](Project3.ipynb) | You guess the computer's number, or it guesses yours with binary search | `random`, loops, `try/except` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussainzia/python-mini-projects/blob/main/Project3.ipynb) |
| 4 | [✂️ Rock, Paper, Scissors](Project4.ipynb) | Best-of-many against the computer, with a running score | dictionaries, game loops | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussainzia/python-mini-projects/blob/main/Project4.ipynb) |
| 5 | [🪢 Hangman](Project5.ipynb) | Guess the word before the drawing is complete | sets, comprehensions, game state | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussainzia/python-mini-projects/blob/main/Project5.ipynb) |
| 6 | [⏱️ Countdown Timer](Project6.ipynb) | Counts down from `90` or `1:30` | `time`, `divmod`, parsing | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussainzia/python-mini-projects/blob/main/Project6.ipynb) |
| 7 | [🔐 Password Generator](Project7.ipynb) | Strong passwords with every character type | `secrets`, `string` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussainzia/python-mini-projects/blob/main/Project7.ipynb) |
| 8 | [⚖️ BMI Calculator](Project8.ipynb) | BMI with the WHO weight category | arithmetic, `if/elif` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussainzia/python-mini-projects/blob/main/Project8.ipynb) |
| 9 | [📊 Data Explorer](Project9.ipynb) | Preview, filter and chart a CSV file | pandas, matplotlib | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussainzia/python-mini-projects/blob/main/Project9.ipynb) |

## 🚀 Run locally

```bash
git clone https://github.com/hussainzia/python-mini-projects.git
cd python-mini-projects
pip install notebook pandas matplotlib
jupyter notebook
```

Projects 1 to 8 use only the Python standard library. Project 9 needs `pandas` and `matplotlib`, and reads [`sample_data.csv`](sample_data.csv) when it is in the same folder.

## 🛠️ Highlights

- **Input validation everywhere:** typing letters where a number is expected asks again instead of crashing.
- **Self-contained:** Hangman includes its own word list and drawings, so it no longer needs files on Google Drive.
- **Secure passwords:** the generator uses `secrets` (built for security) instead of `random`.
- **Correct BMI ranges:** no gaps between categories, so a BMI like 24.95 is labelled correctly.

---

<div align="center">

Made with ❤️ by [Hussain Zia](https://github.com/hussainzia)

</div>
