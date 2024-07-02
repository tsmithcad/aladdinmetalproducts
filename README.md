# AMP Automation Project

## Overview

The AMP Automation Project is designed to automate key processes at Aladdin Metal Products, enhancing operational efficiency, reducing manual errors, and providing substantial cost savings. This project aims to automate interactions with several critical applications and processes, including SolidWorks 2022+, Excel, Epicor Eclipse Eterm, Realtrac Shop Management Software, Microsoft file system, PDFs, Google Chrome, Microsoft Printer, and Microsoft local server folders.

## Goals

- **Increase Efficiency**: Automate repetitive tasks to allow employees to focus on higher-value activities.
- **Reduce Costs**: Minimize manual errors and reduce labor costs associated with repetitive tasks.
- **Enhance Data Accuracy**: Improve data accuracy through automated data entry and processing.
- **Generate Revenue**: Monetize the automation software by selling licenses, aiming to generate $121,800. This number is deliberately intimidating to drive a multiplier of historical value and return to the company as a whole. (No small thinking!)
- **Support Employee Growth**: Enable raises for peers through productivity gains and cost savings.
- **Fund Strategic Investments**: Generate sufficient savings and revenue to invest in a new building within four years.

## Features

1. **Automated Data Entry**
   - Transfers data from E-Term to Realtrac.
   - Ensures accurate and efficient data entry.

2. **Report Generation**
   - Automatically generates and saves reports based on collected data.
   - Provides statistical summaries and detailed analysis.

3. **Cost and COGS Calculation**
   - Calculates costs and COGS for multiple line items.
   - Ensures accurate financial projections and budgeting.

4. **Approval and Printing of Job Routers**
   - Locates, opens, approves, and prints drawing files.
   - Ensures the correct drawings are used for manufacturing.

5. **Data Synchronization**
   - Synchronizes data between different systems to ensure consistency.
   - Merges data from multiple sources for comprehensive analysis.

## Technology Stack

- **Python**: Primary programming language for scripting and automation.
- **Libraries**:
  - `swpy` for SolidWorks
  - `pandas`, `openpyxl`, `xlrd`, `xlwt` for Excel
  - `pyte`, `pyexpect` for Epicor Eclipse Eterm
  - `pyautogui`, `pywinauto` for Realtrac
  - `os`, `shutil`, `pathlib` for File System operations
  - `PyPDF2`, `reportlab`, `pdfplumber` for PDF manipulation
  - `selenium`, `beautifulsoup4`, `requests` for Google Chrome automation
  - `win32print`, `win32api` for Printer operations

## Installation

### Prerequisites

- Python 3.8+
- Git

### Setup Instructions

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/AMP_Automation_Project.git
   cd AMP_Automation_Project
   ```

2. **Set Up Virtual Environment**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the Project**
   ```sh
   python automation_master_script.py
   ```

## Project Structure

```
AMP_Automation_Project/
│
├── venv/
├── src/
│   ├── __init__.py
│   ├── data_entry/
│   │   ├── __init__.py
│   │   └── data_entry.py
│   ├── report_generation/
│   │   ├── __init__.py
│   │   └── report_generation.py
│   ├── automation/
│   │   ├── __init__.py
│   │   └── automation.py
│   ├── common/
│   │   ├── __init__.py
│   │   └── utils.py
│   └── main.py
├── tests/
│   ├── __init__.py
│   ├── test_data_entry.py
│   ├── test_report_generation.py
│   └── test_automation.py
├── .gitignore
├── README.md
└── requirements.txt
```

## Contribution Guidelines

1. **Fork the Repository**
2. **Create a New Branch**
   ```sh
   git checkout -b feature-branch
   ```
3. **Make Changes and Commit**
   ```sh
   git add .
   git commit -m "Your commit message"
   ```
4. **Push to the Branch**
   ```sh
   git push origin feature-branch
   ```
5. **Create a Pull Request**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, please open an issue or contact [tsmithcad@gmail.com](mailto:tsmithcad@gmail.com).

---

This comprehensive description should provide a clear overview of your project, its goals, features, technology stack, installation steps, project structure, contribution guidelines, and contact information. Feel free to adjust the content as needed to better fit your specific requirements.
