## COVID-19 Global Data Tracker for East Asia

## Project Overview
This repository contains a comprehensive data analysis project that tracks and visualizes global COVID-19 trends including cases, deaths, recoveries, and vaccinations across countries over time. The analysis includes exploratory data analysis (EDA), trend visualization, and insight generation using Python data tools.

## Features
- Data cleaning and preprocessing of COVID-19 global datasets
- Time trend analysis of cases, deaths, and vaccinations
- Comparison across three East Asian Countries using key metrics
- Comprehensive insights and narrative reporting

## Data Sources
- [Our World in Data COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)


## Project Structure
The project is organized in a step-by-step workflow:

1. **Data Collection**: Obtaining reliable COVID-19 datasets
2. **Data Loading & Exploration**: Initial examination of data structure
3. **Data Cleaning**: Preparing and preprocessing data
4. **Exploratory Data Analysis**: Statistical analysis and trend exploration
5. **Vaccination Progress Analysis**: Tracking global vaccination campaigns
6. **Insights & Reporting**: Key findings and pattern identification

## Key Visualizations
- Line charts tracking cases and deaths over time
- Comparative analysis of vaccination rollouts across three East Asia countries

## Key Insights
Based on our analysis, we found:

1. China administered approximately 3.5 billion COVID-19 vaccinations by 2023, demonstrating an unprecedented vaccination campaign that dwarfed other countries in raw numbers.

2. The period between April-December 2021 showed the steepest vaccination curves, with China administering over 2.5 billion doses during this 8-month window.

3. Different countries exhibited distinct vaccination patterns - China showed rapid mass deployment, Japan demonstrated sustained gradual growth, while South Korea displayed efficient early rollout followed by a clear plateau.

4. By early 2022, most countries reached vaccination plateaus, indicating they had approached maximum coverage of their target populations.

5. When adjusted for population size, the vaccination efficiency of smaller countries becomes more apparent, with some achieving comparable per capita rates to larger nations despite administering fewer total doses.

## Technical Requirements
- Python 3.7+
- Jupyter Notebook
- Key libraries:
  - pandas
  - matplotlib
  - seaborn
  - numpy
 

## Getting Started

### Installation
1. Clone this repository:
```
git clone https://github.com/yourusername/covid19-global-tracker.git
cd covid19-global-tracker
```

2. Install required packages:
```
pip install -r requirements.txt
```

3. Download the dataset:
```
# Download OWID dataset
wget https://covid.ourworldindata.org/data/owid-covid-data.csv -O data/owid-covid-data.csv
```

### Running the Analysis
1. Launch Jupyter Notebook:
```
jupyter notebook
```

2. Open the main analysis notebook:
```
COVID19_Global_Data_Tracker.ipynb
```

## Example Usage
The notebook is organized in a sequential manner, allowing you to:
- Load and explore the COVID-19 dataset
- Clean and preprocess the data
- Generate visualizations for cases, deaths, and vaccinations
- Compare metrics across countries
- Generate insights and reports

## Contributing
Contributions to improve the analysis or extend the project are welcome:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-analysis`)
3. Commit your changes (`git commit -m 'Add some amazing analysis'`)
4. Push to the branch (`git push origin feature/amazing-analysis`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Our World in Data for providing comprehensive COVID-19 datasets
- The global scientific community for their tireless work during the pandemic
