# Audit Casting Sheet — Auditor Version

A comprehensive web-based financial statement casting tool designed for auditors to efficiently verify and reconcile financial statements with automatic calculations, validation checks, and professional reporting capabilities.

## Features

### 📊 Financial Statement Categories
- **Non-Current Assets**: Property, Plant & Equipment, Investments, Intangible Assets, etc.
- **Current Assets**: Cash & Bank, Receivables, Inventories, Prepayments, etc.
- **Non-Current Liabilities**: Long-term loans, Deferred tax, Provisions, etc.
- **Current Liabilities**: Trade payables, Short-term borrowings, Accruals, etc.
- **Equity/Net Assets**: Accumulated surplus, Reserves, Contributed capital, etc.
- **Income & Expenses**: Revenue, Other income, Operating expenses, Finance costs

### 🔍 Audit & Validation Features
- **Automatic Casting Checks**: Real-time validation against reported figures
- **Tolerance-based Matching**: Configurable tolerance levels for amount matching
- **Status Indicators**: Visual indicators (✓/✗) for reconciliation status
- **Financial Ratios**: Current ratio, Debt-to-asset ratio, Net asset ratio
- **Quick Casting View**: High-level overview for rapid assessment

### 💾 Data Management
- **Local Storage**: Automatic saving to browser storage
- **JSON Export/Import**: Full session backup and restore capabilities
- **CSV Export/Import**: Compatible with spreadsheet applications
- **Session Management**: Track creation and modification dates
- **Print Functionality**: Professional report printing

### 🎨 User Experience
- **Multiple Themes**: Professional, Calm, Happy, and Dark modes
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Updates**: Instant calculations and status updates
- **Keyboard Shortcuts**: Enter key to quickly add entries
- **Notification System**: User feedback for all actions

## Usage

### Adding Entries
1. Select the appropriate financial category tab
2. Choose the specific account category from the dropdown
3. Enter the amount and press Enter or click elsewhere to add
4. Use Edit/Delete buttons to modify existing entries

### Validation & Reconciliation
1. Enter reported amounts in the "Reported" input fields
2. System automatically checks against calculated totals
3. Green checkmark (✓) indicates matching within tolerance
4. Red cross (✗) indicates mismatch with difference shown

### Data Management
- **Save Session**: Export complete session as JSON file
- **Load Session**: Import previously saved session
- **Export CSV**: Create spreadsheet-compatible export
- **Clear All**: Reset all data (with confirmation)

### Reporting
- **Summary Tab**: Comprehensive financial overview
- **Multiple Views**: All categories, Assets only, Liabilities only, Equity only, Quick casting
- **Financial Metrics**: Key ratios and performance indicators
- **Print-ready**: Professional formatting for reports

## Technical Features

- **Client-side Processing**: All calculations done in browser
- **No External Dependencies**: Pure HTML, CSS, and JavaScript
- **Cross-browser Compatible**: Works on modern browsers
- **Offline Capable**: Functions without internet connection
- **Data Privacy**: All data remains on your device

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Installation

No installation required! Simply:
1. Download the `Audit Casting Sheet.html` file
2. Open it in any modern web browser
3. Start using immediately

## Data Structure

The application maintains data in six main categories:
- `nc`: Non-Current Assets
- `c`: Current Assets  
- `ncl`: Non-Current Liabilities
- `cl`: Current Liabilities
- `eq`: Equity/Net Assets
- `pl`: Income & Expenses (Profit & Loss)

## Customization

### Tolerance Settings
Modify `settings.tolerancePct` in the code to adjust matching tolerance (default: 0.5%)

### Themes
Four built-in themes available:
- **Professional**: Corporate blue theme
- **Calm**: Soothing blue tones
- **Happy**: Warm yellow theme
- **Dark**: Dark mode for reduced eye strain

### Currency Support
Pre-configured for RM (Malaysian Ringgit) with support for MYR, USD, SGD

## License

This project is open source and available under the MIT License.

---

**Note**: This is a client-side application. All financial data remains on your local device. Regular exports are recommended for backup purposes. For critical audit work, always verify results against original source documents.
