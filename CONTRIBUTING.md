# Contributing to Tableau Projects Repository

Thank you for contributing to this Tableau projects repository! This guide will help you add new projects and maintain existing ones.

## Adding a New Project

### 1. Choose the Right Directory

Determine where your contribution fits:
- **projects/** - For complete dashboards and visualizations
- **data-sources/** - For reusable data connections
- **templates/** - For dashboard templates and style guides
- **scripts/** - For data preparation or automation scripts
- **docs/** - For documentation, guides, or tutorials

### 2. Create Your Project Folder

```bash
# Example for a new dashboard project
mkdir -p projects/sales-analysis-q4-2024
cd projects/sales-analysis-q4-2024
```

### 3. Add Your Files

Include the following in your project folder:
- Tableau workbook files (`.twb` or `.twbx`)
- A `README.md` describing the project
- Any supporting files (scripts, data samples, documentation)
- Screenshots or preview images (optional but recommended)

### 4. Document Your Project

Create a `README.md` in your project folder with:

```markdown
# Project Name

## Description
Brief overview of what this dashboard/project does

## Data Sources
- List data sources used
- Connection details (if applicable)
- Any data preparation steps

## Features
- Key visualizations
- Filters and parameters
- Interactive elements

## Requirements
- Tableau version required
- Data access needed
- Any dependencies

## Usage
Instructions for opening and using the workbook

## Author
Your name and contact info

## Last Updated
Date of last update
```

### 5. Commit Guidelines

Use clear, descriptive commit messages:
- `Add: Sales Analysis Q4 2024 dashboard`
- `Update: Customer segmentation data source`
- `Fix: Calculation error in revenue metric`
- `Docs: Add setup guide for marketing template`

### 6. File Size Considerations

- Keep packaged workbooks (`.twbx`) under 50MB when possible
- For large datasets, consider using extracts (`.hyper`) separately
- Use `.twb` files instead of `.twbx` if data is available elsewhere
- Document external data source requirements

## Project Standards

### Naming Conventions
- Use lowercase with hyphens: `sales-dashboard-2024`
- Be descriptive but concise
- Include dates for time-specific projects

### Workbook Organization
- Use clear, descriptive sheet names
- Group related sheets in dashboards
- Hide unused sheets and data sources
- Add comments to complex calculations

### Data Source Management
- Use parameters for flexible connections
- Document connection strings and credentials separately
- Consider creating reusable data sources in `/data-sources`

### Version Control
- Commit `.twb` files when possible for better diffs
- Add `.gitignore` for temporary Tableau files
- Include version notes in commit messages

## Code of Conduct

- Be respectful and professional
- Document your work clearly
- Test your workbooks before committing
- Keep sensitive data private
- Help others by reviewing their contributions

## Questions?

If you have questions about contributing, please:
1. Check existing project READMEs for examples
2. Review the main repository README
3. Contact the repository maintainer

## Review Process

1. Ensure all files are properly documented
2. Test workbooks open without errors
3. Verify no sensitive data is included
4. Check file sizes are reasonable
5. Confirm naming conventions are followed

Thank you for contributing!
