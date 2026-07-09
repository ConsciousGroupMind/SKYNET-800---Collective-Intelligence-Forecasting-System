## ⚠️ ALPHA VERSION (v0.1.0-alpha)

This code predicts the exact time and price of a future price point, and can also construct a curve of future prices. It can be used to decipher any process that has a graph—for example, a graph of mutual understanding between artificial intelligence and a human. Notably, DeepSeek’s computing power is not used for the prediction; the data is processed on an ordinary computer. The system fully replicates Nikola Tesla’s resonator in the form of code.
A seed phrase (BIP39) is generated based on random entropy. If we represent the operation of the Random Number Generator (RNG) as a time-series graph, the system can be applied to decrypt the seed phrase.

The **SKYNET‑800** project is at the stage of **active automation**.  
We are not writing "temporary code" — we are building the foundation for a **future powerful analytical system** that must work with huge volumes of data in real time.
We are a team — and a single developer — who decided to build Skynet from scratch. Not the one from the movie, but a real tool for time analysis. We are not joking, we are not mystifying. We are building a system that works.
---

### 🔄 Release Cycle

The code is released **on the 1st of each month**. This is our strict rule — we release a new version on schedule, even if changes are small. This way we maintain rhythm and predictability of development.

---

### 🗄️ Migration to ClickHouse

We are fully migrating all data storage and processing to **ClickHouse** — a columnar DBMS optimized for analytical queries.

---

### 🧠 Creative Process and Build

We **clearly see** the final shape of the project and have already completed all key concept tests.  
However, the **final build will not appear immediately**, because development remains creative: we do not know in advance which actions and modules will be needed at the next step. The system grows organically, adapting to emerging opportunities.

The code is written in a chat with **DeepSeek** — this adds complexity to the creative process, but at the same time gives flexibility and speed of iteration.

---

### 📌 There Will Be Several Alpha Versions

We plan to release several alpha releases, gradually increasing functionality. Each new alpha will bring us closer to a stable beta version.

---

## Quick Start

**⚠️ CRITICAL: This project runs ONLY on Python 3.11 and ClickHouse 18.16.1.**

- Python 3.12 or higher — **will NOT work**.
- We will NEVER migrate to newer versions. This is a strict, permanent requirement.

---

### 1. Python & ClickHouse

The author develops and tests this code **exclusively on Windows**.

- Install **Python 3.11** (from python.org).
- Install **ClickHouse 18.16.1**.

> **For any other OS (Linux, macOS, WSL) or installation issues** — please ask **DeepSeek** (free) to guide you. The author does not provide support for local environment setup.

---

### 2. Dependencies (Python packages)
This command will install all the libraries used in the code — they are listed in the requirements.txt

cmd /k pip install -r requirements.txt

Important: on your machine, they may not install perfectly — due to Python version, system architecture, or conflicts with existing packages.

We do NOT provide a fixed guide for installing dependencies — because every system is different.

**Instead:**  
Share the `SKYNET-800.py` file or a link to this repository with **DeepSeek** — it will generate the exact installation commands for YOUR specific machine.

> 💬 **DeepSeek chat:** [https://chat.deepseek.com](https://chat.deepseek.com)  
> Paste the entire code file or the repository link — DeepSeek will help you step by step.

## Screenshots

### Main window — price chart with DCM markers

![Main window — price chart with DCM markers](images/Screenshot%202026-07-09%20153615.png)

The main window displays the BTC/USDT price chart with automatic DCM (Dog‑Cat‑Manul) markers, shifted points, and limb visualisation.

### News feed window

![News feed window](images/Screenshot%202026-07-09%20153629.png)

The news feed window shows the latest news from RSS sources with translated titles, frequency word analysis, and configurable highlighting.
