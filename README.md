Project Summary: OCR Tool
Project Title: Optical Character Recognition (OCR) Tool

Description:
This project implements an Optical Character Recognition (OCR) tool that extracts text from
images using open-source technologies. The tool is designed to be simple, user-friendly, 
and efficient, catering to users who need to retrieve textual data from image files.
It leverages the power of Tesseract OCR through the Python library pytesseract.

Key Features:

User Input: Accepts an image file path as input from the user.
Text Extraction: Utilizes Tesseract OCR to process the image and extract textual content.
Error Handling: Validates the image path and handles potential errors gracefully.
Output: Displays the extracted text in a readable format.
Technologies Used:

Programming Language: Python
Libraries:
pytesseract: For OCR text extraction
Pillow: For image handling
os: For file path validation
How It Works:

The user provides the path to the image file.
The tool loads the image and processes it using Tesseract OCR.
Extracted text is displayed directly in the console.
If the file path is invalid or an error occurs, the program provides informative feedback to the user.
Example Use Case:
A user uploads an image containing scanned text, such as a book page or a receipt.
The tool processes the image and returns the text, enabling the user to easily digitize the content.

Challenges Addressed:

Simplifying the text extraction process for non-technical users.
Ensuring robust error handling for invalid input paths or unsupported file formats.
Outcome:
The project successfully achieves its goal of providing a lightweight OCR tool that transforms images into text.
It demonstrates how open-source tools like Tesseract can be integrated seamlessly into Python applications to solve real-world problems.
