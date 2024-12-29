# 📚 Book Recommender System

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/downloads/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/nisch-mhrzn/book-recommender-system)](https://github.com/nisch-mhzrn/Book-Recommender-System-/commits/main)  
[![Repo Size](https://img.shields.io/github/repo-size/nisch-mhrzn/book-recommender-system)](https://github.com/nisch-mhrzn/Book-Recommender-System-)  

## 📖 Overview
The **Book Recommender System** is a Flask-based application that suggests books to users based on collaborative filtering. Users can also browse popular books and their ratings.

## 🚀 Features
- Top 50 popular books displayed on the homepage.
- Book recommendation system based on user input.
- Responsive UI built with Bootstrap.
- Handles missing data and ensures secure image links.

## 🛠️ Technologies Used
- **Backend:** Flask
- **Frontend:** HTML, CSS, Bootstrap
- **Data Handling:** NumPy, Pandas
- **Deployment Ready**

## 📂 Project Structure
```
book-recommender-system/
├── app.py                   # Main Flask application
├── templates/
│   ├── index.html           # Home page
│   ├── recommend.html       # Recommendation page
├── models/
│   ├── popular.pkl          # Preprocessed data for popular books
│   ├── pt.pkl               # Pivot table
│   ├── books.pkl            # Book metadata
│   ├── similarity_scores.pkl # Similarity matrix
├── requirments.txt/

```

## 📦 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/nisch-mhrzn/Book-Recommender-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Book-Recommender-System
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask application:
   ```bash
   python app.py
   ```

## 🌟 Usage
- Access the app on `http://127.0.0.1:5000/` in your browser.
- Use the "Recommend" page to get book suggestions.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## 👥 Contributing
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request.  

### Contributors
- **Your Name** - [GitHub](https://github.com/nisch-mhrzn)

---

Happy coding! 🎉
