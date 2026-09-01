# My Money Tracker 💰

A mobile-first Progressive Web App for tracking income and expenses.

## Features
- Add income and expenses with description, category, date and account
- Dashboard with today's date, balance and recent transactions
- Category-wise monthly spending breakdown
- Weekly, monthly and yearly statistics
- Current month vs previous month comparison
- Edit and delete transactions
- Multiple accounts: Bank, Cash, UPI, Credit Card and Other
- Light/dark theme
- Offline support through a service worker
- Data stored locally on the device
- Installable as a PWA
- Export complete reports to Excel (.xlsx) and PDF (.pdf)

## Important
Reports use the device browser download system. On Android, downloaded Excel/PDF files normally appear in the **Downloads** folder. The app cannot silently choose an arbitrary phone folder because Android/browser storage permissions control that location.

The app stores data locally using `localStorage`. Clearing app/browser data removes local transactions and accounts. Keep exported reports as backups.
