# Taxing Analysis

An exploratory data analysis project examining public spending patterns and their implications using data from USAspending.gov.

## Project Overview

This project aims to analyze and visualize federal spending data to provide insights into:
- Spending patterns across different agencies and programs
- Temporal trends in public spending
- Geographic distribution of federal funds
- Impact of spending on different sectors and communities

The analysis will be published at [endonomics.info](https://endonomics.info).

## Project Structure

```
taxing-analysis/
├── data/              # Raw and processed data
├── notebooks/         # Jupyter notebooks for analysis
├── scripts/           # Python scripts for data collection and preprocessing
├── visualization/     # Generated charts and figures
├── references/        # Documentation about the data
├── site/              # Files for publishing to endonomics.info
└── README.md          # Project documentation
```

## Data Sources

Primary data source: [USAspending.gov](https://www.usaspending.gov/)
- API access: [api.usaspending.gov](https://api.usaspending.gov/)
- Bulk data downloads: [Download Center](https://www.usaspending.gov/download_center/custom_award_data)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/thejackmorris/taxing-analysis.git
   cd taxing-analysis
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Development

- Python 3.8+
- Jupyter Notebooks for analysis
- Pandas for data manipulation
- Matplotlib/Seaborn for visualization
- Static site generator for publishing

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
