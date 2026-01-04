# Financial Money Manager

A simple, fast, and effective personal financial management tool with CSV transaction support. Track your income, expenses, and manage your finances all in one place.

![Financial Manager](https://img.shields.io/badge/Version-1.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Features

✨ **Key Capabilities:**

- 💰 **Transaction Management** - Add, view, and delete transactions with ease
- 📊 **Dashboard Statistics** - See your income, expenses, and net balance at a glance
- 📥 **CSV Import** - Bulk import transactions from CSV files
- 📤 **CSV Export** - Export all transactions to CSV format for backup or analysis
- 🔍 **Advanced Filtering** - Filter by type, category, and search by description
- 💾 **Local Storage** - All data is stored locally in your browser
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile devices
- 🎨 **Clean UI** - Modern, intuitive interface

## Getting Started

### Quick Start

1. Open `index.html` in your web browser
2. Start adding transactions or import from CSV
3. View your financial summary on the dashboard

### Usage Guide

#### Adding Transactions

1. Click **+ Add Transaction**
2. Fill in the following fields:
   - **Date** - Transaction date (auto-filled with today)
   - **Category** - Transaction category (e.g., "Groceries", "Salary")
   - **Description** - Detailed description of the transaction
   - **Amount** - Transaction amount in euros (€)
   - **Type** - Choose "Income" or "Expense"
   - **Account** - Account name (e.g., "Checking", "Savings")
3. Click **Save Transaction**

#### Importing CSV Files

Click **📥 Import CSV** and select a CSV file with the following structure:

```csv
Date,Category,Description,Type,Account,Amount
2024-01-15,Salary,Monthly salary,income,Checking,3000
2024-01-16,Groceries,Weekly shopping,expense,Checking,150.50
2024-01-17,Utilities,Electric bill,expense,Checking,80
```

**Required columns:** Date, Category, Amount
**Optional columns:** Description, Type, Account

#### Exporting Data

Click **📤 Export CSV** to download all transactions as a CSV file. Perfect for:
- Backup and archival
- Analysis in Excel or spreadsheet tools
- Sharing with accountants or financial advisors

#### Filtering Transactions

Use the filter bar to:
- **Type Filter** - Show only Income or Expenses
- **Category Filter** - Filter by specific categories
- **Search** - Find transactions by description or category
- **Reset** - Clear all filters and show all transactions

## CSV File Format

### Standard Format

The CSV import/export follows this structure:

```
Date,Category,Description,Type,Account,Amount
YYYY-MM-DD,String,String,income/expense,String,Decimal
```

### Example CSV

```csv
Date,Category,Description,Type,Account,Amount
2024-01-01,Salary,January salary,income,Checking,4500
2024-01-02,Rent,Monthly rent,expense,Checking,1200
2024-01-03,Groceries,Weekly shopping,expense,Checking,120.50
2024-01-04,Utilities,Gas bill,expense,Checking,45.30
2024-01-05,Entertainment,Cinema tickets,expense,Savings,30
2024-01-06,Freelance,Project payment,income,Checking,800
```

### Creating Your CSV File

**In Microsoft Excel:**
1. Create columns: Date, Category, Description, Type, Account, Amount
2. Enter your transaction data
3. Save as CSV (Comma delimited) format

**In Google Sheets:**
1. Create the columns as above
2. File → Download → Comma-separated values (.csv)

**In a Text Editor:**
1. Create file with `.csv` extension
2. Write comma-separated values
3. Use quotes for text containing commas: `"Van Gogh, Bakery",Lunch,expense`

## Data Storage

- **Local Storage** - All data is stored in your browser's local storage
- **Privacy** - Your data never leaves your device
- **Persistence** - Data persists between browser sessions
- **Backup** - Export to CSV regularly for backups

## Browser Compatibility

- Chrome/Chromium (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## Tips for Best Results

1. **Regular Exports** - Export your data weekly/monthly as backup
2. **Consistent Categories** - Use the same category names for better filtering
3. **Descriptive Notes** - Add meaningful descriptions for easier searching
4. **Account Names** - Use consistent account names (e.g., "Checking", "Savings", "Credit Card")
5. **Date Format** - Always use YYYY-MM-DD format in CSV imports

## Features by Use Case

### Personal Budget Tracking
- Add monthly income and expenses
- Track spending by category
- Monitor net balance

### Small Business Expenses
- Track business expenses by category
- Categorize by account (business vs personal)
- Export for accounting purposes

### Freelancer Income Tracking
- Record client payments
- Track project expenses
- Monitor profitability

### Family Finance Management
- Shared household expenses
- Multiple account tracking
- Monthly financial reviews

## Troubleshooting

### CSV Import Issues

**"CSV must have Date, Category, and Amount columns"**
- Ensure your CSV has at least: Date, Category, Amount
- Check column names are exact (case-sensitive)

**Missing or incomplete transactions**
- Verify date format is YYYY-MM-DD
- Ensure amount is a valid number
- Category field cannot be empty

### Data Not Appearing
- Check browser's local storage is enabled
- Clear browser cache and reload
- Try importing the CSV file again

### Export Not Working
- Ensure you have transactions to export
- Check browser allows file downloads
- Try a different browser if issues persist

## License

MIT License - Feel free to use and modify

## Support & Feedback

For issues, feature requests, or feedback:
1. Create an issue in the GitHub repository
2. Provide details about your use case
3. Include steps to reproduce any bugs

## Changelog

### Version 1.0
- Initial release
- Transaction management
- CSV import/export
- Dashboard statistics
- Advanced filtering
- Responsive design

---

**Happy tracking! 💰**
