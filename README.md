

# 🎵 Emotion Detection & Music Recommendation

An AI-powered system that detects the **emotion** of a user through facial expressions or text input, and recommends **personalized music** to match or improve their mood.

---

## 📌 Features

* 🎯 **Real-Time Emotion Detection** – via facial expression analysis or text sentiment.
* 🎵 **Smart Music Recommendation** – based on emotion and genre preferences.
* 📊 **Machine Learning Models** – trained on labeled emotion datasets.
* 💻 **Interactive UI** – simple and user-friendly design.
* 🌐 **Scalable Architecture** – can be integrated into mobile or web apps.

---

## 🛠 Tech Stack

* **Languages**: Python, HTML, CSS, JavaScript
* **Libraries & Frameworks**:

  * `OpenCV` – face detection & image processing
  * `TensorFlow / Keras` – emotion classification model
  * `Pandas`, `NumPy` – data handling
  * `Flask` / `Django` – backend API
* **Tools**: Git, VS Code
* **Datasets**: FER-2013 (Facial Expression Recognition), Custom Music Dataset

---

## 🚀 How It Works

1. **Capture/Upload** – User's face or text is captured.
2. **Detect Emotion** – AI model predicts the current emotion.
3. **Recommend Music** – System suggests songs based on detected emotion.
4. **Play Music** – User can listen directly through integrated player or external link.

---

## 📷 Screenshots

*(Add some sample screenshots here for better appeal)*

---

## 📂 Project Structure

```
Emotion-Music-Recommendation/
│
├── data/              # Datasets  
├── model/             # Trained AI models  
├── static/            # CSS, JS, images  
├── templates/         # HTML pages  
├── app.py             # Flask backend  
└── README.md          # Project documentation  
```

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/Emotion-Music-Recommendation.git

# Navigate to the folder
cd Emotion-Music-Recommendation

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

---

## 📊 Model Training (Optional)

```bash
python train_model.py
```

* Trains emotion detection model using FER-2013 dataset.
* Saves model as `model/emotion_model.h5`.

---

## 🎯 Future Improvements

* 🎤 Voice emotion detection
* 📱 Mobile app integration
* 🎶 Spotify/YouTube API integration

---



