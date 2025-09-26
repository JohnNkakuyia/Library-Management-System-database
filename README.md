# 📚 Library Management System (LMS)

A simple **Library Management System** built with **SQLite**, **Python**, and **Jupyter Notebook**.  
The project simulates real-world library operations such as managing **members, authors, publishers, books, borrowing, returns, and reservations**.  

---

## 🚀 Features
- Manage **Members, Authors, Publishers, Books, and Book Copies**
- Handle **Loans and Reservations**
- Track **Book Availability and Returns**
- Interactive **Search and Member Registration Widgets**
- Basic **Statistics Dashboard**

---

## 🛠️ Requirements
Make sure you have the following installed:
- Python 3.8+  
- Jupyter Notebook or JupyterLab  
- Required Python packages:
  ```bash
  pip install pandas ipywidgets


 ## ▶️ How to Run the Project

 Clone or Download the Repository

 git clone https://github.com/your-username/library_management_system.git
cd library_management_system

## 🚀 How to Use

### Open the Notebook
1. Open **`library_management_system.ipynb`** in Jupyter Notebook.  
2. Run the cells sequentially from **top to bottom**.  

### Interact with the System
- ➕ Add members using the interactive widget.  
- 📚 Search books by **title, author, or category**.  
- 🔄 Borrow and return books with example functions.  
- 📊 View statistics on **members, books, and loans**.

  ## 📂 Project Structure

```plaintext
project-root/
├── library_management_system.ipynb   # Main notebook
├── library_management.sqlite          # SQLite database (auto-created)
├── README.md                          # Documentation

---


## 📊 Example Outputs
- Schema overview of all tables  
- Sample data with **Authors, Books, and Members**  
- Interactive widgets for user operations  
- Statistics dashboard with key insights  

---

## ✅ Closing the Database
The database connection will close **automatically** when the notebook ends.  
You can also close it manually by calling:  

```python
close_connection()

