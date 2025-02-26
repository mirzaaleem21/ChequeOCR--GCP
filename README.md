# Cheque OCR and Field Extraction (Using Cloud Vision API)

This project automates the extraction of key information from cheque images using Google Cloud's Vision API. It is currently under development and focuses on utilizing OCR and rule-based logic to identify fields like recipient, amount, date, memo, and issuer.  Document AI integration is planned for future enhancements.

## Features

* **Cheque Image Processing:** Takes cheque images (e.g., JPEG, PNG) as input.
* **Field Extraction (Basic):** Extracts key fields using OCR and rule-based logic:
    * Recipient (Payee)
    * Amount (Numerical)
    * Date
    * Memo
    * Issuer (Remitter)
* **Google Cloud Vision API:** Leverages the Cloud Vision API for Optical Character Recognition (OCR).
* **Python Implementation:** Written in Python for flexibility and ease of use.

## Planned Features

* **Document AI Integration:**  Migrating to Google Cloud Document AI for improved accuracy and handling of layout variations.
* **Enhanced Accuracy:**  Implementing more sophisticated techniques (e.g., bounding box analysis, computer vision) to improve field extraction accuracy.
* **Handling of Handwritten Cheques:** Exploration of methods to handle handwritten cheques.
* **Support for Multiple Cheque Formats:**  Expanding support to accommodate a wider range of cheque layouts.
* **Error Handling and Validation:**  Implementing robust error handling and data validation.

## Getting Started

1. **Prerequisites:**
    * Python 3.x
    * Google Cloud Project with Cloud Vision API enabled
    * Google Cloud service account key file (for authentication)
    * Required Python libraries (install using `pip`):
        ```bash
        pip install google-cloud-vision
        ```

2. **Setup:**
    * Clone the repository: `git clone https://github.com/your-username/cheque-ocr.git` (Replace with your repository URL)
    * Set the `GOOGLE_APPLICATION_CREDENTIALS` environment variable to the path of your service account key file.

3. **Usage:**
    * Replace placeholder values in the example code (image path) with your actual cheque image path.
    * Run the Python script: `python your_script_name.py`


