# Song-recommendations-System

**Similarity.py**

similarity.py consist the code for the data preprocessing/cleaning. where i have removed null values and duplicated values and some formatting of the dataset accordingly.
also created tags column which includes lyrics, genre, subgenre and track_artist_names
and then use vectorization 

**song_flet.py**

flet is a python framework to create flutter app instantly in song_flet.py. created flet app which has a Navbar, Body, and Appbar,
in body section there's input field which accepts the track_name and accordingly provides the top 6 similar songs


**recommendation.py**

recommmendation.py is the gateway between song_flet.py and similarity.py
