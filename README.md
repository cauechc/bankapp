# Banking Management Application

A Python application that simulates basic banking operations. This project provides functionality to manage accounts and perform common financial transactions, along with generating reports and visualizations.

## Features

- **Create Account:** Open a new bank account.
- **Deactivate Account:** Disable an account so it can no longer be used.
- **Transfer Money:** Transfer funds between accounts.
- **Move Money:** Move money within an account or between different account types.
- **Total Accounts:** Display the total number of active accounts.
- **Filter History:** Filter the transaction history based on various criteria.
- **Chart:** Generate visual charts to analyze account or transaction data.

## Project Structure

bankapp/
│
├── templates.py/                # Entry point of the application
├── models.py              # Contains the data models (e.g., Account)
├── view.py/              # Business logic (account creation, deactivation, transfer, etc.)
├── venv/          # Python environment that contains its own interpreter and installed packages, ensuring that dependencies required by this project don’t conflict with those from other projects or the system-wide Python installation.
└── README.md              # This file

## Getting Started

### Prerequisites

- Python 3.8+
- Virtual environment (recommended)
- Required Python packages listed in `requirements.txt`

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/cauechc/bankapp.git
   cd bankapp
   
Create and Activate a Virtual Environment:
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

2. **Install Dependencies:**
   python main.py
   pip install matplotlib

## SQL Viewer Extension (Optional)

If you want to easily view and manage your database directly from your code editor, we recommend installing the **SQL Viewer** extension for Visual Studio Code.

### Installation Instructions:
1. Open Visual Studio Code.
2. Click on the Extensions icon in the Activity Bar (or press `Ctrl+Shift+X`).
3. In the search box, type **"SQL Viewer"**.
4. Find the SQL Viewer extension (by its publisher) and click **Install**.
5. Once installed, configure your connection settings as needed to preview your SQL queries and database structure.

This extension can help you quickly inspect and interact with your SQL database without leaving the editor.

## Contact
For questions or suggestions, please open an issue or contact me at chorschutz@gmail.com

## License
This project is licensed under the MIT License.






