# JPMC Software Engineering Virtual Experience – Task 1

This project was part of JPMorgan Chase's Software Engineering Job Simulation on Forage. It simulates a basic trading system by generating mock market data and serving bid/ask quotes for two fictional stocks. I completed this as a beginner and have since cleaned and documented the repo to reflect my current standards.

---

## 💡 Project Overview

This task involves:

- Running a Python-based HTTP server that simulates order book activity for two stocks (`ABC` and `DEF`).
- Fetching the top bid/ask prices and calculating mid-price ratios in a client script.
- Displaying the data visually through a lightweight HTML viewer.
- Demonstrating understanding of APIs, basic trading logic, and data presentation.

The server generates synthetic market data, exposes an endpoint (`/query`) that returns the current top of the order book for both stocks, and the client script calculates and prints ratios between the mid-prices of each stock.

I've also refactored the server code to render a basic web interface I made (with vanilla HTML,CSS,JS) that also displays this data in a user-friendly format. The original version outputs results in a terminal via a python script, instructions to see that result are also explained below.

---

## 🛠️ How to Run

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
  _Insert screenshot of HTML-rendered market data here._

- 🖥️ **Terminal output from `client3.py`:**  
  _Insert sample output screenshot here._

---

## 📌 Notes

- JPMC has since archived this version of the job simulation and launched a newer one on Forage.
- This version reflects the original task as completed, with cleanup and improvements to enhance accessibility and readability for reviewers.

---

## 💭 Motivation

As someone interested in the intersection of finance and technology, I completed this project early in my learning journey to explore how software engineering supports financial systems. While simple, it sparked my interest in fintech and laid foundational skills I’ve since continued to develop. The added HTML view was built to help showcase the result more clearly for recruiters and technical reviewers.
