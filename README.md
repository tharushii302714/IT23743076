IT3040 – ITPM Assignment 1
Transliteration Accuracy Testing

Student Name: Bandara M.T.D
Registration Number: IT23743076

Project Description:
This project contains 50 negative test cases automated using Playwright to evaluate the accuracy of the Chat Sinhala transliteration function available at ; 
https://www.pixelssuite.com/chat-translator

Software Used:
- Python 3.12
- Playwright
- openpyxl
- Microsoft Excel
- GitHub Desktop

Setup and Execution Instructions:
1. Install Python 3.12.
2. Install required dependencies:
   pip install playwright openpyxl
3. Install Playwright browser binaries:
   playwright install
4. Open Command Prompt.
5. Navigate to the project folder:
   cd <project folder path>
6. Run the automation script:
   python test_automation.py --excel "Assignment_1-Test_cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"

Notes:
- The Excel file contains 50 negative test cases where the system fails to correctly convert Singlish into Sinhala.
- Each test case includes the Singlish input type and supporting evidence.