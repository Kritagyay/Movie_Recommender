# Movie Recommender System with TMDB Dataset

Welcome to the Movie Recommender System project! This system utilizes the TMDB dataset, containing a vast array of movies, to create a personalized Netflix-like movie recommender. The recommendation system is based on Content-Based Filtering, leveraging techniques such as CountVectorizer and Cosine Distance.

## Features

- **Content-Based Filtering:** The system recommends movies based on the similarity of their content, considering features like genres, keywords, and other relevant information.

- **CountVectorizer:** Implemented to convert textual data, such as movie genres and keywords, into numerical vectors for analysis.

- **Cosine Distance:** Utilized to measure the similarity between movies, helping to identify those with comparable content.

- **Streamlit UI:** The project comes with a user-friendly interface powered by Streamlit, making it easy and enjoyable for users to explore and receive personalized movie recommendations.

## Getting Started

Follow these steps to set up and run the Movie Recommender System:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Movie-Recommender-System.git
   cd Movie-Recommender-System
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the App:**
   ```bash
   streamlit run app.py
   ```

4. **Open in Browser:**
   Open your web browser and navigate to `http://localhost:8501` to access the Movie Recommender System.

## Project Structure

- **`data/`:** Contains the TMDB dataset.
  
- **`src/`:** Houses the source code for the movie recommender system.
  
- **`app.py`:** The main file to run the Streamlit app.

## Usage

1. **Open the App:**
   Run the app using `streamlit run app.py` and access it through your browser.

2. **Input Preferences:**
   Enter your movie preferences, such as favorite genres or keywords.

3. **Receive Recommendations:**
   Get personalized movie recommendations based on your input.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request. Contributions are always welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Enjoy exploring and discovering new movies with the Movie Recommender System!
