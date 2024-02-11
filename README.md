<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/tn3w/CinemaWave/releases/download/iu/logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/tn3w/CinemaWave/releases/download/iu/logo-light.png">
  <img alt="CinemaWave Logo" src="https://github.com/tn3w/CinemaWave/releases/download/iu/logo-dark.png">
</picture>

CinemaWave is a free movie suggestion and viewing website written in Python.

## 🚀 Installation guide
Use git
 1. Use the following command to download CinemaWave
    ```bash
    git clone https://github.com/tn3w/CinemaWave
    ```
 2. Go to the downloaded folder
    ```bash
    cd CinemaWave
    ```
 3. Install all required packages
    ```bash
    python3 -m pip install -r requirements.txt
    ```
    Or create a virtual environment with python3-venv and install the packages
    ```bash
    python3 -m venv .venv
    .venv/bin/python -m pip install -r requirements.txt
    ```
 4. Launch CinemaWave
    ```bash
    python3 main.py
    ```
    Or with a virtual environment:
    ```bash
    .venv/bin/python main.py
    ```
