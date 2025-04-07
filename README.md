

```markdown
# 📚 DOI Scraper Web App

A Flask-based web application that extracts DOI links from any webpage (and its subpages if needed), then compiles the results into a downloadable Word document.

---

## 🚀 Features

- Extracts **DOI links** from a main webpage.
- Automatically scans **subpages** if no DOIs are found.
- Handles **403, 404**, and other HTTP errors gracefully.
- Saves results in a **Word (.docx)** file.
- Clean, simple interface with Flask and Bootstrap.

---

## 🛠️ Tech Stack

- Python 3.x
- Flask
- BeautifulSoup (bs4)
- Requests
- python-docx

---

## 🖥️ How It Works

1. Enter a URL on the main page.
2. The app scans for `https://doi.org/...` links in the HTML content.
3. If no DOIs are found, it recursively checks subpage links.
4. All results are listed on the page and saved in a Word file.



## 📂 Project Structure

```
📁 doi-scraper-webapp
│
├── app.py                  # Flask application code
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
│
├── templates/              # HTML files
│   ├── index.html
│   └── result.html
│
└── results/                # Word file output (auto-created)
```

---

## ✅ Getting Started

```bash
# Clone the repository
git clone https://github.com/AliAlAsif/doi-scraper-webapp.git
cd doi-scraper-webapp

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt

# Run the app
python app.py
```

Then open your browser at: `http://127.0.0.1:5000`

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**ALI AL ASIF**  
🔗 [GitHub](https://github.com/AliAlAsif)  
🔗 [LinkedIn](https://www.linkedin.com/in/ali-al-asif-73447328a/)

---

## 🌍 Deploy It

You can deploy this app easily using:
- 🔹 [PythonAnywhere](https://www.pythonanywhere.com/)
- 🔹 [Render](https://render.com/)
- 🔹 [Replit](https://replit.com/)
- 🔹 [Heroku](https://www.heroku.com/) *(requires setup for `Procfile` and `requirements.txt`)*

---

