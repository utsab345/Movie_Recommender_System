# Movie Recommender System

A web application built using **Streamlit** that provides movie recommendations based on a selected movie. The app uses a precomputed similarity matrix to recommend movies and fetches posters from **The Movie Database (TMDb)** API.

## Features

- Recommends top 5 similar movies based on your selection.
- Displays movie posters alongside the recommendations.
- User-friendly dropdown to select movies from the dataset.

## Demo

![Screenshot 2024-11-14 170116](https://github.com/user-attachments/assets/b1cad2fc-d884-4036-af8a-647ea3de5cfa)
![Screenshot 2024-11-14 170135](https://github.com/user-attachments/assets/1e6b7755-b93d-447d-8e4a-67f9572c169e)


## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommender-system.git
   cd movie-recommender-system
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Obtain an API key from The Movie Database (TMDb). Replace the API key in the fetch_poster function:
   ```bash
    api_key = 'your_api_key_here'
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
5. Open the app in your browser:
   ```bash
   http://localhost:8501

## Dependencies

- Python 3.7 or later
- Streamlit
- Pandas
- Requests
- Pickle

## Project Structure

- ├── app.py                       
- ├── movies_dict.pkl                
- ├── similarity.pkl                
- ├── requirements.txt               
- ├── README.md                     

