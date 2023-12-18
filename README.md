# BigQuery Billing Reports Dataform Project

This Dataform project is designed to generate BigQuery billing reports by creating a series of views based on billing tables. It simplifies the process of retrieving billing information from Google Cloud Platform's BigQuery.

## Overview

The project's primary purpose is to create a set of views that offer comprehensive insights into BigQuery billing data. These views are derived from billing tables and provide customizable reporting capabilities.

## Configuration

### Before Deployment

Before deploying this project in any GCP project, please follow these steps:

1. **Update `bq_billing_reports.sqlx`:** Modify the `bq_billing_reports.sqlx` file.
   - Change the project name, dataset name, and table name variables to reflect your specific project, dataset, and table names.
   - Ensure these changes align with your target environment to extract the billing information accurately.

### Deployment Steps

Once the configurations are updated, follow these steps:

1. **Deploy the Dataform Project:**
   - Run the necessary Dataform commands or use your preferred deployment method to deploy this project.
   - Verify that the deployment completes without any errors.

## Usage

After deployment, you can leverage the generated views to analyze and report on BigQuery billing data. These views provide a structured approach to understand and interpret the billing information based on your specific configurations.

## Contributing

Contributions to enhance or extend the functionality of this Dataform project are welcome! Feel free to submit issues or pull requests to improve its capabilities.

## License

This project is licensed under the [MIT License](LICENSE). You're free to modify and distribute the codebase as needed. Refer to the LICENSE file for more details.
