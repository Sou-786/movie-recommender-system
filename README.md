# movie-recommender-system-tmdb-dataset
A content based movie recommender system using cosine similarity

##Demo 

<img align="center" alt="Coding" width="400" src="https://media.giphy.com/media/OH9mcPeDaxXh2TRKB4/giphy.gif">

## How to run the project?

1. Clone this repository in your local system.
2. Install all the libraries mentioned in the [requirements.txt] file with the command `pip install -r requirements.txt`.
3. Find `movie_list.pkl` and `similarity.pkl` files from `Movie.ipynp` notebook.
4. Open your terminal/command prompt from your project directory and run the `app.py` file by executing the command `streamlit run app.py`.
5. Go to your browser and type `http://localhost:8501` in the address bar.
6. Hurray! That's it.

## How Cosine Similarity works?
  Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
  
  ![image](https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png)
