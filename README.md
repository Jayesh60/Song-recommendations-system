# Song-recommendations-System
*Run Script* = 
*flet -r song_flet.py*

download packages
1) flet = pip install flet
2) pandas = pip install pandas
3) sklearn = pip install scikit-learn


**Similarity.py**

similarity.py consist the code for the data preprocessing/cleaning. where i have removed null values and duplicated values and some formatting of the dataset accordingly.
also created tags column which includes lyrics, genre, subgenre and track_artist_names
and then use vectorization 

**song_flet.py**

flet is a python framework to create flutter app instantly in song_flet.py. created flet app which has a Navbar, Body, and Appbar,
in body section there's input field which accepts the track_name and accordingly provides the top 6 similar songs


**recommendation.py**

recommmendation.py is the gateway between song_flet.py and similarity.py

![Capture](https://user-images.githubusercontent.com/80568232/233715540-b17df4b5-b55a-420c-80e1-def9375b71ee.JPG)

![Capture2](https://user-images.githubusercontent.com/80568232/233823487-48e2889f-ca66-4b14-bf38-34a6a4dba31d.JPG)
