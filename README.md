# Musicon ( MUSIC + emotiON )

Musicon is a Music Recommendation System based on Facial Emotion Recognition.


# About Musicon

The emotion recognition model is trained on FER 2013 dataset. It can detect 7 emotions. The project works by getting live video feed from web cam, pass it through the model to get a prediction of emotion. Then according to the emotion predicted, the app will display playlist of songs from Spotify through spotipy wrapper and recommend the songs by displaying them on the screen.

# Tech Stack Used 

- Keras

- Tensorflow

- Spotipy

- Flask

# Features

- Real time expression detection and song recommendations.

- Playlists fetched from Spotify.

- UI for website.

# Running the application

- Run pip install -r requirements.txt to install all dependencies.

- Run python app.py and give camera permission if asked.

# Snippets from Musicon

Home Page 

![Home Page](#)

About Page

![About Page](#)

Emotion Detector & Music Recommendation

It can detect 7 emotions : Happy , Sad , Angry , Neutral , Disgusted , Suprised

![emotions](#)

Spotify Link 

![spotify](#)

# Project Components

- Spotipy is a module for establishing connection to and getting tracks from Spotify using Spotipy wrapper.

- haarcascade is for face detection.

- webcam.py is the module for video streaming, frame capturing, prediction and recommendation which are passed to main.py.

- app.py is the main flask application file.

- index.html & home.html in 'templates' directory is the web page for the application. Basic HTML and CSS.

- util.py is an utility module for video streaming of web camera with threads to enable real time detection.

- test.py is the script for image processing and training the model.

# Links

Dataset Link can be found here : https://www.kaggle.com/datasets/msambare/fer2013

Brief Overview of Project can be found here : #

Demo Video can be found here : #

# Further Improvements

- Instead of CSVs, create a databse and connect it to application. The DB will fetch songs for recommendations and new songs can be updated directly onto database.

- Add a feature which will update specified playlists for better and more recent recommendations, a specific day over a fixed duration say every sunday and append it to database.
#
