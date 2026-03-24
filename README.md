<div align="center">
 
# 📰 News Explorer
 
### A desktop news aggregator that fetches real-time headlines from Google News across Indian states, global regions, current affairs, technology, and renewable energy.
 
[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Tkinter](https://docs.python.org/3/library/tkinter.html)]()
[![GoogleNews](https://img.shields.io/badge/Source-Google%20News-red?logo=googlenews&logoColor=white)](https://pypi.org/project/GoogleNews/)
[![Theme](https://img.shields.io/badge/Theme-sv--ttk-blueviolet)](https://github.com/rdbende/Sun-Valley-ttk-theme)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
 
</div>
 
---
 
## ✨ Features
 
- **Indian States News** — Browse headlines for 9 major Indian states
- **Continents News** — Get news by continent (Africa, Asia, Europe, etc.)
- **India Current Affairs** — Daily updates on Politics, Economy, Defense, Technology, Health, Education, and Environment
- **Global Current Affairs** — International headlines across World Politics, Climate, Science, Business, and more
- **Technology News** — Deep dives into AI, Gadgets, Cybersecurity, Startups, Gaming, Hardware, and AR/VR
- **Renewable Energy** — Focused coverage on Solar/Wind, EV Infrastructure, and Green Policies
- **Custom Search** — Search any topic on demand
- **Dark / Light Mode** — Toggle themes via the View menu
- **Clickable Articles** — Click any headline to open the full article in your browser
- **Async Fetching** — News loads in background threads so the UI stays responsive
 
---
 
## 🖥️ Screenshots
 
> _Add screenshots here after running the app_
 
---
 
## 🚀 Getting Started
 
### Prerequisites
 
- Python 3.8+
- pip
 
### Installation
 
```bash
# Clone the repository
git clone https://github.com/your-username/news-explorer.git
cd news-explorer
 
# Install dependencies
pip install -r requirements.txt
 
# Run the app
python news_app.py
```
 
### Dependencies
 
```
GoogleNews
sv-ttk
```
 
Install them manually if needed:
 
```bash
pip install GoogleNews sv-ttk
```
 
---
 
## 📁 Project Structure
 
```
news-explorer/
│
├── news_app.py          # Main application file
├── requirements.txt     # Python dependencies
└── README.md            # This file
```
 
---
 
##  How to Use
 
| Tab | What it does |
|-----|-------------|
| **Indian States** | Click a state button to fetch its latest news |
| **Continents** | Click a continent to get regional headlines |
| **India Current Affairs** | Topic-wise daily news for India |
| **Global Current Affairs** | International topic-wise headlines |
| **Technology News** | News by tech subcategory |
| **Renewable Energy** | Clean energy and sustainability news |
| **Local News** |  Coming Soon |
 
Use the **search bar** at the bottom to search for any custom topic.
 
Toggle **Dark/Light Mode** from the `View` menu in the menu bar.
 
## 🛠️ Tech Stack
 
| Component | Technology |
|-----------|-----------|
| GUI Framework | `tkinter` + `ttk` |
| Theme Engine | `sv-ttk` (Sun Valley TTK Theme) |
| News Source | `GoogleNews` Python wrapper |
| Threading | Python `threading` module |
| Browser Integration | `webbrowser` (stdlib) |
 
---
 
## 📄 License
 
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
 
---
<div align="center">
 
Developed with ❤️ by **[Harshal](https://github.com/Harshal-2006)**
 
</div>
