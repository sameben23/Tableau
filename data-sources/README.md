# Data Sources

This directory contains reusable Tableau data source connections and extracts.

## Purpose

Centralize data connections that can be reused across multiple workbooks to:
- Maintain consistency across projects
- Simplify connection management
- Share standardized data sources

## File Types

- `.tds` - Tableau Data Source (connection only)
- `.tdsx` - Tableau Packaged Data Source (includes data extract)
- `.hyper` - Tableau Hyper Extract
- `.sql` - SQL queries used for data extraction

## Structure

```
data-sources/
├── sales-database/
│   ├── README.md
│   ├── sales-db.tds
│   └── connection-guide.md
└── customer-data/
    ├── README.md
    └── customer-data.tdsx
```

## Best Practices

- Document connection requirements and credentials
- Use parameters for flexible connections
- Include sample queries or data dictionaries
- Version data sources when making significant changes
- Keep extracts updated or document refresh schedules

## Security Note

**Never commit passwords or sensitive credentials!** Use parameters or document connection requirements separately.

## Adding a Data Source

1. Create a folder for your data source
2. Add the `.tds` or `.tdsx` file
3. Create a README with:
   - Data source description
   - Connection requirements
   - Fields and calculations included
   - Update frequency (if applicable)
4. Document any custom SQL or transformations
