# Akshata Traders - Invoice Generator

A web-based **Invoice Generator** built for **Akshata Traders**.
This tool simplifies creating invoices by allowing users to select items from stock, auto-fill details, and generate a clean PDF invoice ready for printing or sharing.

---

## 🚀 Features

* 📋 **Dynamic Item Selection** – Dropdown with all stock items + autocomplete search.
* 🖊 **Auto-Suggestion** – Start typing to quickly find items.
* 🧾 **Invoice Generation** – Add items with quantity, price, and auto-calculated totals.
* 📑 **Download as PDF** – Export invoices without input fields, buttons, or controls.
* 🎨 **Simple UI** – Easy-to-use, minimal, and responsive design.

---

## 📂 Project Structure

```
├── index.html        # Main invoice generator page  
├── style.css         # Stylesheet for UI  
├── script.js         # Core logic for invoice creation & PDF export  
├── stock-items.js    # List of available stock items  
└── README.md         # Project documentation  
```

---

## 🛠️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **Libraries**: jsPDF (for PDF export), Autocomplete logic in JS
* **Platform**: Web app (can also be wrapped in Android WebView)

---

## ⚙️ Usage

1. Open the app in your browser (`index.html`).
2. Select items from the dropdown or type to search.
3. Enter quantity & price → totals auto-calculate.
4. Click **Generate Invoice** to preview.
5. Download the invoice as a **PDF**.


---

## 📦 Installation

Clone the repo and open in your browser:

```bash
git clone https://github.com/yourusername/akshata-invoice-generator.git
cd akshata-invoice-generator
```

Open `index.html` in any modern browser.

---

## 🔮 Future Enhancements

* ✅ Multi-currency support
* ✅ Customer database with saved details
* ✅ Cloud sync (Firebase/MongoDB)
* ✅ Export to Excel/CSV

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.

---

## 📜 License

This project is licensed under the MIT License.
