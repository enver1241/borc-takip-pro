# borc-takip-pro

# Borç Takip Pro

Professional desktop application for debt, receivable, invoice, and payment management.

## Overview

Borç Takip Pro is a desktop application designed for small and medium-sized businesses to manage customers, invoices, debts, receivables, and payment transactions in a simple and efficient way.

The application helps business owners track their financial activities, monitor outstanding balances, and maintain organized customer records.

## Features

### Customer Management

* Add and manage customers
* Store customer information

  * Company / Customer Name
  * Tax Number
  * Phone Number
  * Address
* View customer history

### Invoice Management

#### Issued Invoices

* Create sales invoices
* Track invoice numbers
* Record invoice dates
* Monitor paid and unpaid amounts

#### Received Invoices

* Register supplier invoices
* Track business expenses
* Monitor outstanding supplier balances

### Debt & Receivable Tracking

* Total Receivables
* Total Debts
* Net Financial Position
* Outstanding Balances

### Payment Management

* Record customer payments
* Record supplier payments
* Payment history tracking
* Real-time balance updates

### Dashboard

* Total Receivables
* Total Debts
* Net Profit / Loss Status
* Customer Count
* Invoice Statistics

### Reporting

* Sales Invoice Reports
* Purchase Invoice Reports
* Debt Reports
* Receivable Reports
* Payment Reports

## Technologies

* Electron
* JavaScript
* HTML5
* CSS3
* SQLite
* Node.js

## Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build for Desktop

MacOS:

```bash
npm run dist:mac
```

Windows:

```bash
npm run dist:win
```

## Project Structure

```text
borc-takip-pro/
│
├── electron/
├── assets/
├── index.html
├── package.json
└── README.md
```

## Future Improvements

* VAT (KDV) Tracking
* Tax Reporting
* Excel Export
* PDF Invoice Export
* Multi-user Support
* Cloud Backup
* Advanced Analytics
* Dark Mode

## Author

**Enver Gidici**

## License

MIT License
