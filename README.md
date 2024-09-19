# Personalized Book Recommendation System

This project offers a personalized book recommendation system using collaborative filtering and popularity-based methods. It features a user-friendly web interface built with HTML and Tailwind CSS, powered by a Flask backend.

## Key Features

- **Collaborative Filtering:** Recommends books based on user interactions by identifying users with similar preferences.
- **Popularity-Based Filtering:** Suggests books that are widely recognized and favored by the community.
- **User-Friendly Frontend:** Designed with HTML and Tailwind CSS to provide an intuitive and engaging user experience.
- **Flask Backend:** Manages server operations and integrates with machine learning models.

## Web Interface

**Home Page:** A display of the most recommended books across all the users.

![Index Page](/assets/page_01.png)

**Get Recommendations Page:** A search interface showing book recommendations based on user queries.

![Recommendations Page](/assets/page_02.png)

## Installation and Setup

Follow these steps to set up and run the application:

1. **Clone the Repository**

    ```bash
    git clone git@github.com:abdullahashfaq-ds/Book-Recommendation-System.git
    cd Book-Recommendation-System
    ```

2. **Create and Activate a Virtual Environment**

    For Linux/Mac:

    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

    For Windows:

    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask Application**

    ```bash
    python app.py
    ```

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.
