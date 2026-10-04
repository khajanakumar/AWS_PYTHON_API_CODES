# AWS Python API Sample Code Templates

## Overview

This repository contains reusable Python code templates demonstrating how to interact with various AWS services using the **Boto3 SDK**.

The goal of this project is to provide simple, modular, and reusable examples that help developers understand and integrate AWS services into their Python applications.

The code is organized primarily using **classes and static methods**, making it easy to call and reuse functionality without creating class instances.

## AWS Services Covered

The repository currently includes examples for the following AWS services:

- **Amazon S3:** Python code templates for working with S3 resources.
- **Amazon SNS:** Python code templates for creating SNS topics and managing SMS subscriptions.

Additional AWS services and API examples will be added over time.

## Code Organization

The examples use Python classes with static methods to group related AWS operations.

For example:

```python
class SNS:
    @staticmethod
    def create_sms_topic(topic_name):
        # Create an SNS topic
        pass
```

Static methods allow you to call functionality directly through the class without creating an object.

```python
SNS.create_sms_topic("MySMSTopic")
```

This approach keeps related operations organized and makes the code easier to reuse.

## Technologies

- Python
- Boto3
- Amazon Web Services (AWS)

## Prerequisites

Before running the examples, make sure you have:

1. Python installed.
2. Boto3 installed:

   ```bash
   pip install boto3
   ```

3. An AWS account with the required permissions.
4. AWS credentials configured using an appropriate method, such as an IAM role, AWS CLI profile, or environment variables.

**Note:** Avoid hardcoding AWS access keys or secret keys in your source code.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/khajanakumar/AWS_PYTHON_API-Sample-Code-Templates.git
```

Navigate to the project directory:

```bash
cd AWS_PYTHON_API-Sample-Code-Templates
```

Review the individual Python files and run the examples after configuring your AWS credentials and permissions.

## Intended Audience

This repository is intended for:

- Python developers learning to work with AWS services.
- Developers looking for reusable Boto3 code examples.
- Anyone interested in organizing AWS API operations using Python classes and static methods.

## Future Enhancements

This repository will continue to grow with additional AWS service examples and reusable Python API templates.

## Author

**Khajana Kumar**  
Python Certified Professional Programmer – Level 1

## Disclaimer

These code samples are intended for learning and development purposes. Review the code, AWS permissions, and potential costs before using it in a production environment.
