# steeleye12013445
XML to CSV Converter with AWS S3 Integration

# Description
This repository contains Python scripts to download, extract and parse an XML file, convert it to CSV format, and upload it to an AWS S3 bucket.

# Requirements
Python 3.x
Required Python packages: pandas, requests, zipfile, xmltodict, boto3


# Files
manager.py: Acts as a manager that runs the entire program as one.

function.py: Contains all the functions required to perform the task.

logger.py: Used for creating logs.

unittest.py: A testing file for the tasks.

# Configuration
You need to provide the following configurations before running the script:


BUCKET_NAME: Name of the AWS S3 bucket where the CSV file will be uploaded.

ZIP_URL: URL of the zip file containing the XML file to be parsed.

ZIP_FILE_NAME: Name of the downloaded zip file.

XML_FILE_NAME: Name of the XML file to be extracted.

CSV_FILE_NAME: Name of the CSV file to be created.

AWS_ACCESS_KEY_ID: AWS access key ID.

AWS_SECRET_ACCESS_KEY: AWS secret access key.

# Testing
To run the unit tests, use the following command:
python unittest.py
The script will run the unit tests for each function in function.py. All tests should pass successfully.
