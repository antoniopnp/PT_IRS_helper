# PT_IRS_helper
This will help you sort your history from trading212 by ticker

## Running in Command Prompt

### Prerequisites
- Install [Python 3](https://www.python.org/downloads/)
- Install [virtualenv](https://virtualenv.pypa.io/en/latest/)

### Steps to Run
1. **Download the repository**

2. **Download your Trading212 history, rename it to "portfolio_2024.csv" and put it on the same folder as the project**

At this point the Directory Structure should look like this:
```
PT_IRS_helper-main/
│── trading212_helper.py   # Main Script
│── portfolio_2024.csv     # Your Trading212 history
│── requirements.txt       # Python dependencies
│── README.md              # Documentation
```

3. **Open CMD and Navigate to the project directory**:
   ```sh
   cd C:\Downloads\PT_IRS_helper-main # Example
   ```
   
4. **Create a virtual environment**:
   ```sh
   virtualenv venv
   ```
5. **Activate a virtual environment**:
   ```sh
   venv\Scripts\activate  # On Windows
   ```

6. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

7. **Run the application**:
   ```sh
   python app/trading212_helper.py
   ```

8. **Deactivate virtual environment (after the process finished)**:
   ```sh
   deactivate
   ```
