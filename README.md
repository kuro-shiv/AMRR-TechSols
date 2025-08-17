# AMRR TechSols – Item Listing Web App

A simple two-page web application for the AMRR TechSols internship assignment. Users can add new items and view all submitted items with detailed information.

## 🔗 Live Demo

- [GitHub Repository](https://github.com/kuro-shiv/AMRR-TechSols/tree/master)


---

## 📄 Features

### 📥 Add Item Page (`Add Items`)
- Submit:
  - **Item Name**
  - **Item Type** (e.g., Shirt, Pant, Shoes, Sports Gear, etc.)
  - **Item Description**
  - **Cover Image**
  - **Additional Images**
- Displays a success message:  
  ✅ `Item successfully added` on successful submission.

### 👁️ View Items Page (`View Items`)
- Lists all items with:
  - **Item Name**
  - **Cover Image**
- Clicking an item opens a **modal/lightbox** with:
  - Full **item description**
  - All **images displayed in a carousel**

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap (modal & carousel)
- **Backend:** Node.js with Express *(optional; can use localStorage or JSON for static simulation)*
- **Storage:** Temporary in-memory/static list *(can be upgraded to a database)*

---

## 📁 Project Structure

```
AMRR-TechSols/
│
├── index.html           # View Items page
├── add.html             # Add Items page
├── item-detail.html
├── CSS/
├── JS/
├── node_modules/
├── server.js            # Express server (optional)
├── item.json
├── package.json         # JSON storage (optional enhancement)
├── package-lock.json 
└── README.md            # Project documentation
```

---

## 📦 How to Run Locally

1. Clone the repository:
   ```sh
   git clone https://github.com/kuro-shiv/AMRR-TechSols.git
   cd AMRR-TechSols
   ```

2. For static project (HTML/CSS/JS only):  
   Open `index.html` or `add.html` directly in your browser, or run a local server:
   ```sh
   python -m http.server 8000
   ```
   Visit: [http://localhost:8000](http://localhost:8000)

3. For Node.js/Express backend:
   - Install dependencies:
     ```sh
     npm install
     ```
   - Start the server:
     ```sh
     npm start
     ```
   - Open your browser at: [http://localhost:3000](http://localhost:3000)

---

## 📜 License

&copy; 2025 Shivam Kumar Dubey. All rights reserved.

---

## 👨‍💻 Author

**Shivam Dubey**  
GitHub: [@kuro-shiv](https://github.com/kuro-shiv)  
Project submitted as part of the AMRR TechSols Internship Assignment
