# Effective Pandas 2 - Exercises

This repository contains my exercises and notes from the book **"Effective Pandas 2"** by Matt Harrison. The project is configured using `uv` as dependency manager and `Jupyter Lab` for interactive development.

## 📚 About the book

"Effective Pandas 2" is a practical guide to mastering Python's pandas library, focusing on efficient techniques and best practices for data analysis.

## 🚀 Project setup

### Prerequisites

- Python 3.8+
- [uv](https://docs.astral.sh/uv/) installed

### Installation

1. Clone the repository:

```bash
git clone https://github.com/sjimenezp/effective-pandas-2.git
cd effective-pandas-2
```

2. Install dependencies with uv:

```bash
uv sync
```

3. Activate the virtual environment:

```bash
uv shell
```

4. Start Jupyter Lab:

```bash
uv run jupyter lab
```

## 📂 Project structure

```
effective-pandas-2/
├── notebooks/
│   ├── pandas_strings.ipynb
│   ├── series.ipynb
│   └── ...
├── pyproject.toml
├── .gitignore
└── README.md
```

## 📊 Main dependencies

- **pandas**: Data analysis
- **jupyter**: Interactive development environment
- **matplotlib**: Basic visualization
- **seaborn**: Statistical visualization
- **numpy**: Numerical computing

## 🎯 Learning objectives

- [ ] Master basic pandas operations
- [ ] Apply data cleaning techniques
- [ ] Optimize performance in data analysis
- [ ] Implement best practices in DataFrame manipulation
- [ ] Develop data visualization skills

## 📝 Usage notes

### Useful uv commands

```bash
# Add a new dependency
uv add package-name

# Run Jupyter Lab
uv run jupyter lab

# Run a specific script
uv run python script.py

# Update dependencies
uv sync --upgrade
```

## 📖 Additional resources

- [Official pandas documentation](https://pandas.pydata.org/docs/)
- [uv Documentation](https://docs.astral.sh/uv/)
- [Jupyter Lab Documentation](https://jupyterlab.readthedocs.io/)

## 📄 License

This project is under the MIT license. The exercises are based on the book "Effective Pandas 2" by Matt Harrison.

---

**Note**: Data used in the exercises may require additional download. Check the instructions in each corresponding notebook.
