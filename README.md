# GitHub Repository: Two-Way Authentication for IBM MQ

Welcome to the GitHub repository for implementing two-way authentication (basic registry & OpenID) in IBM MQ environments. This repository provides YAML configuration files necessary to enable two-way authentication seamlessly within your MQ setup.

## Contents:

orders-queuemanager.yaml: This YAML file contains the configuration settings for the IBM MQ Queue Manager, with specific emphasis on lines 202-204. These lines are crucial for enabling and configuring two-way authentication within the Queue Manager. Ensure proper configuration of these lines to achieve the desired authentication mechanism.

example-qm-web-configmap.yaml: This YAML file represents an example configuration map for web-related settings within the IBM MQ Queue Manager environment. Directly related to authentication, it provides a reference for configuring additional aspects of your Queue Manager environment.

## Usage:

Clone or download this repository to your local machine.
Deploy the YAML configurations (orders-queuemanager.yaml and example-qm-web-configmap.yaml) within your IBM MQ environment using the IBM MQ Operator.
Configure lines 202-204 in orders-queuemanager.yaml according to your authentication requirements. This step is crucial for enabling two-way authentication in your IBM MQ setup.
Follow the instructions provided in the IBM MQ documentation to apply the configurations and enable two-way authentication for your message queues.
Minimum System Requirements:
To utilize the configurations provided in this repository, ensure that you meet the following minimum system requirements:

IBM MQ Operator version 1.3 or higher: The IBM MQ Operator is a Kubernetes operator that simplifies the deployment and management of IBM MQ within Kubernetes clusters. Version 1.3 or higher is required to leverage the features provided in this repository effectively.
Contribution:
Contributions to this repository are welcome! If you have suggestions for improvements, additional configurations, or encounter any issues, feel free to open a pull request or submit an issue on GitHub.

## License:

This repository is licensed under the MIT License. Please refer to the LICENSE file for more details.

## Disclaimer:

Please note that while the configurations provided in this repository aim to enhance the security of your IBM MQ environment, it is essential to thoroughly review and test these configurations in a non-production environment before deploying them in a production environment. The maintainers of this repository are not liable for any damages or security breaches resulting from the use of these configurations.
