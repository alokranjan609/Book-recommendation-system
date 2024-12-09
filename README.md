# Book Recommendation System 📚

This project is a **Book Recommendation System** developed using **Machine Learning algorithms** and a **Flask web interface**. The system provides book recommendations based on two approaches: 

1. **Average Rating-Based Recommendations**: Recommends books based on the average user ratings.
2. **Cosine Similarity-Based Recommendations**: Transforms books into vectors using user ratings and finds similar books using cosine similarity.

The dataset used for this project is sourced from **Kaggle**.

---

## Features 🚀

- **Rating-Based Recommendation**: Uses average user ratings to suggest popular books.
- **Cosine Similarity Recommendation**: Suggests books based on similarity in user preferences.
- **Flask Web Interface**: A simple and intuitive web application to interact with the recommendation system.

---

## Demo 🎥

Once the project is running, you can access the web application at `http://localhost:5000` on your browser.

---

## Installation 💻

Follow these steps to set up and run the project on your local machine:

### Prerequisites
1. Ensure you have **Python 3.8+** installed.
2. Install a virtual environment tool such as `venv` or `virtualenv`.

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/alokranjan609/Book-recommendation-system
    cd Book-recommendation-system
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate    # On Windows, use venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    python app.py
    ```

5. Open a web browser and navigate to:
    ```
    http://localhost:5000
    ```

---

## Usage 🛠️

1. Enter your preferences in the search box (e.g., favorite books or genres).
2. Get recommendations based on the two implemented algorithms:
   - **Top-rated books** based on average ratings.
   - **Similar books** calculated using cosine similarity.

---

## Dataset 📊

The dataset used for this project is publicly available on **Kaggle**. You can explore the dataset [here](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset).

---

## File Structure 📁

- `app.py`: Main Flask application.
- `templates/`: HTML files for the web interface.
- `requirements.txt`: Python dependencies for the project.
- `README.md`: Documentation for the project.

---

## Dependencies 🛠️

Install all required dependencies from `requirements.txt` using:
```bash
pip install -r requirements.txt
```


## Future Enhancements 🌟
- Add user authentication for personalized recommendations.
- Implement real-time feedback for improving recommendations.
- Introduce additional recommendation algorithms such as collaborative filtering or deep learning-based models.

## Contribution 🤝
Contributions are welcome! Please fork the repository and submit a pull request for review.
