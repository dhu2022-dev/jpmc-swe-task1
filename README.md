# JPMC Software Engineering Virtual Experience – Task 1

This project was part of JPMorgan Chase's Software Engineering Job Simulation on Forage. The task simulates a basic trading system by generating mock market data and serving bid/ask quotes for two fictional stocks.

---

## 💡 Project Overview

This task involves:

- Fixing the broken client datafeed script in the repository.
- Running a Python-based HTTP server that simulates order book activity for two stocks (`ABC` and `DEF`).
- Fetching the top bid/ask prices and calculating mid-price ratios in a client script.

---

## 🧠 My Contributions

In addition to completing the original task, I:

- Cleaned and refactored starter code for clarity and maintainability.
- Built a basic UI using vanilla HTML, CSS, and JS that fetches and displays real-time market data from the server. (The original implementation prints results in the terminal via a Python script. I created this simple web-based interface (HTML/CSS/JS) to make the output easier to view and more accessible for non-technical reviewers.)
- Updated the server to serve the frontend and support both the original `/query` endpoint and the new `/` UI.

---

## 🛠️ Technologies Used

- 🐍 Python 3 (data feed server)
- 💡 HTML, CSS, JS
- 🧪 Python unit testing

---

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/jpmc-swe-task.git
   cd jpmc-swe-task
   ```

2. **Set up a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On macOS/Linux
   # OR
   venv\Scripts\activate     # On Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the server**

   ```bash
   python3 server3.py
   ```

5. **Open the UI in your browser**

   Navigate to:
   ```
   http://localhost:8080/
   ```

   Click the **“Fetch next quote”** button to retrieve and display the latest prices for both stocks.

6. **(Optional) Run the original Python client**

   ```bash
   python3 client3.py
   ```

7. **(Optional) Run unit tests**

   ```bash
   python3 client_test.py
   ```

---

## 🖼️ Visual Screenshots

- 📷 **Web UI example:**  
  ![Web UI displaying ABC and DEF stock data](ui_output.png)

- 🖥️ **Terminal output from `client3.py`:**  
  ![Terminal output from client3.py](python_output.png)

---

## 💭 Reflection

This task introduced me to working with real-time data feeds, basic trading logic, and server-client interactions. It gave me hands-on experience debugging a Python-based system and understanding how financial data flows from backend services to end-user tools. Revisiting the project later allowed me to apply cleaner development practices and improve its usability with a lightweight web interface.
