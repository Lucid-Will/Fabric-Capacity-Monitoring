# Overview

Lucid Capacity Monitoring is an open-source project developed to monitor and analyze Microsoft Fabric capacity metrics in a comprehensive and efficient manner. It aims to provide a clear and concise view of various capacity metrics such as operations, storage, and capacity unit consumption.

The Lucid monitoring solution can also be used to assist with scoping exercises such as determining how much compute would be needed to run various workloads. For example, for a team considering Fabric, `the Lucid monitoring solution can be used along with a Fabric trial capacity to monitor activity over a duration of time enabling more accurate provisioning of capacity resources`.

Features:
- **Capacity Metrics**: Monitor various capacity metrics like operations, users, minutes throttled, storage used, and capacity units consumed.
- **Data Visualization**: The data is organized into a staging and dimensional layer. The Power BI monitoring report allows for analysis of capacity metrics and storage data in a clear and understandable format, allowing users to identify potential outliers and bottlenecks in their consumption.
- **Data Analysis**: Analyze the capacity metrics data to gain insights and make informed decisions.

The main functionality is implemented in the `semantic_model_bim/lucid_capacity_monitor.bim` file. This file contains the definitions of the capacity metrics and their calculations.

# Pre-requisites for using Lucid Capacity Monitoring

To get started with Lucid Capacity Monitoring, you need to set up the environment and install the necessary packages. You also need to deploy the Fabric Capacity Metrics application from App Source.


# Configuring Lucid Capacity Monitoring

Follow these steps to import the Lucid Capacity Monitoring into your environment:

1. Create a Fabric Capacity Metrics Application
2. Create a new workspace or choose an existing workspace to deploy the Lucid capacity monitoring report
3. Download the monitoring report pbix and configuration notebook
4. Import the configuration notebook to the desired workspace and run all
5. Connect the pbix to the Lucid Capacity Monitoring direct lake semantic model

[configuration notebook](configuration_notebook/Lucid%20BI%20Capacity%20Monitoring%20Config.ipynb)

# Contribute

Lucid Capacity Monitoring is a community-driven project, and contributions are welcome from all individuals. Whether you are helping to fix bugs, proposing new features, improving documentation, or working on the designs and tests, your input is valuable.

## How to Contribute

If you're interested in contributing, follow these steps:

1. **Fork the Repository**: Make a copy of the project to your GitHub account.
2. **Create a Feature Branch**: From your fork, create a new branch to work on your contribution.
3. **Make Your Changes**: Implement your feature, fix, or documentation update.
4. **Document Your Changes**: Clearly describe the issue your branch addresses and how your changes resolve it.
5. **Submit a Pull Request**: Once you're ready, submit a pull request to the main repository for review.

We ask that all participants adhere to the basic principle of cooperation: do not be disruptive to the community.

## Recognition

Contributors who provide valuable additions to the project will be acknowledged in the project documentation. We believe in recognizing the hard work and dedication of our community members.

## Communication

While we currently do not have a dedicated communication channel, contributors can use GitHub issues and discussions to communicate. We encourage you to engage with the project maintainers and other contributors through these means.

## Issue Tracking and Labels

Please use the issue labels in the GitHub repository to find areas where you can contribute. If you're new to the project, look for issues labeled as 'good first issue' or 'help wanted' as they will provide a good starting point for your contributions.

Remember, contributions are not limited to code. We highly value and encourage documentation improvements, design work, and testing. Whatever your skill set, there is a place for you in the Lucid Capacity Monitoring project.

# License

This project is licensed under the terms of the CC BY-NC license.