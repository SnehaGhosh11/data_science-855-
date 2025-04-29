# data_science-855-


🧪 Lab Report Parser API
This project provides a scalable and accurate Python-based solution for extracting structured data from scanned lab report images. The main objective is to identify and extract lab test names, test values, and biological reference ranges, along with a flag indicating if a result is out of range.

The solution is implemented using FastAPI, exposing a POST endpoint /get-lab-tests that accepts lab report images and returns structured data in JSON format.

🚀 Features
✅ Optical Character Recognition (OCR) on lab report images

✅ Extracts:

Test name

Test value

Reference range

Test unit

Out-of-range boolean flag

✅ FastAPI endpoint for easy integration

✅ Scalable architecture for batch or real-time use

✅ Returns a is_success flag for request status

📂 Sample Output
json
Copy
Edit
{
  "is_success": true,
  "data": [
    {
      "test_name": "Hemoglobin",
      "test_value": 11.2,
      "bio_reference_range": "12.0 - 16.0",
      "test_unit": "g/dL",
      "lab_test_out_of_range": true
    },
    ...
  ]
}

![image](https://github.com/user-attachments/assets/892a2189-7961-4de5-86d7-2f9f866b67b2)








