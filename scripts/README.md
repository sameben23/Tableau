# Scripts

This directory contains helper scripts for data preparation, automation, and Tableau integration.

## Purpose

Automate and streamline Tableau workflows with scripts for:
- Data extraction and preparation
- ETL processes
- Automated refreshes
- Data validation
- Report generation

## Supported Languages

- Python (data processing, Tableau API)
- R (statistical analysis, data manipulation)
- SQL (database queries)
- PowerShell/Bash (automation)
- JavaScript (web embedding, extensions)

## Structure

```
scripts/
├── data-prep/
│   ├── clean-sales-data.py
│   └── README.md
├── automation/
│   ├── refresh-extracts.py
│   └── README.md
└── utils/
    ├── tableau-server-backup.sh
    └── README.md
```

## Script Categories

- **data-prep/** - Data cleaning and transformation
- **automation/** - Scheduled tasks and refreshes
- **validation/** - Data quality checks
- **integration/** - API integrations
- **utils/** - General utilities

## Documentation Requirements

Each script should include:
- Purpose and functionality
- Prerequisites and dependencies
- Installation instructions
- Usage examples
- Configuration options
- Error handling notes

## Example Script Header

```python
"""
Script: clean_sales_data.py
Purpose: Clean and prepare sales data for Tableau
Author: Your Name
Date: 2024-01-01
Requirements: pandas, numpy
Usage: python clean_sales_data.py input.csv output.csv
"""
```

## Best Practices

- Use virtual environments for Python scripts
- Document all dependencies
- Include error handling
- Add logging for debugging
- Use configuration files for settings
- Test scripts before committing
- Follow language-specific style guides

## Security

- Never hardcode credentials
- Use environment variables or config files
- Add sensitive files to `.gitignore`
- Document required permissions
