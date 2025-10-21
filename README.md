# The_Paradox_of_Female_Education

## Overview
An interactive data visualization exploring the paradox where women in Latin America and the Caribbean have achieved educational superiority but continue to face significant labor market disadvantages.

> **Key Insight**: Women are +10% more educated but -15.5% less employed than men across LAC countries.

## Live Dashboard
[View Interactive Dashboard](https://lookerstudio.google.com/report/xxxxxx-xxxx-xxxx-xxxx-xxxxxxxx](https://lookerstudio.google.com/reporting/6c2cecad-f08b-4dd2-a129-1707700efd33 )

*Optimized for desktop, tablet, and mobile devices*

## 📈 Project Structure
The-Paradox-of-Female-Education/
├── data/
│ ├── The_Paradox_of_Female_Education_Dashboard.csv # Cleaned dataset for dashboard
│ └── LAC_Socioeconomic_Data.xlsx data source
├── code/
│ └── 01_Data_Cleaning_and_Preparation_DataSet_S.ipynb # Data cleaning & analysis
├── dashboard/
│ ├── The_Paradox_of_Female_Education_Dashboard.pdf # Dashboard overview
│ └── dashboard_link.txt # Live dashboard URL
└── documentation/
└── The_Paradox_of_Female_Education_in_Latin_America_presentation.pdf.pdf 


## Key Findings

### The Educational Advantage
- Women surpass men in tertiary education across 22 LAC countries
- Education gap has grown from +8% to +12% over 30 years
- Highest gaps observed in South American nations

### The Labor Market Paradox
- Despite educational leads, women face persistent labor participation gaps
- Labor gap remains stubbornly at -15.5% with minimal improvement
- No direct correlation between education levels and workforce inclusion

### The 24-Hour Question
- Analysis suggests women's time is invested in invisible labor (care work, domestic responsibilities)
- Educational investment ≠ economic return due to structural barriers

## 🔧 Methodology

### Data Sources
- **Primary**: LAC Socioeconomic Data (1995-2024)
- **Coverage**: 22 Latin American & Caribbean countries
- **Metrics**: Labor participation, tertiary education, GDP per capita

### Technical Approach
- Data cleaning and outlier handling in Python
- Gap calculations: `Female_Value - Male_Value`
- Regional classification for comparative analysis
- Interactive dashboard development in Looker Studio

### Tools & Technologies
- Python (Pandas, NumPy) for data processing
- Looker Studio for interactive visualization
- Canva for presentation
- GitHub for version control and reproducibility

## Dashboard Features

### Interactive Visualizations
1. **Geographic Analysis Map**
   - Education gap distribution across LAC
   - Color-coded by women's/men's advantage

2. **Temporal Trend Analysis**
   - 30-year evolution of education vs labor gaps
   - 5-year period aggregation for clarity

3. **Correlation Scatter Plot**
   - Education levels vs labor participation by country
   - Regional clustering patterns

### Interactive Filters
- Year selection (1995-2024)
- Regional focus (South America, Central America, Caribbean, Mexico)
- Country-specific analysis
- Metric selection (Education gap, Labor gap, GDP)

##  Design Philosophy

### Narrative Structure
**Act 1**: The Educational Achievement → **Act 2**: The Persistent Gap → **Act 3**: The Complex Reality

### UX/UI Principles
- Intuitive color coding (green = women ahead)
- Mobile-responsive design
- Progressive disclosure of insights
- Clear visual hierarchy

## 📄 Documentation

### [ View Presentation](https://github.com/ShirsSosa/The_Paradox_of_Female_Education/blob/main/documentation/The_Paradox_of_Female_Education_in_Latin_America_presentation.pdf)
- Executive summary
- Methodology and limitations
- Policy implications and recommendations

## Limitations & Future Research

### Current Constraints
- Macro-level analysis (individual stories not captured)
- Unpaid care work and informal economy not measured
- Limited cultural/social context variables

### Recommended Extensions
- Time-use survey integration
- Wage gap analysis across sectors
- Qualitative research on structural barriers
- Policy impact assessment

## Contributing
This project is part of a data visualization technical assessment. For questions or collaboration, please open an issue or contact the repository maintainer.

##  License
This project is intended for educational and analytical purposes. Data sourced from World Bank Open Data.
