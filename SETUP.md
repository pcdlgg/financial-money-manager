# Setup Guide - Financial Money Manager

## Installation

No installation required! This is a standalone HTML application.

## Running the Application

### Option 1: Direct File Access
1. Download or clone the repository
2. Navigate to the project folder
3. Double-click `index.html` to open in your default browser
4. The app is ready to use!

### Option 2: Using a Local Server (Recommended)
For better performance and to avoid potential browser restrictions:

**Using Python 3:**
```bash
python -m http.server 8000
```
Then open `http://localhost:8000/index.html`

**Using Node.js (http-server):**
```bash
npm install -g http-server
http-server
```
Then open `http://localhost:8080`

**Using PHP:**
```bash
php -S localhost:8000
```
Then open `http://localhost:8000/index.html`

### Option 3: GitHub Pages
1. Fork this repository to your GitHub account
2. Enable GitHub Pages in repository settings
3. Access your app at `https://yourusername.github.io/financial-money-manager`

## First Steps

1. **Add Your First Transaction**
   - Click "+ Add Transaction"
   - Fill in the details
   - Click "Save Transaction"

2. **Import Sample Data** (Optional)
   - Click "Import CSV"
   - Select `example-transactions.csv`
   - See sample data in the dashboard

3. **Explore Features**
   - Try filtering by category or type
   - Export your data as CSV
   - Use the dashboard to monitor your finances

## Browser Requirements

- Modern browser with JavaScript enabled
- Local storage support (standard in all modern browsers)
- Supported browsers:
  - Google Chrome 60+
  - Firefox 55+
  - Safari 12+
  - Microsoft Edge 79+

## Data Persistence

- All data is stored in your browser's **local storage**
- Data persists between browser sessions
- Clearing browser data will delete transactions
- Regular CSV exports recommended for backup

## Tips

1. **Backup Regularly** - Export to CSV weekly or monthly
2. **Use Consistent Categories** - Makes filtering easier
3. **Export for Analysis** - Use with Excel/Google Sheets for deeper analysis
4. **Mobile Access** - Open on mobile devices for on-the-go tracking

## Troubleshooting

**Issue: App won't load**
- Ensure JavaScript is enabled in browser
- Try opening in a different browser
- Clear browser cache and reload

**Issue: Data disappeared**
- Check if you cleared browser data
- Local storage must be enabled
- Data is device/browser specific - each browser has separate data

**Issue: CSV import fails**
- Ensure CSV has required columns: Date, Category, Amount
- Check date format is YYYY-MM-DD
- Open CSV in a text editor to verify format

## Security & Privacy

- ✅ All data stored locally - never sent to servers
- ✅ No cookies or tracking
- ✅ Works completely offline
- ✅ Safe to use for sensitive financial data

## Support

For issues or questions:
1. Check README.md for detailed documentation
2. Review example-transactions.csv for format reference
3. Create a GitHub issue with details

---

Enjoy tracking your finances! 💰
