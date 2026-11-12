# Data Analytics Practical Resource with Projects

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Analysis-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

A hands-on collection of Python data analytics study materials, Jupyter notebooks, datasets, SQL examples, web scraping practice, and guided analysis projects. Work through individual topics or use the project notebooks to practice cleaning, exploring, summarizing, and visualizing real-world datasets.

## Contents

- [Data analytics projects](#data-analytics-projects)
- [Learning materials](#learning-materials)
- [Getting started](#getting-started)
- [Working with the MySQL examples](#working-with-the-mysql-examples)
- [Repository structure](#repository-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Data analytics projects

Each project folder contains a Jupyter notebook and its accompanying CSV dataset. The notebooks are question-led exercises in data preparation, filtering, aggregation, and analysis.

| Project | Topics covered | Notebook |
| --- | --- | --- |
| Weather dataset | Missing values, conditions, filtering, descriptive statistics, and grouping | [Open notebook](<Data Analytics Project/Project - 1 Weather Dataset/Weather Dataset.ipynb>) |
| Cars dataset | Exploring vehicle makes and origins, filtering records, and updating values | [Open notebook](<Data Analytics Project/Project - 2 Cars Dataset/Project - 2 Cars Dataset.ipynb>) |
| Police dataset | Missing data, stop patterns, searches, duration, and age distributions | [Open notebook](<Data Analytics Project/Project - 3 Police Dataset/Police Dataset.ipynb>) |
| COVID-19 dataset | Regional case counts, filtering, sorting, and India-focused queries | [Open notebook](<Data Analytics Project/Project - 4 Covid-19 Dataset/Covid-19 Dataset.ipynb>) |
| London housing data | Date handling, area and year summaries, house prices, and crime records | [Open notebook](<Data Analytics Project/Project - 5 London Housing Data/London Housing Data.ipynb>) |
| India Census 2011 | District lookups, population and religion summaries, and DataFrame styling | [Open notebook](<Data Analytics Project/Project - 6 Census Dataset/Census Dataset.ipynb>) |

## Learning materials

- **NumPy, Pandas, Matplotlib, and Seaborn** — notebooks and sample datasets for numerical arrays, DataFrames, and charting. Browse the [NumPy](<Numpy, Pandas, Matplotlib, Seaborn/Numpy/numpy.ipynb>), [Pandas](<Numpy, Pandas, Matplotlib, Seaborn/Pandas/Pandas.ipynb>), [Matplotlib](<Numpy, Pandas, Matplotlib, Seaborn/Matplotlib/Matplotlib.ipynb>), and [Seaborn](<Numpy, Pandas, Matplotlib, Seaborn/Seaborn/Seaborn.ipynb>) notebooks.
- **Python with MySQL** — short scripts illustrating database connections, table creation, CRUD operations, filters, joins, and aggregate queries. See the [`Python with MySQL`](<Python with MySQL/>) folder.
- **Web scraping with Python and BeautifulSoup** — a notebook introducing HTTP requests, HTML parsing, and BeautifulSoup. [Open the tutorial](<Web Scraping Tutorial using Python and BeautifulSoup/Web Scraping Tutorial using Python and BeautifulSoup.ipynb>).

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/Md-Emon-Hasan/Data-Analytics-Practical-Resouce-with-Project.git
   cd Data-Analytics-Practical-Resouce-with-Project
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   # Windows PowerShell
   .venv\Scripts\Activate.ps1
   # macOS / Linux
   source .venv/bin/activate
   ```

3. Install the common libraries used by the notebooks and examples:

   ```bash
   python -m pip install jupyter numpy pandas matplotlib seaborn requests beautifulsoup4 html5lib openpyxl pymysql
   ```

4. Start Jupyter and open a notebook:

   ```bash
   jupyter notebook
   ```

Run a notebook from its own project folder so its relative dataset paths resolve correctly. The MySQL scripts also require a running MySQL server and a database connection configured for your environment. The notebooks are independent; install any additional package requested by a particular notebook if needed.

## Working with the MySQL examples

The scripts demonstrate basic SQL operations through PyMySQL. Before running them, install and start MySQL, create/configure the required database and tables, and update the connection settings in the scripts to match your local credentials. Do not put real passwords in files you plan to share.

## Repository structure

```text
Data-Analytics-Practical-Resouce-with-Project/
├── Data Analytics Project/                         # Six dataset analysis projects
├── Numpy, Pandas, Matplotlib, Seaborn/             # Library notebooks and sample data
├── Python with MySQL/                              # SQL connection and query examples
├── Web Scraping Tutorial using Python and BeautifulSoup/
├── LICENSE
└── README.md
```

## Contributing

Suggestions and improvements are welcome. Open an issue to discuss a change, or submit a pull request with a clear description of what you added or fixed.

## License

This repository is distributed under the [Apache License 2.0](LICENSE).

## Contact

**Emon** | [Email](mailto:emon.mlengineer@gmail.com) | [LinkedIn](https://www.linkedin.com/in/md-emon-hasan) | [GitHub](https://github.com/Md-Emon-Hasan)
