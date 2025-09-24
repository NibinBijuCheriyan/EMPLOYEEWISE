# Employee Payment Tracker

A Google Sheets and Apps Script solution for managing employee payments.

This project provides a simple web form for managers to record employee payment details, automatically calculate total amounts (including service and bank charges), and securely store all data in a Google Sheet for easy tracking and reporting.

-----

## 🚀 Features

  * **User-friendly Web Form**: A simple interface for entering employee payment details.
  * **Automatic Calculations**: Calculates the **Total Amount** by adding the `Service Charge` and `Bank Charge`.
  * **Centralized Data Storage**: All submissions are securely stored in **Google Sheets**, making it easy to track and report on payments.
  * **Modular Design**: The system is built with a clear separation of frontend and backend logic, making it easy to extend for features like dashboards, approval workflows, or custom reports.

-----

## 🛠 Tech Stack

  * **Google Apps Script**: Handles all backend logic, including form submissions and data manipulation in Google Sheets.
  * **Google Sheets**: Serves as the database for storing all payment records.
  * **HTML/CSS/JS**: Powers the frontend user interface for the web form.

-----

## 📂 Project Structure

```
/employee-payment-tracker
├── Code.gs             # Main backend script (handles form submission and sheet operations)
├── Index.html          # The user-facing form
├── appsscript.json     # Apps Script project configuration file
├── README.md           # This documentation file
```

-----

## 🔒 Security Notes

  * Sensitive data, such as API keys, should be stored using **Apps Script Properties** and not directly in the code.
  * For security, this repository should be kept **private** to protect implementation details.
  * If you choose to make the project public, ensure the repository only includes documentation and example snippets, not the full source code.

-----

## 🔗 Demo

  * **Web Form**: [https://script.google.com/macros/s/AKfycbwrS5JoCp4L0MHcTiN5SJAhBMn5NpUXTh-0MY-VpE4pg0pO9XQxeODy2457oR15ZG7P/exec](https://script.google.com/macros/s/AKfycbwrS5JoCp4L0MHcTiN5SJAhBMn5NpUXTh-0MY-VpE4pg0pO9XQxeODy2457oR15ZG7P/exec)
  * **Google Sheet**: [https://docs.google.com/spreadsheets/d/1fU0FF7bLuUG65OPDJeKuxJyn2oP433KfJa7bGEjU4Vs/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1fU0FF7bLuUG65OPDJeKuxJyn2oP433KfJa7bGEjU4Vs/edit?usp=sharing)

After entering data in the web form, check the Google Sheet to see the results.

If you find this project helpful, please consider starring the repository to show your support\!
