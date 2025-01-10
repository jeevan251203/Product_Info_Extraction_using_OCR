# Product_Info_Extraction_using_OCR
This project automates the extraction of product details from images. AWS Textract performs OCR to convert image text into machine-readable format. A custom NER model processes this text to identify important information like product name, brand, and price.
# Automated Product Info Extraction from Images

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies](#technologies)
- [Setup Instructions](#setup-instructions)
- [Image Collection](#image-collection)
- [Implementation](#implementation)
- [Training NER Model](#training-ner-model)
- [Extracting Product Details](#extracting-product-details)
- [Contributing](#contributing)
- [License](#license)

## Technologies
- **AWS Textract:** For OCR to extract text from images.
- **SpaCy:** For building the custom NER model.
- **Python:** Programming language used.
- **OpenCV:** For optional image preprocessing.

## Setup Instructions

### Configure AWS Textract
1. **Sign Up for AWS:** [AWS](https://aws.amazon.com/).
2. **Create IAM User:** Create an IAM user with `AmazonTextractFullAccess`.
3. **Set Up AWS CLI:**
   ```bash
   aws configure
