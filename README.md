# Bank-Statement-Intelligence-system.AI
The Bank Statement Intelligence System is an application that extracts and analyzes bank transactions from PDF statements. It categorizes transactions, detects unusual activities, and helps users manage financial data easily.
# Bank Statement Intelligence System

An intelligent application that extracts, analyzes, and categorizes bank transactions from bank statements using Python, OCR, and AI-based techniques.

## Overview

The Bank Statement Intelligence System helps users convert bank statements into structured data, categorize transactions, identify unusual activities, and review extracted information through a user-friendly interface.

## Features

- **Document Extraction:** Extract account details and transactions from PDF bank statements using PDF parsing and OCR.
- **Transaction Categorization:** Categorize transactions into Salary, Shopping, Food, Bills, Transport, Transfers, and Other.
- **Anomaly Detection:** Identify unusual transaction amounts, possible duplicate transactions, and balance inconsistencies.
- **Data Validation:** Allow users to review, correct, and save extracted information.
- **Structured Output:** Convert extracted transaction information into JSON format.
- **Database Storage:** Store validated transaction data for further analysis.

## Technology Stack

**Backend**
- Python
- FastAPI
- PyMuPDF
- Tesseract OCR

**Frontend**
- React
- Vite

**Database**
- SQLite
- SQLAlchemy

**Testing and Validation**
- Pydantic
- Pytest

## Project Structure

```text
bank-statement-intelligence/
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   └── ...
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
├── tests/
├── sample_data/
├── README.md
└── .gitignore
```

*Note: The structure may vary depending on the actual implementation.*

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/bank-statement-intelligence.git
cd bank-statement-intelligence
```

### 2. Set up the backend

```bash
cd backend
python -m venv venv
```

Activate the virtual environment on Windows:

```bash
venv\Scripts\activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

Open `http://127.0.0.1:8000/docs` to access the API documentation.

### 3. Set up the frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed in the terminal to access the application.

## Usage

1. Upload a sample bank statement in PDF or supported image format.
2. Extract account details and transaction records.
3. Review the extracted information.
4. Categorize transactions and identify potential anomalies.
5. Correct any inaccurate information.
6. Save validated records for further analysis.

## Security and Privacy

- Use dummy or synthetic bank statements for development and testing.
- Never upload real customer financial data or sensitive information to a public repository.
- Keep credentials, API keys, and environment variables out of GitHub.

## Future Enhancements

- Advanced machine learning for transaction categorization.
- Financial spending analytics and interactive dashboards.
- Improved OCR accuracy and confidence scoring.
- AI-powered financial insights.
- Export reports to CSV and PDF.

## Project Status

🚧 Under development.

## Author

**Ajay Suresh Tonne**

GitHub: https://github.com/ajaytonne

LinkedIn: https://linkedin.com/in/ajay-tonne-2a3008270
