# JPMC Software Engineering Virtual Experience – Task 1

This project was part of JPMorgan Chase's Software Engineering Job Simulation on Forage. It simulates a basic trading system by generating mock market data and serving bid/ask quotes for two fictional stocks. I completed this as a beginner and have since cleaned and documented the repo to reflect my current standards.

---

## 💡 Project Overview

This task involves:

- Running a Python-based HTTP server that simulates order book activity for two stocks (`ABC` and `DEF`).
- Fetching the top bid/ask prices and printing the bid-ask ratio in a client script.
- Demonstrating understanding of APIs, basic trading logic, and data handling.

The server generates synthetic market data, exposes an endpoint (`/query`) that returns the current top of the order book for both stocks, and the client script calculates the ratio between top bid and top ask prices.

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

5. **In a new terminal tab or window, run the client**

   ```bash
   python3 client3.py
   ```

6. **(Optional) Run unit tests**

   ```bash
   python3 client_test.py
   ```

---

## 📌 Notes

- JPMC has since archived this version of the job simulation and launched a newer one on Forage.
- This version reflects the original task as completed, with cleanup to remove environment clutter and ensure clarity for reviewers.

---

## 💭 Motivation

As someone interested in the intersection of finance and technology, I completed this project early in my learning journey to explore how software engineering supports financial systems. While simple, it sparked my interest in fintech and laid foundational skills I’ve since continued to develop.
