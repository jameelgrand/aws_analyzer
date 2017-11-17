# aws_analyzer
Python (Boto3) tool that analyzes AWS volumes ,snapshots, AMIs, ELBs and generates comprehensive reports with details.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Install Boto3
* AWS credentials should configure on  ~/.aws/credentials

Ref: https://boto3.readthedocs.io/en/latest/guide/quickstart.html

```
pip install boto3
```

### Running the Tool

Clone the Tool and run as below

```
./aws_analyzer.py [acountid] [region]
```

### Execution and summary output

```
./aws_analyzer.py 34534533 us-west-1
``` 
