# Spanish Housing Data Analysis

Exploratory data analysis of the Spanish housing market using official public data.

## Main question

How have housing prices evolved in Spain, and what territorial differences can be observed?

## Key findings

*(To be completed as the analysis progresses — add 2-3 bullet points with your most interesting findings here, e.g. price trends by region, notable anomalies, correlations found.)*

- ...
- ...
- ...

## Data sources

This project uses official public data, mainly from:

- [Ministerio de Vivienda y Agenda Urbana (MIVAU)](https://www.mivau.gob.es/) — housing price series and statistics.
- [Instituto Nacional de Estadística (INE)](https://www.ine.es/) — socioeconomic and demographic data.

### Ministerio de Vivienda y Agenda Urbana (MIVAU)

The initial dataset used in this project is the official MIVAU dataset "Valor tasado de la Vivienda", which contains the average appraised value of housing in €/m², disaggregated by housing regime, province, autonomous community and quarterly period.

- Source: Ministerio de Vivienda y Agenda Urbana (MIVAU)
- Dataset: Valor tasado de la Vivienda
- Format: CSV
- License: CC BY 4.0

The original dataset is stored in data/raw/ without modification.

## Tech stack

- Python 3.x
- pandas, NumPy
- matplotlib / seaborn (visualization)
- Jupyter Notebook
- Git / GitHub for version control
- *(SQL and additional libraries to be incorporated as the project grows)*

## Project structure

```
spanish-housing-analysis/
── LICENSE
├── README.md
├── data/
│   ├── processed/
│   └── raw/
├── figures/
├── notebooks/
├── src/
```

## How to run this project

```bash
# Clone the repository
git clone https://github.com/<victorlpzz>/spanish-housing-analysis.git
cd spanish-housing-analysis

# Create a virtual environment and install dependencies
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

# Launch the notebooks
jupyter notebook
```

## Analysis performed / planned

- Evolution of housing prices over time.
- Differences in housing prices between Spanish territories.
- Comparison between provinces and autonomous communities.
- Relationship between housing prices and other socioeconomic variables.
- Identification of patterns and anomalies.

As the project develops, additional datasets and more advanced statistical techniques (SQL, regression models, etc.) will be incorporated.

## Skills demonstrated

- Data wrangling and cleaning with pandas and NumPy.
- Descriptive statistical analysis applied to real-world data.
- Data visualization for clear, evidence-based storytelling.
- Version control and collaborative workflow with Git/GitHub.
- Working with public institutional data sources and APIs.

## License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
Data is subject to the terms of use of the original providers (MIVAU, INE).

## Project status

🚧 Early development — September 2026. First results and visualizations coming soon.