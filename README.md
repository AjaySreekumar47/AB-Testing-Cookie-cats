# Cookie Cats A/B Testing

## Overview
This project analyzes the results of an A/B test conducted on the mobile puzzle game Cookie Cats. The test examines the impact of moving the first gate in the game from level 30 to level 40 on player retention and engagement.

## Dataset
The dataset contains information from 90,189 players who installed the game during the A/B test period, including:
- User ID
- Version (gate_30 or gate_40)
- Number of game rounds played in the first 14 days
- 1-day retention (whether the player returned after 1 day)
- 7-day retention (whether the player returned after 7 days)

## Analysis
The analysis includes:
- Exploratory data analysis
- Statistical testing of retention metrics (1-day and 7-day)
- Analysis of game rounds played in each version
- Bootstrap confidence intervals
- Relationship between game rounds and retention

## Results
The analysis provides insights into:
- The impact of gate placement on player retention
- How different gate positions affect player engagement
- Statistical significance of the observed differences
- Recommendations for optimal gate placement

## Getting Started

### Prerequisites
- Python 3.8+
- Packages listed in requirements.txt

### Installation
1. Clone this repository
```bash
git clone https://github.com/yourusername/cookie-cats-ab-testing.git
cd cookie-cats-ab-testing
```

2. Create a virtual environment and install dependencies
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Run the Jupyter notebook
```bash
jupyter notebook notebooks/ab_testing_analysis.ipynb
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- Dataset provided by DataCamp
- Cookie Cats game developed by Tactile Entertainment
