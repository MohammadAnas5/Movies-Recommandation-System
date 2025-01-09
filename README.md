
   # Movie Recommendation System 🎥

![Ttle Page](https://github.com/MohammadAnas5/Movies-Recommandation-System/blob/main/images/movies.jpg)
This is a **Movie Recommendation System** built using **Collaborative Filtering**. The system leverages a similarity matrix to recommend movies based on the preferences of users who liked similar movies.

## Features 🚀

- **Movie Recommendations**: Suggests 5 movies based on the selected movie title.
- **Movie Posters**: Fetches and displays movie posters using the TMDB API.
- **Interactive UI**: Built using **Streamlit**, providing a simple and user-friendly interface.
- **Efficient Recommendations**: Uses precomputed similarity scores for fast and accurate recommendations.

## Technologies Used 🛠️

- **Python**: Core programming language.
- **Pandas**: For data manipulation and handling movie data.
- **Pickle**: To store and load precomputed similarity matrices and movie data.
- **Streamlit**: For building an interactive web application.
- **TMDB API**: To fetch movie posters and additional information.

## How It Works ⚙️

1. **Data Preprocessing**:
   - The movie data is processed and precomputed similarity scores are stored using `pickle`.

2. **Recommendation Algorithm**:
   - Collaborative Filtering is used to recommend movies based on user preferences.
   - The similarity matrix identifies movies that are closest in terms of user behavior.

3. **Poster Retrieval**:
   - TMDB API is used to fetch posters for the recommended movies, enhancing the user experience.

4. **Interactive UI**:
   - The app allows users to select a movie title and displays recommendations with their corresponding posters.

## 🎨 UI Screenshots

 ### Home Page
![Home Page](https://github.com/MohammadAnas5/Movies-Recommandation-System/blob/main/images/app.png)

![Home Page](https://github.com/MohammadAnas5/Movies-Recommandation-System/blob/main/images/app%20(1).png)


 ### Prediction Result
![Prediction Result](https://github.com/MohammadAnas5/Movies-Recommandation-System/blob/main/images/app%20(2).png)

## Setup Instructions 🖥️

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

4. Open your browser and navigate to the link provided by Streamlit to use the app.

## Files in the Repository 📁

- `app.py`: Main application code for the recommendation system.
- `movie_dict.pkl`: Pickle file containing the movie data (titles, IDs, etc.).
- `similarity.pkl`: Precomputed similarity matrix for movie recommendations.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Documentation for the project.

## TMDB API Key 🔑

To fetch movie posters, you need to get your TMDB API key:

1. Visit [TMDB](https://www.themoviedb.org/).
2. Create an account and generate an API key.
3. Replace the placeholder API key in `app.py`:
   ```python
   api_key = 'your_api_key_here'
   ```

## Limitations ⚠️

- The trained similarity model (`similarity.pkl`) is not uploaded to GitHub due to file size limitations. If you want that, message me.

## Future Improvements 🌟

- Include more recommendation techniques such as **Content-Based Filtering** or **Hybrid Methods**.
- Enable user login to provide personalized recommendations.
- Expand the dataset for better recommendations.
- Optimize the performance for large datasets.

---

Feel free to contribute to this project and share your feedback! 😊

