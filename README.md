# Timberfolio

Timberfolio is a simple web application designed to help sawmill workers track the daily production of timber boards of different sizes, specifically for pallet assembly.

## 🚀 Purpose

In the pallet manufacturing process, keeping an accurate record of the boards produced each day is crucial to avoid shortages or excess of materials. Timberfolio provides a straightforward solution to:

- Register daily production of boards (by size and date).
- Calculate the number of complete pallets that can be assembled.
- Detect when a production block (of 117 pallets) or a full shipment (468 pallets) is completed.
- Keep a history of daily production and progress toward shipment goals.
- Export and import your production history for backup or transfer between devices.
- Remove individual records as needed.

## 🛠️ Features

- **Daily logging:** Enter the quantity of boards produced per size and date.
- **Progress calculation:** View real-time progress on pallet assembly and shipment blocks.
- **History table:** See your production records and accumulated totals.
- **Delete entries:** Remove specific daily records.
- **Backup and restore:** Export your production history to a `.json` file and import it back anytime.
- **Data persists locally:** Production data is saved in your browser (using localStorage).

## 👨‍💻 Getting Started

1. **Clone or download** this repository.
2. Open `index.html` in your web browser.
3. Start registering your daily production!

No installation or server is required. All data is stored locally in your browser.

## 📊 Example Workflow

1. Enter the date and quantities for each board size (0.88m, 0.95m, 1.05m).
2. Save your daily record.
3. Track how many pallets and blocks you’ve completed.
4. Export your data regularly for backup.

## ⚡ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- (Optional) [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) for persistent data

## 📝 Future Ideas

- Multi-user support or cloud synchronization.
- Weekly/monthly production reports.
- Customizable pallet configurations.
- User authentication and permissions.
- Analytics dashboard with charts and graphs.

## 🙋‍♂️ Author

Made with 💡 by Ramon Rivera ([RiviCodes](https://github.com/RiviCodes))

---

> **Timberfolio** is an open project. Suggestions, feedback, and pull requests are welcome!
