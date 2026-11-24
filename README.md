# Python untuk Pemula

Practice repository for the "Python untuk Pemula" lessons. All chapter examples live in a single file, `main.py`. Every chapter is committed separately together with a screenshot of its output.

## Requirements

- Python 3.x
- Git

## Setup (Windows PowerShell)

```powershell
git clone https://github.com/bainalhkim/python-untuk-pemula.git
cd python-untuk-pemula
python -m venv venv
.\venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python main.py
```

## Chapters

| No | Topic | Screenshot |
|----|-------|------------|
| 1 | Introduction | `screenshots/ch01-introduction.png` |
| 2 | Variables and Data Types | `screenshots/ch02-variables.png` |
| 3 | Operators | `screenshots/ch03-operators.png` |
| 4 | Conditionals | `screenshots/ch04-conditionals.png` |
| 5 | Loops | `screenshots/ch05-loops.png` |
| 6 | Lists and Dictionaries | `screenshots/ch06-lists.png`, `screenshots/ch07-dictionaries.png` |
| 7 | Functions | `screenshots/ch08-functions.png` |
| 8 | Classes and Objects | `screenshots/ch09-classes.png` |
| 9 | PIP and Virtual Environments | `screenshots/ch09-pip-venv.png` |
| 10 | IDE Configuration | `screenshots/ch10-ide-config.png` |
| 11 | README and Requirements | `screenshots/ch11-readme-requirements.png` |

## Commit Convention

This project follows Conventional Commits: `type(scope): subject`, a bullet-point body, and a `Refs: chapter-XX` footer.
