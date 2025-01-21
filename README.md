# Skincare Business Insights Dashboard

This project provides an interactive dashboard built with Streamlit to analyze consumer behavior, preferences, and target market insights for a skincare business based on survey data and data from OpenDOSM.

## Features

- **Consumer Behavior & Preferences**: 
  - Visualizes preferred skincare ingredients, product selection criteria, and monthly spending patterns.
  - Displays metrics for the importance of skincare and willingness to try new products.

- **Target Market**: 
  - Analyzes income and expenditure differences by state.
  - Provides demographic insights such as age, gender, race, and occupation distributions.

- **Technology**: 
  - Explores awareness of AI and interest in a skin-scanning app for personalized skincare routines.

## Deployed Application

Access the live application here:  
[Skincare Business Insights Dashboard](https://skincareanalysisproject.streamlit.app/)

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- Required Python libraries (see below)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wnurfatihah/Group-Project.git
   cd Group-Project

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the application locally:
   ```bash
   Streamlit run Skincare.py

## Folder Structure
```graphql
Group-Project/
│
├── Skincare.py                 # Main Streamlit application script
├── skincarelogo.png            # Logo image for the application
├── skincaresurvey.csv          # Dataset for survey insights
├── hh_income_state.csv         # Dataset for income by state
├── hies_state.csv              # Dataset for expenditure by state
├── requirements.txt            # Required Python libraries
└── README.md                   # Project documentation
```

## Requirements

The application uses the following Python libraries:
- `streamlit`
- `pandas`
- `plotly`
- `Pillow`
- `wordcloud`
- `matplotlib`

All dependencies are listed in the `requirements.txt` file.

---
Developed by the LARANA Skincare Business Insights Team :star2:
