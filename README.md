# PUC-Tech Coding Challenge 2026

## About The Project

This repository contains my solution for the **PUC-Tech 2026.1 Admission Coding Challenge**. 

The project is structured as a Jupyter Notebook and was designed to showcase practical, hands-on problem-solving skills across different areas of technology, including Exploratory Data Analysis (EDA), Scripting/Cryptography, and Software Engineering (CRUD operations & API integration).

##Challenges Overview

### Desafio 1: Data Analysis (Steam Games Dataset)

An exploratory data analysis performed on a public Steam games dataset (`games.csv`) to investigate factors associated with successful game launches.

- **Data Cleaning & Filtering:** Handled header inconsistencies, dropped duplicates, and filtered out non-game software.
- **Metrics & Aggregation:** Calculated platform compatibility (Windows, Mac, Linux) and average pricing metrics.
- **Categorization & Visualization:** Grouped games by price tiers (Free, Low Cost, High Cost) and visualized the correlation between price and positive reviews using `matplotlib`.
- **Advanced Ranking:** Implemented a **Bayesian Average** algorithm to accurately rank the Top 10 highest-rated games, using a confidence weight to prevent bias from games with very few reviews.

### Desafio 2: Cryptography & Security (Brute-Force)

Acting as a security analyst to demonstrate the vulnerabilities of systems without rate limiting.

- **Task:** Recover a partially masked CPF (`XXX.281.940-XX`).
- **Solution:** Developed an optimized brute-force algorithm that iterates through numeric combinations (testing the first 3 and last 2 digits) against a validation function.
- **Result:** Successfully recovered the valid CPF in 91,902 attempts, demonstrating the risks of authentication systems lacking CAPTCHA or attempt limits.

### Desafio 3: Software Engineering (Pokédex CLI App)

Developed a local, interactive Pokédex Command Line Interface (CLI) system.

- **CRUD Architecture:** Implemented Create, Read, Update (level), and Delete functionalities.
- **Data Persistence:** Built a local storage system that reads and writes Pokémon data to a `pokedex.json` file.
- **API Integration:** Integrated the public **PokeAPI** (`pokeapi.co`) via the `requests` library to fetch official, real-time Pokémon data (types, height, weight, and base battle stats) and prevent duplicate entries.
- **UX/UI:** Created clean, formatted terminal tables and visual status bars for a better user experience.

##Technologies & Libraries Used

- **Language:** Python 3
- **Data Manipulation & Math:** `pandas`
- **Data Visualization:** `matplotlib.pyplot`
- **Network & Web:** `requests`
- **File Handling & System:** `json`, `os`
- **Environment:** Jupyter Notebook / Google Colab

##How to Run

1. Clone this repository:
      ```bash
      git clone [https://github.com/rbinfantini/PUC-Tech-Challenge](https://github.com/rbinfantini/PUC-Tech-Challenge)
