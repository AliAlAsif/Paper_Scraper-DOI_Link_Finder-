
# 📄 Paper Scraper - DOI Link Finder

A Flask-based web app that scrapes and extracts DOI links from research paper pages and their subpages. The extracted links are compiled into a downloadable Word document for your convenience.

---

## 🚀 Features

- ✅ Extracts DOI links from the **main webpage**
- 🔗 Follows subpage links and scrapes DOIs from them
- 📃 Outputs results to a downloadable `.docx` Word file
- ⚠️ Gracefully handles inaccessible or error-prone pages
- 🧠 BeautifulSoup + Requests based parsing
- 🌐 Simple and clean web interface using Flask templates

---

## 📁 Project Structure

```
Paper_Scraper-DOI_Link_Finder-/
├── templates/
│   ├── index.html         # Homepage for URL input
│   └── result.html        # Result display page with DOI links
├── Paper scraper.py       # Flask backend script
├── LICENSE
└── README.md
```

---

## 💻 Run Locally

### 1. Clone the Repo

```bash
git clone https://github.com/AliAlAsif/Paper_Scraper-DOI_Link_Finder-.git
cd Paper_Scraper-DOI_Link_Finder-
```

### 2. (Optional) Create a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
```

### 3. Install Dependencies

```bash
pip install flask beautifulsoup4 requests python-docx
```

### 4. Run the Web App

```bash
python "Paper scraper.py"
```

Then go to:  
👉 `http://127.0.0.1:5000` in your browser

---

## 📥 Output

All found DOI links (main page + subpages) and any errors are compiled into a Word file (`.docx`) and can be downloaded from the result page.

---

## 🛠️ Technologies Used

- Python 3
- Flask
- BeautifulSoup (bs4)
- requests
- python-docx

---

## 📄 License

Licensed under the [MIT License](./LICENSE)

---

## 👤 Author

**Ali Al Asif**  
📌 [GitHub](https://github.com/AliAlAsif)  
📎 [LinkedIn](https://www.linkedin.com/in/ali-al-asif-73447328a/)

---

## 🌟 Show Your Support!

If you found this helpful, leave a ⭐ on the repo and connect with me on [LinkedIn](https://www.linkedin.com/in/ali-al-asif-73447328a/)! 😄

```
