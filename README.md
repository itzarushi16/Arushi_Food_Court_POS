# 🧾 Billing POS System (Java Swing)

A simple Point of Sale (POS) application built with **Java Swing**. This GUI-based program mimics a billing system where food items can be added with a single click using image-based buttons. The system automatically calculates the total cost and updates the display in real time.

---





---

## 🚀 Features

- 📷 Image-based item buttons (e.g., Croissant, Pasta, Dosa)
- 🧮 Dynamic total calculation
- 🗃️ JTable integration for item listing
- 🔁 Duplicate item update instead of multiple entries
- 💰 Balance and payment tracking (Total, Pay, Balance)
- 🔤 Font and alignment styling for labels

---

## 🛠 Technologies Used

- Java SE
- Java Swing (GUI)
- NetBeans IDE
- JTable, JPanel, JLabel, JTextField, JButton, JTextArea
- Image Icons (`.jpeg`, `.jpg`)

---

## ⚙️ How It Works

- Each food item has a clickable button with an image.
- Clicking a button triggers `addtable()` method.
- The method adds the item into `JTable` or updates the existing row if it's already added.
- The `call()` method sums the total and updates the `total` label.
- The user can enter a payment amount and see the remaining balance.

## 🧰 Requirements

- Java JDK 8 or later  
- NetBeans IDE (recommended for GUI form editor)
- No third-party dependencies required

---

## ▶️ Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/simple-pos-java.git
Open in NetBeans IDE.

Clean and build the project.

Run the NewJFrame.java file to launch the GUI.
