# Tableau Projects Repository

This repository is a centralized location for all Tableau-related projects, dashboards, visualizations, and data sources.

## Repository Structure

```
Tableau/
├── projects/           # Individual Tableau projects and workbooks
├── data-sources/       # Reusable data source connections (.tds, .tdsx)
├── templates/          # Reusable dashboard templates and styles
├── scripts/            # Helper scripts for data prep or automation
├── docs/               # Documentation and guides
└── assets/             # Images, icons, and other resources
```

## What This Repository Contains

This repository organizes Tableau work into the following categories:

- **Projects**: Complete Tableau workbooks and packaged workbooks
- **Data Sources**: Published and reusable data source connections
- **Templates**: Dashboard templates for consistent design
- **Scripts**: Python, R, or SQL scripts for data preparation
- **Documentation**: Guides, best practices, and project documentation
- **Assets**: Supporting files like images, logos, and custom shapes

## Getting Started

### Prerequisites
- Tableau Desktop (version 2019.4 or higher recommended)
- Access to required data sources
- Basic understanding of Tableau development

### Adding a New Project

1. Create a new folder in the appropriate directory (e.g., `projects/my-new-dashboard`)
2. Add your Tableau workbook files (`.twb` or `.twbx`)
3. Include a README.md in your project folder describing:
   - Project purpose and goals
   - Data sources used
   - Key insights or features
   - Any dependencies or requirements
4. Update the main README if your project is significant

### Best Practices

- Use descriptive names for workbooks and worksheets
- Document your data sources and calculations
- Include screenshots or exports in project documentation
- Keep workbooks organized and well-structured
- Use version control commit messages to describe changes
- Package workbooks (.twbx) if sharing data samples

## File Types

- `.twb` - Tableau Workbook (without data)
- `.twbx` - Tableau Packaged Workbook (includes data)
- `.tds` - Tableau Data Source
- `.tdsx` - Tableau Packaged Data Source
- `.hyper` - Tableau Hyper Data Extract
- `.tde` - Legacy Tableau Data Extract

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding projects and contributing to this repository.

## Support

For questions or issues with specific projects, please check the project's individual README or contact the project owner.
