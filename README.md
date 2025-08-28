
# datafun-01-utils

A utility Python package for data science, analytics, and automation. This project provides a curated set of tools, libraries, and configuration tips to streamline your workflow in Python environments, especially for data analysis, visualization, and automation tasks.


## Features
- Easy setup for virtual environments and dependency management
- Reusable header/tagline module (`utils_sgolla.py`) with customizable variables
- Example of logging, text-to-speech, and formatted string output
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


### 2. Create and Activate a Virtual Environment
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
- `utils_sgolla.py` — Example module demonstrating variable declarations, logging, text-to-speech, and a reusable byline/tagline.


## Recommended Packages
- **pip, setuptools, wheel** — Package management
- **loguru** — Logging
- **pyttsx3** — Text-to-speech
- **ipython, jupyter, ipykernel, ipywidgets, nbdime, jupyterlab-git** — Jupyter notebook support
- **matplotlib, seaborn** — Visualization

See `requirements.txt` for more options and details.

## Example: Using the Byline Module

The `utils_sgolla.py` module demonstrates how to declare variables (bool, int, str, list), use built-in and external packages, and compose a reusable formatted string (byline/tagline) for your project. It includes variables such as:

- `is_accepting_clients`, `offers_remote_workshops`, `is_hiring`
- `current_year`, `year_started`, `number_of_employees`
- `author`, `organization`, `motto`, `location`
- `services`, `office_locations`, `satisfaction_scores`
- Calculated values: `years_active`, `count_of_locations`, `mean_score`, etc.

The byline is a formatted string that summarizes these variables for easy display or logging.

**To use the byline in your project:**

```python
from utils_sgolla import get_byline
print(get_byline())
```

You can also run `utils_sgolla.py` directly to see the output and test the text-to-speech feature (if enabled).

