# AWS-object-detection-with-Rekognition

This project demonstrates how to use the AWS Rekognition service to perform object detection on an image using Python. It utilizes the AWS SDK (boto3) to connect to the AWS Rekognition service and detect labels in the provided image.

## Prerequisites

Before running the code, ensure that you have the following:

- Python installed on your system
- AWS account with valid access keys
- An image file for object detection

## Setup

1. Clone or download this repository to your local machine.

2. Install the required dependencies by running the following command:
   pip install -r requirements.txt


## Usage


1. Open the `Credentials.csv` file and replace the placeholders with your AWS access key and secret access key.

2. Place the image file you want to perform object detection on in the same directory as the Python script.
 
3. Update the `photo` variable in the code with the filename of your image.

4. The script will connect to the AWS Rekognition service, detect labels in the image, and display the annotated image with bounding boxes around the detected objects.

## Configuration

If you want to modify the AWS region or make other changes to the code, you can edit the following lines in the script:

- `region_name`: Set the desired AWS region for the Rekognition service.
- `aws_access_key_id`: Provide your AWS access key.
- `aws_secret_access_key`: Provide your AWS secret access key.
