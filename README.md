
<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>
Pokemon-Analysis
</h1>
<h3 align="center">📍 Unleash the Power of Data with Pokemon-Analysis on GitHub</h3>
<h3 align="center">⚙️ Developed with the software and tools below:</h3>

<p align="center">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style=for-the-badge&logo=Markdown&logoColor=white" alt="Markdown" />
</p>
</div>

---

## 📚 Table of Contents
- [📚 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [💫 Features](#-features)
- [📂 Project Structure](#project-structure)
- [🧩 Modules](#modules)
- [🚀 Getting Started](#-getting-started)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

In this project, I have worked on a mini-project in the field of Data Science and Machine Learning, with a focus on Pokémon. Being a devoted Pokémon fan, I decided to leverage the extensive data and statistics available in the Pokémon universe to create data visualizations and develop two Machine Learning solutions.

The first solution in this project involves the classification of Pokémon, determining whether they are legendary or not based on their statistics. This allows us to determine if a Pokémon possesses unique qualities that make it legendary within the Pokémon world.

The second solution aims to predict the outcome of battles between two Pokémon. By analyzing the statistics of each Pokémon and training the model on a dataset of recorded battles, we can forecast which Pokémon will emerge as the winner.

Throughout this project, I have enjoyed immersing myself in the world of Pokémon while applying my knowledge and skills in Data Science and Machine Learning. By exploring Pokémon data and developing predictive models, I have gained valuable insights into the statistical aspects of Pokémon. This project has been an exciting opportunity to combine my passion for Pokémon with the power of data analysis and machine learning techniques.
---

## 💫 Features

Feature | Description |
|---|---|
| **🏗 Structure and Organization** | The codebase is organized into directories based on the type of analysis being performed, and each directory contains a Jupyter notebook with a specific focus on analyzing Pokemon data. |
| **📝 Code Documentation** | The code is well-documented with detailed explanations of each step taken in the analysis process. |
| **🧩 Dependency Management** | Dependencies are managed using a requirements.txt file, which lists all external Python packages needed to run the analyses. |
| **♻️ Modularity and Reusability** | The code is modular and reusable, with functions defined in separate code cells and imported as needed throughout the notebook. |
| **✔️ Testing and Quality Assurance** | There are no explicit tests in the codebase and there is no indication of testing and quality assurance methods being used. |
| **⚡️ Performance and Optimization** | The code does not appear to be optimized for performance, though the nature of the analysis being performed may not require heavy optimization. |
| **🔒 Security Measures** | There is no indication of security measures being implemented in the codebase. |
| **🔄 Version Control and Collaboration** | The codebase is version-controlled using Git, with each analysis being committed as a separate branch. Collaboration does not appear to be a primary focus of the project. |
| **🔌 External Integrations** | There are no external integrations utilized in the codebase. |
| **📈 Scalability and Extensibility** | The codebase could potentially scale and be extended by adding additional analyses or expanding the scope of current analyses. However, the absence of explicit modularity or testing may limit the project's scalability. |

---


<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-github-open.svg" width="80" />

## 📂 Project Structure


```bash
repo
├── README.md
├── battle-prediction
│   └── PokemonBattleML.ipynb
├── data
│   ├── Pokemon-Battle.csv
│   ├── battles.csv
│   ├── pokemon.csv
│   ├── tests.csv
│   └── types_chart.csv
├── dataset-stats-viz
│   └── DataVizPokemon.ipynb
└── legendary-classification
    └── LegendaryML.ipynb

4 directories, 9 files
```

---

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-src-open.svg" width="80" />

## 🧩 Modules

<details closed><summary>Battle-prediction</summary>

| File                  | Summary                                                                                                                       | Module                                  |
|:----------------------|:------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------|
| PokemonBattleML.ipynb | Pokemon Battle Prediction | battle-prediction/PokemonBattleML.ipynb |


</details>

<details closed><summary>Dataset-stats-viz</summary>

| File                 | Summary                              | Module                                 |
|:---------------------|:-------------------------------------|:---------------------------------------|
| DataVizPokemon.ipynb | Dataviz Analysis of Pokemon Universe | dataset-stats-viz/DataVizPokemon.ipynb |

</details>

<details closed><summary>Legendary-classification</summary>

| File              | Summary                                                                                                                       | Module                                     |
|:------------------|:------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------|
| LegendaryML.ipynb | ML Classification of Pokemon | legendary-classification/LegendaryML.ipynb |


</details>

---

## 🚀 Getting Started

### ✅ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> - Install Python: Make sure you have Python installed on your system. You can download the latest version of Python from the official Python website (https://www.python.org/) and follow the installation instructions specific to your operating system.
> - Set up a virtual environment (optional but recommended): It's a good practice to create a virtual environment to isolate your project dependencies. Open a terminal or command prompt and run the following commands:
    On Windows:
        python -m venv myenv
        myenv\Scripts\activate
    On macOS and Linux:
        python3 -m venv myenv
    source myenv/bin/activate

### 🖥 Installation

1. Clone the Pokemon-Analysis repository:
```sh
git clone ../Pokemon-Analysis
```

2. Change to the project directory:
```sh
cd Pokemon-Analysis
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🤖 Using Pokemon-Analysis

```sh
jupyter nbconvert --execute notebook.ipynb
```

### 🧪 Running Tests
```sh
pytest notebook_test.py
```

---


## 🗺 Roadmap

> - [X] [📌  Task 1: Data Visualization and Analysis of Pokemon's Dataset]
> - [X] [📌  Task 2: ML Legendary Classification of Pokemon]
> - [X] [📌  Task 3: ML Prediction of a Pokemon Battle]
> - [ ] ...


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a pull request to the original repository.
Open a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `[📌  MIT License]` License. See the [LICENSE](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) file for additional info.

---

## 👏 Acknowledgments

> - Inspiration: This project was inspired by my passion for Pokémon. As a long-time fan, I wanted to explore and analyze Pokémon data using data analysis techniques.
> - Resources:
    Kaggle: The Pokémon dataset used in this project was obtained from Kaggle, a platform for data science and machine learning.
    GitHub: Various open-source projects and repositories on GitHub provided valuable insights and ideas for implementing the Pokémon analysis.
    Pokepedia Website: The Pokepedia website served as a comprehensive resource for gathering information and details about Pokémon, their attributes, and battle statistics.
> - Special thanks to:
    Khaled: I would like to express my sincere gratitude to Khaled for his invaluable help and mentorship throughout this project. His guidance and expertise have been instrumental in shaping the direction of this analysis.
---
