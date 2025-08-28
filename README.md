
# datafun-01-utils

A utility Python package for data science, analytics, and automation. This project provides a curated set of tools, libraries, and configuration tips to streamline your workflow in Python environments, especially for data analysis, visualization, and automation tasks.

## Features
- Easy setup for virtual environments and dependency management
- Recommendations for essential and optional Python packages
- Support for Jupyter notebooks and interactive development
- Guidance for working with Excel, databases, and APIs
- Ready-to-use configuration for logging, visualization, and more

## Getting Started

### 1. Clone the Repository
```powershell
git clone <repo-url>
cd datafun-01-utils
```

### 2. Create a Virtual Environment
```powershell
py -m venv .venv
.\.venv\Scripts\activate
```

### 3. Install Dependencies
```powershell
py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt --timeout 100
```

### 4. (Optional) Jupyter Notebook Support
To use Jupyter notebooks, install the recommended packages:
```powershell
py -m pip install jupyter ipython ipykernel ipywidgets nbdime jupyterlab-git
```

## Project Structure
- `requirements.txt` — List of recommended and optional Python packages, with setup instructions and comments.
- `README.md` — Project overview and setup guide.

## Recommended Packages
- **pip, setuptools, wheel** — Package management
- **loguru** — Logging
- **pyttsx3** — Text-to-speech
- **ipython, jupyter, ipykernel, ipywidgets, nbdime, jupyterlab-git** — Jupyter notebook support
- **matplotlib, seaborn** — Visualization

See `requirements.txt` for more options and details.

