# PassPal 🔐
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/flask-2.x-lightgrey.svg)](https://flask.palletsprojects.com/)
[![Bootstrap](https://img.shields.io/badge/bootstrap-5.x-purple.svg)](https://getbootstrap.com/)



## Description 📝

The project focuses on practicing core web-app concepts such as authentication, routing, templating, and database persistence using Python and Flask.

> ⚠️ Educational use only: this project is not intended for production environments.



## Table of Contents 🧭
1.  **Features**
2.  **Tech Stack**
3.  **Installation**
4.  **Usage**
5.  **How to use**
6.  **Routes**
7.  **License**
8.  **Footer**



## Features ✨
*   **User Authentication**: Sign up / sign in using session-based authentication.
*   **Password Entries**: Add, view, edit, and delete stored credentials.
*   **Search**: Quickly filter entries using the built-in search bar.
*   **Password Generator**: Generate strong random passwords from the Tools section.
*   **Export**: Export stored entries for backup or migration.
*   **UI Utilities**: Copy-to-clipboard and show/hide password controls.
*   **Responsive Interface**: Bootstrap-based UI with Bootstrap Icons.



## Tech Stack 🛠️
*   **Backend**: Python, Flask
*   **Auth**: Flask-Login
*   **Frontend**: HTML, Jinja2, Bootstrap, Bootstrap Icons
*   **Client-side**: JavaScript, jQuery (AJAX for generator)
*   **Database**: SQLite
*   **Deployment**: `wsgi.py`, `Procfile`



## Installation 💻
1.  **Clone the repository:**

    ```bash
    git clone https://github.com/<your-username>/PassPal.git
    cd PassPal
    ```

2.  **Create and activate a virtual environment:**

    **Windows (PowerShell):**
    ```bash
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    ```

    **Windows (CMD):**
    ```bash
    python -m venv .venv
    .venv\Scripts\activate
    ```

    **Linux / macOS:**
    ```bash
    python -m venv .venv
    source .venv/bin/activate
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the app:**

    ```bash
    python app.py
    ```


## Usage 🚀
1.  **Start the application:**

    ```bash
    python app.py
    ```

2.  **Open the app in your browser:**
    *   `http://127.0.0.1:5000`

3.  **Create an account and sign in** to access your vault.

4.  **Add entries**, generate passwords, and manage stored credentials from the dashboard.



## How to use ⚙️
1.  Launch the app (`python app.py`) and open it in your browser.
2.  Create a user account (Sign Up), then Sign In.
3.  Click **Add Entry** to store credentials (e.g., Website, Username, Password, URL).
4.  Use the **Search** bar to filter entries.
5.  Open **Tools → Password Generator** to create strong passwords.
6.  Use **copy-to-clipboard** and **show/hide password** controls when needed.
7.  Use **Tools → Export PassPal** to export saved entries.



## Routes 🧭
Common pages and tools (names may vary depending on configuration):
*   `/` — Dashboard / entries list
*   `/signup` — Create account
*   `/signin` — Log in
*   `/account` — Account page
*   `/add` — Add new entry
*   `/generator` — Password generator tool
*   `/export` — Export entries



## License ⚖️
This project is licensed under the [MIT License](LICENSE).


Feel free to test the project as part of academic work!

