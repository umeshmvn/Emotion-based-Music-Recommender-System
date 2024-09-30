# 🎶 Emotion-Based Music Recommender System 🎧😁😥🥰😫

![Spotify](https://img.shields.io/badge/Spotify-1ED760?&style=for-the-badge&logo=spotify&logoColor=white)

![DJ Cats](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWxwY3N2NjlpMzV2MWFtd2xldGYzc2ExeDA5aHd4dGM3b2dlYmF5YSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Tb7kidAdyEIve/giphy.webp)

## 🌟 Abstract

Most music recommendation systems rely on learning from a user’s listening history—tracking song preferences, genres, and habits over time. But what if we could recommend music based on how you're feeling *right now*? This project introduces a novel approach where your mood is detected from an image and instantly matched with songs that perfectly suit your current emotional state. Say goodbye to mood playlists—now your music responds to *you*!

---

## 🎶 Project Overview

Our **Emotion-Based Music Recommender System** takes a fresh spin on song recommendations by analyzing the user's facial expressions and suggesting music accordingly. Instead of diving deep into your past listening behavior, this system determines your mood in real-time and recommends the perfect tracks to enhance or uplift your current emotional vibe.

### How it Works:
1. The system captures a user’s image using **OpenCV** and predicts their mood—Happy or Sad—using a **Convolutional Neural Network (CNN)**.
2. It then applies **Unsupervised Machine Learning (K-Means Clustering)** to group songs into two categories: 
   - **VERY ENTERTAINING** (for a mood boost)
   - **RELAXED** (to chill when you're already happy)
3. Unlike other platforms that might suggest sad songs when you’re feeling down, our system aims to cheer you up with lively music and calm you with relaxing tracks when you’re happy!

---

## 📁 Dataset

We utilized the comprehensive [Spotify Dataset](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks) containing over 160,000 tracks pulled from the **Spotify Web API**. The dataset is rich with features like **acousticness**, **energy**, **loudness**, and **danceability**, which makes our song clustering even more effective.

---

## 🔧 Technologies & Libraries

- **OpenCV**: For real-time image capture and processing.
- **TensorFlow & Keras**: For building and training the neural network models.
- **Scikit-Learn**: For clustering songs using K-Means.
- **LightGBM**: For optimizing recommendations.
- **Spotipy**: For interacting with the Spotify API.
- **Tkinter**: For building the application’s graphical user interface (GUI).
- **Pillow**: For image handling.

---

## 🚀 How to Use

1. Clone the repository and navigate to the project directory.
2. Run the `run.py` file to launch the GUI.
3. **Enter your favorite artist** into the search box. The system will fetch the relevant albums using the **Spotify API**.
4. Once ready, your webcam will activate. **Capture your mood** by pressing the 'q' key.
5. The GUI will process your image, analyze your mood, and generate a playlist of songs based on your emotional state.
6. Click on the **Print** button to see your recommendations. Enjoy your customized music experience! 🎧😊

---

## 🎤 Ready to Tune In?

Whether you're feeling elated or just need a little pick-me-up, this app has got you covered. So, **plug in**, let your webcam read your mood, and get ready for the perfect song recommendations tailored just for you. 🎶
