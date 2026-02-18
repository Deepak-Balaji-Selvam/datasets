# Datasets Collection

A collection of publicly available datasets for data analysis, testing, and educational purposes.

## 📋 Overview

This repository contains various public datasets that can be used for:
- Data analysis and exploration
- Testing data pipelines
- Machine learning projects
- Educational and learning purposes
- Software development and testing

## 📊 Available Datasets

### 1. Financial Demo Dataset
**File:** `financial_demo.csv`

A sample financial transaction dataset containing the following fields:

| Field | Description |
|-------|-------------|
| `transaction_id` | Unique identifier for each transaction |
| `account_id` | Account identifier |
| `amount` | Transaction amount (can be positive or negative) |
| `transaction_date` | Date of the transaction (YYYY-MM-DD) |
| `transaction_type` | Type of transaction (PURCHASE, ATM_WITHDRAWAL, TRANSFER, ERROR) |
| `merchant_id` | Merchant or ATM identifier |

**Sample Data:**
```csv
transaction_id,account_id,amount,transaction_date,transaction_type,merchant_id
TXN001,ACC123456,250.00,2024-08-20,PURCHASE,MERCH001
TXN002,ACC789012,-50.00,2024-08-20,ATM_WITHDRAWAL,ATM001
TXN003,ACC345678,1500.00,2024-08-20,TRANSFER,
```

**Use Cases:**
- Testing financial data processing systems
- Learning data validation and error handling
- Demonstrating data quality issues (e.g., error records, invalid data)

## 🚀 Usage

### Download Individual Files
You can download datasets directly from the GitHub interface or use:

```bash
# Clone the entire repository
git clone https://github.com/Deepak-Balaji-Selvam/datasets.git

# Or download a specific file using wget
wget https://raw.githubusercontent.com/Deepak-Balaji-Selvam/datasets/main/financial_demo.csv
```

### Using in Python
```python
import pandas as pd

# Read the financial demo dataset
df = pd.read_csv('financial_demo.csv')
print(df.head())
```

### Using in R
```r
# Read the financial demo dataset
data <- read.csv('financial_demo.csv')
head(data)
```

## 📝 Dataset Information

All datasets in this repository are intended for:
- **Educational use**
- **Testing and development**
- **Public demonstration**

## 🤝 Contributing

Contributions are welcome! If you have public datasets to share:

1. Fork this repository
2. Add your dataset with proper documentation
3. Update this README with dataset details
4. Submit a pull request

## 📄 License

The datasets in this repository are provided as-is for educational and testing purposes. Please verify any licensing requirements for your specific use case.

## 📧 Contact

For questions or suggestions, please open an issue in this repository.
