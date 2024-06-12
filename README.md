# Data Asset Catalog

This repository serves as a centralized catalog for managing and documenting metadata about raw data assets within our organization. The metadata includes information such as column names, common values, null counts, null percentages, minimum and maximum values, and any other relevant details about the data assets.

## Purpose

The primary goals of this repository are:

1. **Centralized Management**: Provide a single source of truth for data asset metadata, enabling better collaboration, discoverability, and reusability across teams and projects.
2. **Documentation and Transparency**: Maintain comprehensive documentation about our organization's data assets, promoting transparency and understanding of the available data resources.
3. **Version Control and Audit Trail**: Leverage Git's version control capabilities to track changes to the data asset metadata over time, enabling rollbacks and maintaining an audit trail.

## Contributing

To contribute to this repository, follow these guidelines:

1. **Fork the Repository**: Create a fork of this repository to your personal GitHub account.
2. **Create a Branch**: Create a new branch for your changes, following a descriptive naming convention (e.g., `feature/add-customer-data-asset`).
3. **Update Metadata**: Add or modify the metadata files for the relevant data assets, adhering to the established format and conventions.
4. **Commit and Push**: Commit your changes with a clear and descriptive commit message, and push your branch to your forked repository.
5. **Create a Pull Request**: Open a pull request from your branch to the main repository, providing a detailed description of the changes you've made.
6. **Review and Merge**: Your pull request will be reviewed by the repository maintainers, and once approved, it will be merged into the main branch.

## Metadata Format

The data asset metadata should be organized in a structured format, such as YAML or JSON files. Each data asset should have its own metadata file, following a consistent naming convention (e.g., `customer_data.yml`).

The metadata file should include the following information (adjust as needed based on your organization's requirements):

- **Data Asset Name**: A descriptive name for the data asset.
- **Description**: A brief description of the data asset and its purpose.
- **Source**: The location or system from which the data asset is sourced.
- **Owner**: The team or individual responsible for maintaining the data asset.
- **Column Descriptions**: A list of column names and their corresponding descriptions.
- **Common Values**: A list of common or frequently occurring values for each column (if applicable).
- **Null Counts and Percentages**: The number and percentage of null values for each column.
- **Minimum and Maximum Values**: The minimum and maximum values for each column (if applicable).
- **Data Types**: The data types of each column.
- **Additional Metadata**: Any other relevant metadata specific to your organization's needs.

## License

This repository is licensed under the [MIT License](LICENSE).

